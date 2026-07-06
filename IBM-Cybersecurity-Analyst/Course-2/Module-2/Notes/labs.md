Hands-on Lab: Enforce Strong Passwords

About This Lab
In this lab, we will use Kaspersky's password checker to learn how vulnerable our passwords are. Using the Local Group Policy Editor, we will also learn how to enforce strong password policies within the Microsoft Windows operating system.

In this hands-on lab, you will:

Check password strength.
Review Windows Local Group Policy Editor.
Configure password policies.

In exercise 1, I was able to test several passwords' strength on Kaspersky's website. It tells you how strong the password is and what it would need to make it stronger. It also has the option to generate passwords for you. 

In exercise 2, I learned to find the command prompt in the Windows search engine. From there, I entered the gpedit command line. That command opens up the local group policy editor. Within the local group policy editor, there are two configurations: Computer Configuration and User Configuration. 

Computer Configuration: This holds settings that are applied to the computer when it is started.
User Configuration: This holds settings that are applied to users when they sign into the computer.

I was prompted to click on computer configuration, and from there I needed to open the Windows settings folder. Within the Windows settings folder, I opened the security settings. When I opened the security settings, there were different types of policies. I chose to open the account policies folder. Under the account policy folder, I opened the password policy folder, which had the following:

Enforce password history: This policy determines how many unique passwords need to be used before an old password can be reused. Microsoft recommends that this be set to 24.

Maximum password age: This policy determines how many days a password can be used before the system requires a password change. Microsoft recommends that this be set somewhere between 30 and 90 days.

Minimum password age: This policy determines how many days a password must be used before the system requires a change. Microsoft recommends that this be set to one day.

Minimum password length: This policy determines the minimum number of characters required in a password. Microsoft recommends that this be set somewhere between 8 and 14.

Minimum password length audit: This policy is designed for organizations that want to track user password lengths. Microsoft recommends using this only in specific scenarios.

Password must meet complexity requirements: This policy indicates that passwords must meet Windows Security complexity requirements. Microsoft recommends that complexity requirements be enabled, especially if you are not enforcing other, more complex, password policies.

Store passwords using reversible encryption: This policy is specific to applications that use protocols requiring the user’s password for authentication. Microsoft recommends that this option be disabled.

Exercise 3, I had to make changes to the following items within the password policy folder:

Enforce password history -> changed to 24 (Microsoft recommends 24)
Maximum password age -> changed to 60 (Microsoft recommends 30-90 days)
Minimum password age -> changed to 1 (Microsoft recommends waiting at least 1 day before changing the password)
Minimum password length -> changed to 12 (Microsoft recommends the password length to be at least 8 to 14 characters)

Lab 2:

Hands-on-Lab: Windows Firewall with Advanced Security
Estimated time needed: 45 minutes

Objectives
By completing this lab, users will develop a comprehensive understanding of how to secure a Windows operating system using the real-time protection provided by Windows Firewall.

In this hands-on lab, you will review settings to enable firewall:

Exercise 1: Configure Firewall Rules Using Windows Defender Firewall

Exercise 2: Configure Firewall Rules Using Windows Defender Firewall with Advanced Security

Further in this hands-on lab, you will also explore few typical use cases:

The different scenarios in this lab will help you explore different aspects of security that can be controlled by Windows Firewall service.

Scenario 1: Block Remote Desktop on the Public Network (Inbound Rules)

Scenario 2: Block Outbound Traffic for Specified Applications (Outbound Rules)

Scenario 3: Block Web Server (HTTP) Traffic on a Public Network (Inbound Rules)

Scenario 4: Allow Key Management Service on the Domain and Private network, and deny the connection on the Public network (Inbound Rules)


Exercise 1:
First, I clicked on the Windows Start button and was prompted to Windows Security. Then I clicked Firewall and Network Protection. From there, we see the following and what they are:

Domain network: Domain networks are workplace networks. A computer must be a part of the domain in order to communicate with other computers on that network.

Private network: Private networks are discoverable networks, meaning that only devices on that network can see or discover other devices on that same network. Home networks are a good example of a private network.

Public network: Public networks are non-discoverable networks. A non-discoverable network is a network where your device cannot be discovered by other devices on your network. A coffee shop or a library would be a good example of a public network. You do not want other individuals to be able to discover your device.

Then I clicked Domain Network to confirm that Microsoft Defender Firewall was enabled. I did the same for the Private network and Public network settings, making sure the Microsoft Windows Firewall was enabled. 


Exercise 2:
Blocking remote unauthorized access: I begin by clicking the Windows Start button and scrolling down to Windows Security. I then click on firewall and network protection. From there I click on advanced settings. In advanced settings on the left side of the pane are these terms and what they mean:

Inbound rules: Inbound rules determine what traffic is allowed to the computer. 

Outbound rules: Outbound rules determine what traffic is allowed to leave the computer. 

Connection security rules: Connection security rules define how and when computers should use IPsec (Internet Protocol Security) to secure traffic. 

Monitoring: Monitoring involves tracking and analyzing the traffic that is allowed or blocked by the firewall.

Next to disable remote desktop on a public network, I click on inbound rules. Then, on the right pane, I clicked on New Rule. There the rule type I selected is Port and I clicked next. From there, the specified port I selected is TCP. Underneath Specific local ports, I typed 3389 and clicked next. To specify the action, I clicked on Block the Connection and clicked next. In the following window, I'm asked which rule it applies to. I deselected Domain and Private as it only applies to Public and clicked next. The next window allows me to name the rule and the description of the rule (it is optional). Under the name, I put: Block remote desktop on public network and clicked finish. (lab froze so I'm waiting for it to respond) lab continues to freeze at this point when I tried it again. I will continue the course without completing this ungraded lab)



