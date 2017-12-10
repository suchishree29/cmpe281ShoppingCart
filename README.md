# cmpe281ShoppingCart
Batman Collection Application : A cloud scale multi-user shopping cart Service on Amazon Cloud 

## Our Logo:
![alt tag](https://github.com/suchishree29/cmpe281ShoppingCart/blob/master/ShoppingCart/Batman_logo.png)

## Architecture:
![alt tag](https://github.com/suchishree29/cmpe281ShoppingCart/blob/master/Architecture.png)

Implemented a 3 tier microservices architecture. Every microservice has a database cluster attached to it. The User Session uses a Redis Cluster in with one master and two slaves. The Product Catalogue uses a MongoDB Cluster with one master and two slaves. The Shopping Cart’s data persists in a 3 node Riak ring. The User Activity is stored in a 3 node Cassandra ring. For providing recommendation we are using the Neo4J graph database.

## Class Diagram:
![alt tag](https://github.com/suchishree29/cmpe281ShoppingCart/blob/master/ClassDiagram.png)



