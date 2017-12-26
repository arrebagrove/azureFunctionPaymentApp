# azureFunctionPaymentApp

The Azure functions pipeline that do following task.
1. Receive the payment (Web Hook)
2. Store the detail in Azure Table Storage
2. Put the Message In a Queue
*. Generate License Message and store in a Blob Storage
*. Then Send a Sucessfull Payment Email to Customer
