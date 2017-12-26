# azureFunctionPaymentApp

The Azure functions pipeline that does following task.
1. Receive the payment (Web Hook)
2. Store the detail in Azure Table Storage
2. Put the Message In a Queue
2. Generate License Message and store in a Blob Storage
2. Then Send a Sucessfull Payment Email to Customer
