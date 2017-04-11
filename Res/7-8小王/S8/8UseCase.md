| Use case name            | Track Package                            |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Eight                           |
| Goal In Context          | The logistics tracks all the packages, collecting the location at fixed period and inserting new addresses of destinations into the database. |
| Preconditions            | The customer or the e-business company deliver the package. |
| Successful End Condition | The logistics tracks all the packages and feeds back to the customer or the e-business. |
| Failed End Condition     | The logistics fails track all the packages and feed back to the customer or the e-business. |
| Primary Actors           | Logistics                                |
| Secondary Actors         | None                                     |
| Main Flow                | Step 1 Postman receives and expresses the package to the logistics. |
|                          | Step 2 Logistics delivers the package to the express station. |
|                          | Step 3 The express station  scans the bar code. |
|                          | Step 4 Server records the express station information of the package. |
|                          | Step 5 Logistics delivers the package to the next express station. |
| Extensions               | Step 3.1 The express station  fails to scan the bar code and gets a new bar code. |

 

| Use case name            | Get Package Track Inmformation           |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Eight                           |
| Goal In Context          | The customer or the e-business can get track Inmformation of the package delivered. |
| Preconditions            | 1. The returning request is admitted. 2. The customer or e-business delivers the returning product 3. The package has not been transferred to the receiver. 4.The customer or the e-business has obtained the tracking number. 5.The logistics tracks all the packages, collecting the GPS location at fixed period and inserting new GPS addresses of destinations into the database automatically. |
| Successful End Condition | The customer or the e-business successfully tracks the package he or she delivered. |
| Failed End Condition     | The customer or the e-business successfully failed to track the package he or she delivered. |
| Primary Actors           | Customer, E-business                     |
| Secondary Actors         | None                                     |
| Main Flow                | Step 1 The customer or the e-business logins the system. |
|                          | Step 2 The customer or the e-business inputs the tracking number. |
|                          | Step 3 The customer or the e-business get package track information. |
| Extensions               | Step 1.1 The customer or the e-business failed to login the system with the wrong account and password. |