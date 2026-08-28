# terraform-module-template

A Cruft / Cookiecutter template for VSHN Terraform modules. It creates a new
module repository with the shared boilerplate we want kept in sync everywhere:

## Create a new module

    pip install cruft
    cruft create https://github.com/vshn/terraform-module-template

## Change the template

Edit the files under `{{cookiecutter.project_slug}}/` and push to main.
Every generated module's weekly `cruft-update` job will then open a PR
with the changes for review.
