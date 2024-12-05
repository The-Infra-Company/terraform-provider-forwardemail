---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "forwardemail_alias Resource - forwardemail"
subcategory: ""
description: |-
  A resource to create Forward Email domain aliases.
---

# forwardemail_alias (Resource)

A resource to create Forward Email domain aliases.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `domain` (String) Fully qualified domain name (FQDN).
- `name` (String) Alias name.

### Optional

- `has_recipient_verification` (Boolean) Whether to enable to require recipients to click an email verification link for emails to flow through.
- `is_enabled` (Boolean) Whether to enable to disable this alias.
- `labels` (List of String) List of labels.
- `recipients` (List of String) List of recipients as valid email addresses, fully-qualified domain names (FQDN), IP addresses, or webhook URL's.

### Read-Only

- `id` (String) The ID of this resource.