### Sagas

Sagas in microservices architecture are a design pattern for managing distributed transactions, offering an alternative to traditional two-phase commit protocols. They are particularly useful in scenarios where a business operation involves multiple services, each with its own database. Sagas facilitate the coordination of these distributed transactions by breaking them into a series of smaller, independent steps, allowing for more flexible error handling and better overall system resilience.

### Transactions

Distributed transactions involve coordinating and managing transactions that span multiple databases or services in a distributed system. Traditional transactions (such as those in a monolithic application) typically rely on a single database, ensuring that either all operations within the transaction succeed or none of them take effect. In a distributed environment, achieving this level of coordination becomes challenging due to issues like network failures, latency, and the need for maintaining consistency across diverse data stores. Distributed transactions aim to extend transactional guarantees across multiple, potentially independent components, ensuring atomicity, consistency, isolation, and durability (ACID properties) despite the challenges of a distributed architecture.

### Basic Example

#### Project Structure

```
/saga-pattern-example
|-- /src
|   |-- order.controller.ts
|   |-- order.service.ts
|   |-- order.saga.ts
|   |-- main.ts
|-- tsconfig.json
|-- package.json

```
