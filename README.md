# ip-terraform-doc
ip terraform doc

# Important
1. Generate documentation
```
terraform-docs -c .terraform-docs.yml --output-file README.md --output-mode inject .
```

2. Generate terraform.tfvars
```
terraform-docs tfvars hcl /path/to/module

terraform-docs tfvars json /path/to/module
``` 

<!-- BEGIN_TF_DOCS -->
## Requirements

No requirements.

## Providers

No providers.

## Modules

No modules.

## Resources

No resources.

## Inputs

No inputs.

## Outputs

No outputs.
<!-- END_TF_DOCS -->
