# Project-6
Azure storage accounts

In this project, below environment will be provisioned and storage accounts will be created according to the table below

![Alt text](/screenshots/Project.png "Main Project")

### Step 1
#### Environment provision 
A resource group named az104-07-rg0 is created through powershell. Using json templates (can be found in json folder) virtual network and virtual machine created.

### Step 2
#### Storage account creation
A storage account is created with blob access tier as cool and public access from everywhere properties.

### Step 3
#### Manage blob storage
New container created under previously created storage account named az104-07-container. LICENSE file is uploaded in this container.

![Alt text](/screenshots/container.jpg "Container")

![Alt text](/screenshots/Licence%20file.jpg "License file")

### Step 4
#### Manage authentication and authorization
In this step I created a SAS token and a SAS URL to reach the file (it has private access therefore cannot be reached otherwise).

![Alt text](/screenshots/error%20message.jpg "Error message")

Using above SAS URL we can reach the file.

Then I added a role assignment to myself as the storage blob data owner in order to change the authentication method to Azure AD User Account.

![Alt text](/screenshots/role%20assignment.jpg "Role")

![Alt text](/screenshots/switch%20success.jpg "Success")

### Step 5
#### Create and configure an Azure Files shares