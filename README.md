# GetsIt Connector

This public repository anchors the multi-architecture GetsIt outbound connector image:

```text
ghcr.io/gorannovitskiy/getsit-connector:1.0.0
```

Setup instructions and enrollment codes are provided inside a GetsIt workspace.

The release workflow publishes signed amd64 and arm64 bundles prepared by the private GetsIt build system. Runtime files are verified against their signed architecture manifest before startup.
