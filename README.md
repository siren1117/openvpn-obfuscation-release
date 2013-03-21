# OpenVPN Obfuscation

OpenVPN Obfuscation is used to encrypt OpenVPN's traffic to avoid protocol identification.

## Patches:
* for OpenVPN git master: 0001-obfuscation.patch
* for OpenVPN 2.2.x: openvpn-2.2.1-obfuscation.diff

## Downloads:

* Windows: openvpn-2.2.2-install-patched.exe - http://goo.gl/g6hE3

* OS X: Tunnelblick.r1823.patched.app.tgz - http://goo.gl/zTpzp

* Linux: apply patch and build from source.
<pre>
patch -p1 &lt; 0001-obfuscation.patch
autoreconf -i -v
./configure
make
sudo make install
</pre>

## Usage:
Add `obfuscation <key>` in your openvpn client and server config files.

## Contact:
siren1117@gmail.com
