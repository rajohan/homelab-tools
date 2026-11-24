# homelab-tools

Docker Compose base definitions and pinned upstream images used by this homelab. The dashboard records verified image updates directly on main as Mira.

The tracked `.env` files contain the source references used by Compose. Load the referenced environment variables before running `docker compose config --images`. To list the pinned images without loading any environment files, run `git grep -h '^[[:space:]]*image:' -- 'apps/*/compose.yaml'`. For your own installation, supply the environment, volumes, network configuration and service-specific settings each application requires in a private Compose override. This base alone is not a configured production deployment.
