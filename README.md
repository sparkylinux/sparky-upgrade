Sparky Upgrade
Sparky Upgrade lets you upgrade the system via one command.

Copyright (C) 2021-2022 Paweł Pijanowski

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

Dependencies:
-------------
apt
grep
iputils-ping
mount
sudo

Suggests:
--------------
nala | nala-legacy

Conflicts:
--------------
sparky-aptus-upgrade (<= 0.3.26)

Replaces:
--------------
sparky-aptus-upgrade (<= 0.3.26)

Install:
-------------
su (or sudo) 
./install.sh

Uninstall:
-------------
su (or sudo)
./install.sh uninstall
