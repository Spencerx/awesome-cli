# gnupg

* Homepage: https://gnupg.org/

GnuPG is GNU's tool for secure communication and data storage.
 It can be used to encrypt data and to create digital signatures.
 It includes an advanced key management facility and is compliant
 with the proposed OpenPGP Internet standard as described in RFC 4880.

 GnuPG 1.4 is the standalone, non-modularized series. In contrast to
 the version 2 series, shipped with the gnupg2 package, it comes
 with no support for S/MIME and some other tools useful for desktop
 environments, but also with less dependencies.

 The gnupg package is built without libcurl. So it does not support
 HKPS keyservers. Install the gnupg-curl package if you want to use
 the keyserver helper tools built with libcurl and supporting HKPS.
