# net-scripts
Network-related scripts for the command line


## cidr2ips

Converts a [CIDR](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing "Classless Inter-Domain Routing") to a list of all of its IPs.


## cidr2regex

Converts a [CIDR](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing "Classless Inter-Domain Routing") to a regular expression that should exclusively match each IP in its range.


## hosts

A wrapper around `host` that accepts any number of hosts to look up (the DNS server may be specified as an option).


## poke

Quick "is it running" test that runs on [TCP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol "Transmission Control Protocol") rather than [ICMP](https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol "Internet Control Message Protocol") (ping).  Defaults to checking port 80 ([HTTP](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol "Hypertext Transfer Protocol")).


## rdesktop

A wrapper around [`rdesktop`](https://github.com/rdesktop/rdesktop) that can handle SSH tunnels and a nickname index.

I do not use this any more and may not be able to support issues that crop up.  The code is old and crufty because I have not maintained it in years.  This may change if I gain a need for regular access to a Windows box.


## ssh-hosthashes

List duplicate entries in your `~/.ssh/known_hosts` file as found by the server's public key.  This can help you consolidate the file (you can have multiple entries separated by commas).


## tsocks

This is a drop-in replacement for the old [`tsocks`](http://tsocks.sourceforge.net/) wrapper script that allows you to shove another program through a SOCKS proxy whether it wants to or not.  Unlike the original `tsocks` script, this supports tons of options that you'd otherwise need a configuration file for. (The [Debian version of tsocks](https://tracker.debian.org/pkg/tsocks) has a [tsocks github repository](https://github.com/TamasSzerb/tsocks).)


