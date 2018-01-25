dxcli
=====

A platform for building CLIs of any size.

Useful Repos
------------

**Plugins**

* [@dxcli/version](https://github.com/dxcli/version) - `mycli -v|--version|version`. Show the current version.
* [@dxcli/not-found](https://github.com/dxcli/not-found) - Display a friendly "did you mean" message if a command is not found.
* [@dxcli/user-plugins](https://github.com/dxcli/user-plugins) - Allow users to add plugins to extend your CLI.
* [@dxcli/autoupdate](https://github.com/dxcli/autoupdate) - Add autoupdate support to the CLI.
* [@dxcli/autocomplete](https://github.com/dxcli/autocomplete) - Add bash/zsh autocomplete.

Building your own plugin
------------------------

Writing code for plugins is essentially the same as writing within a CLI. They can export 3 different types: commands, hooks, and other plugins.

Run `yarn create dxcli plugin mynewplugin` to create a plugin a new directory. This will come with a sample command and hook
