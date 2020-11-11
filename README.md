# Awesome wlroots

A curated list of tools and compositors around [wlroots](https://github.com/swaywm/wlroots). 

wlroots is a compositor library and defines a large and diverse ecosystem around [wlr-protocols](https://github.com/swaywm/wlr-protocols). 

This list is dedicated to cool stuff/useful tools for wlroots desktops. For general cool stuff and applications on Wayland check out [awesome-wayland](https://github.com/natpen/awesome-wayland). 

If you want to contribute, please read [this](CONTRIBUTING.md).

## Table of contents

  - [Brightness Control](#brightness-control)
  - [Clipboard Managers](#clipboard-managers)
  - [Compositors](#compositors)
  - [Display Configuration](#display-configuration)
  - [Docks](#docks)
  - [Keyboards](#keyboards)
  - [Launchers](#launchers)
  - [Notifications](#notifications)
  - [Remote control](#remote-control)
  - [Screen Locking](#screen-locking)
  - [Screencasting](#screencasting)
  - [Screenshots](#screenshots)
  - [Session Management](#session-management)
  - [Status Bars](#status-bars)
  - [Tools](#tools)
  - [Wallpaper](#wallpaper)
  - [License](#license)

## Brightness Control

No Wayland-specific requirements, so you can use your xorg solution of choice to control screen brightness, like [brightnessctl](https://github.com/Hummer12007/brightnessctl), [brillo](https://gitlab.com/cameronnemo/brillo), [light](https://github.com/haikarainen/light), or just directly manipulate `/sys/class/backlight`.

wlroots supports gamma setting through `wlr-gamma-control-unstable-v1`. 

* [gammastep](https://gitlab.com/chinstrap/gammastep) - Tints the display orange to reduce stress on the eyes (Redshift fork with wlroots compatibility patch)
* [wl-gammactl](https://github.com/mischw/wl-gammactl) - Control brightness, contrast and gamma
* [wlr-brightness](https://github.com/mherzberg/wlr-brightness) - A dbus-controllable overlay to darken your screen
* [Wlsunset](https://sr.ht/~kennylevinsen/wlsunset/) - Day/night gamma adjustments for Wayland compositors supporting wlr-gamma-control-unstable-v1.

## Clipboard Managers

* [wl-clipboard](https://github.com/bugaevc/wl-clipboard) - Command-line copy/paste utilities for Wayland
* [clipman](https://github.com/yory8/clipman) - A simple clipboard manager for Wayland

## Compositors

* [Cagebreak](https://github.com/project-repo/cagebreak) - A Wayland tiling compositor inspired by Ratpoison
* [Cardboard](https://gitlab.com/cardboardwm/cardboard) - A scrollable tiling Wayland compositor
* [dwl](https://github.com/djpohly/dwl) - dwm for Wayland
* [epd-wm](https://github.com/dj311/epd-wm) - Wayland window manager that outputs to IT8951 E-Paper displays. 
* [hikari](https://hikari.acmelabs.space/) - A hybrid stacking/tiling Wayland compositor
* [kiwmi](https://github.com/buffet/kiwmi) -  A fully programmable Wayland Compositor 
* [labwc](https://github.com/johanmalm/labwc) - A stacking Wayland compositor with look and feel of openbox
* [river](https://github.com/ifreund/river) - A dynamic tiling Wayland compositor
* [Sway](https://github.com/swaywm/sway) - i3-compatible Wayland compositor
* [tinybox](https://github.com/icedman/tinybox) - tries to emulate the blackbox, fluxbox, openbox family of wm
* [Waybox](https://github.com/wizbright/waybox) - An openbox clone on Wayland
* [Wayfire](https://github.com/WayfireWM/wayfire) - 3D Wayland compositor

## Display Configuration

* [Kanshi](https://github.com/emersion/kanshi) - Dynamic display configuration
* [Wallutils](https://github.com/xyproto/wallutils) - A set of utilities to manage monitors, resolutions, wallpapers and timed wallpapers
* [wdisplays](https://github.com/cyclopsian/wdisplays) - GUI display configurator for wlroots compositors
* [wlay](https://github.com/atx/wlay) - Graphical output management for Wayland
* [wlr-randr](https://github.com/emersion/wlr-randr) - An xrandr clone for wlroots compositors

## Docks

wf-dock (part of [wf-shell](https://github.com/WayfireWM/wf-shell)) - Very simple dock for application switching (no launching)

## Keyboards

* [wf-osk](https://github.com/WayfireWM/wf-osk) - A very, very basic on-screen keyboard using gtkmm, virtual-keyboard-v1 and layer-shell protocols
* [wvkbd](https://github.com/jjsullivan5196/wvkbd) - A "suckless" on screen keyboard

## Launchers

* [bemenu](https://github.com/Cloudef/bemenu) - Dynamic menu library and client program inspired by dmenu
* [dmenu-wayland](https://github.com/nyyManni/dmenu-wayland) - dmenu-wl is an efficient dynamic menu for wayland (wlroots)
* [LavaLauncher](https://git.sr.ht/~leon_plickat/lavalauncher) - A simple launcher panel for Wayland desktops
* [Mauncher](https://github.com/mortie/mauncher) - A GTK-based alternative to dmenu for Wayland which supports display scaling
* [nwg-launchers](https://github.com/nwg-piotr/nwg-launchers) - A GTK-based application grid launcher, button bar and dmenu for Wayland
* [Wofi](https://hg.sr.ht/~scoopta/wofi) - A launcher/menu program for wlroots based Wayland compositors such as sway

## Notifications

* [Mako](https://github.com/emersion/mako) - A lightweight Wayland notification daemon

## Remote control

* [waynergy](https://github.com/r-c-f/waynergy) - An implementation of a synergy client for wlroots compositors ("not ready for primetime")
* [wayvnc](https://github.com/any1/wayvnc) - A VNC server for wlroots based compositors

## Screen Locking

* [swayidle](https://github.com/swaywm/swayidle) - Idle management daemon for Wayland
* [swaylock](https://github.com/swaywm/swaylock) - Screen locker for Wayland
* [swaylock-effects](https://github.com/mortie/swaylock-effects) - A fork of swaylock with effects such as a blurred screenshot as background or a clock on the lockscreen
* [waylock](https://github.com/ifreund/waylock) - A simple screenlocker for Wayland compositors

## Screencasting

* [ssr-wlroots](https://github.com/foxcpp/ssr-wlroots) - A version of SimpleScreenRecorder with support for `wlroots`-based compositors (more specifically, those that support `wlr-screencopy-v1` and `xdg-output`). Doesn't support recording area selection and has issues with multiple screens. 
* [wf-recorder](https://github.com/ammen99/wf-recorder) - A utility program for screen recording of `wlroots`-based compositors (more specifically, those that support `wlr-screencopy-v1` and `xdg-output`)
* [wlrobs](https://hg.sr.ht/~scoopta/wlrobs) - An obs-studio plugin that allows you to screen capture on wlroots based wayland compositors
* [wshowkeys](https://git.sr.ht/~sircmpwn/wshowkeys) - Displays keys being pressed on a Wayland session
* [xdg-desktop-portal-wlr](https://github.com/emersion/xdg-desktop-portal-wlr) - Share your screen through Pipewire

## Screenshots

* [Grim](https://github.com/emersion/grim) - Grab images from a Wayland compositor
* [Slurp](https://github.com/emersion/slurp) - Select a region in a Wayland compositor
* [Swappy](https://github.com/jtheoof/swappy) - A Wayland-native snapshot editing tool, inspired by Snappy on macOS

## Session Management

* [wlogout](https://github.com/ArtsyMacaw/wlogout) - A Wayland-based logout menu

## Status Bars

* [i3status-rust](https://github.com/greshake/i3status-rust) - Very resource-friendly and feature-rich replacement for i3status, written in pure Rust
* [rootbar](https://hg.sr.ht/~scoopta/rootbar) - Root Bar is a bar for wlroots based Wayland compositors such as sway
* [waybar](https://github.com/Alexays/Waybar) - Highly customizable Wayland bar for Sway and Wlroots based compositors
* wf-panel (part of [wf-shell](https://github.com/WayfireWM/wf-shell)) - Panel with support for application launchers
* [yambar](https://gitlab.com/dnkl/yambar) - Modular status panel for X11 and Wayland, inspired by polybar

## Tools

* [wtype](https://github.com/atx/wtype) - A Wayland tool that allows you to simulate keyboard input like [xdotool](https://github.com/jordansissel/xdotool)
* [ydotool](https://github.com/ReimuNotMoe/ydotool) - A generic Linux command-line automation tool for Wayland

## Wallpaper

* [oguri](https://github.com/vilhalmer/oguri) - A very nice animated wallpaper daemon for Wayland compositors
* [mpvpaper](https://github.com/GhostNaN/mpvpaper) - A video wallpaper program for wlroots based wayland compositors
* [swaybg](https://github.com/swaywm/swaybg) - A wallpaper utility for Wayland compositors
* wf-background (part of [wf-shell](https://github.com/WayfireWM/wf-shell)) - Simple wallpaper program supporting switching of images

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
