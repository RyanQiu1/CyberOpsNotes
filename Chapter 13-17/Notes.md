# Chapter 13-17

- Fast flux, double IP flux, and domain generation algorithms are used by cybercrimals to attack DNS servers and affect DNS services. Fast flux is a technique used to hide phishing and malware delivery sites behind a quickly-changing network of compromised DNS hosts (bots within botnets). The double IP flux technique rapidly changes the hostname to IP address mappings and the authoritative name server. Domain generation algorithms randomly generate domain names to be used as rendezvous points.

- A gratuitous ARP is often sent when a device first boots up to inform all other devices on the local network of the MAC address of the new device.

- A computer can have a worm installed through an email attachment, an executable program file, or a Trojan Horse. The worm attack not only affects one computer, but replicates to other computers. What the worm leaves behind is the payload--the code that results in some action. 
an enabling vulnerability, a propagation mechanism, payload

- MAC address spoofing is used to bypass security measures by allowing an attacker to impersonate a legitimate host device, usually for the purpose of collecting network traffic.

- Optional Layer 3 information about fragmentation, security, and mobility is carried inside of extension headers in an IPv6 packet. The next header field of the IPv6 header acts as a pointer to these optional extension headers if they are present.

- Fuzzers are tools used by threat actors when attempting to discover the vulnerabilities of a computer system. Examples of fuzzers include Skipfish, Wapiti, and W3af.

- SPAN is a Cisco technology used by network administrators to monitor suspicious traffic or to capture traffic to be analyzed. It mirrors traffic that passes through a switch port or VLAN to another port for traffic analysis.

- NetFlow collects basic information about the packet flow, not the flow data itself.NetFlow does not capture the entire contents of a packet. Instead, NetFlow collects metadata, or data about the flow, not the flow data itself. NetFlow information can be viewed with tools such as nfdump and FlowViewer.

Threat -  Potential danger to an asset such as data
Vulnerability - Weakness that can be exploited
Attack surface - Total sum of vulnerabilities
Exploit - Mechanism to leverage a vulnerability to compromise an asset
Risk - Likelihood that a particular threat will exploit a particular vulnerability of an asset 

Managing risk
- Risk acceptance
- Risk avoidance
- Risk reduction
- Risk transfer

- Counter measure - Actions taken to protect assets mitigating a threat
- Impact potential damage to organisation

- Gray hat who commit crimes and unethical things but not for personal gain or to cause damage

- IOCs indicator of comprimise
- Malware files, ip of servers used in attacks, file names

- IOA, focus on motivation and stategies behind attack

- CISA uses AIS enables sharing of attack indicators between govt and private
- ENISA europe version

Virus
- Insert copy of itself into another program
- Attach itself to other software
- Virus cannot self-replicate and needs to be sent by a user or software to travel between two diff computers
- Virus need to be host/victim interaction

Worm 
- Replicate themselves, run without a host program
- Enabling vul - install using an exploit mechanism
- Propagation mechanism - Replicates itself and locates new targets
- Payload - Any malicious code that results in some action is a payload. Most often this is used to create a backdoor that allows a threat actor to access the infected host or to create a DOs attack

Trojan
- Appears legitimate but it contains malicious code

Pretexting - pretends to need personal or fin data to confirm the identity of the recipient

Social engineering toolkit (SET) -> white hat hackets to create SE attacks on own network to prepare

Zombies -> Group of compromised hosts

Bots are malware designed to infect a host and communicate with handler

Botnet group of zombies which are infected

Handler is the C2C

botmaster enables unauthorised file transfer services on end devices

Ping of death

# Network Monitoring and Tools
- TAP (Test access points)
- Traffic mirroring using Switch Port Analyser (SPAN) or Port Mirroring

Network Tap
- Is a passive splitting device implemented inline between a device of interest and the netwrok
- Tap forwards all traffic, including physical layer errors to analysis device
- Simultaneouly sends both the transmit (TX) from internal router and the receive (RX) data stream to the internal router on separate, dedicated channels
- Ensures that all data arrives at the monitoring device in real time
- Taps are fail-safe which means that the traffic between the firewall and internal router is not affected

- Source SPAN (the place where packets are mirrored)

- dEST PORT - port that mirrors source ports

- Variation of SPAN called Remote span enables use of flexble vlans to monitor traffic

- Netflow 
- Cisco ios tech

- Cisco stealthwatch collect netflow stats
- Flow switching
- Flow deduplication
- NAT stitching


# Attacking the foundation

Protocol -> Is used to identify the next level protocol, can be icmp, tcp

ICMP is actually at the "top" of the layer 3. It uses the IP protocol to deliver data to a remote host. In other words, ICMP messages must be encapsulated in IP packets.

Consider it as similar to ARP which could be considered to be "at the top" of layer 2, while using the Ethernet protocol to actually send packets.

IPv6 header is more simplified

ICMP attacks
-> Spam
-> ICMP router discovery, used to inject bogus route entries into routing table of a target host

-> Amplification is forward echo messages
-> Reflection
Hosts all reply to the spoofed ip address to overwhelm it

Spoofing attack
-> non-blind - threat attack can see traffic between host and target
-> Blind