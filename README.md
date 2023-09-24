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


![image](https://github.com/srss-pocs/springboot-redisdb/assets/145287517/344e6c5f-884c-45f1-ac0f-f1332f309a0e)
