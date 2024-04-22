Makerverse and Makerhub prior to v1.3.0  are now officially unsupported. There are sometimes ways to patch old versions of makerverse and makerhub (they all had various bugs that have been addressed and fixed) but occassionally those solutions still don't work in some edge cases.

If there are any feature requests, bugs, annoyances, etc,  please open a ticket. 

Recent Fixes:
- Updated the build environment to support Raspberry Pi3 B+ Boards
- version 1.3.0  had two errors in the default machine profile coordinates.  Those are fixed in version 1.3.1-beta1
- forgot to build an appImage for version 1.3.0,  there's no  1.3.0 appImage but there is for  1.3.1

Notes:
Depending on the configuration and version of Rasapian OS, you might need to add fuse libraries


sudo apt-get install libfuse2 fuse-utils python-fuse
sudo apt-get install libfuse2
sudo apt-get install fuse-utils
sudo apt-get install libfuse3
