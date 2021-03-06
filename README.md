<div align="center">
	<img width="500" height="350" src="media/awesome_moleculer.svg" alt="logo of awesome-moleculer repository">
	<br>
	<p>
		<a href="https://moleculer.services/support.html">Moleculer is supported by the community</a>
	</p>
	<br>
</div>

# Awesome Moleculer [![Mentioned in Awesome Node.js](https://awesome.re/mentioned-badge.svg)](https://github.com/sindresorhus/awesome-nodejs)

>A list of awesome things related to Moleculer microservices framework

- [Resources](#resources)
	- [Official Resources](#official-resources)
	- [Cheatsheets](#cheatsheets)
	- [Articles and Blog Posts](#articles-and-blog-posts)
	- [Talks](#talks)
- [Examples](#examples)
- [Templates](#templates)
	- [Javascript](#javascript)
	- [Typescript](#typescript)
- [Services](#services)
	- [Gateways](#gateways)
	- [Databases and Stores](#Databases-and-Stores)
	- [Metrics and Tracing](#metrics-and-tracing)
	- [General](#general)
	- [Security, Authentication and Authorization](#security-authentication-and-authorization)
	- [Others](#others)
- [Middlewares](#middlewares)
	- [Security](#security)
	- [Database](#database)
- [Mixins and Hooks](#mixins-and-hooks)
	- [Tasks, Queues and Jobs](#tasks-queues-and-jobs)
	- [Validation](#validation)
- [Tools](#tools)
- [Projects Using Moleculer](#projects-using-moleculer)
- [Polyglot Implementations](#polyglot-implementations)
	- [Java](#java)
	- [Python](#python)
	- [.NET Core](#.net-core)
	- [Go](#go)

--------

## Resources

### Official Resources
- [Website](https://moleculer.services/)
- [Docs](https://moleculer.services/docs)
- [Blog](https://medium.com/moleculer)
- [Gitter](https://gitter.im/moleculerjs/moleculer)
- [Twitter](https://twitter.com/MoleculerJS)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/moleculer)


### Cheatsheets
- [Core Cheatsheets](https://github.com/moleculerjs/moleculer-cheatsheets/blob/master/moleculer.js) - Cheatsheet for Moleculer's core functionalities
- [Web Gateway Cheatsheets](https://github.com/moleculerjs/moleculer-cheatsheets/blob/master/moleculer-web.js) - Cheatsheet for official gateway
- [DB Cheatsheets](https://github.com/moleculerjs/moleculer-cheatsheets/blob/master/moleculer-db.js) - Cheatsheet for official DB adapters
- [REPL Cheatsheets](https://github.com/moleculerjs/moleculer-cheatsheets/blob/master/moleculer-repl.sh) - Cheatsheet for official RELP tool
- [CLI Cheatsheets](https://github.com/moleculerjs/moleculer-cheatsheets/blob/master/moleculer-cli.sh) - Cheatsheet for Moleculer's command-line interface (CLI)

### Articles and Blog Posts

- [5 easy steps to create your REST microservice in NodeJS](https://medium.com/moleculer/5-easy-steps-to-create-your-rest-microservice-in-nodejs-94aede3249fc)
- [What are microservices and how to create one with Node and Moleculer.js](https://medium.com/@r.heygate.dev/microservices-with-moleculer-js-c7e68803ec09)
- [Moleculer — deployment thoughts](https://dankuida.com/moleculer-deployment-thoughts-8e0fc8c0fb07)

### Talks

- [Microservices 4 Real - Martín Acosta](https://www.youtube.com/watch?v=FrL8at9qGrQ) - Talk *in Spanish* from the JSDayUY 2017 about how a developer that used to work on monolithic apps started to learn and create a complete production app using a microservices architecture on top of Moleculer. [repo](https://github.com/tinchoz49/microservices-for-real)

## Examples

- [Conduit](https://github.com/moleculerjs/moleculer-examples/tree/master/conduit) -  Moleculer + Moleculer Web + Moleculer-DB + MongoDB + JWT + Redis Cacher + Docker
- [Blog](https://github.com/moleculerjs/moleculer-examples/tree/master/blog) - Moleculer + ExpressJS + Pug + Moleculer-DB + Mongoose + NATS + Redis Cacher + Traefik
- [Kanban - A Kanban board application](https://github.com/icebob/kantab) - Moleculer + Moleculer Web + Full authentication + ACL/RBAC + VueJS + VueX + Vue-router + Much much more
- [Moleculer + Babel Example Starter](https://github.com/tinchoz49/moleculer-babel-example)
- [moleculer-nextjs](https://github.com/davidroman0O/moleculer-nextjs) - Server-Side Rendering with Moleculer
- [nestjs-moleculer](https://github.com/jiangzhuo/nestjs-moleculer) - Moleculer Module For Nestjs Framework
- [moleculer-docker-development](https://github.com/nickreese/moleculer-docker-development) - Simple development enviroment for moleculer with Docker
- [moleculer-exploration](https://github.com/simsieg/Moleculer-exploration) - Simple microservices communicating via MoleculerJS.
- [moleculer-mysql-template](https://github.com/AGenson/moleculer-mysql-template) - Moleculer template for creating a secure web api, with a remote MySQL database, and a default account management.

## Templates

### Javascript
- [moleculer-template-project](https://github.com/moleculerjs/moleculer-template-project) - Project template for Javascript project.
- [moleculer-template-nano](https://github.com/moleculerjs/moleculer-template-nano) -
Minimal project template for Javascript project.
- [moleculer-template-addon](https://github.com/moleculerjs/moleculer-template-addon) - Addon template for moleculer-addons
- [moleculer-template-module](https://github.com/moleculerjs/moleculer-template-module) - Simple module template for [moleculer-cli](https://moleculer.services/docs/moleculer-cli.html). *Use it if you want to create a module for Moleculer*

### Typescript
- [moleculer-template-project-typescript](https://github.com/moleculerjs/moleculer-template-project-typescript) - Project template for Typescript project.
- [moleculer-template-nano-typescript](https://github.com/moleculerjs/moleculer-template-nano-typescript) - Minimal project template for Typescript project.

## Services

### Gateways
- [moleculer-web](https://moleculer.services/docs/moleculer-web.html) ![Official Moleculer Module][official] - HTTP gateway
- [moleculer-apollo-server](https://github.com/moleculerjs/moleculer-apollo-server) ![Official Moleculer Module][official] - [Apollo GraphQL](https://www.apollographql.com/) server for Moleculer
- [moleculer-graphql](https://github.com/MerlinLabs/moleculer-graphql#readme) - GraphQL Schema stitching over a microservice network for co-located type definitions.
- [moleculer-sc](https://github.com/tiaod/moleculer-sc#readme) - API Gateway using SocketCluster
- [hapi-moleculer](https://github.com/felipegcampos/hapi-moleculer) - Hapi-based HTTP gateway
- [moleculer-io](https://github.com/tiaod/moleculer-io) - Socket.IO-based gateway
- [moleculer-socketio](https://github.com/davidroman0O/moleculer-socketio) - Manage Socket.IO events like actions in services

### Databases and Stores
- [moleculer-db](https://github.com/moleculerjs/moleculer-db/tree/master/packages/moleculer-db#readme) ![Official Moleculer Module][official] - A [NeDB](https://github.com/louischatriot/nedb)-based service to persist your data
- [moleculer-db-adapter-mongo](https://github.com/moleculerjs/moleculer-db/tree/master/packages/moleculer-db-adapter-mongo#readme) ![Official Moleculer Module][official] - A [MongoDB](https://mongodb.github.io/node-mongodb-native/)-based service to persist your data
- [moleculer-db-adapter-mongoose](https://github.com/moleculerjs/moleculer-db/tree/master/packages/moleculer-db-adapter-mongoose#readme) ![Official Moleculer Module][official] - A [Mongoose](https://mongoosejs.com/)-based service to persist your data
- [moleculer-db-adapter-sequelize](https://github.com/moleculerjs/moleculer-db/tree/master/packages/moleculer-db-adapter-sequelize#readme) ![Official Moleculer Module][official] - A [Sequelize](http://docs.sequelizejs.com/)-based service to persist your data
- [moleculer-db-adapter-couchdb-nano](https://github.com/moleculerjs/moleculer-db/tree/master/packages/moleculer-db-adapter-couchdb-nano#readme) ![Official Moleculer Module][official] - A [CouchDB](http://couchdb.apache.org/) adapter for Moleculer using nano.js
- [moleculer-db-adapter-typeorm](https://github.com/dkuida/moleculer-db-adapter-typeorm#readme) - A [TypeORM](http://typeorm.io/)-based service to persist your data
- [moleculer-db-adapter-dynamodb](https://github.com/katsanva/moleculer-db-adapter-dynamodb) - A [DynamoDB](https://aws.amazon.com/dynamodb/) adapter for Moleculer DB service
- [moleculer-storage-google-cloud](https://github.com/hongkongkiwi/node-moleculer-storage-google-cloud) - A [Google Cloud Storage](https://cloud.google.com/storage/) module
- [moleculer-gundb](https://github.com/smart-matrix/moleculer-gundb) - A [GunDB](https://gun.eco) mixins for Moleculer DB service.


### Metrics and Tracing
- [moleculer-console-tracer](https://github.com/moleculerjs/moleculer-metrics/tree/master/packages/moleculer-console-tracer#readme) ![Official Moleculer Module][official] - Console-based service
- [moleculer-jaeger](https://github.com/moleculerjs/moleculer-metrics/tree/master/packages/moleculer-jaeger#readme) ![Official Moleculer Module][official] - [Jaeger](https://www.jaegertracing.io/)-based metrics service
- [moleculer-prometheus](https://github.com/moleculerjs/moleculer-metrics/tree/master/packages/moleculer-jaeger#readme) ![Official Moleculer Module][official] - [Prometheus](https://prometheus.io/)-based metrics service
- [moleculer-zipkin](https://github.com/moleculerjs/moleculer-metrics/tree/master/packages/moleculer-zipkin#readme) ![Official Moleculer Module][official] - [Zipkin](https://zipkin.io/)-based metrics service
- [moleculer-elastic-apm](https://github.com/intech/moleculer-elastic-apm#moleculer-elastic-apm) - [Elastic APM](https://www.elastic.co/solutions/apm)-based metrics service

### General
- [moleculer-fake](https://github.com/moleculerjs/moleculer-addons/tree/master/packages/moleculer-fake#readme) ![Official Moleculer Module][official] - Fake data generator by [Fakerator](https://github.com/icebob/fakerator)
- [moleculer-mail](https://github.com/moleculerjs/moleculer-addons/tree/master/packages/moleculer-mail#readme) ![Official Moleculer Module][official] - Email service based on [Nodemailer](https://nodemailer.com/about/)
- [moleculer-twilio](https://github.com/moleculerjs/moleculer-addons/tree/master/packages/moleculer-twilio#readme) ![Official Moleculer Module][official] - SMS service based on [Twilio  API](https://www.twilio.com/docs/usage/api)
- [moleculer-slack](https://github.com/moleculerjs/moleculer-addons/tree/master/packages/moleculer-slack#readme) ![Official Moleculer Module][official] - Send Messages to [Slack API](https://api.slack.com/)
- [moleculer-elasticsearch](https://github.com/moleculerjs/moleculer-addons/tree/master/packages/moleculer-elasticsearch) ![Official Moleculer Module][official] - [Elasticsearch](https://www.elastic.co/) service for Moleculer.
- [moleculer-flydrive](https://github.com/molobala/moleculer-flydrive#readme) -  Storage manager service with [Node Flydrive](https://github.com/Slynova-Org/node-flydrive)
- [moleculer-markdown](https://github.com/alsofronie/moleculer-markdown#readme) - Markdown to HTML Service

### Security, Authentication and Authorization
- [moleculer-protect-services](https://github.com/icebob/moleculer-protect-services) - [JWT](https://jwt.io/) protection for service actions
- [imicros-auth](https://github.com/al66/imicros-auth) - Authentication, Authorization and ACL services
- [moleculer-antivirus](https://github.com/designtesbrot/moleculer-antivirus) - Service for [ClamAV](https://www.clamav.net/) Antivirus Scanning
- [moleculer-vault](https://github.com/designtesbrot/moleculer-vault) - Service for [HashiCorp's Vault](https://www.vaultproject.io/)
- [oauth-moleculer](https://github.com/zerocowl/oauth-moleculer) - [OAuth2](https://oauth.net/2/) Server service

### Others
- [imicros-flow](https://github.com/al66/imicros-flow) - Service for loose coupled event handling
- [serverless-moleculer](https://github.com/davidroman0O/serverless-moleculer) - Serverless Framework handler for Moleculer
- [moleculer-state-machine](https://github.com/fugufish/moleculer-state-machine#readme) - State Machine mixin that extends a Moleculer Service to act as a finite-state machine.
- [moleculer-minio](https://github.com/designtesbrot/moleculer-minio) - Service providing actions for managing buckets and objects in an AWS S3 or [Minio](https://www.minio.io/) powered backend
- [moleculer-segment](https://github.com/winoteam/moleculer-segment) - Service for [Segment](https://segment.com/)
- [moleculer-sharp](https://github.com/designtesbrot/moleculer-sharp) - A Moleculer Service for Image Manipulation using [sharp](http://sharp.pixelplumbing.com/en/stable/)

## Middlewares

## Security
- [moleculer-middleware-permissions](https://github.com/Embraser01/moleculer-middleware-permissions) - A middleware solution to validate permissions of a request
- [Secure IDs](https://gist.github.com/icebob/5f71b4e7b38a06765c5912ba74c31857) - Encode & decode your IDs with [hashids](https://github.com/ivanakimov/hashids.js)

## Database
- [Memoize mixin for Moleculer services methods](https://gist.github.com/icebob/40a612ec3c453347aef7a808b82ab747) - Caching for Moleculer service [methods](https://moleculer.services/docs/0.13/services.html#Methods)
- [DB handler mixin for Moleculer DB](https://gist.github.com/icebob/a093d0011ff0fa0f29d02dc4324557be) - Swap easily between [MongoDB](https://www.mongodb.com/) for development & production and [NeDB](https://github.com/louischatriot/nedb) for unit testing
- [Cache cleaner mixin for Moleculer DB service](https://gist.github.com/icebob/a69082b3078c8769f66de6c6dc4e56ba)


## Mixins and Hooks
### Tasks, Queues and Jobs
- [moleculer-bee-queue](https://github.com/moleculerjs/moleculer-addons/tree/master/packages/moleculer-bee-queue#readme) ![Official Moleculer Module][official] - Task queue mixin for [Bee-Queue](https://github.com/bee-queue/bee-queue)
- [moleculer-bull](https://github.com/moleculerjs/moleculer-addons/tree/master/packages/moleculer-bull#readme) ![Official Moleculer Module][official] - Task queue mixin for [Bull](https://github.com/OptimalBits/bull)
- [moleculer-cron](https://github.com/davidroman0O/moleculer-cron#readme) - Cron mixin [Node-Cron](https://github.com/kelektiv/node-cron)

### Validation
- [Default](https://moleculer.services/docs/0.13/validating.html#Built-in-validator) - Moleculer's default validator is based on [fastest-validator](https://github.com/icebob/fastest-validator)
- [Joi](https://moleculer.services/docs/0.13/validating.html#Create-a-Joi-validator) - [Joi](https://github.com/hapijs/joi) based validator
- [moleculer-json-schema-validator](https://github.com/zhaoyao91/moleculer-json-schema-validator#readme) - [JSON Schema](https://json-schema.org/) validator

## Tools
- [moleculer-repl](https://moleculer.services/docs/0.13/moleculer-repl.html) ![Official Moleculer Module][official] - Interactive developer console
- [moleculer-cli](https://moleculer.services/docs/0.13/moleculer-cli.html) ![Official Moleculer Module][official] - Command-Line Tool for development & testing
- [moleculer-decorators](https://moleculer.services/docs/0.13/services.html#Use-decorators) - ES7/TS decorators for Service declaration



## Projects Using Moleculer
- [Concierge Auctions](https://www.conciergeauctions.com/)
- [ingenious](http://www.ingsw.com/)
- [THB](https://www.thb.co.in/)
- [Zaoblako](https://zaoblako.ru/)
- [Altcoin mining pools](http://altcoinminingpools.com)
- [zebbra](https://zebbra.ch/)
- [Uiza](https://uiza.io)
- [Distopik](https://www.mixanalog.com)
- [AMRetail](http://amretail.ru)
- [DAZTA](https://dazta.com)
- [SmartTones Media](http://www.smarttonesmedia.com/)
- [Helpster](https://www.helpster.asia/id/business-en/)
- [Textalk](https://www.textalk.com/)
- [GetTechDone](https://www.gtechd.com/)
- [Jarvify](https://jarvify.com/)
- [Sonda](https://www.sonda.com/en/)
- [Wino](https://wino.fr)

> If you don't see your company here, [tell us](https://github.com/moleculerjs/moleculer/issues/101).

## Polyglot Implementations
### Java
- [moleculer-java](https://github.com/moleculer-java/moleculer-java) - Java implementation of the Moleculer microservices framework
- [moleculer-java-web](https://github.com/moleculer-java/moleculer-java-web) - Java implementation of the API Gateway service for Moleculer framework
- [moleculer-java-repl](https://github.com/moleculer-java/moleculer-java-repl) - Java implementation of REPL module for Moleculer framework
- [moleculer-java-jmx](https://github.com/moleculer-java/moleculer-java-jmx) - [JMX](https://www.oracle.com/technetwork/java/javase/javamanagement-140525.html) service for Moleculer Framework

### Python
- [moleculer-python](https://github.com/ToGoBananas/moleculer-python) - Python implementation of the Moleculer microservices framework
### .NET Core
- [moleculer-net](https://github.com/alexandredenes/moleculer-net) - NET Core 2.1 implementation of the Moleculer microservices framework.

### Go
- [moleculer-go](https://github.com/roytan883/moleculer-go) - Go implementation of the Moleculer microservices framework

# Contact
Copyright (c) 2016-2018 MoleculerJS

[![@moleculerjs](https://img.shields.io/badge/github-moleculerjs-green.svg)](https://github.com/moleculerjs) [![@MoleculerJS](https://img.shields.io/badge/twitter-MoleculerJS-blue.svg)](https://twitter.com/MoleculerJS)

[official]: media/moleculer-tiny.png
