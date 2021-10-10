---
layout: post
title:  "Spring Cloud Inter Microservice Communication with Feign Example"
date:   2021-10-03 20:41:00 +0700
categories: [spring, spring-cloud]
---

In this example, we have built a simple Spring Cloud application with 2 microservices. The Microservies are registered with Service Registry. It uses Feign to communication between microservices.

The Customer Microservices calls the product microservice to get the products by customer.

This is the [github link](https://github.com/skprasadu/spring-cloud-feign-example) for this example.

This example users [Feign](https://cloud.spring.io/spring-cloud-netflix/multi/multi_spring-cloud-feign.html).