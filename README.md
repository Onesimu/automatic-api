The following is a list of tools that automatically expose a REST, GraphQL, or another kind of API for your database.

|                          Project name/link                           |                                                     Database(s) supported                                                     | API type |       Implementation language       |                       License                       |                      GitHub stats                       |                                                                   Notes                                                                    |
|----------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|----------|-------------------------------------|-----------------------------------------------------|---------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [Datasette](https://github.com/simonw/datasette)                     | SQLite 3                                                                                                                      | REST     | Python 3                            | Apache 2.0                                          | 1107&nbsp;★; 253&nbsp;commits, latest&nbsp;2017-12-15   | Read-only.                                                                                                                                 |
| [DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory) | MySQL, PostgreSQL, SQLite, MongoDB, CouchDB, and [others](https://www.dreamfactory.com/products).                             | REST     | PHP 5                               | Apache 2.0, proprietary (optional extras)           | 739&nbsp;★; 760&nbsp;commits, latest&nbsp;2017-11-16    |                                                                                                                                            |
| [Eve](https://github.com/pyeve/eve)                                  | MongoDB; extensions for Elasticsearch, Neo4j, SQLAlchemy (SQL databases).                                                     | REST     | Python 2/3                          | BSD (three-clause)                                  | 4641&nbsp;★; 2706&nbsp;commits, latest&nbsp;2017-12-06  | The SQLAlchemy extension isn't automatic. It requires the user to write SQLAlchemy mappings.                                               |
| [HTSQL](https://bitbucket.org/prometheus/htsql/src)                  | MySQL, PostgreSQL, SQLite (free); Oracle, MS SQL (proprietary)                                                                | REST     | Python 2                            | GNU AGPLv3, proprietary (Oracle and MS SQL support) | n/a                                                     |                                                                                                                                            |
| [neo4j-graphql](https://github.com/neo4j-graphql/neo4j-graphql)      | Neo4j                                                                                                                         | GraphQL  | Kotlin                              | Apache 2.0                                          | 147&nbsp;★; 108&nbsp;commits, latest&nbsp;2017-09-23    | Can generate a GraphQL API from an existing database or derive a new database model from a GraphQL schema and auto-generate the resolvers. |
| [PHP-CRUD-API](https://github.com/mevdschee/php-crud-api)            | MySQL, PostgreSQL, MS SQL Server 2012. Limited support for SQLite 3.                                                          | REST     | PHP 5                               | MIT                                                 | 1238&nbsp;★; 1004&nbsp;commits, latest&nbsp;2017-11-19  |                                                                                                                                            |
| [PostGraphQL](https://github.com/postgraphql/postgraphql)            | PostgreSQL                                                                                                                    | GraphQL  | TypeScript (Node.js)                | MIT                                                 | 4632&nbsp;★; 666&nbsp;commits, latest&nbsp;2017-12-25   |                                                                                                                                            |
| [PostgREST](https://github.com/begriffs/postgrest)                   | PostgreSQL                                                                                                                    | REST     | Haskell                             | MIT                                                 | 10107&nbsp;★; 1351&nbsp;commits, latest&nbsp;2017-12-12 |                                                                                                                                            |
| [pREST](https://github.com/prest/prest)                              | PostgreSQL                                                                                                                    | REST     | Go                                  | MIT                                                 | 1579&nbsp;★; 400&nbsp;commits, latest&nbsp;2017-12-20   |                                                                                                                                            |
| [RESTHeart](https://github.com/SoftInstigate/restheart)              | MongoDB                                                                                                                       | REST     | Java                                | GNU AGPLv3                                          | 411&nbsp;★; 1333&nbsp;commits, latest&nbsp;2017-12-17   |                                                                                                                                            |
| [sandman2](https://github.com/jeffknupp/sandman2)                    | All supported by SQLAlchemy (MySQL, PostgreSQL, SQLite, Oracle, MS SQL, and others).                                          | REST     | Python 2/3                          | Apache 2.0                                          | 663&nbsp;★; 129&nbsp;commits, latest&nbsp;2017-03-06    |                                                                                                                                            |
| [tuql](https://github.com/bradleyboy/tuql)                           | SQLite 3                                                                                                                      | GraphQL  | JavaScript (Node.js)                | MIT                                                 | 201&nbsp;★; 34&nbsp;commits, latest&nbsp;2017-11-22     | Read-only.                                                                                                                                 |
| [xmysql](https://github.com/o1lab/xmysql)                            | MySQL                                                                                                                         | REST     | JavaScript (Node.js)                | MIT                                                 | 1693&nbsp;★; 205&nbsp;commits, latest&nbsp;2017-12-07   |                                                                                                                                            |
| [ZenQuery](https://github.com/BjoernKW/ZenQuery)                     | PostgreSQL, MySQL, IBM Db2, Oracle Database, Microsoft SQL Server and [others](https://github.com/BjoernKW/ZenQuery#database) | REST     | Java (JavaScript for the front-end) | Apache 2.0                                          | 28&nbsp;★; 282&nbsp;commits, latest&nbsp;2017-01-31     | Read-only.                                                                                                                                 |


GitHub stats updated 2017-12-27. The commit count and the latest commit date are for the default branch (usually `master`).

# Contributing

Your contributions are welcome! Please submit a pull request or create an issue to add a new project to the list or to update an existing one. See [CONTRIBUTING](./CONTRIBUTING.md) for the details.

# License

This document and the data in `data/` are licensed under the [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). By contributing you agree to release your contribution under this license.
