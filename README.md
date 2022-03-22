[![CircleCI](https://circleci.com/gh/mtharpe/ansible-terraform-enterprise/tree/master.svg?style=svg)](https://circleci.com/gh/mtharpe/ansible-terraform-enterprise/tree/master)


#  Description

This Ansible playbook installs and configures Terraform enterprise in a fully automated fashion. There are some requirements, but overall this is very simple to work with.

This is designed to be edited per use, the tasks will work for your needs but you will want to update the playbook info to ensure you have what you need.

## Requirements:

- Ansible 2.x
- Test-Kitchen
- Inspec

## Roles

- terraform_enterprise
  
## Vars:

|Variable|Value|Required|Description|
|---|---|---|---|
|installation_type|string|yes|Terraform Installation Type (default = POC)|
|installation_file_location|string|yes|Terraform Installation File used to install (default = `tmp`)|

## License and Maintainer

Maintainer:: HashiCorp (<hello@hashicorp.com>)

Source:: https://github.com/mtharpe/ansible-terraform-enterprise

Issues:: https://github.com/mtharpe/ansible-terraform-enterprise/issues

License:: Apache-2.0

