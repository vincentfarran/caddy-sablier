# caddy-sablier

Custom Caddy image with the Sablier Caddy plugin installed.

The image is built by GitHub Actions and published to:

```text
ghcr.io/<owner>/caddy-sablier:latest
```

Use it in Compose:

```yaml
services:
  caddy:
    image: ghcr.io/<owner>/caddy-sablier:latest
```
