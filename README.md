# iptables_sevice
Service files for some specific distros.

Netfilter subsystem for Linux envolve powerful statefull packet filtering.
iptables is a userspace programm which allows to adjust netfilter parameters.
iptables started as fork of ipchains.
Direct configuring of Netfilter via iptables some people find as complicated.
Therefore many tools was created to simplify iptables usage. Each of these tools
accept some tool-specific rule and convert it to iptables rules.
Introducing 'zone' term in each tool as necessarily feature also is a key concept.
The most popular tools for simple iptables configuring are: ufw, firewalld, SUSEFirewall...
Each of these tools have tool-specific syntax and consist of one or several components.
Sometimes during develop or administration needs direct iptables handle is the most
convenient way but distros doesn't provide service files for bare iptables tool.
