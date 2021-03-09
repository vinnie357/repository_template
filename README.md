# repository_template
base repository template using f5-devops-containers
---

includes:
 pre-commit
 go
 docker
 terraform
 terraform-docs
## Development

checking for secrets as well as linting is performed by git pre-commit with the module requirements handled in the devcontainer.

testing pre-commit hooks:
  ```bash
  # test pre commit manually
  pre-commit run -a -v
  ```
---
