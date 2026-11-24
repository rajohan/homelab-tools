# homelab-tools

Docker Compose base definitions and pinned upstream images used by this homelab. The dashboard records verified image updates directly on main as Mira.

Inspect the public base with `docker compose config --images`. For your own installation, supply the environment, volumes, network configuration and service-specific settings each application requires in a private Compose override. This base alone is not a configured production deployment.
