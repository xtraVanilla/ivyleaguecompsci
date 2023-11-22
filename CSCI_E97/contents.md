# Table of Contents

- [Chapter 1: Monoliths](#chapter-1-monoliths)

  - [1.1 Monolith Hell](#11-the-slow-march-toward-monolithic-hell)
    - [1.1.2 Monoliths as a Form of Modularity](#142-microservices-as-a-form-of-modularity)
  - [Summary](#summary)

- [Chapter 2: Decomposition Strategies](#chapter-2-decomposition-strategies)

  - [2.1.1 Defining Services by Applying the Decompose by Business Capability Pattern](#222-defining-services-by-applying-the-decompose-by-business-capability-pattern)
  - [2.1.2 Defining Services by Applying the Decompose by Sub-Domain Pattern](#223-defining-services-by-applying-the-decompose-by-sub-domain-pattern)
  - [2.1.3 Decomposition Guidelines](#224-decomposition-guidelines)
  - [2.1.4 Obstacles to Decomposing an Application into Services](#225-obstacles-to-decomposing-an-application-into-services)
  - [2.1.5 Defining Service APIs](#226-defining-service-apis)
  - [Summary](#summary-1)

- [Chapter 3: Interprocess Communication in a Microservice Architecture](#chapter-3-interprocess-communication-in-a-microservice-architecture)

  - [3.1 Overview of Interprocess Communication in a Microservice Architecture](#31-overview-of-interprocess-communication-in-a-microservice-architecture)
    - [3.1.1 Interaction Styles](#311-interaction-styles)
    - [3.1.2 Defining APIs in a Microservice Architecture](#312-defining-apis-in-a-microservice-architecture)
    - [3.1.3 Evolving APIs](#313-evolving-apis)
    - [3.1.4 Message Formats](#314-message-formats)
  - [3.2 Communicating Using the Synchronous Remote Procedure Invocation Pattern](#32-communicating-using-the-synchronous-remote-procedure-invocation-pattern)
    - [3.2.1 REST](#321-using-rest)
    - [3.2.2 gRPC](#322-using-grpc)
    - [3.2.3 Handling Partial Failure Using the Circuit Breaker Pattern](#323-handling-partial-failure-using-the-circuit-breaker-pattern)
    - [3.2.4 Using Service Discovery](#324-using-service-discovery)
  - [3.3 Communicating Using the Asynchronous Messaging Pattern](#33-communicating-using-the-asynchronous-messaging-pattern)
    - [3.3.1 Overview of Messaging](#331-overview-of-messaging)
    - [3.3.2 Implementing the Interaction Styles Using Messaging](#332-implementing-the-interaction-styles-using-messaging)
    - [3.3.3 Creating an API Specification for a Messaging-Based Service API](#333-creating-an-api-specification-for-a-messaging-based-service-api)
    - [3.3.4 Using a Message Broker](#334-using-a-message-broker)
    - [3.3.5 Competing Receivers and Message Ordering](#335-competing-receivers-and-message-ordering)
    - [3.3.6 Handling Duplicate Messages](#336-handling-duplicate-messages)
    - [3.3.7 Transactional Messaging](#337-transactional-messaging)
    - [3.3.8 Libraries and Frameworks for Messaging](#338-libraries-and-frameworks-for-messaging)
  - [3.4 Using Asynchronous Messaging to Improve Availability](#34-using-asynchronous-messaging-to-improve-availability)
    - [3.4.1 Synchronous Communication Reduces Availability](#341-synchronous-communication-reduces-availability)
    - [3.4.2 Eliminating Synchronous Interaction](#342-eliminating-synchronous-interaction)
  - [Summary](#summary-2)

- Chapter 4: Sagas
  - [4.1.1 what are sagas?](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.1.md)
  - [4.1.2 transactions](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.2.md)
  - [4.1.3 basic example](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.3.md)
  - [4.1.4 communication between services](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.4.md)
  - [4.1.5 choreography](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.5.md)
  - [4.1.6 orchestration](https://github.com/xtraVanilla/ivyleaguecompsci/blob/main/CSCI_E97/4.1.6.md)
  - [Summary]
