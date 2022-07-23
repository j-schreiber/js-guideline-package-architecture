# Organisation

**UNPACKAGED** for all general layouts to standard objects and shared custom objects.

**2GP** for layouts to specific record types or custom objects.

# Considerations

- Standard objects are typically used in multiple packages. One package naturally does not know about other fields that are introduced in downstream dependencies or other independent packages.
- Sometimes, we need to provide temporary custom fields for _quick and dirty_ solutions. These fields need to be added to layouts as well.
- Business often wants to re-arrange layouts for better usability. Minor changes in the presentation layer of our data should not require package upgrades.
- Carefully consider where a custom object will be used. If your package introduces a custom object and will **exclusively** use it, put the layouts in the same package. If other downstream dependencies extend the object, place all layouts in **UNPACKAGED**.

# Links

- [Metadata API Developer Guide: Layout](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_layouts.htm)

# Related Types

- [Custom Object](custom-object.md)
- [Custom Field](custom-field.md)
