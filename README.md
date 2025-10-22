# 🏄 Maksim Tishin

**`A Cybersecurity enthusiast who loves tech`**

I'm a student at Western Governors University studying Cybersecurity and Information Assurance. I have hands-on experience through many projects and my home lab, which I use daily to continue sharpening my skills and improving. I'm a Leader, a quick learner, and a team player, so I get along with people very well.

## Experience:

- Created a home lab for self-hosting and learning new software.
- Assisted friends & family with technical issues.
- Set up remote access via VPN to avoid port forwarding.
- Troubleshot software and devices.
- Built computers and set up workstations.
- Reimaged computers and debloated Windows.
- Experienced in preparing and formatting USB drives for OS installations, recovery media, and multimedia compatibility (FAT32, exFAT, NTFS)
- Knowledgeable in file system management and device compatibility troubleshooting.
- Skilled in creating bootable USB media for Windows installation and hardware diagnostics
- Undervolted hardware (CPU/GPU) for better performance.
- Updated older devices and their drivers to mitigate vulnerabilities.
- Windows/Linux administration via PowerShell/Bash commands


## Projects:

### 1. Home Lab

  I started with a Raspberry Pi 5 and learned a lot about Linux and how to use the terminal. Everything from navigating the terminal to file or user management. I know the different package managers and Linux distros, and the importance of self-hosting services for privacy.

### 2. Linux Administration

  I spent a lot of time practicing Linux commands, doing things like permission management, creating files and directories, adding or deleting users, updating and installing new software.

### 3. Wazuah SIEM

  I set up a SIEM for monitoring other devices on the network:

https://github.com/maksimtishin/SIEM-Wazuah-/tree/main

### 4. Hands-on Hacking
  I practiced hacking legally with a game called "Grey Hack."
  
<img width="1432" height="317" alt="Image" src="https://github.com/user-attachments/assets/4a119ddc-6f11-4a7a-9dfe-b1760c084a16" />



https://github.com/maksimtishin/GreyHack/blob/main/README.md

### 5. Debloated Windows 11 install

I created a custom XML file to remove bloatware that slows down Windows and bypassed the Microsoft account requirement. Formatted the bootable USB with "Rufus" and experienced using different file systems to install Windows on a regular-built desktop and Dell laptops.

<img width="50%" height="660" alt="Image" src="https://github.com/user-attachments/assets/044fc8dc-7354-4f8e-adf2-47fc41d5b952" />

### 6. Formatted USBs to work in the car

A relative was having issues with a USB, saying it was not detected in the car when trying to watch movies. I proceeded to research and analyze the situation. I found out that the USB that was not working had the exFAT file system, while a USB that did work had FAT32. I formatted the USB to FAT32 and moved all the files over safely. Which fixed her issue, and the USB is now detected by the vehicle.

<img width="40%" height="515" alt="Image" src="https://github.com/user-attachments/assets/6fa17f09-54df-48a4-b59d-98163c0e8953" />

### 7. Upgraded the computer's network speed & shared connection to another

I have 2gb internet and noticed my PC is only reaching 1 GB speeds for the download and upload, which led me to buy a 2.5 GB PCIe network interface card, which bypassed my motherboard's limited 1 GB speed. Then I had another device that needed an Ethernet connection. Instead of buying a 2.5 GB switch, I shared my Ethernet connection to the motherboard's NIC, which allowed me to plug my second PC into it and also have a connection without spending extra money on a new switch. 

To do this, go into network settings and into properties of your main NIC, which has an internet connection. Then, go into the sharing tab - check allow other network users to connect through this computer's internet connection, followed by pressing the drop-down menu and selecting your NIC that has the internet connection. Boom! You may now use your other NIC to connect another device to the internet.

<img width="40%" height="463" alt="Image" src="https://github.com/user-attachments/assets/0c6bb7ff-dd54-4db7-a22e-b4c5745f41ef" />

### 8. Slow ISP Router troubleshooting.

I have 2gb internet, but I noticed that I'm only getting around 300 Mbps download speed on my computer using Ethernet, and even my wifi speed is faster. I contacted the ISP and wasted many hours trying to resolve this. They sent me not one but TWO replacement routers, one having the same issue and the other not even being able to connect to the internet. After lots of frustration, I took matters into my own hands and started researching. I figured early on that there is a MAC address binding to the modem, which is why I couldn't get internet on any other router besides the one provided by the ISP. So I found the WAN interface's MAC address and copied it over to my own router, which allowed me to connect to the internet. The download speeds instantly jumped up close to 1 GB, since this router is limited to 1 GB, but that proved my hypothesis of the ISP router limiting my speeds over Ethernet. Soon, I'll be getting a 2.5 G router, which will support my internet speeds completely.

Some troubleshooting I did to identify the source of the problem was using different Ethernet cables and devices, as well as powering off the modem for 30 minutes, trying to release the DHCP lease, which didn't work, which is why I had to clone the MAC address onto my own router.




