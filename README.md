# NimbusCloud

Hiya! 

Thanks for challenging me with this. For easier navigation, here are the documentation files:

**Integration guide:** [/docs/guides/upload-file.mdx](/docs/guides/upload-file.mdx)

**API Reference:** [/static/openapi/nimbus-store.yaml](/static/openapi/nimbus-store.yaml)

> You can also view the live documentation here: [NimbusCloud Docs](https://lulunwenyi.github.io/nimbuscloud/)

#### API Strategy

As an answer to the last task, here's how I would approach improving this documentation, and how I added support for new fields that might come in the future.

In terms of **improvements:**

1. For better error-referencing, I would have a guiding error documentation with a standardised naming convention and schema. 
2. Create a standard versioning process for the product, API and its documentation changes. 
3. Provide wider range of code samples.
4. Offer interactive ways (e.g, Postman collection) for users to test the endpoint. 
5. Include validation rules, especially for required parameters.
6. Add videos to guides to make it more accessible. 
7. Add migration guides to make quick-starts easier, and improve conversion. 

I provided **support for future fields** by:

1. Using the OpenAPI specs to document the API, and YAML to structure the specs, additional fields can be added to each endpoint's documentation, without affecting the documentation for existing fields.
2. By defining schemas, I provided room for flexibility, and adaptability of parameters in future applications .
3. With schemas, I also established a consistent data model for specific entities, like [files](https://lulunwenyi.github.io/nimbuscloud/api-reference#model/files), for uniformity, and so it can act as reusable components that can be referenced across endpoints and the documentation as a whole.
4. By using a consistent naming convention for the fields, there's a set standard that can reduce ambiguity for developers integrating with the API and using the documentation simultaneously. 

But, I would also:

1. Analyse how new fields can affect existing documentation, and find the best touch points to highlight these changes.
2. Include migration assistance for big changes, so that users can adapt their applications to accommodate new requirements and fields.

If this documentation task was in my backlog, some of the **questions I would have to ask the developers** and product managers would revolve around the specifics of this feature as a whole. Stuff like:

- How many files can users upload?
- Can users upload multiple files at a time?
- What's the maximum size limit for each upload?
- What's the maximum size or number of objects a user can have?
- What kind of files are accepted?
- What other ways can they upload files? Are there limitations for the different methods?
- Any restrictions or character limits on folder and file names?
- Are there any planned behaviours or fields to anticipate? (so the documentation can be structured accordingly)

---
I hope these meet(or exceed) your expectations for this task. ^_^
