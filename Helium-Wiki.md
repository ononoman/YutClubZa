### Helium Support Wiki 

## Since the Kit-Kat upgrade, some devices will not allow you to backup to the external SD card. There is no fix for this. SD card backups are not a supported scenario in Helium.

**_We do not offer refunds because there is free version to try before you buy._**

**_Please note: Helium has never been, nor ever will be, compatible with any device running anything less than Android 4.0_**

**_Please note: Helium has never been, nor ever will be, compatible with Chromebooks_**

**_Also note: Helium is NOT compatible with other backup utilities, nor will ever be._**

**_Helium will NOT backup photos or videos_**

**_Helium will NOT backup system files, widgets or voicemail (visual or otherwise), nor will it backup device specific apps like s-note or s-memo. It will not backup your contacts, those should be backed up to your gmail account_**

**_Helium will NOT backup MMS messages, only SMS_**

**_If you're using a non-root device, you MUST connect to a PC via the USB port of your device to enable ADB backup permissions. HAVING THE PREMIUM KEY WILL NOT REMOVE THIS REQUIREMENT. This will be necessary at every reboot of the device._**

**Before sending an email to support, please take the time to read through the wiki to search for an answer to your issue.**

# Unsupported and Problematic Devices.

* **Any Motorola device** - Helium is NOT available to Motorola devices. This is because Motorola phones have a bug that break Android's backup mechanism. Until this is fixed by Motorola, Helium will not work on those Androids. You can download Helium manually here:
http://download.clockworkmod.com/apks/Backup.apk
If you find that Helium *does* work on your Motorola Android, please notify me.

