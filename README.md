## How use this template

Use this template to scaffold a new terraform module. Remember to change the following:
- Update versions required in [versions.tf](versions.tf).
- The descriptions in this [README](README.md).
- Generate documentation with [terraform-docs markdown .](https://github.com/terraform-docs/terraform-docs)
- Update the examples
- Set repository name with this srtucture : `terraform-<PROVIDER>-<NAME>` 

--- 

# terraform-module-template ![Latest Release](https://img.shields.io/github/v/tag/DemisR/terraform-module-template)

## Desription

## Usage

**IMPORTANT:** We do not pin modules to versions in our examples because of the
difficulty of keeping the versions in the documentation in sync with the latest released versions.
We highly recommend that in your code you pin the version to the exact version you are
using so that your infrastructure remains stable, and update versions in a
systematic way so that they do not catch you by surprise.


For a complete example, see [examples/complete](examples/complete).
