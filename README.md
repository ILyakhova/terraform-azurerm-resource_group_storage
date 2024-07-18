# terraform-azurerm-resource_group_storage

## Description

This module creates a resource group and a storage account in Azure.

## Usage

```hcl
module "task6" {
  source = "github.com/your-username/terraform-azurerm-resource_group_storage"

  resource_group_name   = "example-rg"
  location              = "East US"
  storage_account_name  = "examplestorage"
}
