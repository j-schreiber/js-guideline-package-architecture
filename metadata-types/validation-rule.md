# Organisation

Only **packaging**.

# Considerations

- For most complex applications, we deliver our custom objects bundled together with validation rules, custom fields and record types.
- Validation rules may break automations and regularly break test setup. Always put them into packages for more realible regression testing.
- In rare occasions, it is acceptable to temporarly disable or alter a validation rule from a package. In that case, add the overwritten validation rule to unpackaged source.

# Links

- [Metadata API Developer Guide: Validation Rule](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_validationformulas.htm)

# Related Types

- [Custom Field](custom-field.md)
