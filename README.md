# OpenVPN Obfuscation

OpenVPN Obfuscation is used to encrypt OpenVPN's traffic to avoid protocol identification.

## Downloads:

* Windows: openvpn-2.1.4-install patched.exe - http://goo.gl/khwuQ

* OS X: Tunnelblick.r1823.patched.app.tgz - http://goo.gl/zTpzp

* Linux: apply openvpn-2.2.1-obfuscation.diff and build from source.
<pre>
$ aclocal
$ automake
$ ./configure
$ make
$ sudo make install
</pre>

## Usage:
Add `obfuscation <key>` in your openvpn client and server config files.
