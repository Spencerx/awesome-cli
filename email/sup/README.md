# sup

* Homepage: http://supmua.org

The SUP System is a set of programs developed by Carnegie Mellon
 University that provide for collections of files to be maintained in
 identical versions across a number of machines.  These programs are:

 SUP: The "client" program, run by users or system maintainers, which
 initiates the upgrade activity  on  a  machine  requesting  the latest
 version of a collection of files.  SUP will normally be run as a daemon,
 firing up once  each  night  (week,  etc.)  to upgrade the specified file
 collections.

 SUPFILESRV: The "file server" program, a daemon that is run by the system
 maintainer to service requests for files initiated by client SUP programs.
 The file server runs on every machine used as a "repository" of
 distributable versions of files.  It runs continuously and listens for
 network connection requests by individual client processes; for each
 individual client request, a process is forked to service that request.

 SUPSCAN: The "file scanner" program, that may optionally be run
 periodically to speed up execution of the file server.  It pre-compiles a
 list of files on the file system that match the specifications for a given
 file collection so that the file server need not do this during each
 upgrade of that collection.  The file scanner is normally used daily for
 very large file collections that are upgraded by many clients each day; it
 is not so useful for small file collections or for those that are upgraded
 by only a few client machines per day.
