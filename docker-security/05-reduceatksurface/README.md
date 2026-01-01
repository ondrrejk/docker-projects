# reduce attack surface
Remove unnecessary tools:
- No compilers
- No package managers
- No shells (in production)
- No debugging tools
This is why multi‑stage builds matter - the runtime image is clean.