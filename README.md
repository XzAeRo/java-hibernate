# Java Hibernate Test Application
This is just a test application intended for personal use

```bash
$ gradle build
$ gradle bootRun
$ curl http://localhost:8080/people
$ curl -i -X POST -H "Content-Type:application/json" -d '{  "firstName" : "Frodo",  "lastName" : "Baggins" }' http://localhost:8080/people
$ curl http://localhost:8080/people
$ curl http://localhost:8080/people/search/findByLastName\?name=Baggins
$ curl -X DELETE http://localhost:8080/people/1
```
