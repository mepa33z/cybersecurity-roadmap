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
