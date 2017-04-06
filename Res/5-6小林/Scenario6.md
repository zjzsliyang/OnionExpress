| Use case name            | Record the Damage                        |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenerio Six                             |
| Goal In Context          | Postman records the information of the damaged or lost package. |
| Preconditions            | The package was damaged or lost.         |
| Successful End Condition | Postman records the infomation successfully. |
| Failed End Condition     | The information of the package was lost as well. |
| Primary Actors           | Postman                                  |
| Secondary Actors         | None                                     |
| Trigger                  | The package was damaged or lost.         |
| Main Flow                | Step1. Postman records the information of the package. |
|                          | Step2. The logistics company receives the corresponding information. |
|                          | Step3. The logistics company sends a message to the customer, explaining the situation and making an apology to the customer. |
| Extensions               | None.                                    |

| Use case name            | Cancel the Order                         |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Six                             |
| Goal In Context          | The customer wants to cancel the order for some reasons. |
| Preconditions            | The customer has placed the order. The package has not been shipped or the package was damaged or lost during process of delivery. |
| Successful End Condition | The logistics company passes the request. |
| Failed End Condition     | The request is rejected.                 |
| Primary Actors           | Customer                                 |
| Secondary Actors         | None                                     |
| Trigger                  | The customer makes the request of canceling the order. |
| Main Flow                | Step1 Customer logins the logistics system. |
|                          | Step2 Customer selects the button "cancel the order". |
|                          | Step3 Customer explains the reason.      |
|                          | Step4 The logistics company receives the request and passes the request. |
| Extensions               | None.                                    |

| Use case name            | Recreate a New Order                     |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Six                             |
| Goal In Context          | The customer wants to recreate a new order without any extra fees beceause the old package was damaged or lost. |
| Preconditions            | The old package was damaged or lost and the customer has received the message from the logistics company. |
| Successful End Condition | The new order is placed successfully.    |
| Failed End Condition     | The new order is non-compliant and rejected. |
| Primary Actors           | Customer                                 |
| Secondary Actors         | None                                     |
| Trigger                  | The customer makes the request of recreating a new order. |
| Main Flow                | Step1 Customer receives the message about the infomation of the damaged or lost package. |
|                          | Step2 Customer logins the logistics system. |
|                          | Step3 Customer chooses to deliver a new package. |
|                          | Step4 Customer fills in the basic information and recreates a new order whithout any extra fees. |
|                          | Step5 The logistics company receives the new order and passes the request. |
| Extensions               | None                                     |

