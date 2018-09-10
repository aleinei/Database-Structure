# Database-Structure

1-  A new Field with type [bit] in the table [Customers] should be add for confirming the registeration of new customers with default value of 1=Requesting, 2=TrueCustomer, 3-FakeCustomer

2-  When a new customer registers on the server he can not use the application until he receives a message indicating registeration confirmation

3-  the merchant should contact the customer to confirm his information

4-  If the information were true, the merchant should switch the value to 2-TrueCustomer

5-  a message to be sent to the customer's mobile indicating registeration confirmation

6-  If the customer's information were fake, no message would be sent to the customer and and the value to be 3-FakeCustomer

7-  The same for the above to be applied to Merchants

