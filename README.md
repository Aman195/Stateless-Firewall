# Stateless-Firewall
The goal of this project is to design a stateless firewall which can detect and filter packets based on ACL (Access control list). The aim of this project is to design a packet filter which would follow the rules and track communication in both directions and would also prevent fraudulent packets from leaving the network. There are two main types of firewalls known as stateless firewall and state-full firewall. 
In analogy to traditional firewall, stateless firewall is technique in which it checks each packet and applies the rules to decide the filtering (checks the headers of packets). It does not keep states of each connection, rather it takes every packet and examines it with the given rules. Once the rule is matched, it executes the action associated with the rule, i.e. DROP, ACCEPT etc. 
 In this type, firewall is designed to distinguish the type of packets based on the open network connections (TCP stream or UDP stream). For e.g. Packets from active connections can pass through the firewall.  This is done by storing significant attributes of connection in memory. It is advanced and more robust than traditional firewall as it analyses packets rather than checking source and destination and ports to decide between accepting and dropping connection request. A perfect example to undergird the concept can be considering outgoing packets that request specific types of incoming packets are tracked and only those incoming packets constituting a proper response are allowed through the firewall. 

