pinentry-dmenu
==============

pinentry-dmenu is a pinentry program with the charm of [dmenu](https://tools.suckless.org/dmenu).

This program is a fork from
[pinentry-dmenu](https://github.com/ritze/pinentry-dmenu), which is a fork from
[spine](https://gitgud.io/zavok/spine.git) which is also a fork from
[dmenu](https://tools.suckless.org/dmenu).

I removed the config file support because I prefer the simplicity of builtin
configuration values.

Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

	make clean install


Configuration
-------------
Edit config.h to suit your needs, just like with dmenu.

