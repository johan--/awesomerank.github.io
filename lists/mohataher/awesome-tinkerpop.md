<h1 align="center">
Ranked awesome lists, all in one place
</h1>
<p align="center">
	This list is a copy of <a href="mohataher/awesome-tinkerpop">mohataher/awesome-tinkerpop</a> with ranks
</p>
---
# Awesome TinkerPop [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★59088](sindresorhus/awesome)

![alt tag](https://raw.githubusercontent.com/mohataher/awesome-tinkerpop/master/tinkerpop-splash.png)


A curated list of only awesome TinkerPop libraries on Github.

>Apache TinkerPop™ is a graph computing framework for both graph databases (OLTP) and graph analytic systems (OLAP).

### Table of Contents
* [TinkerPop3](#tinkerpop3)
	- [Implementations](#tinkerpop3-implementations)
	- [Wrappers/Clients](#wrappers)
	- [Query Languages](#qlang)
* [TinkerPop2](#tinkerpop2)
* [Communites](#communites)
* [People to Follow](#people-to-follow)
* [Tutorials and Resources](#tutorials-and-resources)
* [How to Contribute](#contributing)
* [License](#license)

### <A NAME="tinkerpop3"></A>TinkerPop3 Libraries
#### <A NAME="tinkerpop3-implementations"></A>Implementations
* [TinkerPop3 implementation ★352](apache/tinkerpop) - Mirror of Apache TinkerPop.
* [sqlg ★84](pietermartin/sqlg) - Sqlg is a implementation of TinkerPop3 on a RDBMS.
* [blazegraph](https://github.com/blazegraph/database) - TinkerPop3 [implementation ★18 ⏳1Y](blazegraph/tinkerpop3) for Blaze Graph; a high performance graph database.
* [tinkergraph-js ★34 ⏳1Y](jbmusso/tinkergraph-js) - A pure JavaScript implementation of TinkerPop's TinkerGraph in-memory graph database.
* [gremlin-javascript ★112](jbmusso/gremlin-javascript) - JavaScript graph database client for TinkerPop3 Gremlin Server.
* [Elastic Gremlin ★59 ⏳1Y](rmagen/elastic-gremlin) - TinkerPop3 implementation on Elasticsearch backend.
* [Hadoop (Giraph)](http://tinkerpop.apache.org/docs/current/reference/#giraphgraphcomputer) - OLAP graph processor using Giraph.
* [Hadoop (Spark)](http://tinkerpop.apache.org/docs/current/reference/#sparkgraphcomputer) - OLAP graph processor using Spark.
* [IBM Graph](https://console.ng.bluemix.net/catalog/services/ibm-graph/) - OLTP graph database as a service.
* [Neo4j](http://tinkerpop.apache.org/docs/currentg/#neo4j-gremlin) - OLTP graph database.
* [Stardog](http://stardog.com/) - RDF graph database with OLTP and OLAP support.
* [TinkerGraph](http://tinkerpop.apache.org/docs/current/reference/#tinkergraph-gremlin) - In-memory OLTP and OLAP reference implementation.
* [Titan](http://thinkaurelius.github.io/titan/) - Distributed OLTP and OLAP graph database with BerkeleyDB, Cassandra and HBase support.
* [Titan (Amazon) ★256](awslabs/dynamodb-titan-storage-backend) - The Amazon DynamoDB storage backend for Titan.
* [Titan (Tupl) ★30](classmethod/tupl-titan-storage-backend) - The Tupl storage backend for Titan.
* [Unipop](https://github.com/rmagen/unipop) - OLTP Elasticsearch and JDBC backed graph.
* [DuctileDB ★14](PureSolTechnologies/DuctileDB) - Ductile DB is a graph database based on Hadoop/HBase which provides a vast set of features.
* [hgraphdb ★55](rayokota/hgraphdb) - HBase as a TinkerPop Graph Database.
* [JanusGraph ★503](JanusGraph/janusgraph) - JanusGraph: an open-source, distributed graph database http://janusgraph.org


#### <A NAME="wrappers"></A>Wrappers/Clients
##### C# .NET
*   [Teva Gremlin](https://www.nuget.org/packages/Teva.Common.Data.Gremlin/) (.NET - C#) - A Gremlin Server driver for .NET.

##### Clojure
* [ogre ★81](clojurewerkz/ogre) - Clojure library for querying TinkerPop graphs.
* [scalajs-gremlin-client ★6 ⏳1Y](viagraphs/scalajs-gremlin-client) (scala) - A Gremlin-Server client with ad-hoc extensible, reactive, typeclass based API.

##### Go
* [go-gremlin ★28](go-gremlin/gremlin) - Go graph database client for TinkerPop3 Gremlin Server.
* [Gremgo ★26](qasaur/gremgo) - A fast, efficient, and easy-to-use Go client for the TinkerPop graph database stack.

##### Haskell
* [gremlin-haskell ★6 ⏳1Y](nakaji-dayo/gremlin-haskell) - Haskell graph database client for TinkerPop3 Gremlin Server.

##### Java
* [gremlin-driver](http://tinkerpop.apache.org/docs/current/reference/#connecting-via-java) (java) - A Gremlin Server driver for Java.
* [neo4j-tinkerpop-api ★4 ⏳2Y](neo4j-contrib/neo4j-tinkerpop-api) - Apache Licensed Neo4j API for TinkerPop3.
* [neo4j-gremlin-bolt ★22](SteelBridgeLabs/neo4j-gremlin-bolt) - Allows use of the Apache Tinkerpop Java API with the neo4j server using the BOLT protocol.

##### Javascript
* [ts-tinkerpop ★25 ⏳1Y](RedSeal-co/ts-tinkerpop) - Utilities for using TinkerPop3 via the node-java API in Typescript.
* [gremlin-javascript ★112](jbmusso/gremlin-javascript) (js) - A Gremlin Server driver for JavaScript.

##### PHP
* [gremlin-php ★27](PommeVerte/gremlin-php) - gremlin-server php driver compatible with TinkerPop3. It will allow you to connect to gremlin-server and it's backends (Neo4J, Titan, etc.).

##### Python
* [Mogwai ★38 ⏳1Y](platinummonkey/mogwai) - TinkerPop3 Graph Database Library for Python.
* [python-gremlin-rest ★1](windj007/python-gremlin-rest) - A REST-based client for Gremlin Server.
* [gremlinclient ★21](davebshow/gremlinclient) - An asynchronous Python 2/3 client for Gremlin Server that allows for flexible coroutine syntax - Trollius, Tornado, Asyncio.
* [aiogremlin ★24](davebshow/aiogremlin) (python) - A Python 3 library based on asyncio and aiohttp that uses websockets to communicate with the Gremlin Server.
* [gremlinrestclient](http://gremlinrestclient.readthedocs.org/en/latest/) (python) - Python 2/3 library that uses HTTP to communicate with the Gremlin Server over REST.
* [goblin](https://github.com/ZEROFAIL/goblin) - OGM for TinkerPop3 Gremlin Server.
* [goblin 3.5 ★35](davebshow/goblin) - A Python 3.5 rewrite of the TinkerPop 3 OGM Goblin.

##### Reactive
* [reactive-gremlin ★22](coreyauger/reactive-gremlin) (scala) - An Akka HTTP Websocket Connector.

##### Scala
* [Gremlin Scala ★320](mpollmeier/gremlin-scala) - Scala wrapper for Apache TinkerPop3 Graph DSL.

#### <A NAME="qlang"></A>Query Languages
* [gremlin-py ★28](emehrkay/gremlinpy) - Write pure Python Gremlin that can be sent to Gremlin Server.
* [gremlin-scala ★320](mpollmeier/gremlin-scala) - A Scala language wrapper for TinkerPop3.
* [gremlin-template-string ★10 ⏳1Y](jbmusso/gremlin-template-string) - A Javascript Gremlin language builder.
* [ipython-gremlin ★8](davebshow/ipython-gremlin) - Gremlin in IPython and Jupyter.
* [ogre](http://ogre.clojurewerkz.org/) - A Clojure language wrapper for TinkerPop3.
* [Peapod ★31](bayofmany/peapod) - A new object-graph-wrapper for the Tinkerpop3 graph stack.
* [sparql-gremlin ★38 ⏳1Y](dkuppitz/sparql-gremlin) - A SPARQL to Gremlin traversal compiler.
* [sql-gremlin ★31](twilmes/sql-gremlin) - A SQL to Gremlin traversal compiler.

### <A NAME="tinkerpop2"></A>TinkerPop 2 Libraries
* [Ferma ★44](Syncleus/Ferma) - An active reworking of TinkerPop frames.
* [Frames ★139](tinkerpop/frames) - An Object to Graph Framework.
* [Archimedes ★36 ⏳1Y](clojurewerkz/archimedes) - Clojure library for Blueprints (part of the TinkerPop graph stack).
* [AccumuloGraph ★28 ⏳1Y](JHUAPL/AccumuloGraph) - An implementation of TinkerPop Blueprints using Accumulo.
* [Frontenac ★24](Loupi/Frontenac) - A .NET port of the TinkerPop Stack.
* [Mogwai ★38 ⏳1Y](platinummonkey/mogwai) - TinkerPop 2 Graph Database Library for Python.
* [spring-data-gremlin ★41](gjrwebber/spring-data-gremlin) - Spring data gremlin makes it easier to implement Graph based repositories. This module extends Spring Data to allow support for potentially any Graph database that implements the TinkerPop Blueprints 2.x API.
* [blueprints-scala ★81 ⏳1Y](anvie/blueprints-scala) - TinkerPop Blueprints Scala.

## <A NAME="communites"></A>Communities
* [Gremlin-users](https://groups.google.com/forum/#!forum/gremlin-users) - Mailing list for Gremlin users.
* [Stack Overflow](http://stackoverflow.com/questions/tagged/tinkerpop3) - Stack Overflow has a relatively active community.
* [TinkerPop-dev](http://mail-archives.apache.org/mod_mbox/incubator-tinkerpop-dev/) - Mailing list for TP3 deverlopers.

## <A NAME="people-to-follow"></A>People to Follow 
* [Marko Rodriguez](https://markorodriguez.com/) - Founder of TinkerPop and Aurelius.
* [Stephen Mallette](https://twitter.com/spmallette?lang=en-gb) - Senior developer for Gremlin, TinkerPop and Titan DB.
* [Daniel Kuppitz](https://about.me/daniel.kuppitz) - One of the main developers of Gremlin.
* [Jason Plurad](https://github.com/pluradj) - Senior Developer at IBM. TinkerPop committer and active on the community.

## <A NAME="tutorials-and-resources"></A>Tutorials and Resources
* [Introduction to Gremlin](http://tinkerpop.apache.org/gremlin.html) - Official introduction to the Gremlin language.
* [Datastax Introduction](https://academy.datastax.com/resources/getting-started-tinkerpop-and-gremlin) - A tutorial provided by Datastax to Gremlin and TinkerPop3.
* [TinkerPop Book](http://www.tinkerpopbook.com/) - A long promised book for Tinkeprop but never fulfilled until now. You cans till request a notification.
* [Linux Foundation Presentation](http://events.linuxfoundation.org/sites/events/files/slides/ApacheCon2015TinkerPop3.pdf) - A presentation by Linux Foundation given by David Robinson at IBM aboit Apache TinkerPop3.
* [Getting Started with TinkerPop](http://tinkerpop.apache.org/docs/current/tutorials/getting-started/) - Learn the basics of getting up and going with TinkerPop.
* [The Gremlin Console](http://tinkerpop.apache.org/docs/current/tutorials/the-gremlin-console/) - Discusses uses cases of the Gremlin Console and usage patterns.
* [Gremlin Recipes](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/recipes/) - Reference for common traversal patterns and style.
* [Gremlin Language Variants](http://tinkerpop.apache.org/docs/3.2.1-SNAPSHOT/tutorials/gremlin-language-variants/) - Learn how to embed Gremlin in a host programming language.
* [SQL2Gremlin](http://sql2gremlin.com/) - Learn Gremlin using typical patterns found when querying data with SQL.
* [Getting Started with Graph Databases](https://academy.datastax.com/demos/getting-started-graph-databases) - Compares relational databases to graph databases and SQL to Gremlin.


## <A NAME="contributing"></A>How to Contribute
Please follow the [guideliness here](https://github.com/mohataher/awesome-tinkerpop/blob/master/contributing.md). Please, make sure your contribution and PR are awesome!
![alt tag](https://github.com/mohataher/awesome-tinkerpop/blob/master/awesome-tinkerpop.jpg)


## <A NAME="license"></A>License
[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [@mohataher](https://github.com/mohataher) has waived all copyright and related or neighboring rights to this work.
---
<p align="center">
	This list is a copy of <a href="mohataher/awesome-tinkerpop">mohataher/awesome-tinkerpop</a> with ranks
</p>
