# HAProxy - Default configuration in docker container

Run by docker-compose

```sudo docker-compose up -d```

If you have linux kernel version >=4.11 then before run docker disable unprivileged port.

```sudo sysctl net.ipv4.ip_unprivileged_port_start=0```
