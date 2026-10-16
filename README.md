<picture>
  <source srcset="./tmux.svg"/>
  <img
    alt="tmux logo"
    src="./tmux.svg"
    height="128px"
    width="128px"
    align="left"
  />
</picture>

### tmux.conf by Degete

> *TMUX configuration for everyone*

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/degete/tmux-conf)

## Getting started

```sh
cd ~
git clone --recursive git@github.com:degete/tmux-conf.git ~/.tmux
ln -s .tmux/tmux.conf .tmux.conf
~/.tmux/plugins/tpm/scripts/install_plugins.sh
```

## Prefix
By default, the `prefix` is: <kbd>⌃</kbd> + <kbd>a</kbd>.

However, the default <kbd>⌃</kbd> + <kbd>b</kbd> can be used instead, to do so uncomment it on [general.conf](./config/general.conf)

## Plugins

### [Tmux Plugin Manager](https://github.com/tmux-plugins/tpm)

#### Plugins list
* Edit [plugins.conf](./config/plugins.conf)
* Add plugins e.g.: `set -g @plugin '<plugin>'`

#### Commands
`prefix` + <kbd>I</kbd> install plugins and reload tmux environment

`prefix` + <kbd>U</kbd> update plugins

`prefix` + <kbd>⌥</kbd> + <kbd>u</kbd> remove plugins

#### [Tmux Sensible](https://github.com/tmux-plugins/tmux-sensible)
A set of tmux options that should be acceptable to everyone.

#### [Tmux Resurrect](https://github.com/tmux-plugins/tmux-resurrect)
Restore tmux environment after system restart.

`prefix` + <kbd>⌃</kbd> + <kbd>s</kbd> save environment

`prefix` + <kbd>⌃</kbd> + <kbd>r</kbd> restore environment

#### [Tmux Continuum](https://github.com/tmux-plugins/tmux-continuum)
Continuous saving of tmux environment, automatic tmux start when computer/server is turned on and automatic restore when tmux is started.

### Mappings

#### General
<kbd>⌥</kbd> + <kbd>r</kbd> reload tmux configuration

`prefix` + <kbd><</kbd> show tmux session menu

`prefix` + <kbd>></kbd> reload tmux pane menu


#### Sessions
<kbd>⌥</kbd> + <kbd>N</kbd> rename session

#### Windows
<kbd>⌥</kbd> + <kbd>t</kbd> new window

<kbd>⌥</kbd> + <kbd>W</kbd> kill window

<kbd>⌥</kbd> + <kbd>←</kbd> previous window

<kbd>⌥</kbd> + <kbd>→</kbd> previous window

<kbd>⌥</kbd> + <kbd>n</kbd> rename window

#### Panes
<kbd>⌥</kbd> + <kbd>w</kbd> kill pane

<kbd>⌥</kbd> + <kbd>d</kbd> split pane vertical

<kbd>⌥</kbd> + <kbd>D</kbd> split pane horizontal

<kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>↑</kbd> move to upper pane

<kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>↓</kbd> move to lower pane

<kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>←</kbd> move to left pane

<kbd>⌥</kbd> + <kbd>⇧</kbd> + <kbd>→</kbd> move to right pane

<kbd>⌥</kbd> + <kbd>z</kbd> zoom pane

## Self Promotion

If you find this project useful, consider giving it a ★ on [GitHub](https://github.com/degete/tmux-conf). You can also follow [Degete](https://github.com/degete) for more projects on [GitHub](https://github.com/degete/).

### See also

- [gitconfig](https://github.com/degete/gitconfig): ⚙️ Git config files
- [tmux-conf](https://github.com/degete/tmux-conf): ⚙️ tmux config files
- [vimrc](https://github.com/degete/vimrc): ⚙️ Vim config files
- [nvim-config](https://github.com/degete/nvim-config): ⚙️ Neovim config files
- [brewfile](https://github.com/degete/brewfile): ⚙️ brewfile config file for macOS 🍏

## License

This project is licensed under the [MIT License](./LICENSE).

Copyright (c) David Tort.