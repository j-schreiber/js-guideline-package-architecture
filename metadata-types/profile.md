# Organisation

Only **UNPACKAGED**.

# Considerations

- Profile deployments are _non-destructive_. If you remove a field or custom object from the source, the permissions on the target org will **still remain enabled**. You must explicitly disable the permission or set the field to not viewable/editable to remove permissions from the profile.
- In most situations, it doesn't make sense to maintain and modify profiles from source. Profiles should be the lowest common denominator. Use permission sets and permission set groups to really control your users permissions.

# Links

- [Metadata API Developer Guide: Profile](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_profile.htm)

# Related Types

- [Permission Set](permission-set.md)
- [Permission Set Group](permission-set-group.md)
- [Custom Application](custom-application.md)
