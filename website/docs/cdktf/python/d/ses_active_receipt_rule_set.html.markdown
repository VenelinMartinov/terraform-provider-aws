---
subcategory: "SES (Simple Email)"
layout: "aws"
page_title: "AWS: aws_ses_active_receipt_rule_set"
description: |-
  Retrieve the active SES receipt rule set
---


<!-- Please do not edit this file, it is generated. -->
# Data Source: aws_ses_active_receipt_rule_set

Retrieve the active SES receipt rule set

## Example Usage

```python
# DO NOT EDIT. Code generated by 'cdktf convert' - Please report bugs at https://cdk.tf/bug
from constructs import Construct
from cdktf import TerraformStack
#
# Provider bindings are generated by running `cdktf get`.
# See https://cdk.tf/provider-generation for more details.
#
from imports.aws.data_aws_ses_active_receipt_rule_set import DataAwsSesActiveReceiptRuleSet
class MyConvertedCode(TerraformStack):
    def __init__(self, scope, name):
        super().__init__(scope, name)
        DataAwsSesActiveReceiptRuleSet(self, "main")
```

## Attribute Reference

This data source exports the following attributes in addition to the arguments above:

* `arn` - SES receipt rule set ARN.
* `rule_set_name` - Name of the rule set

<!-- cache-key: cdktf-0.20.8 input-7e5511881f5e55ae7c44bb058232594f1824f28cdd4358ee38cec88c0c71d14b -->