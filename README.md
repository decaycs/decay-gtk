<p align="center">
  <img align="center" width="128" height="128" src="https://raw.githubusercontent.com/decaycs/.github/main/assets/logo.png">
</p>

<h3 align="center">Decay GTK</h3>

# Decay-Gtk

Welcome! This is the revamped decay port to GTK!

## Notes

1. Decay-GTK is migrating to Gradience, which means that if you want
gtk3 applications to be themed, you'll need to install
[adw-gtk3](https://github.com/lassekongo83/adw-gtk3)

2. Actually the whole decay colorscheme is going through a huge
revamp, which also includes its ports, such as this one :)

## Installation

You can follow the next steps into your command line:

```sh
git clone https://github.com/decaycs/decay-gtk && cd decay-gtk
mkdir -pv ~/.config/presets/user
cp -rvf ./Themes/* ~/.config/presets/user
```

### Note on flatpak users

If you wanna get your flatpak applications themed as well, you will
have to install the adw-gtk3 flatpak, and put the templates
at `~/.var/app/com.github.GradienceTeam.Gradience.Devel/config/presets/`
too!

```sh
cp -rvf ./Themes/* ~/.var/app/com.github.GradienceTeam.Gradience.Devel/config/presets
```

# Thanks to

- [Alxhr0](https://github.com/Alxhr0)

# Info

If you see any inconsistent when using the theme, please, consider
making an Issue in this repository.
