# {{ cookiecutter.project_slug }}

## Overview

{{ cookiecutter.description }}

<!-- Describe what this module provisions and why it exists: the resources it
creates, and how it's meant to be consumed by other stacks. -->

## Architecture

The module defines the following building blocks:

<!-- Replace with this module's actual components. -->

- ...
- ...

The module is stateless: environment-specific wiring happens in the consuming
stack.

## Inputs

| Name      | Description             | Type     | Default | Required |
|-----------|-------------------------|----------|---------|----------|
| `example` | Short description       | `string` | `null`  | yes      |

## Outputs

| Name      | Description       |
|-----------|-------------------|
| `example` | Short description |

## Usage

```hcl
module "{{ cookiecutter.project_slug }}" {
  source = "github.com/vshn/{{ cookiecutter.project_slug }}"

  # inputs
}
```

---

Generated from `terraform-module-template` and kept in sync via Cruft. Change
shared files (CI, Renovate, gitignore) in the template, not here — but this
README is yours to edit; Cruft won't overwrite it.
