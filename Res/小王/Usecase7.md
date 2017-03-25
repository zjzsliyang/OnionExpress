| Use case name            | Make the returning request               |
| :----------------------- | :--------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | The server passes the request and provides information for the customer to send the product back. |
| Preconditions            | The customer wants to return the product the or she unsatisfied with after receiving within a month. |
| Successful End Condition | The server provide the customer a label containing the address to send the product back including the postage. |
| Failed End Condition     | The request is rejected.                 |
| Primary Actors           | Customer                                 |
| Secondary Actors         | Server                                   |
| Trigger                  | The customer makes the request of returning. |
| Main Flow                | Step 1 The customer logs in the system.  |
|                          | Step 2 The customer choose to withdraw the product or exchange the product. |
|                          | Step 3 The customer submits the request of returning. |
|                          | Step 3 The server obtains the information. |
|                          | Step 4 The server provide the customer a label containing the address to send it back including the postage. |
| Extensions               | Step 4.1 The server reject the request.  |

| Use case name            | Withdraw the product                     |
| :----------------------- | :--------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | A customer returns the product and the payment is reimbursed . |
| Preconditions            | The returning project is received by the e-company from the customer. |
| Successful End Condition | The order is completed and  the payment is reimbursed to the customer. |
| Failed End Condition     | E-company reject to reimburse.           |
| Primary Actors           | Customer                                 |
| Secondary Actors         | E-company                                |
| Trigge                   | The customer choose to withdraw the product. |
| Main Flow                | Include::Make the Returning Request      |
|                          | Include::Return the Product              |
|                          | Step 1 E-company receives the returning product. |
|                          | Step 2 E-company check the returning product and the order. |
|                          | Step 3 E-company reimburse the payment.  |
| Extensions               | Step 3.1 E-company reject to reimburse the payment and send the product back. |

| Use case name            | Exchange the product                     |
| :----------------------- | :--------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | A customer returns the product and the delivery schedule is made again upon mutual agreement. |
| Preconditions            | The returning project is received by the e-company from the customer. |
| Successful End Condition | The delivery schedule is made again upon mutual agreement. |
| Failed End Condition     | E-company reject to exchange the product. |
| Primary Actors           | Customer                                 |
| Secondary Actors         | E-company                                |
| Trigge                   | The customer choose to exchange the product. |
| Main Flow                | Include::Make the Returning Request      |
|                          | Include::Return the Product              |
|                          | Step 1 E-company receives the returning product. |
|                          | Step 2 E-company check the returning product and the order. |
|                          | Step 3 The delivery schedule is made again upon mutual agreement. |
| Extensions               | Step 3.1 E-company reject to exchange the product and send the original product back. |

| Use case name            | Return the product                       |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | The returning project is received by the e-company from the customer. |
| Preconditions            | The returning request is admitted and the server provide the customer a label containing the address to send the product back including the postage. |
| Successful End Condition | The returning project is is received by the e-company. |
| Failed End Condition     | The returning project is is not received by the e-company. |
| Primary Actors           | Customer                                 |
| Secondary Actors         | Postman                                  |
| Trigge                   | The customer delivers the returning product. |
| Main Flow                | Step 1 The customer delivers the returning product according to the address provided by the  server. |
|                          | Step 2 Postman receives the package.     |
|                          | Step 3 The package is expressed.         |

