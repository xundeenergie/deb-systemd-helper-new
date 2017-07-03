# deb-systemd-helper-new

Dieses Paket stellt lediglich eine veränderte und erweiterte Version von deb-systemd-helper zur Verfügung, welche auch instanziierende Services (foo@.service) aktivieren und deaktivieren kann, wie es das Original "deb-systemd-helper" aus dem Paket "init-system-helpers" nicht kann. (Siehe Bugreport https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=801822)

## Verwendung ##
Dieses Programm wird bloß in pre/post-rm/install in Debian-Paketen benötigt. Dort kann es genau wie das Original verwendet werden, nur dass damit eben auch instanziierende Services auch funktionieren.

Wird ein Paket installiert, welches dieses Paket verlangt, dann lediglich, weil in den install-Skripten der Aufruf verwendet wird.
