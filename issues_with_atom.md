__the problem:__

The atom command does not exist, and/or  not found in bash or cmd, even though there is a path for system enviromental variables C:.... atom/bin

__The fix:__
1) open terminal
2) cd %localappdata%
   cd atom
   cd app-1.30.0 [the version you have, can check in atom, help]
   atom.exe --squirrel-install
3) if there is nothing returned back try testing the command atom.
4) **SUCCESS!**
