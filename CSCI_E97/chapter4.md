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

```
// src/order.controller.ts

import { OrderService } from './order.service';

export class OrderController {
  constructor(private readonly orderService: OrderService) {}

  async createOrder(orderDetails: any): Promise<any> {
    return this.orderService.createOrder(orderDetails);
  }
}
```

```
// src/order.service.ts

import { OrderSaga } from './order.saga';

export class OrderService {
  constructor(private readonly orderSaga: OrderSaga) {}

  async createOrder(orderDetails: any): Promise<any> {
    return this.orderSaga.handleOrderSaga(orderDetails);
  }
}
```

```
// src/order.saga.ts

export class OrderSaga {
  async handleOrderSaga(orderDetails: any): Promise<any> {
    try {
      // Start the saga transaction
      console.log('Saga: Start Transaction');

      // Perform saga steps
      this.publishOrderCreatedEvent(orderDetails);
      this.callExternalService(orderDetails);

      // End the saga transaction
      console.log('Saga: End Transaction');

      // Return the result of the saga
      return { message: 'Order created successfully' };
    } catch (error) {
      // Handle errors or propagate them to the service
      console.error('Saga: Transaction Failed');
      throw error;
    }
  }

  private publishOrderCreatedEvent(orderDetails: any): void {
    // Publish an event indicating that the order has been created
    // This event might be consumed by other microservices
    console.log('Saga: Publish Order Created Event');
  }

  private callExternalService(orderDetails: any): void {
    // Perform actions related to an external service
    console.log('Saga: Call External Service');
  }
}
```

```
// src/main.ts

import { OrderController } from './order.controller';
import { OrderService } from './order.service';
import { OrderSaga } from './order.saga';

const orderSaga = new OrderSaga();
const orderService = new OrderService(orderSaga);
const orderController = new OrderController(orderService);

// Example: Call the createOrder method
orderController.createOrder({ /* order details */ })
  .then(result => console.log(result))
  .catch(error => console.error(error));
```
