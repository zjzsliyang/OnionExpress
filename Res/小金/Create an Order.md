| Use case: Create an Order                |
| :--------------------------------------- |
| ID:UC01                                  |
| Actor: E-business, Customer              |
| #Preconditions：                          |
| 1. The customer buys products from e-business. He or she can pay for their product through online pay, cash pay, or credit card pay. |
| 2. If the customer choose to pay on-site ( credit card pay or cash pay ), the product will be paid by the logistics company in advance. And the logistics company will get the payment of the delivery from customer or E-business(depending on whether the product is free for the delivery) |
| 3. If the customer choose to pay online, whether he or she pays for the delivery by themselves or not, the logistics company gets the payment from the E-business directly. |
| 4. If the customer want to send packages, he or she can also create orders. |
| #Basic flow:                             |
| 1. The customer buys products from e-business and offers his/her information to the E-business. Then he/she will get an order number from the E-business. |
| 2. E-business collects the information and sends to the system immediately or periodically. |
| 3. The system creates orders automatically according to the information above. |
| 4. The E-business transfers products to the logistics company. If the customer doesn’t pay before, the logistics company will pay for the products for the customer in advance. And if the product is free for the delivery, The E-business also needs to pay for the delivery. |
| 5. The customer gets a tracking number, binding to his/her order number, from the system. |
| #Alternative events:                     |
| 1. The customer wants to send a package and he/she creates an order through thesystem. |
| 2. The customer pays for the delivery and transfers the article to the logistics company. |
| 3. The customer gets a tracking number from the system. |
| #Post conditions:                        |
| 1. The product will be transported to the regional distribution centers. |
| 2. When the product is already sent to the regional distribution centers,  it will be scheduled and assigned to different postmen from regions and quantities. |
| 3. The information of orders, including tracking numbers, destinations, telephonenumbers of customers and so on, will be sent to the corresponding postman by the  system, at the same time, the packages will be transferred to the postmen. |
| #Brief description:                      |
| 1. E-business collects the information and sends to the system immediately or periodically and the system creates orders according to the information. |
| 2. The customer can also create orders if he or she want to send packages. |