Update: Helium is working on the [Motorola Droid Turbo](http://forum.xda-developers.com/showpost.php?p=56954372&postcount=8).

* **Some Sony devices** - If you're seeing an issue where Helium is asking for a desktop password, and your device is _not_ encrypted, then you're hitting a known issue with some Sony devices. There is something in the firmware of these devices that prevents Helium from working. This includes the Xperia S and Xperia Z. Sony has *disabled* backup on these devices completely.
* **Asus Transformer** line of devices. All Transformers have an issue in the firmware that causes a Helium backup or restore process to hang. There is no fix or workaround for devices running stock ROM's.
* **Asus Memopad Devices** * A similar issue to the Transformer line of devices. 

# Known Problematic Applications (errors during backup/restore)

* All Google apps.
* Injustice: Gods Among Us
* Entire Plants V. Zombies Franchise
* Need for Speed Franchise
* Candy Crush
* Simpsons Tapped Out
* Furby Boom
* Smurf Village
* Asphalt series
* Later FIFA games
* Temple Run Franchise
* Need for Speed Franchise

# Common Helium Desktop Related Issues

## Having to enable a device even though a Premium licence key has been purchased. 
The issue that you are seeing is not an issue at all. Since you are using a non-root device, you need to enable Helium at every reboot of the device. This is a limitation in Android itself, as it flushes the ADB backup permissions at every boot. Having the premium key doesn't change this fact. 

## Helium Desktop App Installation Errors and solutions - Windows

### .DLL missing error
This error is caused by an elevation issue on your PC. You will need to run the .msi installer file as admin. To do so, right-click the installer and click run as admin. If you don't have that dialog when right-clicking, you will need to do a [Google Search](https://www.google.com/search?q=how+to+run+a+.msi+as+admin+windows&oq=how+to+run+a+.msi+as+admin+windows&aqs=chrome..69i57j0l5.9184j0j7&sourceid=chrome&espv=210&es_sm=122&ie=UTF-8) on how to run a .msi as admin for your version of Windows.

### Windows 8.1 install not working.

This error is caused by an elevation issue on your PC. You will need to run the .msi installer file as admin. To do so, right-click the installer and click run as admin. If you don't have that dialog when right-clicking, you will need to do a [Google Search](https://www.google.com/search?q=how+to+run+a+.msi+as+admin+windows&oq=how+to+run+a+.msi+as+admin+windows&aqs=chrome..69i57j0l5.9184j0j7&sourceid=chrome&espv=210&es_sm=122&ie=UTF-8) on how to run a .msi as admin for your version of Windows.

### .net 2.0 error
Some users experience an error telling them to install .net 2.0 on their systems, even though they are running a higher version of the .net framework. The solution to this is to install .net 3.5, as 4.0 does not contain the necessary files for some reason. It will not harm your system to do so. 

### Helium Desktop App Not Recognizing Your Device 
More than likely, this is a driver issue on your PC. To fix this, we include a universal ADB USB driver with the desktop installer package. Please follow the directions below to make use of it. 

Make sure you have ALL software and drivers for your device uninstalled including Helium desktop, then restart your machine. Then re-download Helium desktop and install ONLY that. During the install, make sure your device is NOT connected via USB. The driver should install to your system, then be used the next time you try to connect your device via USB.

### Additional Troubleshooting
* Make sure that you are connecting directly to your computer via USB, and not using a hub or an extension cable.
* Check your Windows device manager to ensure that there are no driver issues. If there is a yellow triangle by your device, then there is a driver issue that you need to address.
* Try a different USB port and USB cable. USB cables do indeed go bad.

### For LG G2 AND G3 devices only

If you're having difficulty getting the Helium desktop to recognize your device, please follow the steps below.

1.	Install Helium desktop for Windows
2.	Install Helium for Android on your G2
3.	Go here ([http://www.lg.com/us/support-mobile/lg-LGVS980](http://www.lg.com/us/support-mobile/lg-LGVS980)), and download and install the USB driver that LG now has on their site (the default Windows driver won't suffice, even when using ethernet mode)
4.	Plug the G2 into the USB cable connected to your PC, and switch to ethernet mode

## Helium Desktop App Installation Errors and solutions - Mac

### Helium desktop app won't install due to unrecognized developer error
You will need to turn down your security settings to install Helium Desktop

### Helium Desktop app not recognizing your device
Try a different USB port and different USB cable with your computer. Also, disable Kies or HTC Sync software. If that doesn't help, try installing Android File Transfer.

# Common Helium On-Device App Issues and Solutions

### Scheduled backups don't complete because of a screen-lock

If you have a screen lock on your device, Helium will not complete a backup. This is expected behavior. The reason for this is the fact that Helium has to open your device and make it active to perform a backup. If you have security in place to prevent the device from opening, Helium is written to respect that. There is no workaround or alternative method. 

### Backing up to your PC via PC Download

To backup to your PC, use the PC Download feature found in the settings menu of the app on your device. This will launch a server that you can connect to via a browser on your PC provided that your PC and device are on the same network that you own or control. Upon launching the server, it will give you an IP address that you put into the address bar of the browser on your PC. Once you put the IP address into the browser, you will get on screen instructions on how to backup. Once your backup is complete, you will receive a backup.zip file. DO NOT EXPAND THIS FILE. Keep it intact. You will need this zip intact to restore the data. Please note, PC Download is an all or nothing process. Meaning it backs up everything that you tell it to. You cannot restore individual apps in a PC Download backup. The workaround is to make groups of apps to backup, then to rename the zip file so you can keep multiple backups. 

### Restoring a PC Download backup

To restore a PC Download backup, first initiate a PC Download session as described above. Then, when you have connected to your device simply take the backup.zip file you received in the process above and drag and drop it into the window to start the restore process. Please note, the device has to be and active for the process to complete. Any browser should work, but if you have issues please try using Firefox then Chrome in that order. 

### Restoring from a cloud location gives an error and "sends a log to ClockworkMod"
Try logging out then back into the cloud service inside of Helium. To do this, long press the service in the restore and sync side of the app, then logout when the popup appears. After this, go to the backup side of the app and choose ONE app to backup with the cloud service as the destination. Let the backup complete totally then try again.

### App is asking for a "desktop password" (non-Sony device).
More than likely your device is encrypted, which is what would cause Helium to throw this error. Helium does support encrypted devices. With an encrypted device, it is necessary to put your encryption PIN or password into Helium. To do this, go into the settings menu of the app and then click on device encryption password. In the box that pops up, enter your encryption PIN or password. Then, try your backup again.

### Helium ceases to recognize backups 
There are a few reasons for this, listed below;

* You manually moved the Carbon backup folder that is located at the root of your device storage. 
The app stops recognizing backups that are manually moved, as it's an unsupported scenario. There is no workaround or fix for your issue as it is unsupported. In the future, make backups to your PC using the PC Download feature. To backup to your PC, use the PC Download feature found in the settings menu of the app on your device. This will launch a server that you can connect to via a browser on your PC provided that your PC and device are on the same network that you own or control. Upon launching the server, it will give you an IP address that you put into the address bar of the browser on your PC.

* You saved to internal storage than flashed a new ROM onto your device. It is **_never_** advisable to trust internal storage during a flashing session to a new ROM. Always make an off-device backup using PC Download or a cloud location. There is no supported solution to restore backups made to internal storage then flashed over. You can research ADB backup and restore to see if that helps you.

* You made a backup to a removable SD card. Again, not advisable as mounting then re-mounting a physical card between devices is problematic for backups. Use PC Download, a cloud destination or device-to-device sync. 

### Premium Key not being recognized by the app
How did you pay for the app? Did you use the Play store? If so the Premium Key will be in your list of purchased apps. Make sure to install the free version first, then install the Key. If you paid through PayPal, you go into the settings menu of the free version and restore your license using your PayPal email that you used to purchase the app.

**_Please note: We do NOT handle any of the Google Play Store transactions. If you have issues with your purchase through Play, you will need to contact Google directly._**

### Device-to-Device Sync Issue
If you're having issues with device-to-device sync, run through the following list to see if it helps you:

* Make sure both devices are on the same WiFi network that you own and control.
* Make sure both devices are on and active when attempting the sync.
* If one device can see the other, but the other device cannot, try pulling an app from the problem device to the device that can see it. Often times this initiates the handshake necessary for file transfer.
* Make sure that both devices are connected to the same router, and not through any kind of proxy.
* Turn of any and all security apps that might be running on either device.
* Make sure you are using only the Primary user on each device. Android does not support the backing up of secondary users files.

### PC Download issues
If you're having issues with PC Download, please run through the following steps to see if it helps you:

* Turn off any and all security and anti-virus running on your PC or Android device. Many security apps block ports which make it impossible to make a PC Download backup.
* Use the FireFox browser, we've seen the most success with it.
* Make sure the device and the PC are on the same physical network that you own and control. You cannot do this at a Starbucks or other public network.
* If you cannot reach the device, make sure you can ping the IP the device gives from your PC.
* Make sure the device is on and active during the PC Download backup process. The screen MUST stay live during the backup.
* Make smaller backup groups, pushing several gigs of data can be difficult for older routers and networks.
* Be advised, the PC Download process is an "all or nothing" restore process. If you backup 129 apps in one group, you must restore 129 apps using this process. The workaround is to make smaller groups.

### Device MTP/PTP Connection Change Issues

To change the mode that your device connects to your PC in, there are some steps you need to take. Please note that some devices are different in how they handle connection status, meaning you will need to do a Google search on how to switch your device from storage mode to camera mode and back. This is an Android issue rather than a Helium issue.

* Connect your device to your PC via USB.
* In the windowshade of your device, you will have a notification as to what mode you are connected in. Tap that notification.
* You will be brought to the settings area where you can change the mode from MTP to PTP and back.

### Kit-Kat SMS restore procedure

In Kit-Kat, Google has made it that only the default SMS app can write changes to the SMS folder. So to restore messages, Helium has to make itself the default SMS application, write the changes and then switch the default app back. The correct procedure is to allow Helium to become the default SMS app. It will change itself back after restore.

### Misc.

For Linux users, here is an adjusted desktop script that can use 'adb' from standard system locations as well: https://gist.github.com/olesenm/06ee8cdee893c732462a