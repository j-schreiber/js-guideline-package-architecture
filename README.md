# About

This repository provides a guideline for Salesforce architects how to organise Salesforce metadata. Some components work very well with unlocked packages, others don't.
Here, I gather insights about how these components behave in reality, beyond the limited information from the [Metadata Coverage Report](https://mdcoverage.secure.force.com/docs/metadata-coverage).

This repository is constantly updated, as the Metadata API and SFDX evolve. However, most recommendations are based on non-technical constraints and are not very likely to change anytime soon.

# How To Use

You can find all recommendations in the [metadata-types](metadata-types) folder. Each type has a brief readme with more details.

# Overview

| Metadata                                                    | Primary Organisation |
| ----------------------------------------------------------- | -------------------: |
| [Apex Class](apex-class.md)                                 |              2GP[^1] |
| [Test Suite](apex-test-suite.md)                            |                  2GP |
| [Apex Trigger](apex-trigger.md)                             |                  2GP |
| [Audience](audience.md)                                     |         isolated[^3] |
| [Aura Definition Bundle](aura-definition-bundle.md)         |                  2GP |
| [Custom Field](custom-field.md)                             |                  2GP |
| [Custom Labels](custom-labels.md)                           |                  2GP |
| [Custom Metadata](custom-metadata.md)                       |                  2GP |
| [Custom Object](custom-object.md)                           |                  2GP |
| [Custom Permission](custom-permission.md)                   |                  2GP |
| [Email](email.md)                                           | 2GP / happy-soup[^2] |
| [Experience](experience.md)                                 |         isolated[^3] |
| [Flexi Page](flexi-page.md)                                 |           happy-soup |
| [Flow](flow.md)                                             |                  2GP |
| [Group](group.md)                                           |           happy-soup |
| [Layout](layout.md)                                         |           happy-soup |
| [Lightning Component Bundle](lightning-component-bundle.md) |                  2GP |
| [Navigation Menu](navigation-menu.md)                       |             isolated |
| [Network](network.md)                                       |             isolated |
| [Path Assistant](path-assistant.md)                         |           happy-soup |
| [Permission Set Group](permission-set-group.md)             |           happy-soup |
| [Permission Set](permission-set.md)                         |           happy-soup |
| [Profile](profile.md)                                       |           happy-soup |
| [Queue](queue.md)                                           |     2GP / happy-soup |
| [Quick Action](quick-action.md)                             |                  2GP |
| [Record Type](record-type.md)                               |                  2GP |
| [Report Type](report-type.md)                               |           happy-soup |
| [Role](role.md)                                             |           happy-soup |
| [Sharing Rule](sharing-rule.md)                             |           happy-soup |
| [Sharing Set](sharing-set.md)                               |             isolated |
| [Validation Rule](validation-rule.md)                       |                  2GP |
| [Workflow](workflow.md)                                     |     2GP / happy-soup |

[^1]: **2GP** - Second-generation packaging. Deployed with package install.
[^2]: **happy-soup** - Your primary unpackaged metadata in a single repository. Deployed with source deploy or mdapi deploy.
[^3]: **isolated** - An isolated repository for unpackaged metadata that is not deployed with the rest of happy-soup. Often requires additional deployment steps.
