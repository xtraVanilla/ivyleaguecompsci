# Table of Contents

- Chapter 1: Monoliths

  - [1.1 monoliths](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/1.1.md)
  - [1.2 pool architecture](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/1.2.md)
  - [1.3 load balancing](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/1.3.md)
  - [1.4 example](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/1.4.md)

- Chapter 2: Decomposition Strategies

  - [2.1 business capability pattern](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/2.1.md)
  - [2.2 sub-domain pattern](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/2.2.md)

- Chapter 3: Interprocess Communication in a Microservice Architecture

  - 3.1 Communicating Using the Synchronous Remote Procedure Invocation Pattern

    - [3.1.1 REST](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.1.1.md)
    - [3.1.2 GraphQL](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.1.2.md)
    - [3.1.3 gRPC](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.1.3.md)
    - [3.1.4 Handling Partial Failure Using the Circuit Breaker Pattern](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.1.4.md)

  - 3.2 Service Discovery Patterns

    - [3.2.1 Using Service Discovery](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.2.1.md)
    - [3.2.2 3rd Party Registration](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.2.2.md)
    - [3.2.3 Client-side Discovery](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.2.3.md)
    - [3.2.4 Self-registration](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.2.4.md)
    - [3.2.5 Server-side Discovery](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.2.5.md)

  - 3.3 Communicating Using the Asynchronous Messaging Pattern

    - [3.3.1 Overview of Messaging](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.3.1.md)
    - [3.3.2 Implementing the Interaction Styles Using Messaging](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.3.2.md)
    - [3.3.3 Using a Message Broker](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.3.3.md)
    - [3.3.4 Libraries and Frameworks for Messaging](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.3.4.md)

  - 3.4 Transactional Messaging Patterns

    - [3.4.1 Polling Publisher](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.4.1.md)
    - [3.4.2 Transaction Log Tailing](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.4.2.md)
    - [3.4.3 Transactional Outbox](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/3.4.3.md)

- Chapter 4: Data Consistency Patterns

  - [4.1.1 sagas](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.1.md)
  - [4.1.2 transactions](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.2.md)
  - [4.1.3 basic example](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.3.md)
  - [4.1.4 communication between services](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.4.md)
  - [4.1.5 choreography](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.5.md)
  - [4.1.6 orchestration](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.6.md)
  - [4.1.7 the rollback mechanism](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.7.md)
  - [4.1.8 semantic locks](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.8.md)
  - [4.1.9 commutative updates](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.9.md)
  - [4.2.0 pessimistic views](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.0.md)
  - [4.2.1 re-reading values and by-value strategies](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.1.md)
  - [4.2.2 anomalies](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.2.md)
  - [4.2.3 anomaly mitigation](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.3.md)
  - [4.2.4 idempotency](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.4.md)
  - [4.2.5 quota cache](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.5.md)
  - [4.2.6 eventual commit-sync service](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.6.md)
  - [4.2.7 tracking and managing quotas](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.7.md)
  - [4.2.8 message queue middleware](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.8.md)
  - [4.2.9 orchestrator module](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.2.9.md)
  - [4.3.0 summary](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.3.0.md)
  - [4.3.1 example](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.3.1.md)
  - [4.3.2 use cases](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.3.2.md)

- Chapter 5: Business Logic Design Patterns

  - [5.1.1 aggregator pattern](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/5.1.1.md)
  - [5.1.2 example](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/5.1.2.md)
  - [5.1.3 domain event pattern](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/5.1.3.md)
  - [5.1.4 use cases](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/5.1.4.md)
  - [5.1.5 domain model](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/5.1.5.md)
  - [5.1.6 example](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/5.1.6.md)
  - [5.1.7 event sourcing](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/5.1.7.md)
  - [5.1.8 transaction script](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/5.1.8.md)

- Chapter 6: Query Patterns

  - [6.1.1 api composition](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/6.1.1.md)
  - [6.1.2 command query responsibility segregration](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/6.1.2.md)

- Chapter 7: External API Patterns

  - [7.1.1 api gateway](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/7.1.1.md)
  - [7.1.2 backends for frontends](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/7.1.2.md)

- Chapter 8: Testing Patterns

  - [8.1.1 consumer-driven contract test](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/8.1.1.md)
  - [8.1.2 consumer-side contract test](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/8.1.2.md)
  - [8.1.3 service component test](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/8.1.3.md)

- Chapter 9: Security Patterns

  - [9.1.1 access token](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/9.1.1.md)

- Chapter 10: Cross-cutting Concerns Patterns

  - [10.1.1 externalized configuration](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/10.1.1.md)
  - [10.1.2 microservice chassis](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/10.1.2.md)

- Chapter 11: Observability Patterns

  - [11.1.1 application metrics](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/11.1.1.md)
  - [11.1.2 audit logging](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/11.1.2.md)
  - [11.1.3 distributed tracking](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/11.1.3.md)
  - [11.1.4 exception tracking](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/11.1.4.md)
  - [11.1.5 health check API](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/11.1.5.md)
  - [11.1.6 log aggregation](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/11.1.6.md)

- Chapter 12: Deployment Patterns

  - [12.1.1 deploy a service as a container](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/12.1.1.md)
  - [12.1.2 deploy a service as a VM](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/12.1.2.md)
  - [12.1.3 language-specific packaging format](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/12.1.3.md)
  - [12.1.4 service mesh](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/12.1.4.md)
  - [12.1.5 serverless deployment](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/12.1.5.md)
  - [12.1.6 sidecar](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/12.1.6.md)

- Chapter 13: Refactoring to Microservices Patterns
  - [13.1.1 anti-corruption layer](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/13.1.1.md)
  - [13.1.2 strangler application](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/13.1.2.md)
