# Organisation

Always **2GP** for definitions.

Mostly **2GP** for records. In some occasions, it makes sense to have some records **UNPACKAGED**.

# Considerations

- The default setting for package install does not delete custom metadata records from the target org during a package upgrade.
- Custom metadata and their records are almost always used to configure the behavior of Apex code. Therefore, they must be packaged and tested together with the code.

# Links

- [Metadata API Developer Guide: Custom Metadata](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_custommetadata.htm)
- [CLI Documentation: force:package:install](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference_force_package.htm#cli_reference_force_package_install)
