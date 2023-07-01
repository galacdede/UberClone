
 
# How to Upgrade Cisco IP Phone 7941/7961 to SIP Firmware
 
If you have a Cisco IP Phone 7941 or 7961 that runs SCCP (Skinny Call Control Protocol) and you want to use it with a SIP server, you need to upgrade the firmware to SIP. This article will guide you through the steps to do this.
 
**Download File ————— [https://t.co/M4OlDjFQps](https://t.co/M4OlDjFQps)**


 
Before you start, you need to have the following:
 
- A Cisco IP Phone 7941 or 7961 with power supply or PoE port
- A Cisco account with access to software downloads
- A network connection with an active DHCP server
- A SIP server configured and connected to the same network as the phone
- A file transfer client software installed on your computer (e.g. WinSCP)
- Two XML configuration files: dialplan.xml and SEP(MAC).cnf.xml

Here are the steps to upgrade the firmware:
 
Cisco IP Phone 7941/7961 Firmware Load 8.5(4) SCCP[^1^],  Cisco IP Phone 7941G/7961G Firmware version 8.5(4) zip file[^1^],  Cisco Unified CallManager Release Notes for 7941/7961 Firmware 8.5(4)[^1^],  Image Authentication Support for Cisco IP Phone 7941G/7961G[^1^],  Cisco IP Phone Model 7941G/7961G Skinny Client Control Protocol[^1^],  Cisco IP Phone 7941/7961 Firmware Load 8.5(2) SCCP[^2^],  Cisco IP Phone 7941G/7961G Firmware version 8.5(2) zip file[^2^],  Cisco Unified CallManager Release Notes for 7941/7961 Firmware 8.5(2)[^2^],  Compatible Cisco Call Manager Release for 7941/7961 Firmware 8.5(2)[^2^],  Cisco IP Phone Model 7941G/7961G Voice Software download page[^2^],  Cisco Community Forum for 7941 SCCP 8.5(2) Firmware[^3^],  How to install cmterm-7941-7961-sccp.8-5-2 on Cisco Unified CallManager,  How to upgrade or downgrade Cisco IP Phone 7941/7961 Firmware,  How to troubleshoot Cisco IP Phone 7941/7961 Firmware issues,  How to configure Cisco IP Phone 7941/7961 settings,  How to reset Cisco IP Phone 7941/7961 to factory defaults,  How to use Cisco IP Phone 7941/7961 features and functions,  How to register Cisco IP Phone 7941/7961 with Cisco Unified CallManager,  How to backup and restore Cisco IP Phone 7941/7961 data,  How to enable or disable image authentication on Cisco IP Phone 7941/7961,  How to change the display language on Cisco IP Phone 7941/7961,  How to adjust the volume and ringtone on Cisco IP Phone 7941/7961,  How to transfer, hold, or conference calls on Cisco IP Phone 7941/7961,  How to access the directories and services on Cisco IP Phone 7941/7961,  How to use the speakerphone and headset on Cisco IP Phone 7941/7961,  How to update the firmware of multiple Cisco IP Phones using bulk administration tool,  How to compare the features and specifications of Cisco IP Phone models,  How to find the serial number and MAC address of Cisco IP Phone 7941/7961,  How to check the firmware version and device information of Cisco IP Phone 7941/7961,  How to enable or disable secure signaling and media on Cisco IP Phone 7941/7961,  How to customize the background image and ringtone of Cisco IP Phone 7941/7961,  How to use the web interface of Cisco IP Phone 7941/7961 for administration and monitoring,  How to troubleshoot network connectivity issues of Cisco IP Phone 7941/7961,  How to resolve common error messages and codes of Cisco IP Phone 7941/7961,  How to optimize the performance and quality of Cisco IP Phone 7941/7961,  How to integrate Cisco IP Phone 7941/7961 with other applications and devices,  How to use the expansion module with Cisco IP Phone 7941/79611,  How to enable or disable power over ethernet (PoE) on Cisco IP Phone 79411/79611,  How to use the soft keys and navigation buttons on Cisco IP Phone 79411/79611,  How to access the online help and user guide of Cisco IP Phone 79141/79161

1. Log into your Cisco account and go to the software download page for your phone model: [https://software.cisco.com/download/navigator.html?mdfid=269065653&flowid=46196](https://software.cisco.com/download/navigator.html?mdfid=269065653&flowid=46196)
2. Select Session Initiation Protocol (SIP) Software as the software type and download the latest 8.xx software version.
3. Extract the downloaded zip file (e.g. cmterm-7941\_7961-sip.8-5-4.zip) to a new folder on your computer.
4. Edit the dialplan.xml and SEP(MAC).cnf.xml files according to your SIP server settings and phone preferences. You can use the template files provided by E-MetroTel at [https://www.emetrotel.com/tsd/content/convert-cisco-7941g-phone-sccp-skinny-call-control-protocol-sip-protocol](https://www.emetrotel.com/tsd/content/convert-cisco-7941g-phone-sccp-skinny-call-control-protocol-sip-protocol) as a reference.
5. Copy all the files in the folder to the root directory of your TFTP server.
6. Reset your phone to factory default settings by pressing \*\*#\*\* while powering on the phone. Then enter \*\*123456789\*0#\*\* when prompted.
7. The phone will request a new configuration file from the TFTP server and start downloading the new firmware.
8. Wait until the phone completes the upgrade process and reboots.
9. The phone should now be running SIP firmware and ready to register with your SIP server.

Congratulations! You have successfully upgraded your Cisco IP Phone 7941/7961 to SIP firmware.
 8cf37b1e13
 
