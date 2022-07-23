# Organisation

Mostly **2GP** for field updates.

Mostly **UNPACKAGED** for email alerts.

# Considerations

- Workflows can be considered deprecated and should mostly have been replaced with flows by now.
- Workflows are not optimized for source driven development: They are still in the old "MDAPI" format (rules, alerts and updates are all in a single file).
- We can install multiple packages in an org that all have their own workflow-file on the same object.
- Email alerts usually require real email addresses as recipients. We definitely do not want to use these during development. As as result, we have to use fake emails during development and we almost always have to override the email alert in happy-soup later.
- Some workflow-components such as email alerts are referenced from flows. If the flow is in a package, the email alert must be, too.

# Links

- [Metadata API Developer Guide: Workflow](https://developer.salesforce.com/docs/atlas.en-us.238.0.api_meta.meta/api_meta/meta_workflow.htm)

# Related Types

- [Flow](flow.md)
