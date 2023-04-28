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

13.3.4.6 Lab - Configure Windows Firewall
