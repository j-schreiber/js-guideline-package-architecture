# Organisation

Mostly **2GP**.

**UNPACKAGED** to override queue members or queue emails.

# Considerations

- Queues themselves are usually stable and rarely change.
- Queue members and queue emails change regularly and are usually not commited to source at all.
- Package upgrades that only contain the queue definition (without queue email and queue members) do not override changes that were made on a Sandbox or Production instance.

# Links

- [Metadata API Developer Guide: Queue](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_queue.htm)
