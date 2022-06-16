# Recommendation

Almost always **packaging**. Limit **unpackaged** custom fields to temporary workarounds.

# Considerations

- For most complex applications, we deliver our custom objects bundled together with validation rules, custom fields and record types.
- Sometimes, business requires additional fields on custom or standard objects that help temporary processes.
- Ensure that unpackaged fields are always modified from source. You want all changes in version control, even though admins can easily change them in the UI.

# Links

- [Metadata API Developer Guide: Custom Field](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/customfield.htm)

# Related Types

- [Custom Object](custom-object.md)
- [Layout](layout.md)
