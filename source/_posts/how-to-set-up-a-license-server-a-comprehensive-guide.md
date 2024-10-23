---
title: "How to Set Up a License Server: A Comprehensive Guide"
date: 2024-10-17T16:05:40.684Z
updated: 2024-10-22T23:31:36.948Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: "This Article Describes How to Set Up a License Server: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/700293ffdf9a4730d9df7fa5093979f42d9fa58b0347dc31082bc6c29ca2c642.jpg
---

## How to Set Up a License Server: A Comprehensive Guide

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Per-User Subscription](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Team Subscription](https://tools.techidaily.com/advancedinstaller/products/)  
   * [License Server](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Features and Functionality](https://tools.techidaily.com/advancedinstaller/products/)
* [Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Samples](https://tools.techidaily.com/advancedinstaller/products/)
* [How-tos](https://tools.techidaily.com/advancedinstaller/products/)
* [FAQs](https://tools.techidaily.com/advancedinstaller/products/)
* [Windows Installer](https://tools.techidaily.com/advancedinstaller/products/)
* [Deployment Technologies](https://tools.techidaily.com/advancedinstaller/products/)
* [IT Pro](https://tools.techidaily.com/advancedinstaller/products/)
* [MSIX](https://tools.techidaily.com/advancedinstaller/products/)
* [Video Tutorials](https://tools.techidaily.com/advancedinstaller/products/)
* [Advanced Installer Blog](https://tools.techidaily.com/advancedinstaller/products/)
* [Table of Contents](https://tools.techidaily.com/advancedinstaller/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Configuring the License Server

To use an Advanced Installer **floating license** you first need to install and configure the License Server. A running License Server is required when registering your copy of Advanced Installer.

* 1\. [Install the license server](https://tools.techidaily.com/advancedinstaller/products/)
* 2\. [Launch the configuration wizard](https://tools.techidaily.com/advancedinstaller/products/)
* 3\. [Set a port number](https://tools.techidaily.com/advancedinstaller/products/)
* 4\. [Specify your license key](https://tools.techidaily.com/advancedinstaller/products/)
* 5\. [Configuring the License Server from Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * 5.1 [The syntax for configuring the License Server is:](https://tools.techidaily.com/advancedinstaller/products/)  
   * 5.2 [The syntax for restarting the License Server is:](https://tools.techidaily.com/advancedinstaller/products/)  
   * 5.3 [The Syntax for uninstalling the License Server is:](https://tools.techidaily.com/advancedinstaller/products/)
* 6\. [Configure the license server page](https://tools.techidaily.com/advancedinstaller/products/)
* 7\. [Limit access to the license server page](https://tools.techidaily.com/advancedinstaller/products/)
* 8\. [Register using the license server](https://tools.techidaily.com/advancedinstaller/products/)

## 1\. Install the license server

The license server is part of Advanced Installer. You must [download](https://tools.techidaily.com/advancedinstaller/products/) and install the entire application on your server machine. Just copying the license server files over is not enough.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087239/19272" target="_top" id="2087239">
  <img src="//a.impactradius-go.com/display-ad/19272-2087239" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087239/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Launch the configuration wizard

Launch advinstlicenseserver.exe from the /bin/x86 subfolder of the Advanced Installer install directory.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The license server configuration process requires Administrator privileges.

## 3\. Set a port number

The first setting is the license server port number. It will be used by client Advanced Installer instances to connect to the server.

Set an unused port number in the appropriate field and press \[Next \] button.

![License Server Configuration Wizard](https://cdn.advancedinstaller.com/img/dialog/license-server-config.png "License Server Configuration Wizard")  

The License Server Wizard will automatically check if the specified port is open. It will also configure the Windows Firewall to allow access to this port. If the port is blocked by an external firewall, an error message will be shown.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Specify your license key

If your server machine has an active Internet connection, you can enter your_License Key_ and press \[Next \]. The wizard will automatically download the license file and finish the configuration.

If no Internet connection is available, you can use the “I would like to register by email” option. We will require your _Computer ID_ along with the License Key to generate and return you a license file.

![Register License Server](https://cdn.advancedinstaller.com/img/dialog/license-server-key.png "Register License Server")  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Configuring the License Server from Command Line

The License Server could be also configured using Command Line, by calling our tool**advinstlicenseservercli.exe** from the /bin/x86 subfolder of the Advanced Installer install directory.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)**advinstlicenseservercli.exe** requires Administrator privileges so it must be run from an Administrator Command Prompt

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934254/19272" target="_top" id="1934254">
  <img src="//a.impactradius-go.com/display-ad/19272-1934254" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934254/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 5.1 The syntax for configuring the License Server is:

          advinstlicenseservercli.exe   /ConfigureLicenseServer   <floating_license_id>  <license_server_tcp_port>
          

Copy

Parameters:

* **<floating\_license\_id>** \- The License key
* **<license\_server\_tcp\_port>** \- The License Server port number

### 5.2 The syntax for restarting the License Server is:

          advinstlicenseservercli.exe   /RestartLicenseServer  [-stoppreviousservice]
          

Copy

Parameters:

* **\-stoppreviousservice** \- Use this parameter if you have a License Server of an older version of Advanced Installer running on your machine. This will stop the service associated with the old version of the License Server and will start the new version.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006914/19272" target="_top" id="2006914">
  <img src="//a.impactradius-go.com/display-ad/19272-2006914" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006914/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### 5.3 The Syntax for uninstalling the License Server is:

          advinstlicenseservercli.exe  /UninstallLicenseServer
          

Copy

## 6\. Configure the license server page

Access the license server page by going tohttp://\[servername\]:\[port\]/admin in your web browser.

 Check the available registered licenses, add the computers that use them, and set the priority level of each computer. 

Check "Log license incidents" to enable logging the license server. The log is created in %ALLUSERSPROFILE%\\Caphyon\\License Server\\licenseincidents.json on your license server computer. 

![Register License Page](https://cdn.advancedinstaller.com/img/tutorial/license-server-ai/server-page.png "Register License Page")  

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)If one of your computers is a Build Server, or you just want to give priority to a certain computer in case of a simultaneous request to use the license. you could set its**Priority Level** to _Build Server_.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 7\. Limit access to the license server page

Limiting access to the license server page can be done by following these steps: 

1\. Create an empty JSON file in C:\\ProgramData\\Caphyon\\License Server and name it accesslist.json.

2\. Copy and paste the code below into the new JSON.

 "FormatVersion": 1,
 "AccessList": [

     "Path": ["/admin", "/admin.html", "/getlicense"],
     "Deny": [],
     "Allow":[]

]

Copy

3\. Add the IPs of the computers that are allowed access to the license server page; if left empty anyone from your network can access the page.

  "Allow":["11.0.0.1" , "11.0.0.2"]

Copy

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)To deny access to a few specific computers, add their IPs to Deny and leave Allow empty.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)FQDN (fully qualified domain name) is supported in Allow and Deny list. To obtain the FQDN of a computer use _ping -a <ip>_ command line.

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)Using FQDN can delay license acquiring from the server even when the access list is not used. The FQDN resolve can be disabled from Admin panel (http://\[servername\]:\[port\]/admin) by uncheking _Resolve IP to fully qualified domain name (FQDN)_ option.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105867/7443" target="_top" id="2105867">
  <img src="//a.impactradius-go.com/display-ad/7443-2105867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105867/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Register using the license server

With a running license server, you can now [register](https://tools.techidaily.com/advancedinstaller/products/) any Advanced Installer instance. Start Advanced Installer, access the “Help > Register” menu inside the application and select the “by using a license server” option.

![Register Advanced Installer](https://cdn.advancedinstaller.com/img/dialog/register-with-server.png "Register Advanced Installer")  

After specifying the license server host name and port number, you can click\[Next \] to finish the registration. Your current Advanced Installer instance will use one of the available license slots.

![License Server Address](https://cdn.advancedinstaller.com/img/dialog/license-server-access.png "License Server Address")  

![Tip](https://cdn.advancedinstaller.com/svg/common/IconMessageTip.svg)Once an Advanced Installer copy is registered with a license server, it stays permanently registered. You don't need to re-register every time you edit a project.

#### Did you find this page useful?

Please give it a rating:

 Thanks!

#### Report a problem on this page

Information is incorrect or missing

Information is unclear or confusing

Something else

#### Can you tell us what’s wrong?

Send message

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://fox-links.techidaily.com/new-choosing-the-best-mac-mkv-players-guide-for-2024/"><u>[New] Choosing the Best Mac MKV Players Guide for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-5-leading-resources-to-masterfully-add-text-flair-online/"><u>[New] In 2024, 5 Leading Resources to Masterfully Add Text Flair Online</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-mastering-borders-on-instagrams-short-films/"><u>[New] In 2024, Mastering Borders on Instagram's Short Films</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-rotate-videos-for-instagram-a-guide-for-desktop-and-mobile-users-alke-for-2024/"><u>[New] Rotate Videos for Instagram A Guide for Desktop and Mobile Users Alke for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-tricks-for-snagging-youtube-dialogues/"><u>[Updated] In 2024, Tricks for Snagging YouTube Dialogues</u></a></li>
<li><a href="https://fox-shield.techidaily.com/1-supercharge-your-storage-speeds-the-lightning-fast-fix-to-boost-your-languishing-usb-flash-drive-efficiency/"><u>1. Supercharge Your Storage Speeds: The Lightning-Fast Fix to Boost Your Languishing USB Flash Drive Efficiency</u></a></li>
<li><a href="https://fox-shield.techidaily.com/windows-10-outlook-pst/"><u>如何恢复在Windows 지 10에서 손실된 Outlook PST 파일: 두 가지 유용한 방법</u></a></li>
<li><a href="https://fox-shield.techidaily.com/1728507792129-windows-11c/"><u>適用Windows 11的四大轉置程式自C:檔案卡到新目標位址之道</u></a></li>
<li><a href="https://fox-shield.techidaily.com/come-recuperare-partizioni-eliminate-un-manuale-di-ripristino-per-windows-10-e-11/"><u>Come Recuperare Partizioni Eliminate: Un Manuale Di Ripristino per Windows 10 E 11</u></a></li>
<li><a href="https://fox-shield.techidaily.com/datenloschung-an-verschlusselter-datentrager-zwei-ansatze-ohne-passwort-eingabe/"><u>Datenlöschung an Verschlüsselter Datenträger: Zwei Ansätze Ohne Passwort-Eingabe</u></a></li>
<li><a href="https://fox-shield.techidaily.com/expert-tips-for-securely-backing-up-your-raspberry-pi-sd-card-with-windows-tools/"><u>Expert Tips for Securely Backing Up Your Raspberry Pi SD Card with Windows Tools</u></a></li>
<li><a href="https://techidaily.com/hard-reset-nokia-c210-in-3-efficient-ways-drfone-by-drfone-reset-android-reset-android/"><u>Hard Reset Nokia C210 in 3 Efficient Ways | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-enthralling-thesis-fabricator/"><u>In 2024, Enthralling Thesis Fabricator</u></a></li>
<li><a href="https://fox-shield.techidaily.com/iphone-videoubertragung-ohne-qualitatseinbussen-direkt-von-iphone-zu-iphone/"><u>IPhone-Videoübertragung Ohne Qualitätseinbußen – Direkt Von iPhone Zu iPhone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/migration-mastery-moving-from-win7-to-win11/"><u>Migration Mastery: Moving From Win7 to Win11</u></a></li>
<li><a href="https://fox-shield.techidaily.com/1728470397446-windows-1110/"><u>Windows 11/10の日常的なバックアップ手順:ステップバイステップガイド</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/windows-intel-raid-recovery-fixing-a-malfunctioned-raid-controller/"><u>Windows Intel RAID Recovery: Fixing a Malfunctioned RAID Controller</u></a></li>
</ul></div>

