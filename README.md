my_larbin_ipv6
==============

replace the adns liberary(v1.2) in the original larbin by adsn1.4 which can resolve both IPv6 and IPv4 address.

F: How to run it?

A: First you should configure, then make, at last run the 'larbin'.

Steps:

[user@host ~]$cd my_larbin_ipv6

[user@host my_larbin_ipv6]$ ./configure

[user@host my_larbin_ipv6]$ make

Then a file named larbin will be created in the directory My_larbin_ipv6. Run it.

[user@host my_larbin_ipv6]$ ./larbin

You can change the startUrl in the file of larbin.conf.

F: what are required to run the program?

A: You can my_larbin_ipv6 on both ubuntu and centos. To setup the program, you should install the tool of makedepend. To run the program, you should garantee that the linux could access the IPv6 network. The tool of miredo will help you to do this.

