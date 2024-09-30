---
title: Optimizing User Experience with Single Vs. Multiple Pages
date: 2024-09-28T09:05:27.828Z
updated: 2024-09-30T04:07:58.330Z
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

### Renaming an instance

 Use the “Rename” command from the context menu or press the F2 key while an element is selected, to rename an instance.

<!-- affiliate ads begin -->
<span id="1975555">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975555.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975555">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975555.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975555%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975555/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Removing an instance

 Use the “Delete” command from the context menu, or press the Delete key while an element is selected, to remove an instance.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044583/7443" target="_top" id="2044583">
  <img src="//a.impactradius-go.com/display-ad/7443-2044583" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044583/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Specifying the instances' installation order

Use the “Move Up” / “Move Down” context menu item or press the Shift+Up /Shift+Down keys while an instance is selected.

## Generate instances at install time

This option enables generating custom name instances at install time for the selected build. It implies loosing all previously created instances.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Build major upgrades for multiple instances

The package is built with major upgrades support. This option has effect only after changing the [Product Version](https://tools.techidaily.com/advancedinstaller/products/). 

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)You cannot author major upgrades and generate instances at install time. The two options above are not compatible.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-crafting-captivating-animations-creating-gifs-from-your-favorite-youtube-videos/"><u>[New] In 2024, Crafting Captivating Animations Creating GIFs From Your Favorite YouTube Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-unlocking-success-with-instagrams-business-platform/"><u>2024 Approved Unlocking Success with Instagram's Business Platform</u></a></li>
<li><a href="https://driver-error.techidaily.com/acemagic-commemorates-may-4th-with-a-special-edition-x-wing-themed-gaming-pc-for-enthusiasts/"><u>AceMagic Commemorates May 4Th with a Special Edition X-Wing Themed Gaming PC for Enthusiasts</u></a></li>
<li><a href="https://fox-shield.techidaily.com/download-mylifetime-show-episodes-as-mp4-files-easy-guide-and-best-tools/"><u>Download MyLifetime Show Episodes as MP4 Files - Easy Guide & Best Tools</u></a></li>
<li><a href="https://fox-shield.techidaily.com/download-your-favorite-bbc-iplayer-shows-as-mp4-or-avi-files-with-our-top-downloading-tool/"><u>Download Your Favorite BBC iPlayer Shows as MP4 or AVI Files with Our Top Downloading Tool</u></a></li>
<li><a href="https://fox-shield.techidaily.com/efficient-media-converter-save-your-mediasite-files-as-mp4-mov-or-avi-with-ease/"><u>Efficient Media Converter: Save Your Mediasite Files as MP4, MOV or AVI with Ease</u></a></li>
<li><a href="https://fox-shield.techidaily.com/exploring-the-leading-5-video-grabber-apps-for-both-mac-os-x-and-microsoft-windows-platforms/"><u>Exploring the Leading 5 Video Grabber Apps for Both Mac OS X and Microsoft Windows Platforms</u></a></li>
<li><a href="https://fox-shield.techidaily.com/free-art-lessons-comprehensive-downloads-of-annamasonartcom-courses-and-video-guides/"><u>Free Art Lessons: Comprehensive Downloads of AnnamasonArt.com Courses and Video Guides</u></a></li>
<li><a href="https://fox-shield.techidaily.com/free-downloads-ted-talks-and-episodes-on-macwindows-watch-now/"><u>Free Downloads: TED Talks & Episodes on Mac/Windows - Watch Now!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mkv-files-on-redmi-note-12-5g-by-aiseesoft-video-converter-play-mkv-on-android/"><u>How do you play MKV files on Redmi Note 12 5G?</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-infinix-note-30-vip-racing-edition-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Infinix Note 30 VIP Racing Edition?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/how-to-resolve-the-integration-difficulty-of-chatgpt-with-plugin-services/"><u>How To Resolve the Integration Difficulty of ChatGPT with Plugin Services</u></a></li>
<li><a href="https://driver-install.techidaily.com/maximize-huion-h420-upgrading-for-windows-users/"><u>Maximize Huion H420: Upgrading for Windows Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/trendy-themes-cool-wallpapers-for-your-desktop/"><u>Trendy Themes Cool Wallpapers for Your Desktop</u></a></li>
</ul></div>

