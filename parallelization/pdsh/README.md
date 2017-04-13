# pdsh

* Homepage: https://code.google.com/p/pdsh/

Pdsh is a high-performance, parallel remote shell utility, similar to dsh.
 It has built-in, thread-safe clients for rsh. Pdsh uses a "sliding window"
 parallel algorithm to conserve socket resources on the initiating node and
 to allow progress to continue while timeouts occur on some connections.

 It makes all parallel connections from one client machine, and attempts to
 keep 32 (default, can be changed on command line) connections to remote
 machines at any given time.  It can run single commands or as an
 interactive shell.
