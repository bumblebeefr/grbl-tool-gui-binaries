grbl-tool-gui-binaries
======================

"Precompiled" packages to help users running [grbl-tool-gui](https://github.com/bumblebeefr/grbl-tool-gui/)


##Packages
###What's in
Those packages contains grbl-to-gui code, node-webkit and a precompiled serial port module for the specified platform.

To use it you simply have to extract it wherever you want an run the executable file ``grbl-tool-gui-[architecture])``

*On Some version of GNU/Linux you may have an error indicating a missing "libudev.so.0", in this case please follow [those explanations](https://github.com/rogerwang/node-webkit/wiki/The-solution-of-lacking-libudev.so.0) to solve the problem* 

You can also update the package to the latest version of grbl-tool-gui by running a ``git pull`` in folder ``grbl-tool-gui``.

###Supported architectures
For the moment I have prepared only packages for [gnu-linux-32bit](https://github.com/bumblebeefr/grbl-tool-gui-binaries/blob/master/grbl-tool-gui-i386.tar.gz?raw=true) and [gnu-linux-64bit](https://github.com/bumblebeefr/grbl-tool-gui-binaries/blob/master/grbl-tool-gui-i686.tar.gz?raw=true) architectures (tested on ubuntu and derivated). Grbl-tool-gui should also properly works on windows and mac platforms, I'll try to provide "precompiled" packages for those platforms later.
