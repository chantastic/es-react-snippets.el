# es-react-snippets.el

Yasnippets for [React] [].

[React]: http://facebook.github.io/react/

## Installation

### Dependencies

* [Yasnippet] [] version 0.7.0 or higher.

[Yasnippet]: https://github.com/capitaomorte/yasnippet

### MELPA

Install `es-react-snippets` is via [MELPA] [].

[MELPA]: http://melpa.milkbox.net/

If you don't have MELPA installed, use this [Getting Started guide] [].

[Getting Started][https://melpa.org/#/getting-started]

If you don't have Yasnippet installed, you can now use MELPA to do so. Installation instructions are [here](https://github.com/capitaomorte/yasnippet#installation).

Finally, install `es-react-snippets` with this command.

    M-x package-install RET es-react-snippets RET

### Manual

First, clone this repository somewhere.

    $ cd /path/to/somewhere
    $ git clone https://github.com/chantastic/es-react-snippets.el.git

Then, in your Emacs init file, add that path to your `load-path`.

    (add-to-list 'load-path "/path/to/somewhere/es-react-snippets.el")

## Setup

Simply require the package.

    (require 'es-react-snippets)

## License

Copyright (C) 2016 Michael Chan and John Mastro

This program is free software; you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program. If not, see <http://www.gnu.org/licenses/>.
