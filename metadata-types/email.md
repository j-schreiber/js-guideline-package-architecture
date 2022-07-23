# Organisation

**2GP** for emails that are used in automations.

**UNPACKAGED** for the final texts of these emails.

# Considerations

- Automations (flows, apex code) rely on classic email templates and cannot use lightning templates yet.
- Development of lightning templates is severly limited (requires `AccessContentBuilder` permission, feature must be activated).
- Email templates (especially HTML templates) typically undergo many revisions and are regularly updated (contact information, signatures, etc). You do not want to create new package versions for every typo or grammar fix.
- The recommended approach is having the core templates (for testing and development) in 2GP, while overriding the final texts from a happy-soup repository.

# Links

- [Metadata API Developer Guide: Email Template](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_emailtemplate.htm)
