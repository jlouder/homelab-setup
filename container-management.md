## Creating a new container

TBD

## Updating to latest image

```
sudo su - vaultwarden
podman ps   # note image path
systemctl --user stop vaultwarden
podman pull docker.io/vaultwarden/server:latest
systemctl --user start vaultwarden
```
