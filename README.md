[![pipeline status](https://gitlab.com/ansible-playbooks4/terraform_enterprise/badges/master/pipeline.svg)](https://gitlab.com/ansible-playbooks4/terraform_enterprise/-/commits/master)

#  Description

This Ansible playbook installs and configures Terraform enterprise in a fully automated fashion. There are some requirements, but overall this is very simple to work with.

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

Source:: https://github.com/mtharpe/chef-terraform-enterprise

Issues:: https://github.com/mtharpe/chef-terraform-enterprise/issues

License:: Apache-2.0