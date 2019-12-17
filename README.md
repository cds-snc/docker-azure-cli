# Docker Azure CLI

Docker image for Azure CLI, Terraform, and other commonly used CLI tools for CI jobs.

## Run

This runs a build of the image published to Google Container Registry.

1. `docker run -it --rm gcr.io/cdssnc/azure-cli:<tag or latest>`
1. Now you can run `az`, `terraform`, etc. commands. Remember to login first.