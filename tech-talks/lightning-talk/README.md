# Graph lightning talk

## Title

Graph Databases
Two Graphs in 15 minutes, 
aka: 11 slides in that same time. Let’s rock.
by Doug Auclair, guy with the tie

![title page](imgs/01-title.png)

## SQL ain’t what it used to be

* The problem with rows (are not accessed in constant time)
* The problem with relations (relations are not entities)
* The problem with schemata (schemata (‘schemas’) are imposed, not derived)

![SQL: Problems](imgs/02-sql-probs.png)

## Alternatives to SQL

* No, SQL is great, and stuff, don’t get me wrong, BUT …
* Mongo for document-store-y-stuff
* HBase/Hadoop for … yeah: storing the NYSE (Did that. Good times.)
* … aaaaaannnndddd Graph databases … are good for … hmm, what, exactly?

![Alternatives to SQL](imgs/03-sql-alternatives.png)

## Vite! Vite! What’re Graph Databases, yo?

* Graph databases from graph theory, blah, blah, blah
* Composed of entities: nodes and relations, both have [optional] property sets
* Node-to-node traversal is in CONSTANT-time.
* Relations have properties: intensity? of connection, kind of connection
* Nodes (can be) typed but each node (‘row’) has its own types and relations
* ‘Implied’ schemata
* Graphs are ‘truly-relational’ … so: relationships, influences

### ex: Lyft

Lyft. replaced: 

* 150 node postgresSQL with a
* 42 node mongo db with a
* 6 node graph database … to do the same work

![Graph Database Introduction and example usage](imgs/04-graph-db-intro.png)

## FOX BREAK!

![Juniper QT](imgs/05-juniper-break.png)

## Graph 1: Game of Thrones

![Game of Thrones Knowledge Base-as-graph](imgs/06-GoT.png)

## Graph 2: ATO-as-Graph

![ATO-as-graph](imgs/07-ATO-as-graph-1-graph.png)

## ATO-as-Graph

What can we get from this?

* Compatibilities is in constant-time
* Track Jumps (entered. By. hand. Each. one. Pain. steak. ingly.)
* Track Jumps (computed)

![ATO-as-Graph discussion](imgs/08-ATO-as-graph-2-text.png)

## ATO-as-graph Demo

* ETL written in Python (Doug, guy with tie: Python-expert)
* ATO-as-Graph in neo4j

![ATO-as-graph demo](imgs/09-ATO-as-graph-demo.png)

## “Good Night, and Good Luck.”

### Linkies: neo4j.com

### Further readings:
1. [Introduction to Graph Databases](https://neo4j.com/lp/book-graph-databases/)
2. [Graph Algorithms](https://neo4j.com/lp/book-graph-algorithms/)

![Further Reading](imgs/10-further-readings.png)

## PEACE OUT!

Juniper sez: “PEACE OUT!”
… and THAT’S what the fox says!

![Juniper sez bai!](imgs/11-juniper-bai.png)
