---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "anypoint_vpc Data Source - terraform-provider-anypoint"
subcategory: ""
description: |-
  Reads a specific `vpc` in the business group.
---

# anypoint_vpc (Data Source)

Reads a specific `vpc` in the business group.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **id** (String) The ID of this resource.
- **org_id** (String)

### Optional

- **owner_id** (String)
- **shared_with** (List of String)

### Read-Only

- **associated_environments** (List of String)
- **cidr_block** (String)
- **firewall_rules** (Block List) (see [below for nested schema](#nestedblock--firewall_rules))
- **internal_dns_servers** (List of String)
- **internal_dns_special_domains** (List of String)
- **is_default** (Boolean)
- **name** (String)
- **region** (String)
- **vpc_routes** (Block List) (see [below for nested schema](#nestedblock--vpc_routes))

<a id="nestedblock--firewall_rules"></a>
### Nested Schema for `firewall_rules`

Read-Only:

- **cidr_block** (String)
- **from_port** (Number)
- **protocol** (String)
- **to_port** (Number)


<a id="nestedblock--vpc_routes"></a>
### Nested Schema for `vpc_routes`

Read-Only:

- **cidr** (String)
- **next_hop** (String)

