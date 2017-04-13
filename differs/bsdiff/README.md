# bsdiff

* Homepage: http://www.daemonology.net/bsdiff/

bsdiff and bspatch are tools for building and applying patches to binary
 files. By using suffix sorting (specifically, Larsson and Sadakane's
 qsufsort) and taking advantage of how executable files change, bsdiff
 routinely produces binary patches 50-80% smaller than those produced by
 Xdelta, and 15% smaller than those produced by .RTPatch (a commercial
 patch tool).
