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