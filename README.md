## Overview

"Open URI Context Menu" is a plugin for gedit, the default Gnome text editor. This plugin adds two context menu items when we right-click on an URI present in the file content: open on the browser or open on gedit to view source code.

[Original version](http://wiki.sukimashita.com/GEdit_Plugins) was developed by Martin Szulecki for gedit 2.

The current repository is a port of the plugin to gedit 3.

## Requirements

The plugin uses the command `xdg-open` from the package `xdg-utils`.

## Installation

- [Download the archive of the latest version.](https://github.com/jpfleury/open-uri-context-menu/archive/master.zip)

- Extract the archive.

- Copy files `open-uri-context-menu.plugin` and `open-uri-context-menu.py` in the following folder:

		~/.local/share/gedit/plugins/

- Enable the plugin in the gedit menu *Edit > Preferences > Plugins*.

## Development

Git is used for revision control. [Repository can be browsed online or cloned.](https://github.com/jpfleury/open-uri-context-menu)

## License

Authors: Martin Szulecki <<opensuse@sukimashita.com>>, Jean-Philippe Fleury (<http://www.jpfleury.net/en/contact.php>)  
Copyright © 2007-2008 Martin Szulecki  
Copyright © 2011 Jean-Philippe Fleury

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
