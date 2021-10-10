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

This is a simple example to jump start a spring cloud application. However there are lot of other components of Spring Cloud Services as below,

![Spring Cloud Netflix OSS](https://raw.githubusercontent.com/skprasadu/skprasadu.github.io/master/static/img/_posts/spring-cloud-netflix-oss.png)

In the coming material we will demonstrate some of these capabilities.
