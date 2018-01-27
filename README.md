# cmpe281ShoppingCart
Batman Collection Application : A cloud scale multi-user shopping cart Service on Amazon Cloud 

## Project Walk Through Video
![alt tag](https://drive.google.com/open?id=1kEel7a9Z4pE7bhfU5OIzpnXl_1-qqG2V)

## Architecture:
![alt tag](https://github.com/suchishree29/cmpe281ShoppingCart/blob/master/Architecture.png)

Implemented a 3 tier microservices architecture. Every microservice has a database cluster attached to it. The User Session uses a Redis Cluster in with one master and two slaves. The Product Catalogue uses a MongoDB Cluster with one master and two slaves. The Shopping Cart’s data persists in a 3 node Riak ring. The User Activity is stored in a 3 node Cassandra ring. For providing recommendation we are using the Neo4J graph database.

## Class Diagram:
![alt tag](https://github.com/suchishree29/cmpe281ShoppingCart/blob/master/ClassDiagram.png)

## HomePage: 
![alt tag](https://github.com/suchishree29/cmpe281ShoppingCart/blob/master/Homepage.PNG)

## Sign In Page:
![alt tag](https://github.com/suchishree29/cmpe281ShoppingCart/blob/master/SignInPage.PNG)

## Register Page:
![alt tag](https://github.com/suchishree29/cmpe281ShoppingCart/blob/master/SignupPage.PNG)





