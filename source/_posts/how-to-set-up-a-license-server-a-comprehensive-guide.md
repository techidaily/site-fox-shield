---
title: "How to Set Up a License Server: A Comprehensive Guide"
date: 2024-10-03T21:43:02.839Z
updated: 2024-10-05T17:54:32.340Z
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148642/16836" target="_top" id="2148642">
  <img src="//a.impactradius-go.com/display-ad/16836-2148642" border="0" alt="https://techidaily.com" width="300" height="50"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148642/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Install the license server

The license server is part of Advanced Installer. You must [download](https://tools.techidaily.com/advancedinstaller/products/) and install the entire application on your server machine. Just copying the license server files over is not enough.

## 2\. Launch the configuration wizard

Launch advinstlicenseserver.exe from the /bin/x86 subfolder of the Advanced Installer install directory.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The license server configuration process requires Administrator privileges.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094482/7443" target="_top" id="2094482">
  <img src="//a.impactradius-go.com/display-ad/7443-2094482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Set a port number

The first setting is the license server port number. It will be used by client Advanced Installer instances to connect to the server.

Set an unused port number in the appropriate field and press \[Next \] button.

![License Server Configuration Wizard](https://cdn.advancedinstaller.com/img/dialog/license-server-config.png "License Server Configuration Wizard")  

The License Server Wizard will automatically check if the specified port is open. It will also configure the Windows Firewall to allow access to this port. If the port is blocked by an external firewall, an error message will be shown.

<!-- affiliate ads begin -->
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Specify your license key

If your server machine has an active Internet connection, you can enter your_License Key_ and press \[Next \]. The wizard will automatically download the license file and finish the configuration.

If no Internet connection is available, you can use the “I would like to register by email” option. We will require your _Computer ID_ along with the License Key to generate and return you a license file.

![Register License Server](https://cdn.advancedinstaller.com/img/dialog/license-server-key.png "Register License Server")  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049364/7443" target="_top" id="2049364">
  <img src="//a.impactradius-go.com/display-ad/7443-2049364" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049364/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Configuring the License Server from Command Line

The License Server could be also configured using Command Line, by calling our tool**advinstlicenseservercli.exe** from the /bin/x86 subfolder of the Advanced Installer install directory.

![Important](https://cdn.advancedinstaller.com/svg/common/IconMessageInfo.svg)**advinstlicenseservercli.exe** requires Administrator privileges so it must be run from an Administrator Command Prompt

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
<a href="https://appsumo.8odi.net/c/5597632/2037318/7443" target="_top" id="2037318">
  <img src="//a.impactradius-go.com/display-ad/7443-2037318" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135372/19272" target="_top" id="2135372">
  <img src="//a.impactradius-go.com/display-ad/19272-2135372" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135372/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 8\. Register using the license server

With a running license server, you can now [register](https://tools.techidaily.com/advancedinstaller/products/) any Advanced Installer instance. Start Advanced Installer, access the “Help > Register” menu inside the application and select the “by using a license server” option.

![Register Advanced Installer](https://cdn.advancedinstaller.com/img/dialog/register-with-server.png "Register Advanced Installer")  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-capture.techidaily.com/new-elevate-zoom-sound-a-guide-to-exceptional-quality-for-2024/"><u>[New] Elevate Zoom Sound A Guide to Exceptional Quality for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-insta-growth-hacks-todays-essential-hashtags-guide/"><u>[Updated] 2024 Approved Insta Growth Hacks Today's Essential Hashtags Guide</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-youtube-video-shooting-equipment-choosing-guide/"><u>[Updated] YouTube Video Shooting Equipment Choosing Guide</u></a></li>
<li><a href="https://fox-shield.techidaily.com/advanced-techniques-in-managing-data-storage-systems/"><u>Advanced Techniques in Managing Data Storage Systems</u></a></li>
<li><a href="https://fox-shield.techidaily.com/comprehensive-guide-to-various-java-development-models/"><u>Comprehensive Guide to Various Java Development Models</u></a></li>
<li><a href="https://fox-shield.techidaily.com/create-your-own-chat-bubbles-with-these-5-awesome-ios-sticker-making-apps-enjoyable-and-straightforward-designing/"><u>Create Your Own Chat Bubbles with These 5 Awesome iOS Sticker Making Apps - Enjoyable and Straightforward Designing!</u></a></li>
<li><a href="https://fox-shield.techidaily.com/deciphering-spear-phishing-vs-traditional-hacking-techniques-what-sets-them-apart/"><u>Deciphering Spear Phishing Vs. Traditional Hacking Techniques: What Sets Them Apart?</u></a></li>
<li><a href="https://fox-shield.techidaily.com/how-to-overcome-issues-editing-converts-of-word-ppt-or-pdf-files/"><u>How to Overcome Issues Editing Converts of Word, PPT, or PDF Files</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-realme-c33-2023-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos from Realme C33 2023 to New Android? | Dr.fone</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-keeping-up-with-aspect-ratios-for-twitter-content/"><u>In 2024, Keeping Up with Aspect Ratios for Twitter Content</u></a></li>
<li><a href="https://video-capture.techidaily.com/mastering-screencasts-a-step-by-step-manual-for-2024/"><u>Mastering Screencasts A Step-by-Step Manual for 2024</u></a></li>
<li><a href="https://fox-shield.techidaily.com/navigating-the-preferences-pane-customizing-mac-os-x-system-controls/"><u>Navigating the Preferences Pane: Customizing Mac OS X System Controls</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/perfectly-prepared-videos-a-guide-to-instagram-fitness/"><u>Perfectly Prepared Videos A Guide to Instagram Fitness</u></a></li>
<li><a href="https://fox-shield.techidaily.com/quick-fixes-how-to-retrieve-deleted-texts-from-an-iphone-with-minimal-hassle/"><u>Quick Fixes: How to Retrieve Deleted Texts From an iPhone with Minimal Hassle</u></a></li>
<li><a href="https://fox-shield.techidaily.com/quickconfigurator-a-powerful-locator-and-editor-for-ini-files/"><u>QuickConfigurator: A Powerful Locator and Editor for INI Files</u></a></li>
<li><a href="https://fox-shield.techidaily.com/simple-steps-adding-srt-captions-to-your-avi-videos-with-ease/"><u>Simple Steps: Adding SRT Captions to Your AVI Videos with Ease</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/troubleshooting-tips-step-by-step-guide-to-overcoming-catchvideo-download-hurdles/"><u>Troubleshooting Tips: Step-by-Step Guide to Overcoming Catchvideo Download Hurdles</u></a></li>
<li><a href="https://extra-information.techidaily.com/unleashing-voice-windows-10-audio-basics/"><u>Unleashing Voice Windows 10 Audio Basics</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1726226686533-wav-movavi/"><u>ウェブ上で効率的なWAV形式へ変換 – 無料Movaviアプリ</u></a></li>
</ul></div>

