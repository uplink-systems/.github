# UPLINK SYSTEMS

## Andreas Schreiner IT Services

Welcome to the code repositories of Andreas Schreiner IT-Services.  

### Terraform module repositories

Repositories that have names beginning with **terraform-module-** contain modules for Terraform IaC deployments.  
The module structure tries to follow Hashicorp's recommended structure if possible. For more information see: https://developer.hashicorp.com/terraform/language/modules/develop/structure  

> [!IMPORTANT]
>The modules where developed primarily with my organization's business needs in mind. That means that the modules are as complex as necessary and as simple as possible to match the organization's business requirements and standards. Therefore, as many variable attributes as possible have default values or are even configured as static e.g. to match the organization's internal naming conventions. That makes it easier for the organization to follow standards and prevent the creation of non-standard resources.  
>I've seen a lot of complex modules out there with really fantastic options. Respect for that but mine are not like that. They are as simple as possible and do what I want them to do. Nothing more, nothing less.  
>  
>**Keep that in mind when using them.**  

#### Available modules

The following modules are publicly available under the EUPL 1.2 license or will be released soon:  

* ~~terraform-module-ad-group_policy~~
* ~~terraform-module-azuread-group~~
* ~~terraform-module-azuread-invitation~~
* ~~terraform-module-azuread-named_location~~
* ~~terraform-module-azuread-user~~
* ~~terraform-module-azuredevops-organization_user_entitlement~~
* terraform-module-azuredevops-project
* ~~terraform-module-azuredevops-project_git_repository~~
* ~~terraform-module-azuredevops-project_repository_policy~~
* ~~terraform-module-azuredevops-project_team~~
* ~~terraform-module-azuredevops-project_wiki~~
* ~~terraform-module-azuredevops-project_workitem~~
* ~~terraform-module-azurerm-dns~~
* ~~terraform-module-azurerm-role_definition~~
* terraform-module-github-repository
* ~~terraform-module-pki-1_tier_pki~~