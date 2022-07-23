# Organisation

**UNPACKAGED** only. Isolate each experience bundle into its own repository to deploy independently.

# Considerations

- The metadata format is completely unusable. Experiences can only be modified from the drag-and-drop experience builder. There is no benefit in developing experiences from source.
- Communities cannot be deployed like regular source. You need to have an extra step and publish them afterwards.
- Enabling communities / experience on an org creates lots of boilerplate code that is always included in source push/pull operations.
- Experience builder and navigation menus are not stable enough for Scratch Org Development. It is recommended to only develop and deploy experiences on Sandboxes.

# Links

- [Metadata API Developer Guide: Experience Bundle](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_experiencebundle.htm)
- [Metadata API Developer Guide: Custom Site](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_sites.htm)
