# Chapter 18-20

- When a security audit is performed at a company, the auditor reports that new users have access to network resources beyond their normal job roles. Additionally, users who move to different positions retain their prior permissions. What kind of violation is occurring?

- Users should have access to information on a need to know basis. When a user moves from job role to job role, the same concept applies.

- Concept of least privilege

- Access control models are used to define the access controls implemented to protect corporate IT resources. The different types of access control models are as follows:
- Mandatory access control (MAC) – The strictest access control that is typically used in military or mission critical applications.
- Discretionary access control (DAC) – Allows users to control access to their data as owners of that data. Access control lists (ACLs) or other security measures may be used to specify who else may have access to the information.
- Non-discretionary access control – Also known as role-based access control (RBAC). Allows access based on the role and responsibilities of the individual within the organization.
- Attribute-based access control (ABAC) – Allows access based on the attributes of the resource to be accessed, the user accessing the resource, and the environmental factors such as the time of day.

- The RADIUS server authenticates a user by verifying their credentials against a database. The RADIUS client sends its credentials to the RADIUS server, which then authenticates them against an authentication database. If the credentials are valid, authorization information is returned to the client.

- RADIUS is an open-standard AAA protocol using UDP port 1645 or 1812 for authentication and UDP port 1646 or 1813 for accounting. It combines authentication and authorization into one process.

- AAA Servers: The AAA functions are typically managed by specialized servers or services, such as RADIUS (Remote Authentication Dial-In User Service), TACACS+ (Terminal Access Controller Access-Control System Plus), or Diameter.

- RADIUS: Often used for network access control, it handles authentication and authorization and can also support accounting.

- The server that provides a separation of the authentication and authorization processes is TACACS+ (Terminal Access Controller Access-Control System Plus).

- TACACS+: Provides detailed control over authorization and accounting, and is often used in network device management.

- Diameter: An advanced protocol designed to provide improved security and functionality over RADIUS, often used in modern network environments.

- In order to prepare for a security attack, IT security personnel must identify assets that need to be protected such as servers, routers, access points, and end devices. They must also identify potential threats to the assets and vulnerabilities in the system or design.

- Asset management is a critical component of a growing organization from a security aspect. Asset management consists of inventorying all assets, and then developing and implementing policies and procedures to protect them. As an organization grows, so does the attack surface in terms of security threats. Each of these assets can attract different threat actors who have different skill levels and motivations. Asset management can help mitigate these threats by inventorying the risks as the attack surface grows.

- Many companies now support employees and visitors attaching and using wireless devices that connect to and use the corporate wireless network. This practice is known as a bring-your-own-device policy or BYOD. Commonly, BYOD security practices are included in the security policy. Some best practices that mitigate BYOD risks include the following:
- Use unique passwords for each device and account.
- Turn off Wi-Fi and Bluetooth connectivity when not being used. Only connect to trusted networks.
- Keep the device OS and other software updated.
- Backup any data stored on the device.
- Subscribe to a device locator service with a remote wipe feature.
- Provide antivirus software for approved BYODs.
- Use Mobile Device Management (MDM) software that allows IT teams to track the device and implement security settings and software controls.


A comprehensive BYOD policy should accomplish the following:
- Identification of which employees can bring their own devices
- Identification of which devices will be supported
- Identification of the level of access employees are granted when using personal devices
- Describe the rights to access and activities permitted to security personnel on the device
- Identification of which regulations must be adhered to when using employee devices
- Identification of safeguards to put in place if a device is compromised

- AIS responds to a new threat as soon as it is recognized by immediately sharing it with U.S. Federal Government and the private sector to help them protect their networks against that particular threat.

- Trusted Automated Exchange of Indicator Information (TAXII) is the specification for an application layer protocol that allows the communication of CTI over HTTPS. TAXII is designed to support Structured Threat Information Expression (STIX).

- CybOX is a set of open standards that provide the specifications that aid in the automated exchange of cyberthreat intelligence information in a standardized format. It is a set of standardized schemata for specifying, capturing, characterizing, and communicating events and properties of network operations that support many cybersecurity functions.


- This is a set of specifications for exchanging cyberthreat information between organizations.