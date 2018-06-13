# elasticsearch
Just a docker-compose with cerebro and elasticsearch.

You will need to set your `sysctl vm.max_map_count` is at least 262144 on the host before starting up:

```bash
# sysctl -w vm.max_map_count=262144
```
