# static-dynamic-ip

Dynamic
```
network:
  ethernets:
    eth1:
      dhcp4: true
  version: 2
```

Static
```
network:
 ethernets:
  eth1:
    addresses:
     - 192.168.5.91/24
    gateway4: 192.168.5.1
    nameservers:
      addresses:
      - 8.8.8.8
      - 8.8.4.4
      search: []
 version: 2
```
