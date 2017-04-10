| Use case name            | Reschedule Delivery                      |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario four                            |
| Goal In Context          | Rearrange package delivery. |
| Preconditions            | Customer does not receive the package. |
| Successful End Condition | A new delivery schedule is made; Parcel would be sent again. |
| Failed End Condition     | Delivery reschedule failed.    |
| Primary Actors           | Customer                                   |
| Secondary Actors         | Server                         |
| Trigger                  | Customer requests to reschedule package delivery.   |
| Main Flow                | Step 1 : Customer requests the server to reschedule package delivery, sends a new time that he/she is available (and a new location if he/she needs). |
|                          | Step 2 : Server makes a new delivery plan. |
|                          | include::Made New Delivery Schedule |
|                          | Step 3 : Customer agrees. |
|                          | Step 4 : New Schedule would be executed. |
| Extensions               | Step 3.1 : Customer is not satisfied with the new schedule.  |
|                          | Step 3.2 : Made new delivery schedule again, or cancel the order. |