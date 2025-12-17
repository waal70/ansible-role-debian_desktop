debian_desktop
==============

This is the role that sets some defaults for a system that uses a desktop.
It will use tasksel to install gnome desktop environment and customize it
It will install and configure git defaults
It will delete superfluous gnome packages, such as games, LibreOffice, etc.
It will add flatpak and its repository and installs Firefox from it
It will install Remmina remote desktop
It will install Rust (rustup, cargo)

Requirements
------------

It requires a Debian instance, set-up by the preseed.
It also presumes a live sudo package.
Make sure at least the SSH-key for user ansible is set.

Role Variables
--------------

None

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.html#license-text)

Author Information
------------------

Unless otherwise noted, this entire repository is (c) 2024 by André (waal70). [See github profile](https://github.com/waal70)

Please contact me if you need a commercial license for any of these files
