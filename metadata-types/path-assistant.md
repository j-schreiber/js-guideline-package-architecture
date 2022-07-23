# Organisation

**UNPACKAGED**.

# Considerations

- Translations of path assistants are not yet supported by Metadata API.
- The texts in path assistants are regularly updated and minor changes in help texts should not require package upgrades.
- If the assistant references a standard value set (e.g. `CaseStatus`, `LeadStatus`), deployment is buggy. In many situations, the assistant cannot be deployed because of internal errors.

# Links

- [Metadata API Developer Guide: Path Assistant](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_pathassistant.htm)

# Related Types

- [Record Type](record-type.md)
- Translations
