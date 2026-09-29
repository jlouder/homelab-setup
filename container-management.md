## Creating a new container

TBD

## Updating to latest image

```
podman ps   # note image path
sudo su - vaultwarden
systemctl --user stop vaultwarden
podman pull docker.io/vaultwarden/server:latest
systemctl --user start vaultwarden
```
