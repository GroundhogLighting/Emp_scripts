# Emp scripts

This repository has some useful Lua scripts you can use for doing some
normal every day tasks.

## What is in the box

The main directory has some files (README.md, License.md, etc.) and two 
more directories. One is called **standard** and the other is called **custom**. The custom directory is not tracked, so you can keep your 
own Emp scripts there, and they will not be published. The standard
directory, on the contrary, is meant to be shared. You can pull new 
changes from it every now and then, and also submit changes and
enhancements.

## Making it work

Just add both to the empath. In my Mac I do it by:

```
export EMPATH=[/path/to/this/directory/]standard:[/path/to/this/directory]/custom
```

That is, just write down all the paths you are interested on adding to the EMPATH separated by ':'. You can check if these are correctly added by 
running 

```
emp --checkpath
```

## License

Copyright (C) 2017  German Molina (germolinal@gmail.com)

These scripts are free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

