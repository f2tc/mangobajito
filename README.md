# Mango Bajito
### Pre-SSL authentication hijack PoC

Mango Bajito (something like _low hanginging fruit_ in Dominican lingo) goes for an easier approach rather than trying to break SSL.

It is a MITM proxy that tries to inject mischievous javascript in order to strips SSL and monitor credentials values on login forms.

At the time of writing this successfully tested against facebook.com, hotmail.com, twitter.com and some "super secure" dominican commercial banks' site.

### How does it work?

You need Node.js to run Mango bajito.
You also need to be in the middle first. (ARP poisoning, DNS spoofing, DHCP starvation, etc...)

### Why?

* Because its the easiest and funniest way I have to demonstrate my point.
* To raise awareness to others.
* Because I can.

### Demo
Check out this demonstration video [here](http://vimeo.com/45317077).

XenoMuta - [Methylxantina 256mg http://xenomuta.com/](http://xenomuta.com/)