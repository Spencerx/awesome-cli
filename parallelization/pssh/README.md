# pssh

* Homepage: https://code.google.com/p/parallel-ssh/

pssh provides a number of commands for executing against a group of
 computers, using SSH. It's most useful for operating on clusters of
 homogenously-configured hosts.

 The package contains:

  - Parallel ssh (parallel-ssh, upstream calls it pssh), executes commands on
    multiple hosts in parallel
  - Parallel scp (parallel-scp, upstream calls it pscp), copies files to
    multiple remote hosts in parallel
  - Parallel rsync (parallel-rsync, upstream calls it prsync), efficiently
    copies files to multiple hosts in parallel
  - Parallel nuke (parallel-nuke, upstream calls it pnuke), kills processes on
    multiple remote hosts in parallel
  - Parallel slurp (parallel-slurp, upstream calls it pslurp), copies files
    from multiple remote hosts to a central host in parallel

 These tools are good for controlling large collections of nodes, where
 faster alternatives such as gexec and pcp are not available.
