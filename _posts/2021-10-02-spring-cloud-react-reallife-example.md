---
layout: post
title:  "Spring Cloud React Reallife Example"
date:   2021-10-02 20:41:00 +0700
categories: [spring, spring-cloud, react]
---

In this example, we have built a simple Spring Cloud application with 2 microservices and put a API gateway infront of it and built a small React application talking to talk to this microservices. The Microservies are registered with Service Registry.

This example is built on top of a Udemy course [React + Spring Boot Microservices and Spring Cloud](https://www.udemy.com/course/react-spring-boot-microservices-and-spring-cloud/). And has simplified further with in memory H2 database. 

### Highlevel architecture is as below:

![Spring Cloud React Example Architecture](https://raw.githubusercontent.com/skprasadu/skprasadu.github.io/master/static/img/_posts/spring-cloud-react-example-arch.png)

This is the [github link](https://github.com/skprasadu/react-springboot-microservices) that works with H2 database.

To start this example, git clone this example and the directory structure is as below,

![Folder structure](https://raw.githubusercontent.com/skprasadu/skprasadu.github.io/master/static/img/_posts/react-example-git-folderstructure.png)

Open windows commands Mac terminal under `eureke-discovery-service` and run 

```
./gradlew bootRun
```

Open another windows commands Mac terminal under `microservice-course-management` and run 

```
./gradlew bootRun
```

Open another windows commands Mac terminal under `microservice-user-management` and run 

```
./gradlew bootRun
```

Run Zuul API gateway by `cd` to `zuul-gateway-service` and run
```
./gradlew bootRun
```

Finally `cd` to `client-side` and run 

```
npm install && npm start
```

Open the web browser and type `http://localhost:3000` and you can see the React application. To explore the application more, import all these gradle projects into an IDE of your choise and understand what is going on. 

This is a simple example to jump start a spring cloud application. However there are lot of other components of Spring Cloud Services as below,

![Spring Cloud Netflix OSS](https://raw.githubusercontent.com/skprasadu/skprasadu.github.io/master/static/img/_posts/spring-cloud-netflix-oss.png)

In the coming material we will demonstrate some of these capabilities.
