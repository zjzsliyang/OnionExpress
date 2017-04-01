| Use case name            | Collect Corresponding Information        |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario two, scenario three             |
| Goal In Context          | Collect information and archive related data. |
| Preconditions            | Signing package is finished successfully. |
| Successful End Condition | The order is marked as complete; Relavant information is gathered. |
| Failed End Condition     | The order is unfinished; Inspect system exception. |
| Primary Actors           | Server                                   |
| Secondary Actors         | None                                     |
| Trigger                  | System sends server a message that informs the package delivery is done.   |
| Main Flow                | Step 1 : Information including the data of received products, customer acceptance and some other transaction details are collected by the server. All necessary related data is archived to database |
|                          | Step 2 : Server requests to mark this order as complete. |
| Extensions               | Step 1.1 : Error appears upon the procedure of data collection.  |
|                          | Step 1.2 : Data collection is undone. |