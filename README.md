# Synology Cloud Sync Decryptor Tool

Decrypt files encrypted by Synology Cloud Sync.

## Usage 

```
docker run -it -p 6080:80 -v <your-data-folder>:/data synology-decrypt-docker
```

Then go to http://localhost:6080.

In the (web based) desktop environment open the menu and go to `Accessories` - `Synology Decryptor`.

Resources
---

- https://github.com/fcwu/docker-ubuntu-vnc-desktop
