A Simple Spring Boot Redis as database application for CRUD operations

Steps : Download redis for windows and start the redis server

Check the pom.xml

Start the application

http://localhost:8080/api/product

POST
{
  "id":1, 
"name":"Dell Laptop",
"price":129000,
"qty":1
}

http://localhost:8080/api/product
GET

Note : RedisInsight is the redis client to check 