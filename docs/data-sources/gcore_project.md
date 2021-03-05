---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "gcore_project Data Source - terraform-provider-gcorelabs"
subcategory: ""
description: |-
  Represent project data
---

# gcore_project (Data Source)

Represent project data

## Example Usage

```terraform
provider gcore {
  user_name = "test"
  password = "test"
  gcore_platform = "https://api.gcdn.co"
  gcore_api = "https://api.cloud.gcorelabs.com"
}

data "gcore_project" "pr" {
  name = "test"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String) Displayed project name

### Optional

- **id** (String) The ID of this resource.

