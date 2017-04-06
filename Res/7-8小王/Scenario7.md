| Use case name            | Make the Returning Request               |
| :----------------------- | :--------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | The customer makes the request of returning. |
| Preconditions            | The customer wants to return the product the or she unsatisfied with after receiving within a month. |
| Successful End Condition | The customer makes the request of returning. |
| Failed End Condition     | The customer fails to make the request of returning. |
| Primary Actors           | Customer                                 |
| Secondary Actors         | None                                     |
| Trigger                  | The customer decides to return the product. |
| Main Flow                | Step 1 The customer logins the system.   |
|                          | Step 2 The customer choose to withdraw the product or exchange the product. |
|                          | Step 3 The customersubmits the request of returning. |
| Extensions               | Step 1.1 The customer fails to login the system with a wrong account number and password. |
|                          | Step 3.1 The customer fails to submit the request of returning. |

| Use case name            | Withdraw the product                     |
| :----------------------- | :--------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | A customer returns the product and the payment is reimbursed . |
| Preconditions            | The customer wants to withdraw the product the or she unsatisfied with after receiving within a month. |
| Successful End Condition | The order is completed and the payment is reimbursed to the customer. |
| Failed End Condition     | The order is not completed and the payment is not reimbursed to the customer. |
| Primary Actors           | Customer                                 |
| Secondary Actors         | None                                     |
| Trigge                   | The customer choose to withdraw the product. |
| Main Flow                | Step 1 Customer makes the returning request. |
|                          | Include::Make the Returning Request      |
|                          | Step 2 Server checks the returning request. |
|                          | Include::Check the Returning Request     |
|                          | Step 3 The package is delivered.         |
|                          | Include::Deliver the package             |
|                          | Step 4  The e-business receives and checks the pack. |
|                          | Step 5 The e-business agrees the returning. |
|                          | Step 6 Customer gets payment back.       |
| Extensions               | Step 4.1 The e-business disagrees the returning. |

| Use case name            | Reimburse the Payment                    |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | The third-party trade agent reimburse the payment to the customer. |
| Preconditions            | E-company has checked the returning product and agreed to reimburse the payment. |
| Successful End Condition | The order is completed and  the payment is reimbursed to the customer. |
| Failed End Condition     | The third-party trade agent fails to reimburse the payment. |
| Primary Actors           | The third-party trade                    |
| Secondary Actors         | None                                     |
| Trigge                   | E-company  agrees to reimburse the payment. |
| Main Flow                | Step 1 The third-party trade agent reimburses the payment to the customer. |
|                          | Step 2 The customer checks the payment.  |
| Extensions               | Step 1.1 The third-party trade agent fails to reimburse the payment. |

| Use case name            | Exchange the product                     |
| :----------------------- | :--------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | A customer returns the product and the delivery schedule is made again upon mutual agreement. |
| Preconditions            | The customer wants to exchange the product the or she unsatisfied with after receiving within a month. |
| Successful End Condition | The delivery schedule is made again upon mutual agreement. |
| Failed End Condition     | The delivery schedule fails to be made again upon mutual agreement. |
| Primary Actors           | Customer                                 |
| Secondary Actors         | None                                     |
| Trigge                   | The customer choose to exchange the product. |
| Main Flow                | Step 1 Customer makes the returning request. |
|                          | Include::Make the Returning Request      |
|                          | Step 2 Server checks the returning request. |
|                          | Include::Check the Returning Request     |
|                          | Step 3 The package is delivered.         |
|                          | Include::Deliver the package             |
|                          | Step 4  The e-business receives and checks the pack. |
|                          | Step 5 The e-business agrees the returning. |
|                          | Step 6 Customer gets payment back.       |
| Extensions               | Step 4.1 The e-business disagrees the returning. |

| Use case name            | Make the new Delivery Schedule           |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | The delivery schedule is made again between the customer and the e-business. |
| Preconditions            | E-company has checked the returning product and agreed to make the delivery schedule again with the customer. |
| Successful End Condition | The delivery schedule is made again between the customer and the e-business. |
| Failed End Condition     | E-company fails to make the new delivery schedule with the customer. |
| Primary Actors           | E-business                               |
| Secondary Actors         | None                                     |
| Trigge                   | E-company agrees to make the delivery schedule again with the customer. |
| Main Flow                | Step 1 E-company make the delivery schedule again. |
|                          | Step 2 The customer check the new delivery schedule. |



| Use case name            | Return the product                       |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | The customer returns the product and gets the payment or the exchanged product. |
| Preconditions            | The customer wanted to return the product he or she unsatisfied with after receiving within a month. |
| Successful End Condition | The customer returns the product and gets the payment or the exchanged product. |
| Failed End Condition     | The customer fails to return the product and gets the payment or the exchanged product. |
| Primary Actors           | Customer                                 |
| Secondary Actors         | None                                     |
| Main Flow                | Step 1 Customer makes the returning request. |
|                          | Include::Make the Returning Request      |
|                          | Step 2 Server checks the returning request. |
|                          | Include::Check the Returning Request     |
|                          | Step 3 The package is delivered.         |
|                          | Include::Deliver the package             |
|                          | Step 4  The e-business receives and checks the pack. |
|                          | Step 5 The e-business agrees the returning. |
|                          | Step 6 Customer gets payment back.       |
| Extensions               | Step 4.1 The e-business disagrees the returning. |

| Use case name            | Check the Returning Request              |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | The server check the returning request of the customer. |
| Preconditions            | The customer has made the request of returning. |
| Successful End Condition | The details are verified.                |
| Failed End Condition     | The details are not verified.            |
| Primary Actors           | Server                                   |
| Secondary Actors         | None                                     |
| Trigge                   | The customer makes the request of returning. |
| Main Flow                | Step 1 The details are provided to the system. |
|                          | Step 2 The database verifies the details. |
|                          | Step 3 The details are returned as verified by the database. |
| Extensions               | Step 2.1 The database does not verify the details. |
|                          | Step 3.2 The details are returned as unverified. |

| Use case name            | Provide Imformation to Return            |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | The server provides information for the customer to send the product back. |
| Preconditions            | The server has passed the request.       |
| Successful End Condition | The server provide the customer a label containing the address to send the product back including the postage. |
| Failed End Condition     | The server fails to provide the information. |
| Primary Actors           | Server                                   |
| Secondary Actors         | None                                     |
| Trigge                   | The server verifies the returning request of the customer. |
| Main Flow                | Step 1 The server collectsthe information about the order. |
|                          | Step 2 The server provides the information for the customer. |
|                          | Step 3 The customer checks the information. |
| Extensions               | Step 1.1 The server fails to collectsthe information about the order. |
|                          | Step 1.2 The server asks information from the e-business |

| Use case name            | Deliver the package                      |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Seven                           |
| Goal In Context          | The postman delivers the returning product back to the e-business. |
| Preconditions            | The returning request has been admitted and the server has provided the customer a label containing the address to send the product back including the postage. |
| Successful End Condition | The postman delivers the returning product back to the e-business. |
| Failed End Condition     | The postman fails to deliver the returning product back to the e-business. |
| Primary Actors           | Postman                                  |
| Secondary Actors         | None                                     |
| Trigge                   | The customer asked the postman to deliver the package. |
| Main Flow                | Step 1 The customer asks the postman to deliver the package. |
|                          | Step 2 The package is delivered by ogistics company. |
|                          | Step 3 E-business receives the package.  |

