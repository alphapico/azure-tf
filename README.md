## Design Azure Virtual Network using Terraform

<img width="1087" alt="Azure-4-network" src="https://github.com/alphapico/azure-tf/assets/65488712/0946f6c1-db08-4ccc-93f5-de1313801014">

### Setting up `terraform.tfvars`

```jsx
business_divsion = "hr";
environment = "dev";
resource_group_name = "rg";
resource_group_location = "eastus";
vnet_name = "vnet";
vnet_address_space = ["10.1.0.0/16"];

web_subnet_name = "websubnet";
web_subnet_address = ["10.1.1.0/24"];

app_subnet_name = "appsubnet";
app_subnet_address = ["10.1.11.0/24"];

db_subnet_name = "dbsubnet";
db_subnet_address = ["10.1.21.0/24"];

bastion_subnet_name = "bastionsubnet";
bastion_subnet_address = ["10.1.100.0/24"];
```
