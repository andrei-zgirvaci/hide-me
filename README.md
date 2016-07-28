#hide-me - mac and hostname random changer

##About
Every time I was trying to do an attack throught a network, I needed to type same commands every time, put my interface down, change my mac address, change my hostname, putting interface back up, and restarting network-manager service, and when done, change my mac address and hostname to original one. This took me a while and sometimes I even forgot to do something from those steps. Then I came to an idea to make a script that does all that for me. Basicly this script will change the mac address to a random one and will pick a random hostname from specified file.

##Installation
*To install this script, type following commands in your shell:*
```
  git clone https://github.com/MD3XTER/hide-me
```
  
*To execute script from anywhere, type this:*
```
  PATH=/path/to/hide-me:"$PATH"
```

*Now you can type 'hide-me' from anywhere and it will execute!*

##Usage
*Usage: hide-me device [file_location]*
```
  -h, --help       Print this help
  [file_location]  Indicate file location with hostnames
  quit             Retrieve changes to original
```

*A default .txt file with random hostnames is located in 'dict' folder*

##Contribute
Contributions are always welcome!

##License
This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307 USA

See 'LICENSE' for more information.

##Author
> Andrei Zgirvaci
