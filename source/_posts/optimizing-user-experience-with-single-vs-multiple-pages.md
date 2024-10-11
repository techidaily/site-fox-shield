---
title: Optimizing User Experience with Single Vs. Multiple Pages
date: 2024-10-07T07:18:04.872Z
updated: 2024-10-11T03:24:34.162Z
tags:
  - user-guide
categories:
  - advancedinstaller
description: This Article Describes Optimizing User Experience with Single Vs. Multiple Pages
thumbnail: https://thmb.techidaily.com/b750413312d41df96b3e21641f92f421092aa15408d61475c9e34aa15be286e0.jpg
---

## Optimizing User Experience with Single Vs. Multiple Pages

Table of Contents

* [Introduction](https://tools.techidaily.com/advancedinstaller/products/)
* [Registration](https://tools.techidaily.com/advancedinstaller/products/)
* [Using Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [GUI](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Working with Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Installer Project](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Product Information](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Product Details](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Digital Signature](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Updater](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Upgrades](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Licensing Page](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [CD/DVD Autorun](https://tools.techidaily.com/advancedinstaller/products/)  
                  * [Multiple Instances Page](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Instance Properties Tab](https://tools.techidaily.com/advancedinstaller/products/)  
                              * [Instance Components Tab](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Resources](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Package Definition](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Requirements](https://tools.techidaily.com/advancedinstaller/products/)  
         * [User Interface](https://tools.techidaily.com/advancedinstaller/products/)  
         * [System Changes](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Server](https://tools.techidaily.com/advancedinstaller/products/)  
         * [Custom Behavior](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Patch Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Merge Module Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Updates Configuration Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Store App Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Modification Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Optional Package Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Windows Mobile CAB Projects](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio Extension Project](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Software Installer Wizards - Advanced Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Visual Studio integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Alternative to AdminStudio/Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Replace Wise](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Migrating from Visual Studio Installer](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Keyboard Shortcuts](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Shell Integration](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Command Line](https://tools.techidaily.com/advancedinstaller/products/)  
   * [Advanced Installer PowerShell Automation Interfaces](https://tools.techidaily.com/advancedinstaller/products/)
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

## Multiple Instances Page

This page allows you to install multiple instances of your product on the target computer. The existence of multiple instances is verified by the [EXE setup file](https://tools.techidaily.com/advancedinstaller/products/). This is why the corresponding option must be checked in the [Configuration Tab](https://tools.techidaily.com/advancedinstaller/products/) page.

![Multiple instances](https://cdn.advancedinstaller.com/img/ui/multiple-instances.png "Multiple instances")  

Windows Installer permits only one instance of the ProductCode to be installed per machine and one instance to be installed per user. Starting with Windows Installer 3.x or later multiple instances can be installed by applying ProductCode transforms (called instance transforms) to the base MSI package.

Advanced Installer creates a transform for each defined instance with the same name as in the “Instance IDs” pane and streams it into the MSI database. When the package runs the Multiple Instances selection dialog displayed by the EXE allows the user to install new instance or maintain an already installed one.

The instances are uniquely distinguished by a new**ProductCode** and additionally by the **InstanceId** property. Other properties can be created in the [Instance Properties](https://tools.techidaily.com/advancedinstaller/products/) page. When the first instance is created the InstanceId property, it is added to the project with "#0" as value for the selected build. You can change it in the [Install Parameters](https://tools.techidaily.com/advancedinstaller/products/) page.

![Note](https://cdn.advancedinstaller.com/svg/common/IconMessageNote.svg)The "#0" value is reserved for the base package.

 Advanced Installer uses the name of an instance from “Instance IDs” pane as the InstanceId property value for the corresponding instance. The InstanceId property **will not** be resolved outside the Multiple Instances page.

### Creating a new instance

 Use the “New Instance” command from the context menu or press the Insert key while the “Instance IDs” panel is selected, in order to create a new instance.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Renaming an instance

 Use the “Rename” command from the context menu or press the F2 key while an element is selected, to rename an instance.

### Removing an instance

 Use the “Delete” command from the context menu, or press the Delete key while an element is selected, to remove an instance.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137211/26400" target="_top" id="2137211">
  <img src="//a.impactradius-go.com/display-ad/26400-2137211" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137211/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Specifying the instances' installation order

Use the “Move Up” / “Move Down” context menu item or press the Shift+Up /Shift+Down keys while an instance is selected.

## Generate instances at install time

This option enables generating custom name instances at install time for the selected build. It implies loosing all previously created instances.

<!-- affiliate ads begin -->
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Build major upgrades for multiple instances

The package is built with major upgrades support. This option has effect only after changing the [Product Version](https://tools.techidaily.com/advancedinstaller/products/). 

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)You cannot author major upgrades and generate instances at install time. The two options above are not compatible.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105867/7443" target="_top" id="2105867">
  <img src="//a.impactradius-go.com/display-ad/7443-2105867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105867/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Topics

* [Instance Properties Tab](https://tools.techidaily.com/advancedinstaller/products/)  
In this tab you can set/overwrite properties for an instance.
* [Instance Components Tab](https://tools.techidaily.com/advancedinstaller/products/)  
In this page you can overwrite components for an instance.

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
<li><a href="https://tiktok-clips.techidaily.com/updated-in-2024-culinary-content-kings-and-queens-of-tiktok/"><u>[Updated] In 2024, Culinary Content Kings & Queens of TikTok</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-top-gamers-screen-guide-best-monitors-at-4k-quality/"><u>[Updated] In 2024, Top Gamers' Screen Guide Best Monitors at 4K Quality</u></a></li>
<li><a href="https://fox-shield.techidaily.com/best-lock-screen-apps-for-windows-8-top-picks-and-feature-comparisons/"><u>Best Lock Screen Apps for Windows 8: Top Picks and Feature Comparisons</u></a></li>
<li><a href="https://fox-shield.techidaily.com/customize-your-experience-with-easy-steps-in-the-user-account-settings-section/"><u>Customize Your Experience with Easy Steps in the User Account Settings Section</u></a></li>
<li><a href="https://fox-that.techidaily.com/efficient-photo-management-combining-identical-pictures-of-the-same-individuals-using-iphone-and-mac-tools/"><u>Efficient Photo Management: Combining Identical Pictures of the Same Individuals Using iPhone & Mac Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-infinix-smart-8-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Infinix Smart 8</u></a></li>
<li><a href="https://techtrends.techidaily.com/issanlilar-arasindaki-yatirim-sistemleri-ve-nakliye-politikalari/"><u>İşsanlılar Arasındaki Yatırım Sistemleri Ve Nakliye Politikaları</u></a></li>
<li><a href="https://discord-videos.techidaily.com/master-class-bots-for-chat-engagement/"><u>Master-Class Bots for Chat Engagement</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-nubia-z50s-pro-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Nubia Z50S Pro Device</u></a></li>
<li><a href="https://fox-shield.techidaily.com/mastering-data-integration-using-the-excel-connection-setup-prompt-effectively/"><u>Mastering Data Integration: Using the Excel Connection Setup Prompt Effectively</u></a></li>
<li><a href="https://fox-shield.techidaily.com/step-by-screen-mirroring-connect-your-huawei-p50-with-a-computer/"><u>Step-by-Screen Mirroring: Connect Your Huawei P50 with a Computer</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-downloading-high-quality-windows-11-wallpapers-and-desktop-backgrounds-hd-4k-for-free/"><u>Step-by-Step Guide: Downloading High-Quality Windows 11 Wallpapers & Desktop Backgrounds (HD, 4K) for Free</u></a></li>
<li><a href="https://fox-shield.techidaily.com/top-rated-hd-recording-software-for-world-of-warcraft-a-comprehensive-guide/"><u>Top-Rated HD Recording Software for World of Warcraft: A Comprehensive Guide</u></a></li>
<li><a href="https://fox-shield.techidaily.com/understanding-and-customizing-excels-edit-trigger-prompt-box/"><u>Understanding and Customizing Excel's Edit Trigger Prompt Box</u></a></li>
</ul></div>

