# Part 1: Querying Knowledge Graphs (KGs)

This section explains how to search and retrieve information from knowledge graphs using structured methods. The main tool covered is SPARQL, a query language designed for RDF data. SPARQL works like SQL and lets users search using triple patterns (subject, predicate, object). The readings also introduce other systems for storing and querying knowledge graphs, including relational databases and NoSQL options. Relational stores organize data in different ways: one big table of triples, property tables by subject, or split tables by property. NoSQL databases such as Neo4j and Cassandra are better at handling messy, large, or changing data. Neo4j uses a model where both relationships and nodes have properties and is easy to query with the Cypher language. Cassandra is good for high-speed storage and retrieval of massive data. Lastly, the readings explain special features like hypernodes and the difference between schema and instance graphs, which help manage more complex or real-world data.

## Key Takeaways
1. SPARQL helps users find information in knowledge graphs using patterns.
2. KGs can be stored in relational or NoSQL systems depending on the data type and size.
3. Tools like Neo4j and Cassandra help with fast, flexible graph queries.

## References
Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. *Knowledge Graphs: Fundamentals, Techniques, and Applications*. Cambridge, MA: MIT Press, 2021. Chapter 12, “Structured Querying,” 307–335. ISBN-13: 978-0262045094.  
W3C. “SPARQL 1.1 Query Language.” World Wide Web Consortium, March 21, 2013. https://www.w3.org/TR/sparql11-query/.  
Robinson, Ian, Jim Webber, and Emil Eifrem. *Graph Databases: New Opportunities for Connected Data*. 2nd ed. Sebastopol, CA: O’Reilly Media, 2015. https://neo4j.com/developer/graph-database/.

[Back to README](README.md)
