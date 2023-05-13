---
weight: 0
title: "DISKPART Usage"
description: "DISKPART Usage"
tags: ["Software"]
---

Why u​se DiskPart to clean and format a drive?  
  
When you have an external storage ​drive connected to your Windows 10 PC, such as a USB flash drive or hard drive, or even an SD Card that isn't working correctly because of data corruption or another serious issue. Many times the Format tool may not be able to fix the problem, and this is when DiskPart can come in handy.  
DiskPart is a powerful command-line utility that has been part of Windows for a long time, and it allows you to manage storage devices, partitions, and volumes with features that other tools such as Format or Disk Management can't fix.  
In this Windows 10 guide, we'll walk you through the steps to use DiskPart to successfully clean, format, label, and assign a drive letter using the Command Prompt.  
  
  
How to use DiskPart to clean and format a drive​  
Important: Using DiskPart will completely erase everything on the drive you select, making it impossible to undo any changes. It's crucial that you correctly choose the drive you want to clean and format. We always recommend making a full backup of your system before proceeding.  
Use the Windows key + X keyboard shortcut to open the Power User menu and select Command Prompt (Admin).Connect the drive you want clean and format to your computer.  
  
Type the following command and press Enter:  
  
**diskpart**  
  
Type the following command to list all the available drives and press Enter:  
**list disk**  
Take your time and very carefully, on the output from the previous command, identify the drive you want to clean.  
For example, in the screenshot below, we can see that we have four different drives listed, including Disk 0, which is 30GB, and we can quickly determine that it's the primary system drive. And because we're trying to clean an 8GB drive, we can easily spot that Disk 3 is the drive we need to select.  
Use the following command to select the drive and press Enter:  
**select disk 3**  
Remember to change 3 in the command with the number of the drive you want to clean. If you fail to choose the correct number will erase all the data from the wrong drive.![](https://www.windowscentral.com/sites/wpcentral.com/files/styles/xlarge/public/field/image/2016/06/diskpart-select-disk-windows-10.jpg?itok=Y2AM38RI)  
  
Type the following command to clean the drive and press Enter:  
**clean**  
Type the following command to double-check the drive still selected and press Enter:  
**list disk**  
  
If the drive still selected, you will notice an asterisk (\*) next to the disk.  
Type the following command to create a partition and press Enter:  
**create partition primary**  
Type the following command to select the partition you just created and press Enter:  
**select partition 1**  
  
Type the following command to set the partition active and press Enter:  
**active**  
 ![](https://www.windowscentral.com/sites/wpcentral.com/files/styles/xlarge/public/field/image/2016/06/diskpart-clean-drive-windows-10.jpg?itok=0zOZmSXA)  
  
  
Type the following command to format the partition using NTFS and to set a label, and press Enter:  
**format FS=NTFS label=WC-Drive quick**  
  
Remember to change the WC-Drive in the command with the drive name you want to use.  
Type the following command to assign a drive letter and press Enter:  
  
**assign letter=W**  
  
![](https://www.windowscentral.com/sites/wpcentral.com/files/styles/xlarge/public/field/image/2016/06/diskpart-format-ntfs-windows-10.jpg?itok=8UamFDc5)  
Remember to change W in the command with a letter you want that isn't in use by another drive on This PC.  
  
   
Use the **exit** command to close DiskPart to complete the task.  
  
  
Again, using this guide, remember to take your time and carefully select the drive you want to repair. If you have multiple external drives connected to your computer, it's a good idea to temporary disconnect them before proceeding to reduce the chances of erasing the wrong drive.  
Keep in mind that while there is many other tools to format a drive, DiskPart is likely to be your best choice when you're dealing with data corruption, drive inaccurately showing the storage capacity, and other serious problems.  
  
  
<https://www.windowscentral.com/how-clean-and-format-storage-drive-using-diskpart-windows-10>​  
  
![NIU-Recruiting-Banner.png](/sites/housing/restech_helpdesk/SiteAssets/kb/How%20to%20Use%20DiskPart%20to%20Clean%20and%20Format%20Storage%20Drive/NIU-Recruiting-Banner.png)  
​  
  
​  
  
  
 ​  
  


