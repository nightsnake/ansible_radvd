# radvd role
by Night Snake. Based on imp1sh radvd

## Example to set variables:
```radvd_ifs:
  - if: "eth1"
      prefixes:
            - prefix: "2001:470:7e68:1000::/64"
```
Adopted for Ubuntu 20.04+ and Debian 10+
You can also set DNS servers and set some parameters (please see defaults/main.yml)
