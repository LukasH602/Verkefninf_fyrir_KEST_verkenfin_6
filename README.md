# Verkefninf_fyrir_KEST_verkenfin_6

13.2.3.7 Bitlocker and Bitlocker To Go

part 1
step 2

3. Why is it important to save a BitLocker recovery key?

The recovery key is needed for you to gain access to the computer in the event the password is forgotten, or in the event of certain hardware problems, such as a motherboard replacement or hard drive crash, or even after performing a BIOS update. Without it, there is no way to access your data.

part 2
step 1

9. What is the function of a TPM in relation to BitLocker?

Trusted Platform Module (TPM) can be used to store the disk encryption key so it can tie use of the disk to a specific computer.





13.3.2.5 Configure Windows Local Security Policy

step 4

1. According to the security policy in Step 1, how many times is a user allowed to attempt to login before the account is locked?

5 attempts

1. How long should the user have to wait before attempting to log back in?

5 minutes

step 6

2. Are there any you would recommend changing? Why?

The student may not understand all the settings. However, the student should be able to provide at least one example of a User Rights Assignment security setting that should be changed. Although the computer is stand-alone, this does not mean that it is not on a network. Stand-alone, in this case, means the computer is not a part of an Active Directory domain. Therefore, many of the User Rights Assignment settings could be changed to better protect the computer on the LAN. For example, the Access this computer from the network security setting defaults to allow everyone network access. The student might recommend that only the Administrator group be allowed access.


4. For the remaining security policy requirements in Step 1, list the policy and security setting values you need to change in Security Options in the table below. The first one is done for you.


Devices: Allow undock without having to log on: Disabled

Interactive logon: Message title for users attempting to log on: Caution:

Change the Interactive logon: Message text for users attempting to log on: Your activity is monitored. This computer is for business use only.

Interactive logon: Prompt user to change password before expiration: 7 days


13.3.3.6 Configure Users and Groups in Windows

1. What are the names of the accounts listed?
Lukas

2. Select the Groups folder. Name five groups from the list.
Administrators, Backup Operators, Guests, Power Users, and Users

3. Which group does your account belong to?
Administrator

4. What is Student01 required to do when logging in the first time?
Change password

5. What group does User01 belong to?
Users

6. From the description, can the members of the Users group make system wide changes? What can the Users group do on the computer?
The members of the Users group cannot make system wide changes

7. Who are the group members?
Student01 part of the Users group

8. Were you successful in creating the new account? Explain.
Access is denied, you cannot create a new user account

9. Were you able to navigate to www.cisco.com? Explain.
Yes

10. With the group ITEStaff highlighted, what can the members do in this folder?
read / execute, list folder contents, and read permissions

11. Which additional checkbox would you select?
Full Controll

12. Were you successful? Explain.
Yes. As a user in the group ITEStudent, Student02 has full control in this folder.

13. Were you successful? Explain.
No. As a user in the group ITEStudent, Student02 has no permission to access this folder

14. Were you able to access the content in the folders Staff, Student\Student01 and Student\Student02? Explain.
Yes. As a user in the group ITEStaff, Staff01 has all the content in C:\Staff and C:\Student

15. Can you log on as Staff02? Explain.
No. Because the account has been disabled



13.3.4.6 Lab - Configure Windows Firewall

1. Under PC-1, are you able to see the shared folder Cisco?
Yes

2. What are the benefits of Windows Firewall?
Windows Firewall can help prevent hackers or malicious software from gaining access to your computer through the internet or a network.

3. Describe a negative consequence of having too many exceptions.
Exceptions for a program to communicate through the Windows Firewall are like opening a hole in the firewall

4. Can you connect to PC-1 and view the Cisco shared folder?
No

5. Did you receive an error message on PC-2?
Yes

6. Can you connect to computer 1?
Yes

7. List the short name of four services that are available in the Customize Service Settnigs window.
AeLookupSvc, Appinfo, ALG, AppMgmt

8. List four of the Specific ICMP types.
Packet Too Big, Destination Unreachable, Source Quench, Redirect
