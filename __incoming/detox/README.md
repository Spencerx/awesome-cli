# detox

* Homepage: http://detox.sourceforge.net/

Detox is a utility designed to clean up filenames. It replaces difficult
 to work with characters, such as spaces, with standard equivalents. It
 will also clean up filenames with UTF-8 or Latin-1 (or CP-1252) characters
 in them.

 Features:

  * Removal or replacement of upper ASCII Latin-1 (ISO 8859-1) characters
  * Removal or replacement of UTF-8 encoded Unicode characters.
  * Removal or replacement of spaces and other potentially tricky characters
  * Trimming of excessive "_" and "-"s
  * Directory recursion, dry runs, verbose listings

 It is designed with safety in mind. It won't overwrite a file that already
 exists, and it doesn't touch special files if not requested.
