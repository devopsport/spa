# Baseline - SPA

[![Build](https://github.com/devopsport/spa/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/devopsport/spa/actions/workflows/main.yml)
[![GitHub Issues](https://img.shields.io/github/issues/devopsport/spa.svg)](https://github.com/devopsport/spa/issues)
[![GitHub Tag](https://img.shields.io/github/tag-date/devopsport/spa.svg?style=plastic)](https://github.com/devopsport/spa/tags/)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/devopsport/spa)

## Usage

```hcl
module "main" {
  source  = "github.com/devopsport/spa"

  project          = "titan"
  env              = "staging"
  service          = "intranet"
  domain           = "spa.falcon.staging.punkerside.io"
  aws_route53_zone = "punkerside.io"
}
```

## Authors

The module is maintained by [DevOpsPort](https://github.com/devopsport)
