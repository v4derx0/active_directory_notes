# 01 Installing the DC

Use  'scconfig' to:
    - change the hostname
    - change the IP address to static
    - change the DNS server to our own IP address


2. Install the AD Windows Feature

```shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```