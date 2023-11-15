# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:ueransim_3.2.6_amd64.rock docker-daemon:ueransim:3.2.6
docker run ueransim:3.2.6
```
