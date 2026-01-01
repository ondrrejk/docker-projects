# use minimal base images
The smaller the image:
- The fewer vulnerabilities
- The faster the build
- The smaller the attack surface
Good options:
- python:3.11-slim (already good)
- python:3.11-alpine (very small, but can break some packages)
- distroless images (ultra‑minimal, no shell)
Distroless images are used in production at Google.