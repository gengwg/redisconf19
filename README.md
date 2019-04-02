## Day 1
## microservices architecture workshop

two pizza teams  
samll autonojous teams

deliver software rapidly reliably.

* mtaintanabilty
* test
* deploy


monolithic deliver software rapidly reliably deliery imposible.

monolithic hell

app -- > a set of services:

* maintainable and testable
* loosely coupled
* independently deployable
* organized around business capabilities


```
database per service  
schema change withoiut cordination with other teams
looser coupling
eliminate runtime coupling, e.g. locks.
shared db but private tables
separate db
```
expriment safely and evolve the tech stack.

complexity

- dev: ipc, partial failure, distributed data
- testing: integration, end2end
- deployment: k8s

devops/continuous delivery  
product-centered teams

pattern: reusable solution to  a problem described objectively.

https://microservices.io

## trasactions

transactions and queries in microservice using asynchronous messaging.

loosely coupled services

online store api  
customer management  
order management

sagas

series of local trasactions

syncrhonous rest api call initiates asynchronous saga.

event handlers  
indicrect way to make sth happen

saga orchestrator

event sourcing  
event centric approcach

## k8s and redis

'making reliable scalable, agile distributed system a cs101 exercise.'

self-healing keep workloads at desired state.

run containers in multiple nodes

### networking.

-  communicate directly via overlay network.
- service lookup by name via internal dns servervice.
- cloud lb to route traffic.
- dispatch incoming traffic to relevant backend (ingress)

management

```
customre resource definition
+
customer controller 
= operator
```

stateful set controller

