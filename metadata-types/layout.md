# Recommendation

For layouts of standard objects, prefer **unpackaged**.

If the custom object is exclusively owned by a package, it is acceptable to **package** the layout with it.

# Considerations

- Standard objects are typically used and extended in multiple packages. A package naturally cannot know about other fields that are introduced in down-stream dependencies or other independent packages.
- Sometimes, we need to provide temporary custom fields for _quick and dirty_ solutions. These fields need to be added to layouts as well.
- Business often wants to re-arrange layouts for better usability. Minor changes in the presentation layer of our data should never require package upgrades.

# Links

- [Metadata API Developer Guide: Layout](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_layouts.htm)

# Related Types

- [Custom Object](custom-object.md)
- [Custom Field](custom-field.md)
