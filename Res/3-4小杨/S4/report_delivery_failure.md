| Use case name            | Report Delivery Failure                  |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario four                            |
| Goal In Context          | Rearrange package delivery. |
| Preconditions            | Customer does not receive the package. |
| Successful End Condition | A new delivery schedule is made; Parcel would be sent again. |
| Failed End Condition     | Delivery reschedule failed.    |
| Primary Actors           | Postman                        |
| Secondary Actors         | Server                         |
| Trigger                  | Package was received by no one.|
| Main Flow                | Step 1 : Postman sends a report message, which inform the failure of delivery, to server. |
|                          | Step 2 : Server makes a new delivery plan. |
|                          | include::Made New Delivery Schedule |
|                          | Step 3 : A new feasible schedule is made, postman would execute it. |
| Extensions               | Step 2.1 : Server fail to reschedule a new delivery plan.  |
|                          | Step 2.2 : Postman wait until a new delivery schedule is made, or the order is cancelled. |