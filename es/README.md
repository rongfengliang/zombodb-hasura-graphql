# es docker-compose running

## add vm config

```code
echo vm.max_map_count=655360 >> /etc/sysctl.conf && \
sysctl -p
```