# arth_ansible

### async_ansible.yml
If you want to update specific number of systems at once then you can use "serial" keyword.
- hosts: all
  serial:
    - 1   or 10%
    - 2   or 20%
    - 4   or 40%
