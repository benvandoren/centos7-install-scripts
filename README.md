Series of scripts for configuring a fresh CentOS install. 

Assumes particular software and subnet, so tweak those if necessary.

Call centos7-general to trigger everything:

centos7-general eth99 DE:AD:DE:AD:DE:AD 192.168.10.99 node99 user123

Additionally manually call centos7-security if desired (currently only sets SSH to key based login only)
