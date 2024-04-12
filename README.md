# Github Action to Lint a Terraform Module using LCAF

## About

This action is designed to lint a Terraform module repository used with LCAF, the Launch Common Automation Framework. The repository must have been created from the [LCAF Terraform Skeleton](https://github.com/launchbynttdata/lcaf-skeleton-terraform).

## Usage

```workflow
...
  steps:
  - name: Lint Module
    uses: launchbynttdata/actions-lcaf-terraform_lint@v0
...
```

## Compatibility

This action has only been tested on GitHub.com.
