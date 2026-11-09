# Tasqs — Community Applications templates

The [Community Applications](https://docs.unraid.net/community-applications/) template repository for the **Tasqs notification agent** plugin. The plugin itself lives in [tasqs-public/unraid-agent](https://github.com/tasqs-public/unraid-agent); this repository only holds the listing metadata CA reads.

- `ca_profile.xml` — the repository profile shown in Apps
- `plugins/tasqs.xml` — the plugin listing (its `PluginURL` must match the `.plg`'s `pluginURL` exactly)
- `tasqs.png` — the icon

Changelog and version come from the `.plg`, not from here. Nothing else should be added to this repository: CA parses every `.xml` it finds.

Thank you!
