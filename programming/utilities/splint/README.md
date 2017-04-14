# splint

* Homepage: http://splint.org/

splint is an annotation-assisted lightweight static checker.  It is a tool
 for statically checking C programs for security vulnerabilities and coding
 mistakes.  If additional effort is invested in adding annotations to
 programs, splint can perform stronger checking.

 splint does many of the traditional lint checks including unused
 declarations, type inconsistencies, use before definition, unreachable
 code, ignored return values, execution paths with no return, likely
 infinite loops, and fall through cases.  Problems detected by Splint
 include:

  * Dereferencing a possibly null pointer
  * Using or returning storage that is undefined or not properly defined
  * Type mismatches, with greater precision and flexibility than by C compilers
  * Memory management errors like use of dangling references and memory leaks
  * Inconsistent (with specified interface) global variable modification or use
  * Problematic control flow such as likely infinite loops etc.
  * Buffer overflow vulnerabilities
  * Dangerous macro implementations or invocations
  * Violations of customized naming conventions
