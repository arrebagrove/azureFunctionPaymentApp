# azureFunctionPaymentApp

The Azure functions pipeline that does following task.
1. Receive the payment (Web Hook)
2. Store the detail in Azure Table Storage
2. Put the Message In a Queue
2. Generate License Message and store in a Blob Storage
2. Then Send a Sucessfull Payment Email to Customer


### The Repo Contains
#### Three Azure Function
1. Payment Provider WebHook
2. Generate License Message
3. License File

#### Input Binding
1. Order Row 

#### Four Output Binding
1. Message in Queue
2. Row in Table
2. License File in Blob storage
2. Send email to customer
