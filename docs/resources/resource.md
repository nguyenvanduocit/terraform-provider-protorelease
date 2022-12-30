---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "scaffolding_resource Resource - terraform-provider-scaffolding"
subcategory: ""
description: |-
  Sample resource in the Terraform provider scaffolding.
---

# scaffolding_resource (Resource)

Sample resource in the Terraform provider scaffolding.

## Example Usage

```terraform
resource "scaffolding_resource" "example" {
  sample_attribute = "foo"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `sample_attribute` (String) Sample attribute.

### Read-Only

- `id` (String) The ID of this resource.

