| Use case name            | Create an Order                          |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario One                             |
| Goal In Context          | The customer or E-business requests to create an order. |
| Preconditions            | The customer buys products from E-business or wants to send packages. |
| Successful End Condition | The system creates an order according to the information provided by E-business. |
| Failed End Condition     | The system refuse to create an order.    |
| Primary Actors           | E-business                               |
| Secondary Actors         | Customer                                 |
| Trigger                  | E-business sends the related information to the system. |
| Main Flow                | Step 1 : The customer buys products from e-business and offers his/her information to the E-business. Then he/she will get an order number from the E-business. |
|                          | Step 2 : E-business collects the information and sends to the system immediately or periodically. |
|                          | Step 3 : The system creates orders automatically according to the information above. |
|                          | Step 4 : The E-business transfers products to the logistics company and pays for the delivery. If the customer doesn’t pay before, the logistics company will pay for the products for the customer in advance. |
| Extensions               | Creating an Order is rejected.           |

| Use case name            | Accept an Delivery Task                  |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario One                             |
| Goal In Context          | Postmen accept an delivery task assigned by the system. |
| Preconditions            | Orders have been created and the logistics company have been transported to the regional distribution centers. |
| Successful End Condition | Postmen accept an delivery task and send the package to the customer. |
| Failed End Condition     | Postmen fail to accept an delivery task. |
| Primary Actors           | Postman                                  |
| Secondary Actors         | None                                    |
| Trigger                  | Postmen accept an delivery task.         |
| Main Flow                | Step 1 : Postmen log in the system and accept delivery tasks assigned by the system. |
|                          | Step 2 : The system sends the information list to the corresponding postman,including tracking number, destination, personal information about receivers, QR code for payment( if the customer choose to pay on-site ) and so on. |
|                          | Step 3 : The postman goes to the regional distribution center and gets the package. The postman delivers it to the destination and informs the customer to take it |
| Extensions               | Accepting an delivery task is failed.    |