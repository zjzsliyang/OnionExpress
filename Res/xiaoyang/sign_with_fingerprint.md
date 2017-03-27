| Use case name            | Sign with Fingerprint                    |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario two, scenario three             |
| Goal In Context          | A customer or the receiver designated by him/her requests to sign his/her name (or other proofs of identity) on Pad. |
| Preconditions            | The package has delivered to the customer-specified location on time. |
| Successful End Condition | The customer receives the package; Package delivery success. |
| Failed End Condition     | The customer fails to get the package; Package should be returned or reschedule delivery.    |
| Primary Actors           | Customer, Package receiving representative.                  |
| Secondary Actors         | Postman                                  |
| Trigger                  | Postman requests customer to sign via fingerprint with the agreetment of customer.   |
| Included Cases           | Confirm Reception, Collect Corresponding Information         |
| Main Flow                | Step 1 : Customer checks if the parcel is delivered right and in good condition in person. |
|                          | Step 2 : Customer signs with fingerprint. |
|                          | Step 3 : Postman confirms the package is received by customer or his/her representative. |
|                          | Step 4 : All corresponding information including the data of the received product and customer acceptance will be transferred back to the server; The order will be marked as complete. |
|                          | include::Collect Corresponding Information |
| Extensions               | Step 1.1 : The customer is not convenient to sign the package and asks someone to receive for him/her.           |
|                          | Step 2.1 : The representative of customer request to sign the package. |
|                          | Step 2.2 : A confirming message is send to customer and he/she should ensure the package is received by the person he/she designated. |
|                          | include::Confirm Reception |
|                          | Step 2.3 : The representative signs with fingerprint. |