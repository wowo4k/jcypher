jcypher
=======

JCypher aims to provide seamlessly integrated Java access to graph databases (Neo4J) at different levels of abstraction.

- At the bottom level a 'Native Java DSL' in form of a fluent Java API allows to intuitively and comfortably formulate queries against graph databases.
   The DSL (Domain Specific Language) is based on the CYPHER language. Hence the name JCypher.
   (The Cypher Language is developed as part of the Neo4J Graph Database by 'Neo Technology').
   The DSL provides all the power and expressiveness of the Cypher language.

- At the next level of abstraction, access to graph databases is provided based on a generic graph model.
   The model consists of nodes, relations, and paths, together with properties, labels, and types. While simple, the model allows to easily manipulate graphs.

- At the top level, arbitrarily complex business domains can be mapped to graph databases in a completely non-invasive way (not even annotations invading the business model).
   Additionally, JCypher provides database access in a uniform way to remote as well as to embedded databases (including in-memory databases).

Please have a look at: https://github.com/Wolfgang-Schuetzelhofer/jcypher/wiki for a more comprehensive documentation. There you will also find code snippets, references to samples, tipps on how
to get started with JCypher, and you will be informed about future directions.

For more information about Neo4J have a look at: http://www.neo4j.org/
</br>For more information about the CYPHER language have a look at: http://docs.neo4j.org/chunked/stable/cypher-query-lang.html

For adding JCypher as a Maven dependency:

```xml
<dependency>
  <groupId>net.iot-solutions.graphdb</groupId>
   <artifactId>jcypher</artifactId>
   <version>1.0.0</version>
</dependency>
```

Copyright (c) 2014 IoT-Solutions e.U.

License:
								Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/