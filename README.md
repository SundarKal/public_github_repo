# oracle_patching# oracle_19c_patching
### IMPORTANT STEP

If you want to install the csc ansible-role via the `ansible-galaxy` command
you'll need to create a [requirements.yml](roles/requirements.yml)
file in "roles/" directory (if one doesn't already exist),
with the following contents:

```bash
---
- name: ansible-role_orapatch
  src: https://cscgithub.cscglobal.com/INFRA/ansible-role_orapatch
  scm: git
```

...and install role(s) using the following command from parent directory:

`ansible-galaxy install -p roles -r roles/requirements.yml`

## Default Variables

See [`defaults/main.yml`](defaults/main.yml).

Default Variables listed below:

| Variable | Description |
| --- | --- |
| variable | value |

## Custom Variables

See [`vars/main.yml`](vars/main.yml).

Custom Variables listed below:

| Variable | Description |
| --- | --- |
| variable | value |

## Inventory Variables

**REQUIRED:** These variables would be defined in inventory file as host varables.

| Variable | Description |
| --- | --- |
| variable | value |
