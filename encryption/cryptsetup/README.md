# cryptsetup

* Homepage: https://gitlab.com/cryptsetup/cryptsetup

Cryptsetup provides an interface for configuring encryption on block
 devices (such as /home or swap partitions), using the Linux kernel
 device mapper target dm-crypt. It features integrated Linux Unified Key
 Setup (LUKS) support.

 Cryptsetup is backwards compatible with the on-disk format of cryptoloop,
 but also supports more secure formats. This package includes support for
 automatically configuring encrypted devices at boot time via the config
 file /etc/crypttab. Additional features are cryptoroot support through
 initramfs-tools and several supported ways to read a passphrase or key.
