# atool

* Homepage: http://www.nongnu.org/atool/

atool is a script for managing file archives of various types (tar,
 tar+gzip, zip etc). The main command is probably aunpack, extracting files
 from an archive. It overcomes the dreaded "multiple files in archive root"
 problem by first extracting to a unique subdirectory, and then moving back
 the files if possible. aunpack also prevents local files from being
 overwritten by mistake.

 Other commands provided are apack (create archives), als (list files in
 archives), and acat (extract files to standard out).
