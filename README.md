# Plover Plugins Registry

This repo contains the list of plugins that will show in the Plover Plugins Manager.

In order for your [Plover](https://github.com/openstenoproject/plover) plugin to be installable from the Plugins Manager, it must be listed in [registry.json](registry.json).

If a plugin is incompatible with a newer Plover version, it will be listed in [unsupported.json](unsupported.json) — a JSON dictionary mapping plugins to the earliest unsupported major Plover version.

## Contributing

To add your plugin to the registry, please:

- Fork this repository
- Add your plugin to the list as it's named on [PyPI](https://pypi.org)
- Ensure that the list is an alphabetical JSON array
- Open a pull request ([how to open a pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request))
- After your PR is merged, the plugin will be listed in the Plover Plugins Manager
