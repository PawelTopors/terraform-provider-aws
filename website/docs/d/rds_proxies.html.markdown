---
subcategory: "RDS (Relational Database)"
layout: "aws"
page_title: "AWS: aws_rds_proxies"
description: |-
  Terraform data source for managing an AWS RDS (Relational Database) Proxies.
---

# Data Source: aws_rds_proxies

Terraform data source for managing an AWS RDS (Relational Database) Proxies.

## Example Usage

### Basic Usage

```terraform
data "aws_rds_proxies" "example" {}
```

## Argument Reference

## Attribute Reference

This data source exports the following attributes in addition to the arguments above:

* `proxy_arns` - Set of ARNs of the RDS proxies.
* `proxy_names` - Set of names of the RDS proxies.
