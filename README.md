# Bookstore REST API using Gin and Gorm

Read the [article](https://blog.logrocket.com/how-to-build-a-rest-api-with-golang-using-gin-and-gorm/).

How to use:

```
$ go run main.go
```

How to build: Read the [article](https://medium.com/@monirz/golang-dependency-solution-with-go-module-and-docker-8967da6dd9f6):

docker build .

Test API: 

REST POST:  
curl -X POST -d @file.txt http://localhost:8080/books

REST GET: 
curl http://localhost:8080/books


