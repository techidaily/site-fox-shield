---
title: Optimizing User Experience with Single Vs. Multiple Pages
date: 2024-10-02T20:53:37.902Z
updated: 2024-10-05T17:39:05.678Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148773/18498" target="_top" id="2148773">
  <img src="//a.impactradius-go.com/display-ad/18498-2148773" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148773/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Creating a new instance

 Use the “New Instance” command from the context menu or press the Insert key while the “Instance IDs” panel is selected, in order to create a new instance.

### Renaming an instance

 Use the “Rename” command from the context menu or press the F2 key while an element is selected, to rename an instance.

### Removing an instance

 Use the “Delete” command from the context menu, or press the Delete key while an element is selected, to remove an instance.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Specifying the instances' installation order

Use the “Move Up” / “Move Down” context menu item or press the Shift+Up /Shift+Down keys while an instance is selected.

## Generate instances at install time

This option enables generating custom name instances at install time for the selected build. It implies loosing all previously created instances.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Build major upgrades for multiple instances

The package is built with major upgrades support. This option has effect only after changing the [Product Version](https://tools.techidaily.com/advancedinstaller/products/). 

![Caution!](https://cdn.advancedinstaller.com/svg/common/IconMessageWarning.svg)You cannot author major upgrades and generate instances at install time. The two options above are not compatible.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997675/19272" target="_top" id="1997675">
  <img src="//a.impactradius-go.com/display-ad/19272-1997675" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997675/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-digital-arcade-over-a-hundred-game-channels/"><u>[New] 2024 Approved Digital Arcade Over a Hundred Game Channels</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-unleashing-creativity-essential-lenses-for-youtube-vloggers/"><u>[New] 2024 Approved Unleashing Creativity Essential Lenses for YouTube Vloggers</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-syncopated-shots-picking-the-best-music-for-social-media/"><u>[New] In 2024, Syncopated Shots Picking the Best Music for Social Media</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-pc-games-memory-freeze-and-capture-6-ways-to-win/"><u>[New] PC Games Memory - Freeze and Capture 6 Ways to Win</u></a></li>
<li><a href="https://fox-shield.techidaily.com/aspects-instead-of-properties-and-rephrasing-to-highlight-key-ideas-such-as-placement-attributes-and-positioning/"><u>Aspects Instead of Properties and Rephrasing to Highlight Key Ideas Such as Placement, Attributes, and Positioning.</u></a></li>
<li><a href="https://fox-shield.techidaily.com/discover-the-essentials-of-iprogid-in-programming/"><u>Discover the Essentials of IProgID in Programming</u></a></li>
<li><a href="https://fox-shield.techidaily.com/effective-techniques-for-capturing-high-quality-voice-conversations/"><u>Effective Techniques for Capturing High-Quality Voice Conversations</u></a></li>
<li><a href="https://fox-shield.techidaily.com/elevate-your-videos-with-top-ranking-free-ai-editors/"><u>Elevate Your Videos with Top-Ranking Free AI Editors</u></a></li>
<li><a href="https://fox-shield.techidaily.com/explore-advanced-photo-customization-with-our-easy-to-use-images-dropdown-menu/"><u>Explore Advanced Photo Customization with Our Easy-to-Use Images Dropdown Menu</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1715859771485-in-2024-how-to-minimize-stress-in-ipad-screen-recordings-heres-a-way/"><u>In 2024, How to Minimize Stress in iPad Screen Recordings? Here's a Way!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-quoras-ai-landscape-how-to-engage-with-chatbots-and-llms-via-poe/"><u>Navigating Quora's AI Landscape: How to Engage with Chatbots and LLMs via Poe</u></a></li>
<li><a href="https://fox-shield.techidaily.com/navigating-url-modifications-with-advanced-edit-link-features/"><u>Navigating URL Modifications with Advanced Edit Link Features</u></a></li>
<li><a href="https://fix-guide.techidaily.com/proven-ways-to-fix-there-was-a-problem-parsing-the-package-on-oneplus-nord-ce-3-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Proven Ways to Fix There Was A Problem Parsing the Package on OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://fox-shield.techidaily.com/recognizing-and-guarding-against-fraudulent-technical-aid-schemes/"><u>Recognizing and Guarding Against Fraudulent Technical Aid Schemes</u></a></li>
<li><a href="https://fox-shield.techidaily.com/step-by-step-tutorial-transforming-jpeg-photos-to-pdf-documents-in-windows/"><u>Step-by-Step Tutorial: Transforming JPEG Photos to PDF Documents in Windows</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-little-giant-of-gaming-laptops-razers-book-13-in-focus/"><u>The Little Giant of Gaming Laptops - Razer's Book 13 in Focus</u></a></li>
<li><a href="https://extra-information.techidaily.com/ultimate-premiere-pro-template-guide-no-cost/"><u>Ultimate Premiere Pro Template Guide - No Cost</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-dts-play-fi-the-basics-explained/"><u>Understanding DTS Play-Fi: The Basics Explained</u></a></li>
<li><a href="https://fox-shield.techidaily.com/understanding-various-methods-of-importing-project-structures/"><u>Understanding Various Methods of Importing Project Structures</u></a></li>
</ul></div>

