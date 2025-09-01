# Unraid Templates (drewzh)

This repo hosts Unraid Community Applications templates.

### Add to Unraid (one-time)

1. In Unraid, open **Apps** (Community Applications) → **Settings** → **Repositories**.
2. Click **Add New Repository** and paste:
   `https://github.com/drewzh/unraid-templates`
3. Return to **Apps**, search for **MeshCore Web (Self-Updating Mirror)**, click **Install**.

### Notes

- Default WebUI: `http://[Server-IP]:8080/`
- Persistent data: `/mnt/user/appdata/meshcore-web`
- To force a fresh upstream download, set **FORCE_REFRESH** to `true` and restart the container.

Issues: https://github.com/drewzh/meshcore-web-docker/issues
