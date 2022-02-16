# Azure function app with terraform support in nutshell
## Here is a two ways how we can manage app with Terraform.
## 1st is to use Terraform only for creating resource groups and pushing changes with CLI.
## 2nd way is using zip package deploying, wich would be faster in cold-starts.

1) Load dependecies by running `npm-init` and debug locally in serve mode wih `npm-start` or build in production mode `npm run build:production`
2) Use terraform script inside folder by running `terraform apply`
3) Push changes with CLI command `func azure functionapp publish azurepetfun-dev-function-app`. 