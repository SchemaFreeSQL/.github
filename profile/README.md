# SchemafreeSQL

## SchemafreeSQL is a cloud datastore for Radical Data Structures
Radical Data Structures have the same _fluidity_ as code. Instead of the typical process of modeling data structures and then coding within the confines of those models, you code your application and the structure of the data follows. The idea is simple, but the implications are "radical". And the end result is that you become a more productive developer.

### Features

- _INSTANT_: No schemas to create. No collections to create. No indexes to manage. No drivers to install.
- _SIMPLE_: Create, modify and query complex structures with ease
- _POWERFUL_: Use sensible, normalized data structures with any-to-any Object References
- _FEARLESS_: Safely alter data structures with Classless Objects and evolve their names and locations
- _SQL_: Perform adhoc queries using a familiar SQL-like language


### Demo Apps
Working with data should NOT be difficult, especially when you are trying to simplify your infrastructure within a serverless paradigm.

To illustrate how easy it can be, our non-techie CEO wrote some demo apps _(live demos included)_:
| Demo | About | github link | Live Demo |
| ------ | ------ | ------ | ------ |
| Shop Admin | A single payload both populates a SFSQL Cloud datastore and queries suppliers, products, customers and orders. (PHP, Cloudfalre Worker, Deno Deploy, Netlify(AWS Lambda), Google CF). This is our "Hello World" App  | [apps/shopadmin](https://github.com/SchemaFreeSQL/apps/tree/main/shopadmin) | [PHP](https://schemafreesql.com/shopadmin/) [CF Worker](https://shopadmin.sfsql.workers.dev/) [Deno Deploy](https://sfsqlshopadmin.deno.dev/) [Netlify (AWS Lambda)](https://harmonious-mermaid-c4d794.netlify.app/.netlify/functions/shopadmin) [GCF](https://us-east1-sfsql-347312.cloudfunctions.net/shopadmin)
| Todo List | todo list in varioes platforms (PHP, Cloudfalre Worker, Deno Deploy) | [apps/todo](https://github.com/SchemaFreeSQL/apps/tree/main/todo) |[PHP](https://schemafreesql.com/apps/todo/) [CF Worker](https://sfsqltodo.sfsql.workers.dev/) [Deno Deploy](https://sfsqltodo.deno.dev/)
| Blog  | a simple PHP blog platform | [apps/blog](https://github.com/SchemaFreeSQL/apps/tree/main/blog/php) | [Blog](https://schemafreesql.com/apps/blog/)
| Object Tree Walker  | a PHP script to navigate SFSQL Objects. This run against the root of a SFSQL CLoud datastore. It is read only and meant to run behind a secure login unless you want to make your data public  | [apps/objectTreeWalker](https://github.com/SchemaFreeSQL/apps/tree/main/objectTreeWalker/php) | [Object Tree Walker](https://schemafreesql.com/showgraph/index.php)
| Netlify Site  | a Netlify site continig the Todo and Shop Admin apps via Netlify AWS Lambda funstions | [/netlifysite](https://github.com/SchemaFreeSQL/netlifysite) | [Site](https://harmonious-mermaid-c4d794.netlify.app//)
