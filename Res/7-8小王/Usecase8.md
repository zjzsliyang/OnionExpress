| Use case name            | Get package Track Information            |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Eight                           |
| Goal In Context          | The logistics tracks all the packages, collecting the GPS location at fixed period and inserting new GPS addresses of destinations into the database. |
| Preconditions            | The customer or the e-business company deliver the package. |
| Successful End Condition | The logistics tracks all the packages and feeds back to the customer or the e-business. |
| Failed End Condition     | The logistics fails track all the packages and feed back to the customer or the e-business. |
| Primary Actors           | Logistics                                |
| Secondary Actors         | None                                     |
| Main Flow                | Step 1 The logistics tracks all the packages. |
|                          | Step 2 The logistics feeds back to the customer or the e-business. |
| Extensions               | Step 1.1 The logistics fails to track the packages because of some equipment problems. |
|                          | Step 2.1 The logistics fails to feed back to to the customer or the e-business because o0f some system problems. |

 

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
| Extensions               | Step 1.1 The customer or the e-business failed to login the system with the wrong account and password. |
|                          | Step 2.1 The customer or the e-business inputs the wrong tracking number. |