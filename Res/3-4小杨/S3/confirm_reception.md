| Use case name            | Confirm Reception                        |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario two, scenario three             |
| Goal In Context          | Customer verifies if the receiver is designated by him/her. |
| Preconditions            | The package has delivered to the customer-specified location on time but customer is not convenient to received it. |
| Successful End Condition | The receiver has the permission to sign the package. |
| Failed End Condition     | The receiver is an imposter; Postman refuses giving him/her the package.    |
| Primary Actors           | Customer                                 |
| Secondary Actors         | Postman                                  |
| Trigger                  | Someone but not customer claims that he/she have the permission to receive the package.   |
| Main Flow                | Step 1 : Postman collects the necessary information of *that person* and then sends to customer. |
|                          | Step 2 : Customer confirms the if the potential receiver is as expected. |
|                          | Step 3 : Postman gets a positive feedback from customer. |
|                          | Step 4 : The receiver can sign the package under customer's permission. |
| Extensions               | Step 3.1 : Postman gets a negative feedback from customer; *That person* is an imposter.  |
|                          | Step 3.2 : Postman refuses to give away the parcel. |