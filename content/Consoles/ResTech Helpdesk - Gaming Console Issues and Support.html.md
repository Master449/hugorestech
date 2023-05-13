---
weight: 0
title: "Console Issues"
description: "Console Issues"
tags: ["Hardware", "Troubleshooting"]
---​​

​​​​​​​​​​​​​​​​​​​​​​Gaming Console Issues and Support​​


[Play Station 2](#PS2)​   
[Play Station 3](#PS3)    
[Play Station 4](#PS4)    
[Xbox 360](#X360)    
[Xbox One](#XONE)    
[PC](#PC)    
[Internet Issues​](#INTERNET)​ 

​​​  



Play Station 2


Obtaining MAC addresses

1. Power up the PlayStation 2 and load the Network Adaptor Startup Disc

2. Once it has loaded, Press X to enter the ISP setup

3. The ISP SETUP will begin to load

4. Once the setup process has loaded press X to continue

5. After the network adapter has been found, press X to continue

6. Press X again to continue

7. Select NEW and then press X to continue

8. Type a name for your ISP setting. This can be any name you would like to associate with this connection.

9. When asked if you currently subscribe to an ISP service, select YES and press X to continue

10. For connection type, choose HIGH SPEED CONNECTION (CABLE OR DSL) and press X to continue

11. Select AUTOMATIC SETTINGS and press X to continue

12. When asked if your ISP requires a User ID and Password, select NO and press X to continue

13. When asked if your Internet Service Provider requires you to input a DHCP Host Name, select NO, Unplug your Ethernet Cable from the PS2, and press X to continue (Unplugging your Ethernet cable from the PS2 will cause the test to fail, you want this to happen so you can get the PS2 to display your MAC address)

14. Wait while your network connection is tested.

15. The network connection test will fail. Do NOT press X or Triangle. Press Select to see the error message.

16. The Network Adapter/MAC address will be displayed. The address is a combination of 12 numbers and letters.​  
  



​​DNAS Issues  


DNAS is a network verification system made by Sony Computer Entertainment Inc (SCEI), used in most Playstation2 games with online capabilities. It stands for **D**ynamic **N**etwork **A**uthentication **S**ystem.

If you receive a message during login identifying a DNAS authentication error and you're ripping your hair out in frustration, please write down the exact error code number, and contact SCEA at 1-866-466-5333 or 1-800-345-7669 between the hours of 6:00am - 7:00pm (Pacific Standard Time)

 

For a "DNS Error (-610)", first try making sure it is registered on the network.  According to my forum research, an error 610 should NOT indictate blocked ports - if their MAC is registered, call SCEA(1-866-466-5333 or 1-800-345-7669) - they may have to send a new DNAS pin. 
  


DNAS Error Codes



* Authentication Errors:



> 
> **-101 sceDNAS2\_SS\_SERVER\_BUSY** DNAS server is busy. "DNAS Error (-101) The network authentication server is busy. Please try again later."
> 
> 
> **-102 sceDNAS2\_SS\_BEFORE\_SERVICE** DNAS authentication service period has not started for this title. "DNAS Error (-102) This software title is not in service."
> 
> 
> **-103 sceDNAS2\_SS\_OUT\_OF\_SERVICE** DNAS authentication service period has ended for this title. "DNAS Error (-103) This software title is not in service."
> 
> 
> **-104 sceDNAS2\_SS\_END\_OF\_SERVICE** All DNAS services have stopped. "DNAS Error (-104) The network authentication server is not in service."
> 
> 
> **-105 sceDNAS2\_SS\_SESSION\_TIME\_OUT** Session timeout. "DNAS Error (-105) Connection to the network authentication server has timed out. Please try again later."
> 
> 
> **-106 sceDNAS2\_SS\_INVALID\_SERVER** DNAS library (PS2) received an invalid server response. "DNAS Error (-106) A network authentication system error has occurred."
> 
> 
> **-107 sceDNAS2\_SS\_INTERNAL\_ERROR** DNAS library (PS2) internal error while authentication DNAS server. "DNAS Error (-107) A network authentication system error has occurred."
> 
> 
> **-108 sceDNAS2\_SS\_EXTERNAL\_ERROR** DNAS server received corrupted data. "DNAS Error (-108) A network authentication system error has occurred."
> 
> 


* Data Downloading Errors:



> 
> **-201 sceDNAS2\_SS\_DL\_NODATA** This title does not have a data download service. "DNAS Error (-201) A download error has occurred."
> 
> 
> **-202 sceDNAS2\_SS\_DL\_BEFORE\_SERVICE** Data download service has not started for this title. "DNAS Error (-202) A download error has occurred."
> 
> 
> **-203 sceDNAS2\_SS\_DL\_OUT\_OF\_SERVICE** Data download service has ended for this title. "DNAS Error (-203) A download error has occurred."
> 
> 
> **-204 sceDNAS2\_SS\_DL\_NOT\_UPDATED** No new download data. "DNAS Error (-204) A download error has occurred."
> 
> 


* Machine Information Errors:



> 
> **-401 sceDNAS2\_SS\_INVALID\_PS2** Invalid PS2 hardware. "DNAS Error (-401) A PS2 hardware information error has occurred."
> 
> 
> **-402 sceDNAS2\_SS\_INVALID\_MEDIA** Invalid disc. "DNAS Error (-402) A PS2 disc information error has occurred." Incorrectly updated or missing patch. Possibly more than one update needed.
> 
> 
> **-403 sceDNAS2\_SS\_INVALID\_AUTHDATA** Invalid or corrupted disc authentication data. "DNAS Error (-403) A PS2 disc information error has occurred." Incorrectly updated or missing patch. Possibly more than one update needed.
> 
> 
> **-404 sceDNAS2\_SS\_INVALID\_HDD\_BINDING** Current PS2 and HDD combination is different than registered combination. "DNAS Error (-404) A PS2 hardware information error has occurred."
> 
> 


* Network Errors:



> 
> **-601 GLUE\_ABORT** A network connection was aborted. "DNAS Error (-601) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-602 NET\_PROXY** Proxy server error. "DNAS Error (-602) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-610 NET\_SSL** An SSL session error occured. "DNAS Error (-610) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-611 NET\_DNS\_HOST\_NOT\_FOUND** The DNS resolver did not recognize the DNAS server host name. "DNAS Error (-611) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-612 NET\_DNS\_TRY\_AGAIN** The DNS resolver cannot be found. "DNAS Error (-612) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-613 NET\_DNS\_NO\_RECOVERY** The DNS resolver response is invalid. "DNAS Error (-613) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-614 NET\_DNS\_NO\_DATA** The DNS resolver found no IP address for the DNAS server host name. "DNAS Error (-614) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-615 NET\_DNS\_OTHERS** Other DNS resolver-related errors. "DNAS Error (-615) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-616 NET\_EISCONN** A server connection already exists from this client IP address. "DNAS Error (-616) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-617 NET\_ETIMEOUT** A network timeout occurred. "DNAS Error (-617) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-618 NET\_ECONNREFUSED** The connection was refused (the server is not running). "DNAS Error (-618) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-619 NET\_ENETUNREACH** The network destination is unreachable. "DNAS Error (-619) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-620 NET\_ENOTCONN** The network connection is down. "DNAS Error (-620) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-621 NET\_ENOBUFS** An out-of-memory error occured. "DNAS Error (-621) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-622 NET\_EMFILE** Unable to create any more network connections. "DNAS Error (-622) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-623 NET\_EBADF** The title requested a network connection using an invalid value. "DNAS Error (-623) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-624 NET\_EINVAL** The title requested a network function using invalid options. "DNAS Error (-624) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 
> **-625 NET\_OTHERS** Other network-related errors. "DNAS Error (-625) A network error has occurred." Please double-check your network connection and/or network configuration.
> 
> 


* Unique ID Errors:



> 
> **-701 sceDNAS2\_SS\_ID\_NOUSE** The title does not use the unique \*category\* ID feature. "DNAS Error (-701) A software category error has occurred."
> 
> 
> **-702 sceDNAS2\_SS\_ID\_CAT\_NOT\_EXIST** The specified unique \*category\* ID category does not exist. "DNAS Error (-702) A software category error has occurred."
> 
> 
> **-703 sceDNAS2\_SS\_ID\_NOT\_JOIN\_TO\_CAT** The title does not belong to the specified unique \*category\* ID category. "DNAS Error (-703) A software category error has occurred."
> 
> 


* Unexpected Errors:



> 
> **-832** Unregistered title ID. Incorrect title ID in SYSTEM.CNF. Using the wrong regional DNAS library, thus talking to the wrong DNAS server. Using the production server (debug=0) without DNS redirection.
> 
> 
> **-833** Region Error
> 
> 
> **-840** Server is down, try again later.
> 
> 
> **-848** Wrong authentication data or passphrase.
> 
> 
> **-864** Invalid media: e.g. using burned CD-R and DVD-R discs against the production server, or using manufactured discs against the development server.  
> 
> 
> 


Port Forwarding 

In this article we'll explain the concept of ports and guide you through the process of configuring your port settings so that the majority of PlayStation 2 network games will function correctly. This process is variously known as port forwarding and port mapping, but these terms are interchangeable. The aim is to ensure that all network games for your PlayStation 2 will work online as soon as you drop the disc in the disc tray.


**Ports explained**

Built in to most routers is a firewall. The firewall, along with various other security features, provides a level of protection to every device in the home network by not responding to data sent from other computers on the Internet, unless that data has been specifically requested. In normal usage of a home computer, this doesn't cause too many problems of access to information on the Internet (web pages, file downloads etc.). The great benefit is that the computers in your home network are offered a good level of protection from internet threats such as hackers and viruses. However, the requirements for network gaming are slightly different. Game data is sent to and from the console (or computer) 100's of times a minute. In some cases, a firewall may stop crucial game information being passed to the PS2. This is not a good thing for successful fast-moving network gaming. Ports can be best described as locked doors in a firewall. There are over 65,000 of these 'doors'. Certain ports are unlocked and opened automatically by applications you install. For the purposes of network gaming, you can also manually open particular ports or a range of ports to allow game data to flow freely.


**So, how do I solve this issue?**

Some people may decide that they do not need a firewall and deactivate it, for example if each computer on the network has up-to-date firewalls and virus checking software already installed. However, for those of you who'd like to keep your entire home network secure, there is a more methodical approach. This is approach is known as port forwarding - essentially you define which ports should be opened based upon the requirements for the games you play. The basic ports that you will need to open in order to play all PlayStation 2 network games are given below.


**Settings for all PlayStation 2 network games**

* Allow ICMP
* 53
* 80
* 443

When you purchase a game, the ports (or ranges of ports) which need to be opened in order to network play the game should be detailed in the gameplay manual. Of course, network-enabled titles from other publishers can be set up in the same way, though the specific ports that should be opened may differ. Port settings are generally to be found in the gameplay manual, packaged with the game. If they're not, contact the publisher's customer helpline or website and they'll be able to supply you with the specific ports. Below is a list of the most common ports and port ranges (a group of sequentially numbered ports).


**UDP port ranges to be left open for all common network play titles**


**TCP Ports:** 4558, 7001, 10070-10080, 17087   
**UDP Ports:** 4558, 6000-6999, 10070, 17087


**How do I change the settings in my router?**
All routers have a web-based interface which lets you quickly and easily configure almost every aspect of your router's settings, including port settings. You can open single ports or a range of ports in order that installed programs can function properly (MSN Messenger, for example). In many routers, these port settings are grouped together under 'Gaming and Applications' settings, though they may be grouped under 'Ports' or 'Port Forwarding' headings, too.


**Note:** To help with administration, it's always wise to give any new settings an obvious name, for example the game name if the game requires special port forwarding settings.

* For particular details of your router, we recommend you consult the device's full user manual (which is often included on a CD), rather than the printed quick install guide. Unfortunately, we are unable to individually support the huge number of routers available across Europe, through this website or our network gaming careline. However, all reputable hardware manufacturers do provide customer help lines to assist with setup issues, if you cannot find the information required in the device's manual.


Of course, there are other ways to set up your home network for network gaming. If you want to learn more about your options, check out the Related Articles.​

  



[Back to Top](#Top)  



Play Station 3  



**Error Codes**  


Besides the specific error codes below, a common issue that can prevent a PS3 from connecting to the network is a weak ethernet signal from the wall jack.  The ethernet port on a PS3 seems to be less sensitive than other devices, so it may exhibit intermittent or consistent connectivity problems even when other devices are able to connect to the network through the same wall jack.  
**Solution: Connect a powered switch between the wall jack and the PS3.**  If our test switch resolves the issue, advise the student to purchase their own switch as we do not sell or rent any.


***E (Other/General) Errors***


**Error Code DescriptionAction**


**CE-32889-0   
CE-32928-4**

Download has canceled because the downloading of this content has previously been started and experienced an error.


**Step 1:** Go to [Notifications] > [Downloads] and check the content is on the list. Delete the content from [Options], and retry downloading the content from the Library.


**Step 2:** If you fail downloading the content again, back up the data using USB device or PS+ online storage, and then go to Safe Mode to try ｢4.Rebuild Database]. After the Rebuild Database is finished, bring back the data and retry your download from the Library.


**Step 3:** If the error occurs again, go to [Settings] > [Initialization] > [Initialize PS4] and try the PS4 initialization.


**CE-32883-4**

Internal error

* Turn off the PS4 and restart the system.


**CE-33179-3**

Application is not found.

* Retry after the installation is completed.
* Installation of Add-Ons fails until the installation of application installation is complete.


**CE-33991-5**

Connection error.Retry Internet Connection test.


**CE-34788-0**

This update file cannot be used.

* Connect a USB storage device that contains an update file for re-installation for version 1.50 or later.
* Delete the Update file from the USB storage device, and replace it with the update for re-installation.


**CE-34878-0**

Application has crashed.


**Step 1:** Close the application, install the latest system software and game update, and restart the system.


**Step 2:** If the error occurs again, back up your saved data, and then go to [Settings] > [Initialization] and choose [Initialize PS4].


**CE-33743-0  
CE-33945-4**

Connection to server failed

* The PS4 was unable to connect to the server.
* Please try again later.


**CE-30392-7   
CE-30608-7**

Hardware Error

* Your system likely needs to be serviced.


**CE-33992-6**

Internet connection test error

* Make sure you are signed in to PSN before you start the connection test.
* It's also possible that the PSN may be be undergoing maintenance.


**CE-30005-8**

Access to HDD or Blu-Ray failed


**Step 1:** Eject the disc from the PS4 system, and check that the disc is not dirty or damaged. Then retry.


**Step 2:** Back up the data using a USB device or PS+ online storage. Then, delete the application by pressing the Options button and choosing "Delete" from the content area. Reload the data from the USB or online storage.


**Step 3:** If the error occurs again, please contact SCEA for additional technical support.


**CE-32947-5**

Could not download the file


**Step 1:** Try the Internet connection test at [Settings] > [Network] > [Test Internet Connection]. Check that the internet status is valid.


**Step 2:** Delete the content (if it is shown in content area), and try re-downloading the content from Library.


**Step 3:** If the error occurs again, please contact SCEA for additional technical support.


**CE-32807-0**

License Error


**Step 1:** If you have previously activated the system as your Primary PS4, go to [Settings] > [PSN] > [Activate as Your Primary PS4], deactivate, and then reactivate.


**Step 2:** Go to [Settings] > [PSN] > [Restore Licenses],and choose the restore option.


**Step 3:** If the error occurs again, please try again later.


**CE-34861-2**

Connection to server failed


**Step 1:** If you have been able to connect to the Internet previously, PSN or the game's server may be temporarily unavailable. Please check the status of the game's server via its website.


**Step 2:** If you have this error every time you try to connect to the Internet, check the SSL in your Internet environment and verify that SSL is available.


**CE-33983-6   
CE-33984-7   
CE-33985-8   
CE-33986-9   
CE-33987-0   
CE-33988-1   
CE-33989-2   
CE-33990-4**  
Internet Connection test error

* Retry the Internet connection test.
* It's also possible that the PSN may be be undergoing maintenance.


**CE-34224-5**

System internal error


**Step 1:** Back up your saved data using a USB device or PS+ online storage. Go to [Settings] > [Initialization] > [Initialize PS4] and try the PS4 initialization.


**Step 2:** Restore your saved data.


**Step 3:** If the error occurs again there may be an issue with the PS4's hard drive (HDD). If you have previously changed the HDD, use the other HDD. If not, please contact SCEA for additional technical support.


**CE-35463-1**

The disc cannot be played


**Step 1:** Copied media, CD's, and 3D Blu-Ray movies cannot be played. Please verify that the type of disc you're trying to play is support by the PS4.


**Step 2:** Make sure the disc you're trying to play isn't dirty, scratched, or otherwise damaged.


**CE-30784-2**

PS4 failed to detect USB device


**Step 1:** Verify that the USB device supports USB 2.0 or 3.0.


**Step 2:** Ensure the device is properly inserted in the PS4, and then wait one minute before trying to access the device again.


**Step 3:** Make sure there are not multiple partitions on the device.


**Step 4:** Initialize the device on a PC if possible.


**CE-30012-6**

Internal Error


**Step 1:** Update the PS4 system with the latest system software.


**Step 2:** Clean disc to ensure the disc you're trying to play isn't dirty, scratched, or otherwise damaged.


**Step 3:** Restart the PS4 system.


**CE-35230-3**

Network Error.

* Response speed from DNS server is likely delayed.
* Go to [Settings] > [Network] > [Set Up Internet Connection] > [Custom] and change the DNS settings.

 

 


***E (External) Errors***


**Error CodeDescriptionAction**


**E-8200002E**

The credit card information is not valid

* Remove credit card from account, and then re-enter the credit card information.


**E-82000102**

Server returned "Unknown Error"Try again.

* If the error happens on PS Store, close the store and retry.
* If the error persists, exit store and Sign-out and Sign-in to PSN at [Settings] > [PSN].


**E-8200012**

FInvalid voucher code

* Double check and re-enter the code exactly as written.


**E-8F000001**

Purchased Failed

* Purchase the game directly from the PS Store, not from inside the game demo.


**E-82F001F8  
E-800085D1  
E-82E101F6**

Connection to server failed

* The PS4 was unable to connect to the server.
* Please try again later.


**E-82000163**

The home address registered on your PSN account does not match the address for your credit card.

* It is not currently possible to change your address via the PS4's PSN settings.
* So you'll need to use the web browser (PS4, PC, or mobile device) to change it via Sony Entertainment Network.


**E-82000171**

Credit card on file is invalid

* Verify that your credit card number and expiration date are valid and up to date.


**E-82000138**

Failed to add funds to wallet using a voucher or PSN card

* Verify that redeeming the code will not put your wallet over the $150 limit. If it does, redeem the code at a later date when your balance is lower.
* If you aren't at the limit and still get this error, please try again later.


**E-82F001F7**

PSN is undergoing maintenance

* PSN is undergoing maintenance. Please try again later.


**E-82000113**

Voucher error

* The server was unable to verify the voucher. Please try again later.


**E-82000134**

Product voucher region does not match the account's region

* This product or content is not available in your account's country/region.


**E-FFFFFFFF**

System internal error

* Update your system software to the latest version.
* If the error occurs again, please contact SCEA for additional technical support.





**E-80411302**

Internal error


**Step 1:** Close the application and restart the system. If this happens while in the PS Store, close the store and retry.


**Step 2:** If the error occurs again, back up your saved data, and then go to [Settings] > [Initialization] and choose [Initialize PS4].


**E-82000156**  


Rate limit exceeded

* For security reasons there are limits on how many times and how fast you can enter credit card and voucher code information.
* Try again later.


**E-82E0001C  
E-82E01050**

Access DeniedThe user has been banned or suspended.


**E-80F00800**

Downloaded data may be corrupted


**Step 1:** Delete the content from home screen and re-download the content from the Library.


**Step 2:** If the error persists, go to [Settings] > [Initialization] > [Initialize PS4] and try the PS4 initialization.


**Step 3:** If the error occurs again there may be an issue with the PS4's hard drive (HDD). If you have previously changed the HDD, use the other HDD. If not, please contact SCEA for additional technical support.​  



***NP (Network Server) Errors***


**Error CodeDescriptionAction**


**NP-32091-5**

Trophy data is corrupted


**Step 1:** Back up the save data using USB device or PS+ online storage, and then go to [Settings] > [Initialization] > [Initialize PS4] and try the PS4 initialization.  
**Step 2:** Transfer the saved data back to PS4 and retry the Trophy sync.


**NP-35000-8**

PSN is undergoing maintenance

* PSN is undergoing maintenance.
* Please try again later.


**NP-31952-0**

Could not connect to the network

* Retry the Internet connection test and make sure all of your network settings are correct.
* It's also possible that the PSN may be be undergoing maintenance.


**NP-34846-5  
NP-32157-8**

Trophy error


**Step 1:** Try to manually sync your trophies at [Trophies] > Options > [Sync Trophies with PSN].


**Step 2:** Close the application and restart the system.


**Step 3:** If the error occurs again, back up your saved data. Delete the user at [Settings] > [Initialization] > [Delete User]. Create a new user and restore the data.


**Step 4:** If you've tried the previous three steps, the error still occurs, back up your saved data. Then go to [Settings] > [Initialization] and choose [Initialize PS4].  



***NW (Network Library) Errors***


**Error CodeDescriptionAction**


**NW-31484-0**

DNS server not specified.

* Restart the PS4 system.


**NW-31367-0**

Could not open wireless device.

* Restart the PS4 system.


**NW-31453-6**

Delayed server response.

* Try Internet connection test at [Settings] > [Network] > [Test Internet Connection].
* Check that the internet status is valid.


**NW-31172-4**

Connection to server failed.

* Try Internet connection test at [Settings] > [Network] > [Test Internet Connection].
* If you are able to connect, but still get the error, the server is likely busy.
* Please try again later.


**NW-31201-7   
NW-31194-8**  
Could not connect to the network


**Step 1:** PSN or the game's server may be temporarily unavailable. Please check the status of the game's server via its website.


**Step 2:** If the servers are active, run the Internet connection test at [Settings] > [Network] > [Test Internet Connection] and make sure you can connect to the network.


**Step 3:**Update your router to the latest firmware. Turn off other devices that are connected to your network to reduce stress. If this does not work, try again later as the server may be experiencing high volume.


**NW-31456-9   
NW-31448-0**

Connection error

* PSN or the game's server may be temporarily unavailable.
* Please check the status of the game's server via its website.
* This is likely a temporary issue, so please try again later.


**NW-31485-1**

Timed out

* Restart the PS4 system.


**NW-31162-3**

Undefined error

* Restart the PS4 system.


**NW-31200-6**

Failed to update the system software due to connection error


**Step 1:** If you have access to a PC, follow these instructions to update your system software using a USB device.

Required Items:

* PlayStation®3 system.
* SIXAXIS™ wireless controller connected to the *PS3* with a USB cable.
	+ You must have the SIXAXIS wireless controller connected to the *PS3* system directly via a USB cable before you attempt to do a System *Update*. If you do not have a USB cable to connect the SIXAXIS wireless controller , do not attempt to do the System *Update*.
* Computer/PC with Internet access.
* Storage media\* (Memory Stick™, SD Memory Card, Compact Flash®) or a USB Mass Storage device such as a USB flash drive with least 110 MB of free space.
	+ An appropriate USB adaptor (not included) is required to use storage media with some models.

 

Download the System Software *Update*

1. Create a folder on the storage media in which to save the *update* data.   
Using a computer, create a folder named "*PS3*" on the storage media. Within the "*PS3*" folder, create a folder named "*UPDATE*". Make sure that both folder names are all UPPER CASE. Save the *update* data in the "*UPDATE*" folder.  
 
![System Software folder structure](http://us.playstation.com/csimg/PS3/kbid_275/kbid275_1.jpg)
2. Download the *update* data and save it in the "*UPDATE*" folder created in step 1.   
Note: Be sure to save the *update* data as described above. **If the data is not saved in the correct way or the folders are not created exactly as shown, the *PS3* will not recognize the *update* data.**
	* Location: Save in the "*PS3*" folder > "*UPDATE*" folder
	* File name: Save as file name "PS3UPDAT.PUP".


*Update* the System Software on the *PS3*


**IMPORTANT:**

* Do not turn off the *PS3*™ system during an *update*. If an *update* is cancelled before completion, the system software may become damaged, and the system may require servicing or exchange.
* During an *update*, the power button on the system front and PS button of the controller are inactive.
* Make sure the SIXAXIS wireless controller is plugged directly to the *PS3* system via USB cable at all times.
1. Insert the storage media or USB device that contains the *update* data in the *PS3* system.
2. From the XMB™ home menu, select ![Settings icon](http://us.playstation.com/csIMG/ps3/shared/icn_settings.gif) (Settings) > ![System Update icon](http://us.playstation.com/csIMG/ps3/shared/icn_ntwkupdate.gif) (System *Update*) , and then press the ![X button icon](http://us.playstation.com/csIMG/ps3/shared/icn_btnx_color.gif) button. 
 
![system update screenshot](http://us.playstation.com/csimg/PS3/kbid_275/kbid275_2.jpg)
3. Select [*Update* via Storage Media], and then press the ![X button icon](http://us.playstation.com/csIMG/ps3/shared/icn_btnx_color.gif) button. The system automatically searches for and finds the latest version of the *update* data saved on the storage media or USB device. 
 
![system update screenshot 2](http://us.playstation.com/csimg/PS3/kbid_275/kbid275_3.jpg)
4. Start the *update*.   
Press the ![X button icon](http://us.playstation.com/csIMG/ps3/shared/icn_btnx_color.gif) button to start the *update* data. Follow the on-screen instructions to complete the *update*. 
 
![system software update screenshot 3](http://us.playstation.com/csimg/PS3/kbid_275/kbid275_4.jpg)
5. Confirm that the *update* was successful.   
After the *update* has been completed, go to ![Settings icon](http://us.playstation.com/csIMG/ps3/shared/icn_settings.gif) (Settings) > ![System Settings icon](http://us.playstation.com/csIMG/ps3/shared/icn_syssettings.gif) (System Settings) > [System Information]. If the [System Software] field displays the version number of the *update*, the *update* was successful.
6. You can delete the *update* data from the storage media or USB device after the *update* has been successfully completed.


**NOTES:**

* Depending on the content, you may not be able to play without first *updating* the system software.
* After you have *updated* the system software, you cannot go back to an earlier version.


**Step 2:** If you don't have access to a PC, try Internet connection test at [Settings] > [Network] > [Test Internet Connection] and make sure you can connect to the network.


**Step 3:**If you are able to connect, retry updating at [Settings] > [System Software Update].


**Step 4:** If you're unable to connect, the network may be experiencing issues.Turn off other devices that are connected to your network to reduce stress and try the update again.

 

 


***SU (Software Update) Errors***


**Error CodeDescriptionAction**


**SU-30696-4  
SU-30645-8**

Failed to update the system software.

* The update file may be corrupted.If you are updating the system via Internet, go to **[Settings] > [System Software Update]** and retry update.
* If you are updating via USB storage device, delete the update file on USB and redownload the update file.
* Then retry updating at **[Settings] > [System Software Update]**


**SU-34328-0**

An internal error occurredPlease try again later.


**SU-30733-6**

The latest version of the system software is already installed

* No Action Required.


**SU-30683-0**

Update via USB storage failed


**Step 1:** Go to Safe Mode, choose option ｢7. Initialize PS4], and follow the onscreen instructions.


**Step 2:** If the error occurs again, please contact SCEA for additional technical support.


**SU-34322-4**

Failed to update the system software.

* Update has timed out


**Updating Via Internet:** 

1. Go to [Notifications] > [Downloads] and highlight the notification about the system software update.
2. Push the [Options] button and delete the content.
3. Then retry the update by going to [Settings] > [System Software Update]


**Updating Via USB:** 

* Retry the update by going to [Settings] > [System Software Update].


**SU-30634-6  
SU-30631-3**

USB error occured while updating the system software.


**Step 1:** Delete the Update file from the USB storage device


**Step 2:** Clear your browser cache and redownload the PUP file. Then retry the system update.


**Step 3:** If the error persists, try another USB device.


**Step 4:** If the error occurs again there may be an issue with the PS4's hard drive (HDD).

* If you have previously changed the HDD, use the other HDD.
* If not, please visit our [Contact](https://support.us.playstation.com/app/contact_options/session/L2F2LzEvdGltZS8xMzk3Njc0MjExL3NpZC9YT1NWaFlSbA==) page to contact SCEA for additional technical support.

 

 


***WV (Web View) Errors***


**Error CodeDescriptionAction**


**WV-33907-2**

Operation timeout.

* The specified time-out period was reached according to the conditions.
* Connection timed out / connection error while receiving data.
* Network may not be stable now.
* Please retry after a while.


**WV-33898-1**

Connection timed out / Can't open web page

* Check to make sure the URL you typed is correct.
* If it is correct and you are unable to connect.
* Please try again later.


***Other Error Codes***


**80029945**

Can’t playback burn movie


**80029946**

Attempting to play burnt Dual layer NTSC disc on a Pal ps3

Work around is to transfer files to ps3 via TVersity


**80029301**

An error occurred during the delete operation (attempting to delete some ps2 homebrew from virtual mem card)


**80029513**

Copyright Violation when attempting to install game​  



  


​**​Obtaining the MAC Address**


1. Navigate to the "Settings" icon (located on the far left).


  
2. Navigate up/down until you see the "System Settings" icon.  Press the "X" button.


  
3. Scroll up/down until you see "System Information".  Press the "X" button.  You will see your MAC Address listed inside.​​  



  




[Back to Top](#Top)



Play Station 4  






**Error Codes**


**Error Code CE-33179-3: Application is not found**

This is an installation issue. Recommended action is to re-install or let the current application complete its installation.


**Error Code CE-33991-5: Internet connection issue**

Check whether your internet connection is alright.


**Error Code NW-31484-0: DNS server not set**

You can try restarting your PS4 system.


**Error code e-80e80034**

This is a PS4 sign in issue and is probably related to server overload.


**Error Code NW-31367-0: Could not open wireless device**

You need to restart PS4.


**Error CE-34878-0: An error has occurred in the following application**

This error pops in when the player tries to launch Call of Duty Ghosts. It seems when you go online with the game to download multiplayer updates it corrupts the game files. Neither Activision or Sony have a fix for this yet. However you can still play this game offline.


*Update: This apparently happens when an application has crashed. You need to restart the application.*


**Error Code NW-31453-6: Network Connection Has Been Lost**

You may receive the error code if the PlayStation Network is under heavy load or is currently down. There is nothing much one can do other than keep track of the network status.


**Error Code CD-30774-1: Could not find the Update File**

This error mostly appears if the user has changed the hard disk with their own in the PlayStation 4. Please make sure that your new HDD fulfills the following specifications:

* Should not be thicker than 9.5mm
* 5400 RPM
* SATA II

Fixing this is rather inconvenient as it requires the user the remove the hard disk and redo everything.


**Error Code CE-32958-7: Cannot Launch Application**

This error occurs when your PlayStation 4 is not updated with the latest firmware update. Make sure you have the latest update installed.


**Error NW-31200-6**

This issue happens when you try to download the latest firmware update via PSN but it stalls in between. The best way to update your PS4 is via the USB.


**Error NW-31297-2**

PS4 does not connect to the internet. Try Rebooting the PS4 in safe mode. Below you fill find how to boot the PS4 in safe mode.


**Error code SU-30645-8**

This issue happens when the firmware update is installed. You need to check whether you have the firmware from the correct region installed.


**Error Code E-82000102: Server returns “Unknown Error”**

You need to sign out and sign out of the PlayStation Store. If that does not work close the story and retry.


**Error code NW-31194-8: Connection lost**

Restart the PS4.


**Error code NW-31456-9**

This is related to PS4 features like sending messages or instances where the background gets stuck and does not load. Although not a proven method, the best way to fix is to restart your internet and try again.


**Error code 10302**

Internet connection issue. Try rebooting PS4 and your modem/router.


**Error Code E-8200002E: Credit Card information is invalid**

You need to enter the correct details.


**Error Code 80710092, E-820001F7, CE-33743-0, CE-34861-2 and NW-31448-0**

Server issue. PSN might be down.  



**​Other Fixes**  



**How to start the PlayStation 4 in safe mode:**

Follow the steps below to start the PS4 in safe mode:

1. Turn off the PlayStation 4 by pressing the power button on the front panel. The power indicator will blink for a few moments before turning off.
2. Once the PlayStation 4 is off, press and hold the power button. Release it after you’ve heard two beeps: one when you initially press, and another 7 seconds later.
3. Connect the DualShock 4 controller with the provided USB cable and press the PS button on the controller.


  



Once you boot up Safe Mode, the following options are available. The first five are self explanatory.  


+ Initialize PS4 will reset and delete all data and settings.
+ Initialize PS4 (Reinstall System Software) will every date along with System Software.

 **PS4 Getting Bricked/ Black Screen With Blue Flashing Light**

You can prevent your PS4 from getting bricked by using the following steps. Right now, download the backup software and the software update from us.playstation.com and copy them to a USB drive.

* The relevant links are: [800+MB Update](http://us.playstation.com/support/systemupdates/ps4/pc_update/index.htm) and [300MB Update](http://us.playstation.com/support/systemupdates/ps4/index.htm)
* Make sure that on your flash drive you create a folder called PS4 and drop the 800+ update there, and then create a folder under PS4 called UPDATE (ALL CAPS) and drop the 300 MB there.
* After hooking up the PS4 and before starting to play (I know most of you will want to skip this step, I recommend you don’t), update the software.
* Do not turn off your PS4 or unplug it. Wait for the update to be completed.
* Activate your account and set up your network.
* If you face any problem, do not attempt to solve it on your own. Find technical help on the PlayStation forums.





**Alternatively, Sony have released a**[**complete guide**](http://community.us.playstation.com/t5/PlayStation-4-Support/INFO-Blinking-Blue-Light-PS4-Issues/td-p/42154071)**for Blinking Blue Light PS4 Issues:**  


Here are some of the symptoms associated with blinking blue lights issue:

* blue indicator light blinking
* no video/audio output to television
* console powering off after blinking blue


  



This blinking light issue could indicate any number of causes including but not limited to:

1. Issues with PS4 power supply
2. Issues with PS4 hard drive
3. Issues with other PS4 hardware





**Power Supply Troubleshooting:**  


1) Turn PS4 off completely

* Touch the power button on the front of the PS4 for at least 7 seconds (until the system beeps twice).

2) Disconnect PS4 AC power cord from electrical outlet

* Only disconnect the plug of the AC power cord from the electrical outlet when the power indicator is turned off. If you disconnect it while the power indicator is lit or blinking, data might be lost or corrupted, and the system might be damaged.

3)  Check parts AC IN connector, AC power cord, and electric socket for any conspicuous damage or anomalies

* *You can try using another compatible AC cord (like a power cord from a PS3) to see if that resolves the issue*


**Hard Drive Troubleshooting**  


1) Turn PS4 off completely

* Touch the power button on the front of the PS4 for at least 7 seconds (until the system beeps twice).

2) Disconnect PS4 AC power cord from electrical outlet

* Only disconnect the plug of the AC power cord from the electrical outlet when the power indicator is turned off. If you disconnect it while the power indicator is lit or blinking, data might be lost or corrupted, and the system might be damaged.

3) After removing the plug for AC power cord from the electrical outlet, detach the other cables from the PS4.

4) Slide the HDD bay cover to remove it.

5) Inspect the harddrive to make sure it is properly seated in the HDD bay.  A loose hard drive connection can prevent the PS4 from powering on completely.

6)  If you suspect possible hard drive damage or would simply like to replace the PS4′s hard drive with one of your choosing.


**Software Installation Troubleshooting**  


1) If your hard drive and power supply appear in good shape, you can try to booting your PS4 into Safe Mode

* The following options are available in Safe Mode:
1. Restart System - Ends Safe Mode and restarts the PlayStation 4 normally.
2. Change Resolution - Changes the screen resolution to 480p when the PlayStation 4 is restarted.
3. Update System Software - Allows the PlayStation 4 to update the system software via Internet, USB Drive, or Disc.
4. Restore Default Settings - Restores the PlayStation 4 to the default factory settings.
5. Rebuild Database - Scans the drive and creates a new database of all content.This operation may take a long time depending on the type and number of data items.
6. Initialize PS4 - IMPORTANT: All data and settings will be lost by performing this step. Deletes all user data and restores the PS4 to as if it just came out of the box. This option is the same as [Initialize PS4 ] in the (Settings) menu. System software (firmware) is not deleted.
7. Initialize PS4 (Reinstall System Software) - **IMPORTANT**: Deletes all information on the HDD, including the System Software. A message that states a USB storage device containing the System Software must be connected, is displayed. Then you can confirm the selection. (You will need the full system update installer which you can download from the official PlayStation site)





**PS4 Does Not Boot Or Starts:**

You can fix it by following the steps below:

* Turned off console.
* Took out hard drive.
* Turned on console, and booted into Safe Mode (white light bar).
* Plugged in controller and re-placed in hard drive.
* Safe Mode properly restored the Hard Drive.
* The console will rebooted itself and should work!

You can also trying formatting the HDD and re-installing the firmware update.


**PS4 No Video Signal On TV:**

It is probably a problem with your HDMI port. Kotaku faced the same issue and they got it fixed. Check out the video below to see how you can fix this issue.


**Player cannot hear each other people speaking:**

The solution may vary for different headsets/headphones but the method should work for most of them.

1. Hold Home Button2. Adjust Devices3. Output to headphones -> All Audio​​  



  



[Back to Top](#Top)  



Xbox 360  



**Error Codes**



**E45:** Unknown (possibly dashboard update related)  
  
**E64:** [DVD](http://forums.xbox-scene.com/index.php?showtopic=484726&st=0&p=3213514&) Drive Error.... DVD Timeout, Wrong firmware, dvd is without f/w chip, etc.  
  
**E65:** DVD Drive Error.... DVD Timeout, Wrong firmware, dvd is without f/w chip, etc. This can also be caused by the tray not being fully closed on boot.  
  
**E66:** DVD Drive Error: DVD model, or version does not match that of the version expected by the dashboard. OR the firmware version on the drive is older then the firmware version expected by the dashboard. Make sure the DVD drive is of the same version originally included with the console and that it is using either the original firmware included with the console or newer.  
  
**E67:** Hard Drive Error... It could be a problem with the Hard Drive itself or a problem with the internal connection to the hard drive, Try removing the hard drive and playing without it  
  
**E68:** Hard Drive Error... It could be a problem with the Hard Drive itself or a problem with the internal connection to the hard drive, Try removing the hard drive and playing without it, this can also be caused by a Hard Drive Eprom Error. Some also believe this might be caused by a problem with the fans.  
  
**E69:** Hard Drive Error... It could be a problem with the Hard Drive itself or a problem with the internal connection to the hard drive, Try removing the hard drive and playing without it  
  
**E71:** possibly a dashboard update error, Check below in the "Console Reset Codes" for instructions. If that does not work there is no other solution and the console must be sent back to MS for repair.  
  
**E72:** (not yet known)  
  
**E73:** General Hardware Error: Ethernet port... this error is caused by a problem with the Ethernet port.  
  
**E74:** AV cable error... There is a problem with the AV cable, try using a different AV cable. If the cable is known to be working then there is a 90% chance it's a scaler chip problem (the "ANA" or "HANA" chip connected directly to the AV cable) in rare cases it is the GPU.  
  
**E76:** (not yet known)  
  
**E79:** Hard Drive Error... It could be a problem with the Hard Drive itself or a problem with the internal connection to the hard drive, Try removing the hard drive and playing without it  
 


***SECONDARY ERROR CODES***  
The specific type of hardware failure can be determined by a "hidden" error code

* Turn the xbox 360 on, and wait till the 3 red lights are flashing.
* Press and hold the sync up button (the small white one), while holding that button press the eject button.
* The LEDs will now blink the first number in the code (as described below).
* Release the eject button and press it again.
* The LEDs will now blink the second number of the code.
* Release the eject button and press it again.
* The LEDs will now blink the third number of the code.
* Release the eject button and press it again.
* The LEDs will now blink the forth number of the code.
* Release the eject button and press it again.
* The LEDs will go back to the 3 red flashing lights.

You should be able to determine the difference between the 3 flashing lights and the error code lights by the rate in which they flash.  
  
Here is how you interpret the LEDs to get the code number:

* **All four lights flashing - 0**
* **One light flashing - 1**
* **Two Lights flashing - 2**
* **Three lights flashing - 3**


**0001** power supply problem  
**0002** Network Interface problem  
**0003** Power problem could be the PSU could be the GPU/CPU, somehow the console isn't getting clean power from the power supply.  
**0010** over heating  
**0011** over heating - If you are receiving this error after disassembling your console make sure to all 8 of the heatsync screws are tightened securely to the board/heatsink holes.  
**0012** over heating  
**0013** over heating  
**0020** (Not yet known, possibly overheating)  
**0021** DVD Drive Time out - Can be caused by problems with a firmware flash. This is also speculated to sometime be caused by a problem with the southbridge chipset on the motherboard.  
**0022** GPU Error / GPU Overheating  
**0023** (not yet known)  
**0101** (not yet known)  
**0102** unknown error

* likely GPU related (console does not know what is wrong). GPU are not soldered properly to the mother board due either to poor manufacturing or excessive heat up and cool down cycles that stress, weaken and eventually break the soldered connection.


**0103** CPU Error/ CPU Overheating - see solution for error 0102  
**0110** Memory Error / Memory Overheating - see solution for error 0102  
**0200** (not yet known)  
**1000** (not yet known)  
**1001** (not yet known)  
**1002** (not yet known)  
**1003** Hard Drive Error... It could be a problem with the Hard Drive itself or a problem with the internal connection to the hard drive, Try removing the hard drive and playing without it  
**1010** Hard Drive Error, Can be caused buy a corrupt or missing eProm.  
**1011** (not yet known)  
**1012** (not yet known)  
**1013** (not yet known) possibly a dashboard update error  
**1020** (not yet known)  
**1021** (not yet known)  
**1022** AV cable error... There is a problem with the AV cable, try using a different AV cable. (could also be a problem with the encoder chip)  
**1023** DVD drive not connected, connect DVD drive to boot  
**1030** (not yet known)  
**1031** (not yet known)  
**1032** (not yet known)  
**1033** (not yet known)  
**1444 and up** There is no "4" in the error codes four lights is a "0" go back and check your code again.  
  
***Console Reset Codes***  
**Clear All Installed Game Updates and Console Cache**

1. Go to the "system" blade
2. Select "memory"
3. Press Y on the HD symbol
4. Press X,X, Left Bumper, Right Bumper, X,X
5. A message will appear saying: "Do you want to perform maintenance on your Xbox 360 storage devices?"
6. Select Yes


**Clear Any Failed system updates that cause the console to error.**

1. With the console off, press and hold the sync up button (the small white one)
2. While holding the sync button press the power button to turn on the console
3. Continue to hold the sync button until the Console has booted up completely.
4. During the boot process the console should clear any failed updates, allowing you to use it normally.​​​​

​


**​Obtaining the MAC Address**  







|  |
| --- |
| ​1. Go to the System area of the Xbox Dashboard and select Network Settings.
2. Select Edit Settings.3. Under Basic Settings, check to make sure the IP Settings is on Automatic.4. Now go to Additional Settings, select Advanced Settings.5. At the bottom of this screen you'll see a heading called Wired MAC Address.​ |


  




[​​​Back to Top](#Top)


Xbox One  



**Error Codes**


**Error Code 8b050033: Update not available.**

This code indicates that the Xbox One needs an update but it is not currently available. This is mostly a server issues and your best bet is to try again later.


**Error Code E101 xxxxxxxx xxxxxxxx: Emergency Offline Update Issue**

This happens when there was an error when you tried to perform an  emergency offline update. You need to contact your local Xbox Support for this issue.


**Error Code E100 xxxxxxxx xxxxxxxx: Hardware Issue**

Your Xbox One hardware has been damaged while updating. You would need to submit your console for repair. Contact your local Xbox Support for this issue.

This error might also cause your Xbox One to get bricked.


**Error Codes 80072xxx, 87ddxxxx, 8007019x, 8019019x: Network Issues**

You need to check your internet connection for this error. If you are using a wireless connection, check if the connection is alright. If that does not work you need to have a wired connection. Even if this method does not work, you then need to select ‘Start Update’ again, if you see the error again, press the Xbox button on the front of the console for 5 seconds. The console will shut down.  Unplug the power cord for 30 seconds. This will reset the console’s cache. Turn up your Xbox One again and select ’Start Update’. If this does not work you need to contact your local Xbox support.


**Error Code E203 xxxxxxxx xxxxxxxx**

There are no details on this error. Your best course of action is to contact your local Xbox support.


**Error Code E200 00000116 00000000**

This might happen after you are done installing the game. You might need to uninstall the game and turn off the router. Install the game and turn on the router and try again.


**Error Code 8000001f**

This error pops up when Xbox One SmartGlass on Android won’t connect. You might need to connect both devices on the same network.


**Error Code 0x87DD0006**

This error is due to sign in issues. This error might resolve on its own as it seems to be related to the Xbox Live servers.  



**​​Other Fixes**  



**Problem while updating the Xbox One:**

Some users might face issues while updating the Xbox One. Following the steps below might help you out:

* Check your network connection
* If that is okay, you need to press the Xbox button on the front of the console for 5 seconds.
* This will make sure the console shuts down.
* Then unplug the power cord for 30 seconds. This will reset the console’s cache.
* Turn up your Xbox One again and select ’Start Update’.
* If these steps fail you need to contact support


**Disc Drive Issues:**  


Positioning your Xbox One vertically is not the correct way. You need to place it horizontally. Placing it vertically may damage its Disc Drive.  If you have already damaged your Xbox One’s disc drive then we suggest contacting your local Xbox One support.


**Slow Install Times For Games:**

If your Xbox One games are taking a lot of time to install then you need to be patient. Don’t remove the disc and instead stop the install first. After stopping the install, remove the disc, shut down your Xbox One completely, unplug the console. This will make sure that the console’s cache is cleared. Turn on the console and try installing the disc again.


**Here is another method for game installs stuck at 0%:**

* Go to settings and reset your Xbox One to default factory settings.
* Make sure the game disc is not inserted.
* Once the console resets everything, disconnect your internet.
* Insert the game and now it should start installing.


**Hanging Load Screen:**

This is a normal loading screen but it some cases the screen may remain there forever. You need to be patient as the Xbox One is still working.


**Kinect not working:**

* Try unplugging the power cord.
* With the Kinect plugged in, re-plug the power and turn on the console. If the Kinect is still not detected,
* You should see “Kinect is unplugged” at the top right corner on the Home screen.
* Try clicking on “What else does Kinect see.”

If it still does not work, you need to check out with support.


**How do I find the MAC address of the Xbox One:**

* To get your MAC address so you can get online and set up your Xbox One.
* Let the set up fail, then use the troubleshooter.
* It’ll show you the MAC address.


**Xbox One reboots/restarts:**

Certain players might experience Xbox One restarting when playing a game.

* Unplug your console
* Restart console
* Insert game disc
* Try playing again.

If issue persists please contact Xbox support.


**The Xbox One controller may not be turned on after initial update:**

Switch off the Xbox One and turn it on.


**Ban after using Emergency offline update:**

The emergency offline update is not ready yet. If you install it by mistake your Xbox One might get banned. Hopefully Microsoft will fix it soon.


**Xbox One Dashboard Tiles Images Not Loading:**

It might happen that the images on Xbox One’s Dashboard Tiles won’t load. In order to fix the issue, follow the steps below:

* Open Internet Explorer on Xbox One
* Open your Internet Service Provider’s Hub Page and follow the instructions
* Sign into your ISP account
* Reboot your Xbox One
* Things will load fine now

Note: This works with British Telecom in UK. And this solution may or may not vary for different Internet Service Providers.


**Green Screen of Death**

Many users are reporting that they are getting a ‘Green screen of death’ wherein the Xbox One just hangs on the screen with its logo.  Some users have escaped by simply switching off the consoles off and then turning it on. Unfortunately there is no official word from Microsoft on this. However there are a couple of things you can consider in order to avoid this:

* Use a wired connection
* Be patient and check whether the Xbox One is active. The Kinect sensor is a good indication for this.
* Even if you get passed the Green screen of death and the update stalls, do not shut down your Xbox One. This will prevent bricking of the console.
* If you see no activity on Kinect or Xbox One, it means that it is bad console and you should check out with support.


**Xbox One controller disconnection issues:**

For users facing frequent Xbox One controller disconnection issues, follow the steps below:

* Power off the Xbox One (Power Saving Mode).
* Plug in controller via USB cable.
* Unplug the Kinect cable from the console.
* Plug Kinect cable back into console.
* Power on console.
* Run the Kinect Setup.
* The issue should now be fixed.


**Xbox One Slow/Laggy UI:**

This happens due to a memory dump issue. You can temporary fix it by holding the power button for 10 seconds.​  



  



[​Back to Top](#Top)  



PC​​​




Perform the following steps to troubleshoot game server connectivity on a PC with a wired connection:

 

* Try a different ethernet cord & make sure it is plugged in correctly.
* Perform a netsh and ipconfig reset. Use ResTool, if available, to expedite the process
* Try connecting the computer to a network switch, or directly to the wall if it is already connected through a switch
* Verify that the correct ethernet jack is being used and is active with onsite laptop.  See [KB2952](http://intranet.restech.niu.edu/knowledge.php?action=view&id=2952) to see what jacks should be active in what rooms.
* If the issue is related to Steam login, try to login to Steam on the Surface using that connection, and using WiFi. See [KB2950](http://intranet.restech.niu.edu/knowledge.php?action=view&id=2950) for Steam login information
* If the issue is related to a specific game login, check whether you can perform similar activities in different games.
* Run a DoIT speed test.  If you are unsure what speed results are too slow, check [HERE](https://kb.niu.edu/page.php?id=54641).

 

**Make sure to include the exact steps that you have attempted in the ticket, do not just reference this knowledge base.  This is important to include in case we need to escalate the issue to DoIT.  There may be steps that you think of that are not included in this KB.  Feel free to try these steps and update the KB as needed.**

 



---

 

Occasionally, PCs are able to connect to the network and successfully launch games, but cannot connect to online services.  If this is the case, we need to verify and include the following information in the ticket before requesting referral:

 

* Is the ethernet jack active?
* Run DoIT speed tests.  Include screenshots and record results manually in the text of the ticket as well.
* Record network statistics:
	+ IP address
	+ DNS/Gateway Addresses
	+ MAC (Wired/Wireless)
	+ any other pertinent data
* Record ethernet jack number.
* Record ports that the game uses (can usually be found online).
* Record any error message the game generates.
* Include any other information you may find relevant.​  
​

  



[​Back to Top](#Top)  



Internet Issues  


 ​ 
 ​​Wireless Issues


**WORKING**

If any are not working check that the user's device matches the ones currently in the filter.

Current filters as of January 26, 2013 are listed below, highlighted devices ONLY work with wired connection (Ethernet cable).

Nexus Devices - Wildcard    08:60:6E:\*    10:BF:48:\*    30:85:A9:\*    50:46:5D:\*    E8:92:A4:\*

Microsoft Surface - Wildcard    28:18:78:\*    60:45:BD:\*    D4:BE:D9:\*


Apple TV - Wildcard    00:24:36:\*    58:55:CA:\*    70:56:81:\*    2C:B4:A1:\*    9C:20:7B:\*


Roku - Wildcard    00:0D:4B:\*    CC:6D:A0:\*


Vizio - Wildcard    00:19:9D:\*


Tivo - Wildcard    00:11:D9:\*


Sony Bluray - Wildcard    F0:BF:97:\*


Samsung Bluray - Wildcard    F4:7B:5E:\*

BB Playbook - Wildcard    14:74:11:\*

Galaxy Tab - Wildcard    50:A4:C8:\*    08:08:C2:\*

Motorola Razr - Wildcard    B0:79:94:\*

LG - Wildcard    E8:5B:5B:\*

Blackberry - Wildcard    A0:6C:EC:\*

Samsung S4 - Wildcard    CC:3A:61:\*

Windows 8 Phone - Wildcard    34:C8:03:\*


Playstation 2 & 3 - Wildcard    00:04:1F:\*    00:13:15:\*    00:15:C1:\*    00:1D:0D:\*    00:1F:A7:\*    00:24:8D:\*    A8:E3:EE:\*    FC:0F:E6:\*    28:0D:FC:\*


Xbox & 360 - Wildcard    00:03:FF:\*    00:0D:3A:\*    00:12:5A:\*    00:15:5D:\*    00:50:F2:\*    00:17:FA:\*    00:1D:D8:\*    00:22:48:\*    00:25:AE:\*    7C:ED:8D:\*    7C:1E:52:\*


Nintendo Wii - (The user must have purchased an ethernet adapter for the Wii. Its wireless does not support the WPA2) Wildcard    00:19:FD:\*    00:0B:E6:\*    00:1B:EA:\*    00:17:AB:\*    00:19:1D:\*    00:27:09:\*    00:0E:C6:\*    00:1F:32:\*    A4:5C:27:\*    CC:9E:00:\*



---


**PARTIALLY WORKING**

HP Slate Tablet - Wildcard D0:E7:82:\* (The user needs to download an app called Wireless Connection Manager or Wireless Manager in order to allow them to connect to our network.)



---


**NOT WORKING - WIRELESS**

Nook - The nook has some sort of software glitch in it that causes it to crash and reboot if the user attempts to connect to NIUwireless. Even with the MAC in the filter it is still non-functional. This is a problem with the device itself and not one that we can fix or deal with.

Kindle Wi-Fi or Wi-Fi + 3G  
Xbox 360 S or Xbox wireless networking adapter  
Sony Playstation 3 and Sony PSP  
Nintendo Wii, DS, DSi and 3DS  
Apple TV 1st and 2nd Generation  
Nook v1.5  
Roku HD/XD/XDS Streaming Player  
TiVo Wireless Network Adapter​​  



  




[Back to top​](#Top)  


