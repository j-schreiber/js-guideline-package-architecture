# Organisation

**2GP** for functional permission sets.

# Considerations

- For complex applications, you will typically end up with 2 to 4 permission sets per functionality. Consider each role and design a permission set per role. Develop and deploy it in the package that implements the functionality.
- For production, you typically assign those permission sets to the trained users individually, or you add it to general permission set groups (e.g. Standard Sales User, Standard Marketing User).
- Permission set deployments are _destructive_. If you remove a field or object from the source, the permissions on the target org **will be removed**. This is different than how profiles behave.

# Links

- [Metadata API Developer Guide: Permission Set](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_permissionset.htm)

# Related Types

- [Profile](profile.md)
- [Permission Set Group](permission-set-group.md)
- [Custom Permission](custom-permission.md)
- [Custom Object](custom-object.md)
