# Chapter 11-12

- ISIS and OSPF are link-state routing protocols. EIGRP and RIP are distance vector routing protocols. BGP is a path vector protocol.
- Routed ports on a Cisco switch behave similarly to those on a router. They are configured with an IP address and forward Layer 3 packets. Unlike Layer 2 switch interfaces, routed ports do not support STP, nor do they support subinterfaces as routers do.

- A wireless client operating in active mode must know the name of the SSID. Probe requests are broadcast by a client across multiple channels and include the SSID name and supported standards. Active mode is used if an AP is configured to not broadcast beacon frames.

- In passive mode, the wireless clients learn what networks and APs are available. The client learns this information from beacon frames, sent by the APs, that contain the WLAN SSID, supported standards, and security settings.

- An interface can belong to only one zone. Creating a zone is the first step in configuring a zone-based policy firewall. A zone cannot be assigned to an interface if the zone has not been created. Traffic can never flow between an interface that is assigned to a zone and an interface that has not been assigned to a zone.


- Zone-based policy firewalls (ZPFs) use the concept of zones to provide additional flexibility. A zone is a group of one or more interfaces that have similar functions or features. Zones help you specify where a Cisco IOS firewall rule or policy should be applied. In the figure, security policies for LAN 1 and LAN 2 are similar and can be grouped into a zone for firewall configurations. By default, the traffic between interfaces in the same zone is not subject to any policy and passes freely. However, all zone-to-zone traffic is blocked. In order to permit traffic between zones, a policy allowing or inspecting traffic must be configured.

The only exception to this default deny any policy is the router self zone. The self zone is the router itself and includes all the router interface IP addresses. Policy configurations that include the self zone would apply to traffic destined to and sourced from the router. By default, there is no policy for this type of traffic. Traffic that should be considered when designing a policy for the self zone includes management plane and control plane traffic, such as SSH, SNMP, and routing protocols.

- The Cisco Web Security Appliance is a secure web gateway which combines advanced malware protection, application visibility and control, acceptable use policy controls, reporting, and secure mobility functions. With traditional web security appliances, these functions are typically provided through multiple appliances. It is not a firewall appliance in that it only filters web traffic. It does not provide VPN connections, nor does it provide email virus and spam filtering; the Cisco Email Security Appliance provides these functions.
- URL filter and Web reporting

- TACACS+ uses TCP, encrypts the entire packet (not just the password), and separates authentication and authorization into two distinct processes. Both protocols are supported by the Cisco Secure ACS software.

- A VPN is a private network that is created over a public network. Instead of using dedicated physical connections, a VPN uses virtual connections routed through a public network between two network devices.

- SNMP is an application layer protocol that allows administrators to manage devices on the network by providing a messaging format for communication between network device managers and agents.
