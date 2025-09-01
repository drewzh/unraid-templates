# Unraid Community Applications Templates

This repository hosts Unraid Community Applications templates for various Docker applications.

## Adding This Repository to Unraid

1. In Unraid, open **Apps** (Community Applications) → **Settings** → **Repositories**
2. Click **Add New Repository** and paste:
   ```
   https://github.com/drewzh/unraid-templates
   ```
3. Return to **Apps** and search for the desired application

## Available Applications

### MeshCore Web (Self-Updating Mirror)

A dockerized, self-updating mirror of the MeshCore web client that maintains a local copy for improved reliability and performance.

**Key Features:**

- Self-updating mirror functionality
- Atomic version switching
- Fallback to last good version if upstream is unreachable
- Nginx-based web serving

**Default Configuration:**

- WebUI: `http://[Server-IP]:8080/`
- Persistent data: `/mnt/user/appdata/meshcore-web`
- To force a fresh upstream download, set **FORCE_REFRESH** to `true` and restart the container

**Support:** https://github.com/drewzh/meshcore-web-docker/issues

## General Information

- All applications are provided as-is with no warranty
- Templates are maintained independently from the upstream applications
- Please report template-specific issues to this repository
- For application-specific issues, use the support links provided for each application

## Repository Compliance

This repository adheres to the [Unraid Community Applications policies](https://forums.unraid.net/topic/87144-ca-application-policies-privacy-policy/) including:

- Open source applications or applications from reputable sources
- Proper template formatting and descriptions
- Security best practices
- No code injection or additional bash commands

## Author

Maintained by drewzh

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding new templates or improving existing ones.
