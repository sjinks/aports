# aports

[![Hosted By: Cloudsmith](https://img.shields.io/badge/OSS%20hosting%20by-cloudsmith-blue?logo=cloudsmith&style=for-the-badge)](https://cloudsmith.com)

Various Alpine packages which have not found their way into the official Alpine 3.13 repo.

## Setup

```bash
echo "https://dl.cloudsmith.io/public/wild-wild-angel/alpine-3-13-packages/alpine/v3.13/main" >> /etc/apk/repositories
wget -q https://dl.cloudsmith.io/public/wild-wild-angel/alpine-3-13-packages/rsa.862248B726792D3C.key -O /etc/apk/keys/rsa.862248B726792D3C.key
apk update
```

------

Package repository hosting is graciously provided by  [Cloudsmith](https://cloudsmith.com).
Cloudsmith is the only fully hosted, cloud-native, universal package management solution, that
enables your organization to create, store and share packages in any format, to any place, with total
confidence.
