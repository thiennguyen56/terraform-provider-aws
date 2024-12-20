---
subcategory: "Redshift"
layout: "aws"
page_title: "AWS: aws_redshift_data_shares"
description: |-
  Terraform data source for managing AWS Redshift Data Shares.
---


<!-- Please do not edit this file, it is generated. -->
# Data Source: aws_redshift_data_shares

Terraform data source for managing AWS Redshift Data Shares.

## Example Usage

### Basic Usage

```typescript
// DO NOT EDIT. Code generated by 'cdktf convert' - Please report bugs at https://cdk.tf/bug
import { Construct } from "constructs";
import { TerraformStack } from "cdktf";
/*
 * Provider bindings are generated by running `cdktf get`.
 * See https://cdk.tf/provider-generation for more details.
 */
import { DataAwsRedshiftDataShares } from "./.gen/providers/aws/data-aws-redshift-data-shares";
class MyConvertedCode extends TerraformStack {
  constructor(scope: Construct, name: string) {
    super(scope, name);
    new DataAwsRedshiftDataShares(this, "example", {});
  }
}

```

## Argument Reference

There are no arguments available for this data source.

## Attribute Reference

This data source exports the following attributes in addition to the arguments above:

* `id` - AWS region.
* `dataShares` - An array of all data shares in the current region. See [`dataShares`](#data_shares-attribute-reference) below.

### `dataShares` Attribute Reference

* `dataShareArn` - ARN (Amazon Resource Name) of the data share.
* `managedBy` - Identifier of a datashare to show its managing entity.
* `producerArn` - ARN (Amazon Resource Name) of the producer.

<!-- cache-key: cdktf-0.20.8 input-a6e02994b2fd3f90675bcbc9f0776c98f5364aa58fe770ac23f494179694a345 -->