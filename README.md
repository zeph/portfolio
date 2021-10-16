SqlHbase 
========
https://pypi.org/project/SqlHBase/

Built back in 2013, it is a MySQL-dump ingestion tool.
The idea behind it was to have data deduplication on dumps
that were coming in from 300 different ventures every night.
Probably the most interesting thing about this project is
 how the data parsing was achieved as it has elements of
finite state machine theory.

Wicd
====
I've been the maintainer of such deamon/UI for network 
configuration on Devuan back in 2019. https://github.com/zeph/wicd 
initial clone of the official repo https://code.launchpad.net/wicd

 - python2 to python3 migration
 - implementation of the new kernel API & tools related to wifi

 https://git.launchpad.net/wicd/log/?qt=author&q=Serra

Traefik
=======
The project is an Ingress Controller for Kubernetes.
The implementation of the `X-Real-IP`, header to determine the IP
on the public internet / behind several reverse proxies, is
currently suboptimal. The project is in Golang, never saw the codebase,
in less than 6 hours I had a unit test and a proposal of a patch.

https://github.com/traefik/traefik/pull/7875/files

