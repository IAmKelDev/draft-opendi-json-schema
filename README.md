# json-schema-internal
Internal repository for the OpenDI JSON Schema definition.

# Getting up to speed

The best way to get familiar with the schema is to browse some test data. See `test-data.json`.  
Ideally, clone the repo to a dev environment that has JSON Schema integration, like VS Code. See instructions below.

Alternatively, there is static HTML documentation in `docs/schema_docs.html`.  
These docs pull information directly from the schema and presents it in a more readable format. 

## VS Code

1. Clone the repository to a local folder.
2. Open the repository folder VS Code.
3. In VS Code, open `test-data.json`.
4. Hover over portions of the test data to see popups for the title and description information included in the schema.
5. Try adding to the test data. Use the [Problems Panel](https://code.visualstudio.com/docs/editor/editingevolved#_errors-warnings) to see what changes would bring your data into schema compliance (missing/malformed fields, etc).

# Resources Used

The OpenDI JSON Schema definition is based on the Schema specifications managed by [JSON-Schema.org](https://json-schema.org/).

Static HTML documentation is generated with [JSON Schema For Humans](https://github.com/coveooss/json-schema-for-humans).
