SSLSecurityChecker:
===================

Author:
-------
Original Author: Thomas Pornin <pornin@bolet.org>
Modified by: Manish Saindane <msaindane@gdssecurity.com>

Info:
-----
IronWASP module used to test the security of SSL services. The original tool TestSSLServer (http://www.bolet.org/TestSSLServer/) written by Thomas Pornin was modified to inlcude it as a module within IronWASP.

This currently reports the following:
- Supported versions (among SSL 2.0, SSL 3.0, TLS 1.0, TLS 1.1 and TLS 1.2).
- Support of Deflate compression (TLS-level compression, not HTTP-level gzip/deflate compression, which this tool does not consider).
- Supported cipher suites, for each protocol version.
- Server certificate hash and name.

License:
--------
The original license is included in the source code (TestSSLServer.cs)
