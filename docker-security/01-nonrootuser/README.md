# run containers as non-root user
By default, containers run as root inside the container.
This is dangerous because:
- If the container is compromised, the attacker is root
- If a container escape happens, they become root on the host
- Many security scanners flag root containers as high‑risk
