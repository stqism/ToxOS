ToxOS
=====

ToxOS is an OS design to do one thing and one thing only, Tox.

###FAQ:
#####What does it do?
Boot straight in to Tox, loading only Tox. Nothing else exists, just Tox.

#####What Linux distro is it forked from?
It isn't, ToxOS is its own OS

#####How do I compile it?
```
sh build.sh -m{ARCH} -O /path/to/toolchain tools
sh build.sh -m{ARCH} -O /path/to/toolchain -j {number of cores} -U distribution
```
If you want an ISO or installer or something run ``sh build.sh -h``

#####Where can I download it?
WIP

#####What's it based off of?
It's a fork of Minix 3.3.0
