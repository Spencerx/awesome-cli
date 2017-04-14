# rush

* Homepage: http://gnu.org/s/rush

GNU Rush is a restricted shell designed for sites providing only limited
 access to resources for remote users. The main binary executable is
 configurable as a user login shell, intended for users that only are
 allowed remote login to the system at hand.

 A notification service can be implemented individually for each provided
 client service, using the TCPMUX support found within xinetd, or
 inetutils-inetd.

 The standard use is to create access to a chrooted target directory,
 typically providing arbitrary combinations of scp, sftp, rsync, cvs, svn,
 and git. Each service may be further restricted in its capabilities. The
 administrator configures pattern matching rules for manipulating any
 incoming request.

 The present restricted shell is an alternative to the well known "rssh"
 package, which provides similar capabilities.
