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

QR Disaster Recovery
====================
https://github.com/zeph/qr_encode_disaster_recovery
A tool for printing SSL keys on QR Codes, and related 
reconstruction process through some OpenCV

WMI Exporter
============
https://github.com/zeph/wmi_exporter
Golang based tool for instrumenting with prometheus Windows machines.
I needed to know the amount of file descriptors open over time
 on a Windows Logon AD infrastructure, to be able to identify an 
infrastructure bottleneck. (I patched and compiled the tool)

local loadbalancing
===================
https://github.com/zeph/flask-session.nginx-reverseproxy.redis
Several scenario of loadtesting and loadbalancing achieved via docker-compose

GOAD (Apache Benchmark on steroids)
===================================
https://github.com/zeph/goad I was initially extending the tool, 
I became later on (with sponsorship from my employer) the PM/PO
of the solution. 

Yahoo Kafka Manager
===================
Was a scala project, back in 2015 that used JMX to handle Kafka.
I simply provided a mechanism for having user/pass authentication on JMX

GNU+TLA 
=======
The git of the poors, back in 2006
http://savannah.gnu.org/bugs/?15507

mentioned "Guido Serra":
 - https://cloudera.github.io/hue/docs-4.1.0/release-notes/release-notes-4.1.0
 - (for my contributions to Istio, Diaspora & ArgoCD) https://archiveprogram.github.com/
 
bugs:
 - https://jira.mariadb.org/browse/MDEV-4592
 - https://www.mail-archive.com/dev@hbase.apache.org/msg14243.html

