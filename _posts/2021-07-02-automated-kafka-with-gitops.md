---
layout: post
title: Automated Kafka ops with Kafka Topology Builder and Gitops
---

One of the common questions when teams start working with technologies like Apache Kafka is how to automate and simplify the common operations tasks. This task can be such as creating topics, managing their configuration or for example adding the necessary ACLs for a given application.
While many ways can get you to Rome, one of the options is to use Git, Jenkins and a bit of code to solve this problem. Gitops to the rescue.
If you are not aware of this approach, I do recommend reading this very good explanation.

In a nutshell:

>GitOps is a paradigm or a set of practices that empowers developers to perform tasks which typically fall under the purview of IT operations. GitOps requires us to describe and observe systems with declarative specifications that eventually form the basis of continuous everything.

Source https://www.cloudbees.com/gitops/what-is-gitops

So with this we bring into the table:
