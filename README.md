# [Starship](https://starship.rs) configuration

My Starship prompt configuration.

## Getting started

Be sure Starship is already installed.

Then, clone the config at the right place.

```shell
mv ~/.config/starship /tmp/
git clone https://github.com/CCheminaud/starship-config.git ~/.config/starship
```

### Zsh

Add these lines at the end of your `~/.zshrc`.

```zsh
export STARSHIP_CONFIG=~/.config/starship/config.toml
eval "$(starship init zsh)"
```

### Fish

Add these lines at then end of your `~/.config/fish/config.fish`.

```fish
set -x STARSHIP_CONFIG ~/.config/starship/config.toml
starship init fish | source
```
