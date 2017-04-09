| Use case name            | Made New Delivery Schedule               |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario four                            |
| Goal In Context          | Rearrange package delivery. |
| Preconditions            | No one receives the package. |
| Successful End Condition | A new delivery schedule is made; Parcel would be sent again. |
| Failed End Condition     | Delivery reschedule failed.    |
| Primary Actors           | Server                                   |
| Secondary Actors         | Customer, postman                        |
| Trigger                  | Server make a request of reschedule package delivery.   |
| Main Flow                | Step 1 : Server puts forward a new schedule. |
|                          | Step 2 : Server sends the new plan to customer to see if customer is available then. |
|                          | Step 3 : Customer replies yes. |
|                          | Step 4 : Postman sends the package again according to new schedule that specified by customer. |
| Extensions               | Step 3.1 : Customer replies no.  |
|                          | Step 3.2 : Made new delivery schedule again, or cancel the order. |