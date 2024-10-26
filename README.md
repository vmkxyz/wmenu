# fork

I modified the colors, font and font size in menu.c

# wmenu

wmenu is an efficient dynamic menu for Sway and wlroots based Wayland
compositors. It provides a Wayland-native dmenu replacement which maintains the
look and feel of dmenu.

## Installation

Dependencies:

- cairo
- pango
- wayland
- xkbcommon
- scdoc (optional)

```
$ meson build
$ ninja -C build
# ninja -C build install
```

## Usage

See wmenu(1)

To use wmenu with Sway, you can add the following to your configuration file:

```
set $menu wmenu-run
bindsym $mod+d exec $menu
```
