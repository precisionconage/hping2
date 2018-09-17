hping2 readme
antirez@invece.org

DESCRIPTION
===========

hping2 is a network tool able to send custom ICMP/UDP/TCP	packets and to display target replies like ping do with	ICMP replies. hping2 handle fragmentation, arbitrary packet	body and size and can be used in order to transfer files under supported protocols. Using hping2 you are able at least to perform the following jobs:
- Test firewall rules
- \[spoofed\] port scanning
- Test net performance using differents protocols, packet size, TOS (type of service) and fragmentation.
- Path MTU discovery
- Files trasfering even between really fascist firewall rules.
- Traceroute like under different protocols.
- Firewalk like usage.
- Remote OS fingerprint.
- TCP/IP stack auditing.
- A lot of others.

It's also really a good didactic tool to learn TCP/IP.

hping2 is developed and manteined by antirez@invece.org and comes under GPL version 2 of license. Developing is open so you can send me patches/suggestions/affronts without inhibitions.

Thanks to the following peoples for them suggestions/tests/tools/code:

- Valeriano Bedeschi	<vale@seclab.com>
- Lorenzo Cavallaro	<sullivan@seclab.com>
- awgn roofing		<root@roof.penguinpowered.com>
- Darren Reed		<avalon@COOMBS.ANU.EDU.AU>
- Alfonso De Gregorio	<dira@speedcom.it>
- Mika			<mika@qualys.com>
- Yann Berthier		<Yann.Berthier@hsc.fr>
- Lance Spitzner		<lance@spitzner.net>
- Stephane Aubert		<Stephane.Aubert@hsc.fr>
- Nicolas Jombart		<Nicolas.Jombart@hsc.fr>
- Denis Ducamp		<Denis.Ducamp@hsc.fr>
- Francesco Potorti`	<pot@gnu.org>
- Stefano Brandimarte	<stevens@alicom.com>
- "roy kozzer"		<royk50@hotmail.com>
- Jason Lunz		<j@trellisinc.com>
- Domenico Andreoli	<cavok@filibusta.crema.unimi.it>
- Gian-Luca Dei Rossi	<acaso@venezia.linux.it>
- Marco D'Itri		<md@linux.it>
- Rui Miguel Barbosa Machado <rmbm@rccn.net>
- Daniel Ginsburg		<dbg@nm.ru>
- Steve Bleazard		<steve@bleazard.com>
- David Coppa		<coffeec@tin.it>
- Many other, I don't remember.
- Also vim developers, ee.lbl.gov for tcpdump and GNU in general.

DOWNLOAD
========

The hping2 primary download site is the following: http://www.kyuzz.org/antirez/hping2.html

How to get the hping2 source code from the anonymous CVS server
----------------------------------------------------------------

`$ cvs -d :pserver:anonymous@cvs.hping2.sourceforge.net:/cvsroot/hping2 login`

CVS will ask for the password, just press enter, no password is required

then type the following to download the full source code.

`$ cvs -z8 -d :pserver:anonymous@cvs.hping2.sourceforge.net:/cvsroot/hping2 checkout hping2`

How to update your source code tree
-----------------------------------

change the current directory to /somewhere/hping2, than just type:

`$ cvs update`

REQUIREMENTS
============

A supported unix-like OS, gcc, root access.

see PORTINGS file for supported systems list.

USAGE
=====

See the man page and HPING2-HOWTO.

INSTALLATION
============

see INSTALL file.

have fun,
antirez
