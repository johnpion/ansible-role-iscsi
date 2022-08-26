# Ansible role 'iSCSI'

## system
OS: Debian 10

## example vars
```
iscsi_enabled: false
iscsi_connection:
  - name: backup
    storage: /dev/sdb1
    client_ip: 10.0.0.2
    client_name: iqn.1991-05.com.microsoft:example.com
    client_name: AAA123aaa123
```
