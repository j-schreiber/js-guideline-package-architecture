# Organisation

Mostly **UNPACKAGED**.

# Considerations

- Report types usually include fields from all packages, even if they are on separate dependency trees. Especially report types that include standard objects or shared custom objects should be maintained in happy-soup.
- Adding, renaming or removing fields is common and should not require a package upgrade.
- Report types that are deployed with 2GP cannot be modified on the target org.

# Links

- [Metadata API Developer Guide: Report Type](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_reporttype.htm)
