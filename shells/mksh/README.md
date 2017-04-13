# mksh

* Homepage: https://www.mirbsd.org/mksh.htm

mksh is the successor of the Public Domain Korn shell (pdksh),
 a Bourne/POSIX compatible shell which is largely similar to the
 original AT&T Korn Shell (ksh88/ksh93).
 It includes bug fixes and feature improvements, in order to produce a
 modern, robust shell good for interactive and especially script use.
 mksh has UTF-8 support (in string operations and the Emacs editing
 mode). The code has been cleaned up and simplified, bugs fixed,
 standards compliance added, and several enhancements (for extended
 compatibility to other modern shells, as well as a couple of its
 own) are available.
 This shell is Debian Policy 10.4 compliant and may be used as /bin/sh
 on Debian systems (if udev is installed, /bin/lksh should be used;
 otherwise, both /bin/mksh-static and /bin/mksh flavours also work),
 and as rescue and initrd shell (/bin/mksh-static especially).

 The mksh-static binary is a version of mksh, linked against klibc or
 dietlibc (if they exist for that Debian architecture and are usable)
 and optimised for small code size, for example for use on initrd or
 initramfs images, installation or rescue systems, or /bin/sh on slow
 architectures.
 It omits some leaf features to be even smaller.

 The lksh binary is a script shell based on mksh intended to run old
 ksh88 and pdksh scripts, but not for interactive use.

 A sample ~/.mkshrc is included in /usr/share/doc/mksh/examples and
 provided as /etc/mkshrc conffile, which is sourced by another file
 /etc/skel/.mkshrc users are recommended to copy into their home.
