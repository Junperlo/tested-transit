---
title: 'Configuring a Mikrotik Device: A Step-by-Step Guide'
description: 'Configuration of a Mikrotik device '
pubDate: 'Nov 22 2023'
heroImage: '/5158PaL8wIL.jpg'
---

<h1>Configuring a Mikrotik Device: A Step-by-Step Guide</h1>

Prerequisite are a Mikrotik device, a computer, WinBox installed on the computer.

1. Accessing Quickset and Setting a Password

Begin by accessing the Quickset feature on your Mikrotik device. This is typically found in the main menu upon logging into the device's web interface.
In Quickset, set a robust password for your device. This is crucial for securing your network and preventing unauthorized access. Navigate to the password settings section, enter a strong password, and confirm it.

![Second1](/Second1.JPG)


2. Creating an Access List

The access list is essential for controlling which devices are allowed to connect to your network. To create an access list:
Navigate to the access list section in the Mikrotik settings.
Add the MAC addresses of the devices you wish to allow on your network.
Ensure that the access list is enabled and properly configured to restrict access only to the specified devices.

![Second2](/Second2.JPG)

3. Configuring a PC for Network Access

To configure a specific PC to work with your Mikrotik setup:
Ensure the PC's network settings are compatible with the Mikrotik device. This might involve setting a static IP address or ensuring the PC is set to obtain an IP address automatically.
Make sure the PC’s MAC address is added to the access list if such a list is being used.

4. Setting Up a Deny Rule (Blocklist)

Deny rules or blocklists are important for enhancing network security. They help in blocking unwanted traffic or unauthorized access.
To set up a deny rule, navigate to the firewall settings in your Mikrotik device.
Create a new rule that specifies the criteria for blocking traffic. This could be based on IP addresses, MAC addresses, ports, or other network parameters.
Ensure that the rule is activated and placed correctly in the order of firewall rules to be effective.

![Second3](/Second3.JPG)

Note:
Each of these steps requires careful attention to detail to ensure that your network is secure and functions as intended.
Always double-check settings before applying them to avoid unintended network interruptions.