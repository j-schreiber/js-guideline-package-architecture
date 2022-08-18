# Organisation

Almost always **2GP** for the definition.

Use **happy-soup** for extending packaged record types.

# Considerations

- Be careful when filtering picklist values for a record type: It is recommended to remove the filter completely, if not required. This will automatically add all entries of the picklist.
- If you need to filter picklist values of a custom field from the same package on a record type, add the filters on the record type metadata.
- For picklist value filters on standard picklists, organize the record type with the _filters only_ in happy soup.
- Record types cannot be deleted via API, so a package upgrade or uninstall can only deprecate it. An Admin has to manually delete the record type via UI.

# Links

- [Metadata API Developer Guide: Record Type](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_recordtype.htm)

# Related Types

- [Standard Value Set](standard-value-set.md)
