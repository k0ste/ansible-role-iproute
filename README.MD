# ansible-iproute

Management for iproute tables

## Requirements

* Ansible 1.8;

## Example configuration

```yaml
---
iproute:
  - tables:
    - id: '1082'
      name: 'telia'
    - id: '3054'
      name: 'deltax'
```
