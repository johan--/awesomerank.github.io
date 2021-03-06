<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="stve/awesome-dropwizard">stve/awesome-dropwizard</a> with ranks
</p>
---
# Awesome Dropwizard [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)][awesome]

[<img src="https://cdn.rawgit.com/stve/awesome-dropwizard/master/dropwizard-hat.png" align="right" width="50">][dropwizard]

[awesome]: https://github.com/sindresorhus/awesome
[dropwizard]: http://www.dropwizard.io

> Useful resources for creating apps with [Dropwizard](http://www.dropwizard.io)

### Contributing

Please take a quick look at the [contribution guidelines](https://github.com/stve/awesome-dropwizard/blob/master/CONTRIBUTING.md) first.

## Editor Support

*Support for your favorite editors.*

### Eclipse

* [dropwizard-tools ★2 ⏳1Y](Tasktop/dropwizard-tools) - Eclipse Tools for Dropwizard

## Open Source

* [dropwizard-swagger ★83](smoketurner/dropwizard-swagger) - Serves Swagger UI static content and loads Swagger endpoints.
* [dropwizard-jaxws ★38](roskart/dropwizard-jaxws) - enables building SOAP web services and clients using JAX-WS API.
* [dropwizard-redirect-bundle ★13](bazaarvoice/dropwizard-redirect-bundle) - allows for HTTP redirects.
* [dropwizard-template-config ★37](tkrille/dropwizard-template-config) - enables you to write your config.yaml as a Freemarker template.
* [dropwizard-caching-bundle ★7 ⏳1Y](bazaarvoice/dropwizard-caching-bundle) - generate cache-control options for resources and caching responses.
* [dropwizard-xml ★24](yunspace/dropwizard-xml) - Dropwizard bundle for processing and validating XMLs
* [dropwizard-crypto ★12](meltmedia/dropwizard-crypto) - A Cryptographic Bundle for Dropwizard
* [dropwizard-circuitbreaker ★18](mtakaki/dropwizard-circuitbreaker) - A circuit breaker design pattern for dropwizard
* [dropwizard-maxmind-bundle ★3](phaneesh/dropwizard-maxmind-bundle) - MaxMind GeoIP2 support for dropwizard
* [dropwizard-protobuf ★34](dropwizard/dropwizard-protobuf) - Support for reading and writing Google Protocol Buffer objects within Dropwizard
* [dropwizard-activemq-bundle ★29](mbknor/dropwizard-activemq-bundle) - send and receive JSON via ActiveMQ in your Dropwizard application
* [dropwizard-consul ★40](smoketurner/dropwizard-consul) - A Consul bundle for Dropwizard
* [dropwizard-zipkin ★31](smoketurner/dropwizard-zipkin) - A Zipkin bundle for Dropwizard
* [dropwizard-graphql ★9](smoketurner/dropwizard-graphql) - A GraphQL bundle for Dropwizard
* [dropwizard-money ★1](smoketurner/dropwizard-money) - A Money bundle for Dropwizard
* [breakerbox ★55](yammer/breakerbox) - Frontend for Tenacity + Archaius
* [tenacity ★194](yammer/tenacity) - A Hystrix bundle for Dropwizard
* [dropwizard-grpc ★9](msteinhoff/dropwizard-grpc) - use a gRPC server in a Dropwizard service
* [sqs-dropwizard ★9](bascan/sqs-dropwizard) - Amazon SQS integration
* [dropwizard-simple-cors ★0](ojacobson/dropwizard-simple-cors) - A Dropwizard bundle to provide simple, sensible CORS support
* [dropwizard-version-info ★5](palantir/dropwizard-version-info) - A Dropwizard bundle which exposes a version endpoint

### Authentication

* [dropwizard-auth-ldap ★30](yammer/dropwizard-auth-ldap) - LDAP authentication for Dropwizard
* [dropwizard-jwt-cookie-authentication ★16](dhatim/dropwizard-jwt-cookie-authentication) - Dropwizard bundle managing authentication through JWT cookies

### Assets

* [dropwizard-configurable-assets-bundle ★59](bazaarvoice/dropwizard-configurable-assets-bundle) - An implementation of an AssetBundle for use in Dropwizard that allows user configuration.
* [dropwizard-markdown-assets-bundle ★1](rnorth/dropwizard-markdown-assets-bundle) - renders Markdown files as pretty HTML

### Data Stores

* [dropwizard-etcd ★4](meltmedia/dropwizard-etcd) - A Dropwizard Bundle for Etcd
* [dropwizard-mongo ★21 ⏳2Y](eeb/dropwizard-mongo) - Factories and health checks for connecting to mongoDB.
* [dropwizard-elasticsearch ★47](dropwizard/dropwizard-elasticsearch) - A set of classes for using Elasticsearch in a Dropwizard service
* [dropwizard-service-discovery ★3](santanusinha/dropwizard-service-discovery) - Zookeeper service discovery bundle and client for dropwizard.
* [dropwizard-cassandra ★58](composable-systems/dropwizard-cassandra) - Dropwizard support for Cassandra
* [dropwizard-riak ★1](smoketurner/dropwizard-riak) - Dropwizard support for Riak
* [dropwizard-orient-server ★12](xvik/dropwizard-orient-server) - Embedded OrientDB server for dropwizard

### Metrics

* [riemann-bundle ★0](phaneesh/riemann-bundle) - Simplifies dropwizard metrics integration into Riemann
* [metrics](http://metrics.dropwizard.io/3.1.0/manual/third-party/) - Metrics Libraries

### Logging

* [dropwizard-gelf ★44](gini/dropwizard-gelf) - Addon bundle for Dropwizard to support logging to a GELF-enabled servers
* [dropwizard-raven ★13](tradier/dropwizard-raven) - Dropwizard integration for error logging to Sentry
* [dropwizard-logstash-encoder ★12](Wikia/dropwizard-logstash-encoder) - Dropwizard logging addon for sending logs using the logstash-logback-encoder

### Scheduled/Recurrence Jobs

* [dropwizard-quartz ★54 ⏳1Y](jaredstehler/dropwizard-quartz) - Simple Job Scheduler implementation integrating Guice and Quartz.
* [dropwizard-jobs ★89](spinscale/dropwizard-jobs) - Quartz integration for dropwizard
* [dropwizard-sundial ★22](timmolter/dropwizard-sundial) - Scheduled jobs in Dropwizard using Sundial

### Guice

* [dropwizard-guice ★227](HubSpot/dropwizard-guice) - Adds support for Guice.
* [dropwizard-guicey ★100](xvik/dropwizard-guicey) - Dropwizard guice integration
* [dropwizard-guicier ★13](HubSpot/dropwizard-guicier) - A Dropwizard bundle to handle Guice integration.

### Deployment

* [WizToWar ★41 ⏳2Y](twilio/wiztowar) - Build WARs from your Dropwizard apps
* [wizard-in-a-box ★29](rvs-fluid-it/wizard-in-a-box) - deploy Dropwizard apps as a war

## Tutorials

* [Getting Started](http://www.dropwizard.io/0.9.2/docs/getting-started.html)
* [Official docs](http://www.dropwizard.io/0.9.2/docs/manual/index.html)
* [Dropwizard internals](http://www.dropwizard.io/0.9.2/docs/manual/internals.html)
* [Dropwizard Modules Directory](http://modules.dropwizard.io/)

## Guides

* [Serving Static Assets with DropWizard](https://spin.atomicobject.com/2014/10/11/serving-static-assets-with-dropwizard/)
* [Hooking up Custom Jersey Servlets in Dropwizard](https://spin.atomicobject.com/2015/03/30/jersey-servlets-dropwizard/)
* [Using Hibernate DAOs in DropWizard Tasks](https://spin.atomicobject.com/2015/02/03/dropwizard-hibernate-dao/)
* [Hibernate in Dropwizard CLI Commands](http://clearthehaze.com/2015/04/hibernate-in-dropwizard-cli-commands/)
* [Heroku for Highly Available Dropwizard Apps](http://techbytes.anuragkapur.com/2015/05/heroku-for-highly-available-dropwizard.html?m=1)
* [Enabling Newrelic for Dropwizard](http://kyleboon.org/blog/2013/09/23/newrelic-for-dropwizard/)
* [Application Health Checks with DropWizard](http://willhamill.com/2014/12/04/application-health-checks-with-dropwizard)
* [Using Hystrix with Dropwizard](http://christopher-batey.blogspot.com/2014/08/using-hystrix-with-dropwizard.html)
* [Using Dropwizard in combination with Elasticsearch](http://www.gridshore.nl/2014/05/15/using-dropwizard-combination-elasticsearch/)
* [Deploy a Dropwizard Unikernel to AWS](https://boxfuse.com/blog/dropwizard-aws.html)
* [Use Consul's KV store for Dropwizard settings](http://blog.remmelt.com/2015/06/09/use-consuls-kv-store-for-dropwizard-settings/)
* [Deploying Dropwizard on App Engine Flex](https://www.aytech.ca/blog/dropwizard-app-engine-flexible-env/)
* [Measuring the performance of your Dropwizard application](https://www.aytech.ca/blog/measuring-performance-dropwizard-application/)
* [Heroku + Gradle + Dropwizard](https://www.aytech.ca/blog/heroku-gradle-dropwizard/)

## Community

* [dropwizard-user](https://groups.google.com/forum/#!forum/dropwizard-user)
* [StackOverflow](http://stackoverflow.com/questions/tagged/dropwizard)
* [`@dropwizardio` on twitter](https://twitter.com/dropwizardio)

## Videos

* [Introduction to Dropwizard](https://www.youtube.com/watch?v=2tSWsjtw0ms)
* [Instant-ish Real Service Architecture](https://vimeo.com/37930578)

## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/stve/awesome-dropwizard/blob/master/CONTRIBUTING.md) first.

## Awesome!

Check out more [awesome projects ★59088](sindresorhus/awesome).

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Steve Agalloco](http://beforeitwasround.com) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="stve/awesome-dropwizard">stve/awesome-dropwizard</a> with ranks
</p>
