
Simple Mongo DB example connecting to Mongo instance running  locally with swagger enabled

http://localhost:8080/swagger-ui.html#/employee-controller

#spring.data.mongodb.uri=mongodb+srv://<username>:<pwd>@<cluster>.mongodb.net/mygrocerylist
spring.data.mongodb.database=myLocalMongo
spring.data.mongodb.uri=mongodb://localhost:27017/?connectTimeoutMS=300000&minPoolSize=0&maxPoolSize=10&maxIdleTimeMS=900000