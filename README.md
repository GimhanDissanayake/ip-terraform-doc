# ip-terraform-doc
ip terraform doc

# Important
1. Generate documentation
```
terraform-docs -c .terraform-docs.yml --output-file README.md --output-mode replace .
```

2. Generate terraform.tfvars
```
terraform-docs tfvars hcl /path/to/module

terraform-docs tfvars json /path/to/module
``` 