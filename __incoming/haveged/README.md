# haveged

* Homepage: http://www.issihosts.com/haveged

haveged is a userspace entropy daemon which is not dependent upon the
 standard mechanisms for harvesting randomness for the system entropy pool.
 This is important in systems with high entropy needs or limited user
 interaction (e.g. headless servers).

 haveged uses HAVEGE (HArdware Volatile Entropy Gathering and Expansion) to
 maintain a 1M pool of random bytes used to fill /dev/random whenever the
 supply of random bits in dev/random falls below the low water mark of the
 device.

 More information about HAVEGE is available at
 http://www.irisa.fr/caps/projects/hipsor/
