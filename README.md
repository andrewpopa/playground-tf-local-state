# playground-tf-local-state
will create local null resource 

# Pre-requisites 

- install [git](https://git-scm.com/downloads)
- install [Terraform](https://learn.hashicorp.com/terraform/getting-started/install.html)

## clone repository to use it
```
git clone git@github.com:andrewpopa/playground-tf-local-state.git
cd playground-tf-local-state
```

## add .gitignore

we need this to not commit to repo .terraform dir and state file

```
.terraform/
terraform.tfstate*
```

## usage
```
terraform init
terraform plan
terraform apply
```
