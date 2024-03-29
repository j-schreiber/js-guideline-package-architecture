# Organisation

Almost always **happy-soup** for the definition.

Use **2GP** only after careful consideration.

# Considerations

- See [Record Type](record-type.md) for considerations how to filter picklist value entries for standard fields.
- Usage of standard picklists is very hard to contain in a single package. Adding one to a package usually comes with major downsides.
- If one package added a standard value set, no other package can own it (and be installed in the same org).
- If source of the package depends on standard value sets (e.g. approval processes, flow, apex), add it to the package source.
- In general, try to minimize the number of duplicated files you spread accross repositories.

# Links

- [Metadata API Developer Guide: Standard Value Set](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_standardvalueset.htm)

# Related Types

- [Record Type](record-type.md)
