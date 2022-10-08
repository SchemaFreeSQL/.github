# SchemafreeSQL

## SchemafreeSQL is a cloud datastore for Radical Data Structures
Radical Data Structures have the same _fluidity_ as code. Instead of the typical process of modeling data structures and then coding within the confines of those models, you code your application and the structure of the data follows. The idea is simple, but the implications are "radical". And the end result is that you become a more productive developer.

### Features

- _INSTANT_: No schemas to create. No collections to create. No indexes to manage. No drivers to install.
- _SIMPLE_: Create, modify and query complex structures with ease over a JSON-over-HTTP Data API
- _POWERFUL_: Use sensible, normalized data structures with any-to-any Object References
- _FEARLESS_: Safely alter data structures with Classless Objects and evolve their names and locations
- _SQL_: Perform adhoc queries using a familiar SQL-like language


### Demo Apps
Working with data should NOT be difficult, especially when you are trying to simplify your infrastructure within a serverless paradigm.

To illustrate how easy it can be, our non-techie CEO wrote some demo apps _(live demos included)_:
| Demo | About | github | Live Demos |
|:------ |:------ |:------ |:------ |
| Shop&nbsp;Admin | This is our "Hello World" Demo. A single payload that both populates a SFSQL Cloud datastore and queries suppliers, products, customers and orders. Demo available in various platforms and languages.  | [apps/shopadmin](https://github.com/SchemaFreeSQL/apps/tree/main/shopadmin) | [PHP](https://schemafreesql.com/shopadmin/) <br/>[CF&nbsp;Worker](https://shopadmin.sfsql.workers.dev/) <br/>[Deno&nbsp;Deploy](https://sfsqlshopadmin.deno.dev/) <br/>[Netlify&nbsp;(AWS&nbsp;Lambda)](https://harmonious-mermaid-c4d794.netlify.app/.netlify/functions/shopadmin) <br/>[GCF](https://us-east1-sfsql-347312.cloudfunctions.net/shopadmin) <br/>[Azure](https://sfsqltodo.azurewebsites.net/api/shopadmin)
| Todo&nbsp;List | Todo List App in varioes platforms | [apps/todo](https://github.com/SchemaFreeSQL/apps/tree/main/todo) | [PHP](https://schemafreesql.com/apps/todo/) <br/>[CF&nbsp;Worker](https://sfsqltodo.sfsql.workers.dev/) <br/>[Deno&nbsp;Deploy](https://sfsqltodo.deno.dev/) <br/>[GCF](https://us-east1-sfsql-347312.cloudfunctions.net/sfsqltodo) <br/>[Azure](https://sfsqltodo.azurewebsites.net/api/todo)<br>[Netlify (AWS Lambda)](https://harmonious-mermaid-c4d794.netlify.app/todo)
| Blog  | A simple PHP blog | [apps/blog](https://github.com/SchemaFreeSQL/apps/tree/main/blog/php) | [Blog](https://schemafreesql.com/apps/blog/)
| Object&nbsp;Tree&nbsp;Walker  | A PHP script to navigate SFSQL Objects. This run against the root of a SFSQL CLoud datastore. It is read only and meant to run behind a secure login unless you want to make your data public  | [apps/objectTreeWalker](https://github.com/SchemaFreeSQL/apps/tree/main/objectTreeWalker/php) | [Object&nbsp;Tree&nbsp;Walker](https://schemafreesql.com/showgraph/index.php)
| Netlify&nbsp;Site  | A Netlify site containing the Todo, Shop Admin and GOT demos using edge Netlify AWS Lambda functions | [/netlifysite](https://github.com/SchemaFreeSQL/netlifysite) | [Site](https://harmonious-mermaid-c4d794.netlify.app//)
| GOT&nbsp;Most Connected  | Game of Thrones Most Connected Graphical Display |[PHP](https://github.com/SchemaFreeSQL/apps/tree/main/got) <br> [Netlify  Functions](https://github.com/SchemaFreeSQL/netlifysite/tree/main/netlify/functions) |[PHP](https://schemafreesql.com/apps/got/) <br> [Netlify](https://harmonious-mermaid-c4d794.netlify.app//got)
