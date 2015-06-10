# Power ISA-Assembly

A Power ISA assembly language package for the
[Sublime Text](http://www.sublimetext.com) editor, based on the
[M68K Plugin for Sublime](https://github.com/stevenjs/M68k-Assembly) by Steve Saunders

### Installation

##### [Package Control][2]

Open the Command Palette (Shift-Cmd-P in OS X, Shift-Ctrl-P in Linux/Windows).
Select "Package Control: Install Package". Find and install PowerISA-Assembly.

Package Control will automatically keep Power ISA Assembly up to date.

##### Manual Installation

First you must locate the Sublime Text [packages folder][1], then:

Manual installation via git:

    cd /path/to/sublime/packages/folder
    git clone https://github.com/gabbayo/PowerISA.git

Manual installation without git:

    cd /path/to/sublime/packages/folder
    curl -L https://github.com/gabbayo/PowerISA.git/tarball/master | tar xf -

### Contributing

Pull requests welcome. Do *not* edit the `PowerISA-Assembly.tmLanguage` file
directly. Edit the `PowerISA-Assembly.YAML-tmLanguage` file instead and build the
`.tmLanguage` file from it using
[AAAPackageDev](https://github.com/SublimeText/AAAPackageDev).

### License

**PowerISA-Assembly Copyright © 2012, 2015 Oded Gabbay**

```
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
```

[1]:http://docs.sublimetext.info/en/latest/basic_concepts.html#the-packages-directory
[2]:https://packagecontrol.io/
