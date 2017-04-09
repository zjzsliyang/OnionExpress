| Use case name            | Check Delivery Information               |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Two                             |
| Goal In Context          | Postmen accept delivery task assigned by the system. |
| Preconditions            | Orders have been created and packages have been transported to the regional distribution centers. |
| Successful End Condition | Postmen check delivery information and send packages to the customer. |
| Failed End Condition     | None                                     |
| Primary Actors           | Postman                                  |
| Secondary Actors         | None                                    |
| Trigger                  | Postmen accept an delivery task.         |
| Main Flow                | Step 1 : Logistics Company assigns task to Postman. |
|                          | Step 2 : Postmen accept delivery task.   |
|                          | Step 3 : Postmen log in the system.      |
|                          | Step 4 : Postmen check delivery information including tracking number, destination, personal information about receivers, QR code for payment( if the customer choose to pay on-site ) and so on. |
|                          | Step 5 : Postmen go to the regional distribution center and get the package. |
|                          | Step 6 : Postmen deliver it to the destination. |
|                          | Step 7 : Postmen inform customers to take packages. At the same time, Postmen will Inspect Address, if the GPS address of  the customer is not in the database, they will collect the GPS address. |
| Extensions               | None                                     |

| Use case name            | Collect GPS Address                      |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario One                             |
| Goal In Context          | Postmen collect the GPS address of  the customer. |
| Preconditions            | Postmen have delivered packages to the destination. |
| Successful End Condition | Server Updates database successfully.    |
| Failed End Condition     | None                                     |
| Primary Actors           | Postman                                  |
| Secondary Actors         | Server                                  |
| Trigger                  | The GPS address of  the customer is not in the database. |
| Main Flow                | Step 1 : Postmen inspect that whether the GPS address of  the customer is in the database. |
|                          | Step 2 : If the GPS address of  the customer is not in the database, postmen will collect the GPS address. |
|                          | Include::Update database                 |
| Extensions               | None                                     |

| Use case name            | Update Database                          |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario One                             |
| Goal In Context          | Server Updates database.                 |
| Preconditions            | Postmen collected the GPS address of  the customer and sended to server. |
| Successful End Condition | Server Updates database successfully.    |
| Failed End Condition     | Server fails to update database          |
| Primary Actors           | Server                                  |
| Secondary Actors         | None                                     |
| Trigger                  | The GPS address of  the customer is not in the database. |
| Main Flow                | Step 1 : Server Updates database.        |
| Extensions               | None                                     |