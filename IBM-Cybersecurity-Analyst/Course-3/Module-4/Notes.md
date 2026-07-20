This course content explains the evolution and key components of identity and access management (IAM) in cybersecurity.

Evolution of Network Security:

Initially, security focused on creating a defense line at the network edge, assuming internal users were trustworthy and external users were threats.
With remote work and insider threats, the security perimeter shifted from just the network edge to include end users themselves.

The Four A's of Identity and Access Management:

Administration: Managing user accounts through provisioning (creation), updating, and deprovisioning (deletion) to maintain security.
Authentication: Verifying the identity of users to confirm they are who they claim to be, often using methods like multi-factor authentication.

Access Control and Oversight:

Authorization: Determining if an authenticated user has permission to perform specific actions or access resources.
Audit: Reviewing and ensuring that administration, authentication, and authorization processes are correctly implemented and followed.



This course item explains the concept and importance of user authentication in cybersecurity.

Authentication Protocols:

Authentication protocols are digital rules and processes that verify a user's claimed identity before granting access to protected resources.
Common protocols include RADIUS (used for remote user authentication), CHAP (three-way handshake for remote access), EAP (supports various methods for wireless networks), and Kerberos (uses strong encryption and a trusted third-party server).

Authentication Servers:

Authentication servers manage and verify user credentials stored in centralized databases to control access to resources.
Examples include Active Directory, LDAP servers, and RADIUS servers, which act as intermediaries between users and resources.

Authentication Methods:

Passwords are the most common method but have vulnerabilities such as susceptibility to brute force attacks.
Multifactor authentication enhances security using methods like one-time passwords (OTP), biometric authentication (fingerprints, facial recognition), smart cards, security tokens, and mobile push notifications.




This course content explains the concept of authorization for authenticated users, focusing on how access to resources is controlled after identity verification.

Purpose of Authorization:

Authorization determines what actions an authenticated user is allowed to perform within a system or network.
It involves granting or denying rights to access resources, ensuring security and operational efficiency.

Access Control Schemes:

Role-Based Access Control (RBAC) assigns permissions based on organizational roles, simplifying management and limiting access to necessary resources.
Attribute-Based Access Control (ABAC) uses user, resource, action, and environmental attributes to make access decisions.
Rule-Based Access Control (RuBAC) applies specific rules or access control lists, such as firewall rules, to regulate access.
Mandatory Access Control (MAC) enforces strict policies set by administrators, commonly used in government and military settings.
Discretionary Access Control (DAC) allows owners of resources to assign permissions, typical in personal computer environments.

File Access Controls:

File permissions control read, write, and execute rights on files, varying between operating systems like Linux and Windows.
Read permission allows viewing file contents; write permission allows modifying files; execute permission allows running files as programs.
Proper file access controls help maintain data integrity and confidentiality.




This course content explains the concept of access controls and access management in cybersecurity.

Access Controls and Identities:

Access controls are security measures that ensure only authorized individuals can access specific resources.
Identities are unique digital representations of individuals, applications, devices, or organizations, serving as keys to unlock resources with designated access levels.

Traditional Access Control Methods:

Common traditional methods include usernames (which require passwords for security), certificates (digitally signed documents), tokens (physical devices generating codes), SSH keys (cryptographic key pairs), and smart cards (secure credential storage).

Innovative Access Control Methods:

Innovative methods include biometric systems (fingerprints, facial recognition), behavioral biometrics (user behavior patterns), geolocation and time-based restrictions, multifactor authentication (MFA), and single sign-on (SSO).
These methods add layers of security and are often combined in a layered approach to protect against unauthorized access.

Access Control Systems and Monitoring:

Access control systems regulate who can access resources, what actions they can perform, and under what conditions.
They also monitor and record access activities to detect security breaches, ensure compliance with policies, and protect sensitive data.




This course item explains the concept of authentication in cybersecurity, focusing on how systems verify a user's identity.

Factors of Authentication:

Authentication relies on factors such as something you know (e.g., password or PIN), something you have (e.g., a registered mobile device), and something you are (e.g., biometric data like a face).
Each factor has advantages and limitations, such as passwords being easy to generate but vulnerable if shared, and biometrics being unique but requiring good technology.

Single and Multifactor Authentication:

Single-factor authentication uses one of these factors alone, which may have security weaknesses.
Multifactor authentication combines two or more factors (e.g., a message sent to your phone plus facial recognition) to enhance security without excessive complexity.

Goal of Authentication:

The ultimate aim is to create a secure, passwordless, and frictionless environment that still protects user identity effectively.




This course content explains the challenges of managing multiple strong passwords and introduces single sign-on (SSO) as a solution to improve security and user experience.

Password Management Challenges:

Users often have many unique passwords, which are hard to remember, leading to insecure practices like writing them on sticky notes or using the same password everywhere.
These insecure methods increase the risk of compromise because if one password is discovered, all accounts can be accessed.

Single Sign-On (SSO) Solution:

SSO allows a user to log in once with a single strong password to a central manager, which then manages unique passwords for multiple systems.
This reduces the number of passwords a user must remember while maintaining unique credentials for each system.

Benefits and Security Considerations:

SSO improves security by limiting the attack surface to one system at a time and avoids the risk of all accounts falling if one password is compromised.
Adding multifactor authentication to the SSO login enhances protection by requiring additional verification factors.
SSO also reduces help desk costs by decreasing password reset requests and improves the overall user experience.




This course content explains the concept and benefits of using passkeys as a secure and user-friendly alternative to passwords in authentication.

Passkeys and Device Loss:

Passkeys store a private key on your device, unlocked by biometrics like face or fingerprint.
If you lose your device, you lose the private key, but account recovery methods similar to password recovery exist.

Using Multiple Devices and Public Terminals:

Passkeys can be synchronized securely across multiple devices via encrypted cloud sessions.
Using public or untrusted terminals is discouraged due to potential malware capturing keystrokes.

Comparison with Other Security Technologies:

Passkeys use public key infrastructure (PKI) but differ from SSH or TLS by focusing on user login without sending private keys.
The private key remains on the device, enhancing security compared to traditional password transmission.

Problems with Passwords and Password Managers:

Human behavior often leads to weak, reused, or unchanged passwords, increasing vulnerability.
Password managers help but can still be compromised by phishing or database breaches.
Passkeys reduce attack surfaces by keeping secrets on the device and using time-bound credentials.

Adoption and Practical Use:

Many organizations support FIDO passkeys, making them increasingly available.
Passkeys offer better security and usability, and users are encouraged to adopt them when possible.



