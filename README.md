# ftelnetd

DataPlane TELNET server daemon

ftelnetd is a minimal TELNET srever daemon.  It listens on TCP port 23 by
default (IPv4 as well as IPv6 if available).  It logs all incoming TELNET
connection attempts and authentication attempts to syslog.

The base TELNET protocol and daemon code derives from [Robert David
Graham's telnetlogger](https://github.com/robertdavidgraham/telnetlogger).
