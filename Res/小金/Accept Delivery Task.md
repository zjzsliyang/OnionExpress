| Accept Delivery Task                     |
| ---------------------------------------- |
| ID: UC02                                 |
| Actor: Postman                           |
| #Preconditions:                          |
| 1. Orders have been created.             |
| 2. The products to be sent have been transferred to the logistics company by E-business. |
| 3. The logistics company have been transported to the regional distribution centers. |
| #Basic flow:                             |
| 1. Postmen log in the system and accept orders assigned by the system. At the same time, the system sends the information list to the corresponding postman,including tracking number, destination, personal information about receivers, QR code for payment( if the customer choose to pay on-site ) and so on. |
| 2. The postman goes to the regional distribution center and gets the package. The postman delivers it to the destination and informs the customer to take it. |
| 3. If the address of the customer is not stored in the database, postmen will collect the GPS location for the customer’s address.But  																				if the address of the customer is already stored in the database, the data will not be collected again. |
| #Post conditions:                        |
| 1.If the package has problems, the postman must record this in the system and will not send the pachage to customer. Refer to Extension use case: Deal with the Expectation. |
| 2. If no accidents happen in the delivery process, the postman will inform the customer of the package and the receiver will sign the package. Refer toUse case: Sign the Package. |
| #Brief description:                      |
| The postman accept delivery task and the information of packages to be delivered. |