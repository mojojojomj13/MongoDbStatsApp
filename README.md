# MongoDbStatsApp
An embedded MongoDb in Spring Boot for getting statistics of a List of Data


The App has the following parts:
1. A Spring Boot App
2. Embedded MongoDb to do the NoSQL DB operations
3. Java 8 features used

The main business logic is to generate Stats for all the Data(Transactions) that are less than or equal to 1 minute old.
I have used Java 8 map function to get the Statistics and EmbededMongoDB to produce scenarios like in real time.

