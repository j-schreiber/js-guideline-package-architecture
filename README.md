# About

This repository provides a guideline for Salesforce architects how to organise Salesforce metadata. Some components work very well with unlocked packages, others don't.
Here, I gather insights about how these components behave in reality, beyond the limited information from the [Metadata Coverage Report](https://mdcoverage.secure.force.com/docs/metadata-coverage).

This repository is constantly updated, as the Metadata API and SFDX evolve. However, most recommendations are based on non-technical constraints and are not very likely to change anytime soon.

# How To Use

You can find all recommendations in the [metadata-types](metadata-types) folder. Each type has a brief readme with more details.

# Overview

**2GP** - Second-generation packaging. Deployed with package install.

**happy-soup** - Your primary unpackaged metadata in a single repository. Deployed with source deploy or mdapi deploy.

**isolated** - An isolated repository for unpackaged metadata that is not deployed with the rest of happy-soup. Often requires additional deployment steps.

| Metadata                                                                   | Primary Organisation |
| -------------------------------------------------------------------------- | -------------------: |
| [Apex Class](metadata-types/apex-class.md)                                 |                  2GP |
| [Test Suite](metadata-types/apex-test-suite.md)                            |                  2GP |
| [Apex Trigger](metadata-types/apex-trigger.md)                             |                  2GP |
| [Audience](metadata-types/audience.md)                                     |             isolated |
| [Aura Definition Bundle](metadata-types/aura-definition-bundle.md)         |                  2GP |
| [Custom Application](metadata-types/custom-application.md)                 | happy-soup & 2GP[^*] |
| [Custom Field](metadata-types/custom-field.md)                             |                  2GP |
| [Custom Labels](metadata-types/custom-labels.md)                           |                  2GP |
| [Custom Metadata](metadata-types/custom-metadata.md)                       |                  2GP |
| [Custom Object](metadata-types/custom-object.md)                           |                  2GP |
| [Custom Permission](metadata-types/custom-permission.md)                   |                  2GP |
| [Email](metadata-types/email.md)                                           | 2GP / happy-soup[^*] |
| [Experience](metadata-types/experience.md)                                 |             isolated |
| [Flexi Page](metadata-types/flexi-page.md)                                 |           happy-soup |
| [Flow](metadata-types/flow.md)                                             |                  2GP |
| [Group](metadata-types/group.md)                                           |           happy-soup |
| [Layout](metadata-types/layout.md)                                         |           happy-soup |
| [Lightning Component Bundle](metadata-types/lightning-component-bundle.md) |                  2GP |
| [Navigation Menu](metadata-types/navigation-menu.md)                       |             isolated |
| [Network](metadata-types/network.md)                                       |             isolated |
| [Path Assistant](metadata-types/path-assistant.md)                         |           happy-soup |
| [Permission Set Group](metadata-types/permission-set-group.md)             |           happy-soup |
| [Permission Set](metadata-types/permission-set.md)                         |           happy-soup |
| [Profile](metadata-types/profile.md)                                       |           happy-soup |
| [Queue](metadata-types/queue.md)                                           | 2GP / happy-soup[^*] |
| [Quick Action](metadata-types/quick-action.md)                             |                  2GP |
| [Record Type](metadata-types/record-type.md)                               | 2GP / happy-soup[^*] |
| [Report Type](metadata-types/report-type.md)                               |           happy-soup |
| [Role](metadata-types/role.md)                                             |           happy-soup |
| [Sharing Rule](metadata-types/sharing-rule.md)                             |           happy-soup |
| [Sharing Set](metadata-types/sharing-set.md)                               |             isolated |
| [Standard Value Set](metadata-types/standard-value-set.md)                 |           happy-soup |
| [Validation Rule](metadata-types/validation-rule.md)                       |                  2GP |
| [Workflow](metadata-types/workflow.md)                                     | 2GP / happy-soup[^*] |

[^*]: See details for explanation
