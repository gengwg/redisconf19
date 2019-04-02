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

## Day 2

## Gerneral Session

io-thread enabled

acs.
security.
operational safety.
bitmap at runtime.

redis 6

### Google cloud ceo

oracle 22 years.

- unified platform
- different access mothold

learn 18 databases?

data powered.
managed db. tune perfo.
serverless platform 

higher level, higher contribution.
upper level of abstraction.

### games

game industry use redis or die?

## Redis replication

## microservices at credit karma

php monolithic --> 900 micro services.

client side vs service mesh

consol for service discovery

- automate first
- think and plan ahead.
- maintainance overhead will grow exponentially.

orchestration frameworks

- *k8s* 
- swarm
- nomad

helm

### observability

### env parity

unsolved

- shared staging env
- mock services
- load dependencies automatically
    - dependeny tree

tool integration is hard

independent development.

one db per service.

large logical mysql cluster on bm.

85% scala
node picking up

testing  
team owns  
how much tests?  
central pipeline compliance  
dev kube  

config  
consol k/v store  
deployed with services

secrets in vault  

## Turing complete

integer optimization problem

factor graph

