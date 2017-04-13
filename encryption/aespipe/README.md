# aespipe

* Homepage: http://loop-aes.sourceforge.net/

aespipe is an encryption tool that reads from standard input and writes to
 standard output. It uses the AES (Rijndael) cipher.

 aespipe can be used for non-destructive in-place encryption of existing
 disk partitions for use with the loop-AES encrypted loopback kernel
 module.

 It can also be used as an encryption filter to create and restore
 encrypted tar/cpio backup archives and to read/write and convert loop-AES
 compatible encrypted images.

 Note that aespipe does not store any length information with the encrypted
 images, so it cannot be used as general purpose filter for encryption, but
 only for certain formats like tar.
