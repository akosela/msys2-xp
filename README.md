# msys2-xp

MSYS2 dropped support for Windows XP.  But it is still a perfect retro platform
with compatibility going back to Windows 95 -- an excellent solution for your
classic Windows games.  This is an archive of an older release with carefully
picked additional packages that still works on Windows XP.

msys32.zip includes everything you need to start compiling native Windows 
software using MinGW-w64.

The archive includes:
 * base MSYS2 environment
 * msys2_shell.bat
 * mingw32_shell.bat
 * mingw64_shell.bat
 * ter-112n.fon (the best Windows terminal font ever)

This project specifically aims to compile Yamagi Quake II for Windows XP.  It
includes all of the required dependencies.

It also provides some other useful programs: mutt, irssi, tmux, git, ssh, lftp,
curl/wget.

If you need additional packages that still work under this version of MSYS2
you can take a look here:

  [https://mirrors.huaweicloud.com/msys2](https://mirrors.huaweicloud.com/msys2)

Download them to /msys2/var/cache/pacman/pkg and install with:
```
  $ pacman -U <package>.pkg.tar.xz
```
