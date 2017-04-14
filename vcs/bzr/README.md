# bzr

* Homepage: http://bazaar.canonical.com/en/

Bazaar is a distributed version control system designed to be easy to
 use and intuitive, able to adapt to many workflows, reliable, and
 easily extendable.

 Publishing of branches can be done over plain HTTP, that is, no special
 software is needed on the server to host Bazaar branches. Branches can
 be pushed to the server via sftp (which most SSH installations come
 with), FTP, or over a custom and faster protocol if bzr is installed in
 the remote end.

 Merging in Bazaar is easy, as the implementation is able to avoid many
 spurious conflicts, deals well with repeated merges between branches,
 and is able to handle modifications to renamed files correctly.

 Bazaar is written in Python, and has a flexible plugin interface which
 can be used to extend its functionality. Many plugins exist, providing
 useful commands (bzrtools), graphical interfaces (qbzr), or native
 interaction with Subversion branches (bzr-svn).

 Install python-paramiko if you are going to push branches to remote
 hosts with sftp, and python-pycurl if you'd like for SSL certificates
 always to be verified.
