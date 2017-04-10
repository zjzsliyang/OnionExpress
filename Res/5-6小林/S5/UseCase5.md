| Use case name            | Pay for the Product                      |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Five                            |
| Goal In Context          | The customer needs to pay for the product after he/she has placed the product or received the product. |
| Preconditions            | The customer has placed the order.       |
| Successful End Condition | The payment is completed.                |
| Failed End Condition     | The order has been canceled or the customer has not received the product for some reasons. |
| Primary Actors           | Customer                                 |
| Secondary Actors         | None                                     |
| Trigger                  | The customer places the order or receives the product. |
| Main Flow                | Step1 Customer chooses one acceptable way to pay for the product. |
|                          | Step2 Customer checks the amount.        |
|                          | Step3 Customer finishes the payment.     |
|                          | Step4 E-business receives the payment.   |
| Extensions               | Step3.1 Customer asks for a invoice about the product. |

| Use case name            | Pay Online                               |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Five                            |
| Goal In Context          | The customer wants to pay for the product online after he/she has placed the order. |
| Preconditions            | The customer has placed the order, and paying online is provided. |
| Successful End Condition | The payment is completed.                |
| Failed End Condition     | The order has been canceled.             |
| Primary Actors           | Customer                                 |
| Secondary Actors         | None                                     |
| Trigger                  | The customer places the order.           |
| Main Flow                | Step1 Customer logins the Third-party Trade system. |
|                          | Step2 Customer checks the amount in the system. |
|                          | Step3 Customer enters the passwords to pay. |
|                          | Step4 Customer finishes the payment.     |
|                          | Step5 E-business receives the payment.   |
| Extensions               | None.                                    |

| Use case name            | pay offline                              |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Five                            |
| Goal In Context          | The customer wants to pay for the product offline after he/she has received the product. |
| Preconditions            | The customer has received the product, and paying offline is provided. |
| Successful End Condition | The payment is completed.                |
| Failed End Condition     | The customer has not received the product for some reasons. |
| Primary Actors           | Customer                                 |
| Secondary Actors         | Postman                                  |
| Trigger                  | The customer receives the product.       |
| Main Flow                | Step1 Postman checks the amount with the customer. |
|                          | Step2 Customer chooses one way to pay, by cash or by credit card. |
|                          | Step3 Customer finishes the payment.     |
|                          | Step4 Postman records the information about the payment. |
|                          | Step5 The logistics company transfers the money to E-business. |
| Extensions               | **Step2.1** Customer chooses to pay by cash. |
|                          | a.Customers pays for the product by cash. |
|                          | b.Postman checks the amounts of money and confirms the payment in the APP. |
|                          | **Step2.2** Customer Chooses to pay by credit card. |
|                          | a.Postman provide the POS device for the customer. |
|                          | b.Customer gives the postman his/her Visa card or Union-Pay card. |
|                          | c.Postman swipes the card and enters the amount of money. |
|                          | d.Customer enters the password.          |
|                          | e.The bank system adds money to the logistics company’s account. |
|                          | **Step4.1** Postman submits the money to the logistics company. |

| Use case name            | Provide the Invoice                      |
| ------------------------ | ---------------------------------------- |
| Related Requirements     | Scenario Five                            |
| Goal In Context          | E-business provides the invoice about the product for the customer. |
| Preconditions            | The customer has completed the payment and asks for the invoice. |
| Successful End Condition | The Invoice has been sent to the customer. |
| Failed End Condition     | E-business rejects the request.          |
| Primary Actors           | E-business                               |
| Secondary Actors         | Customer                                 |
| Trigger                  | Customer asks for the invoice about the product. |
| Main Flow                | Step1 Customer choose one way to receive the invoice, digital invoice sent by e-mail or a paper invoice sent by post. |
|                          | Step2 E-business sends the invoice to the customer. |
|                          | Step3 Customer receives the invoice and confirm whether the infomation is onsistent. |
| Extensions               | Step1.1 Customer chooses to receive a digital invoice sent by e-mail. |
|                          | a.Customer fills in the e-mail address in the APP. |
|                          | Step1.2 Customer chooses to receive a paper invoice sent by post. |
|                          | a.Customer fills in the mailing address in the APP. |

