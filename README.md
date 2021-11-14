# AAD License Governor Deploy
Code to deploy the AAD License Governor infrastructure and service.

## Actions
All deployments are performed via GitHub Actions.

| Action                                                     | Purpose                                                                               | Status                                                                                                                                                                                                                          |
| ---------------------------------------------------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [app-deploy-prd](.github/workflows/app-deploy-prd.yml)     | Deploys the service to the aadlicense-prd resource group                              | [![app-deploy-prd](https://github.com/jrolstad/aad-license-governor-deploy/actions/workflows/app-deploy-prd.yml/badge.svg)](https://github.com/jrolstad/aad-license-governor-deploy/actions/workflows/app-deploy-prd.yml)       |
| [infra-deploy-prd](.github/workflows/infra-deploy-prd.yml) | Creates and manges the infrastructure in the aadlicense-prd for the service to run on | [![infra-deploy-prd](https://github.com/jrolstad/aad-license-governor-deploy/actions/workflows/infra-deploy-prd.yml/badge.svg)](https://github.com/jrolstad/aad-license-governor-deploy/actions/workflows/infra-deploy-prd.yml) |

## Dependencies
Dependent sources are managed via git submodules.  Submodules for this repo can be found in the [.gitmodules](.gitmodules) file.