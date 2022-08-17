# Task: 2 - Create REST API using NestJS

You created a simple REST API using Express on NodeJS in the previous task. To complete this task, create a new REST API using NestJS for the same specification. Use the default repository pattern in NestJS to organize your modules. (Reading more about Resource Generator -- CRUD Generator -- on NestJS will expedite your development process.)

<center>
<img src="https://camo.githubusercontent.com/5f54c0817521724a2deae8dedf0c280a589fd0aa9bffd7f19fa6254bb52e996a/68747470733a2f2f6e6573746a732e636f6d2f696d672f6c6f676f2d736d616c6c2e737667" alt="NestJS" width="100">
</center>

## Database + ORM

Creating a database was not required during the previous task and you used JSON files to handle that. You can utilize a simple database solution for this task. In order to do that, you can use [TypeORM](https://typeorm.io/) and [NestJS wrapper around the package](https://www.npmjs.com/package/@nestjs/typeorm). You can find its documentation for more information [here](https://docs.nestjs.com/techniques/database).

<center>
<img src="https://github.com/typeorm/typeorm/raw/master/resources/logo_big.png" width=200>
</center>

## Swagger UI

You implemented Swagger UI (OpenAPI) on your Express Application using `tsoa` in the previous task. When using NestJS, you can use its own implementation of Swagger UI to build the API documentation. This will enable you to run tests while developing your application without having to switch between appllications too often.

You can find the documentation for `@nestjs/swagger` at this URL: https://docs.nestjs.com/openapi/introduction.

## Take-aways 📦

- How to create a REST API using NestJS
- How to use TypeORM for managing database queries
- How to implement Swagger UI for NestJS Applications
