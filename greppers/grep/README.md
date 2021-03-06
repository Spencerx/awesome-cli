# grep

* Homepage: http://www.gnu.org/software/grep/

'grep' is a utility to search for text in files; it can be used from the
 command line or in scripts.  Even if you don't want to use it, other packages
 on your system probably will.

 The GNU family of grep utilities may be the "fastest grep in the west".
 GNU grep is based on a fast lazy-state deterministic matcher (about
 twice as fast as stock Unix egrep) hybridized with a Boyer-Moore-Gosper
 search for a fixed string that eliminates impossible text from being
 considered by the full regexp matcher without necessarily having to
 look at every character. The result is typically many times faster
 than Unix grep or egrep. (Regular expressions containing backreferencing
 will run more slowly, however.)
