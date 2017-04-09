| Use case name            | Create Order                             |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario One                             |
| Goal In Context          | The customer or E-business requests to create order. |
| Preconditions            | The customer buys products from E-business or wants to send packages. |
| Successful End Condition | Server creates order according to the information provided by E-business&Customer. |
| Failed End Condition     | Server refuses to create an order.       |
| Primary Actors           | E-business and Customer                  |
| Secondary Actors         | None                                     |
| Trigger                  | E-business&Customer sends the related information to Server. |
| Main Flow                | Step 1 : Customer&E-business Registers Information to Server. |
|                          | Step 2 : Customer&E-business Sends Information to Server. |
|                          | Step 3 : Server checks whether the information is completed. |
|                          | Step 4 : Server creates orders automatically according to the information above. |
|                          | Step 5 : E-business&customer transfers products to Logistics company and pays for the delivery. If the customer doesn’t pay before, Logistics company will pay for products for the customer in advance. |
|                          | Step 6 : Logistics company transports packages to different regional distribution centers. |
| Extensions               | The request of creating Order is rejected. |
