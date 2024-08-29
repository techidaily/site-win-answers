---
title: "Mastering Structure: Fundamental Tips on Crafting Formulas in Excel"
date: 2024-08-27T23:56:55.795Z
updated: 2024-08-28T23:56:55.795Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/704c497d76ce3443a342fa34e8883ce74ed2e3eea338695faa58de9221c96a80.jpg
---

## Mastering Structure: Fundamental Tips on Crafting Formulas in Excel

### Quick Links

* [Parts of a Formula](https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-vivo-s18-pro-drfone-by-drfone-virtual-android/)
* [Formula Examples](https://snapchat-videos.techidaily.com/new-2024-approved-from-ephemeral-to-everlasting-the-art-of-saving-social-media-snaps/)
* [Get Help From Excel](https://activate-lock.techidaily.com/in-2024-unlocking-an-icloud-locked-ipad-and-iphone-6s-plus-by-drfone-ios/)

 We're not all mathematicians, but some tasks in Microsoft Excel are best done using formulas. Maybe you're new to writing formulas or are trying but keep [getting confusing errors](https://instagram-videos.techidaily.com/updated-cut-and-paste-success-enhancing-videos-for-instagram-shares/). Here, we'll cover the basics of structuring formulas in Excel.

##  Parts of a Formula

 While the exact elements can vary, a formula can use the following pieces.

**Equal Sign**: All formulas in Excel, and Google Sheets as well, start with an equal sign (=). Once you type it into a cell, you may immediately see suggestions for functions or formulas.

**Cell Reference**: While you can type values directly into formulas (as a constant), it's possible and usually handier to pull values from other cells. An example cell reference is A1, which is the value in column A, row 1\. References can be [relative, absolute](https://some-guidance.techidaily.com/the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery-for-2024/), or mixed.

* **Relative Reference**: This refers to the relative position of the cell. If you use the reference A1 in your formula and change the position of the reference (for example, if you [copy and paste the data](https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-vivo-y100a-drfone-by-drfone-virtual/) somewhere else), the formula updates automatically.
* **Absolute Reference**: This refers to a specific position of the cell. If you use the reference $A$1 in your formula and change the position of the reference, the formula does not update automatically.
* **Mixed Reference**: This refers to a relative column and absolute row or vice versa. For instance, if you use A$1 or $A1 in your formula and change the position of the reference, the formula only updates for the relative column or row automatically.

**Constant**: You can think of a constant as an inserted value. This is a value that you enter directly into the formula instead of or in addition to a cell reference. For example, instead of using A1 in the formula, you might use its value---15.

**Operator**: This is a special character that performs a task. For instance, the ampersand is the text concatenation operator for [combining text strings](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/). Here are a few more:

* **Arithmetic Operators**: These include an asterisk for multiplication and a plus sign for addition.
* **Comparison Operators**: These include a greater than, less than, and equal sign.
* **Reference Operators**: These include a colon to designate a cell range as in A1:A5 and a comma to combine multiple cell ranges as in A1:A5,B1:5.

**Parentheses**: Like in an algebra equation, you may use parentheses to specify the part of the formula to perform first. For instance, if the formula is 

        `=2+2*3`
    
 , the answer is 8 because Excel performs the multiplication portion first. But if you use 

        `=(2+2)*3`
    
 , the answer is 12 because the portion within parentheses is performed before the multiplication.

 Additionally, functions begin with an opening parenthesis, followed by the arguments (references, values, text, arrays, etc.), and finish with the closing parenthesis. Even if nothing appears in the parentheses as in 

        `=TODAY()`
    
 which gives you [the current date](https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-redmi-note-12-5g-by-stellar-photo-recovery-android-mobile-photo-recover/), you must still include the parentheses.

Related: [How to Insert Today's Date in Microsoft Excel](https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-redmi-note-12-5g-by-stellar-photo-recovery-android-mobile-photo-recover/) 

**Function**: A common but not required [part of a formula is a function](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/). As with our above example the TODAY function provides today's date. Excel supports many, many functions for working with numbers, text, lookups, information, and much more.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Formula Examples

 Now that you know the basic parts of a formula, let's look at the syntaxes for some examples.

 Here is a formula to [add the values in two cells](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/). You have the equal sign, first cell reference (relative reference), plus sign (operator), and second reference (relative reference).

=A1+B1

![Formula to add cell references](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/AddCells-ExcelStructureFormulas.png) 

 This formula [adds distinct values](https://instagram-clips.techidaily.com/updated-2024-approved-unveiling-instagrams-policies-a-musicians-legal-primer/) instead. You have the equal sign, first value (constant), plus sign (operator), and second value (constant).

=15+20

![Formula to add numbers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/AddNumbers-ExcelStructureFormulas.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For a function example, you can add the values in a cell range. Start with the equal sign, enter the function followed by an opening parenthesis, insert the first cell in the range, a colon (reference operator), last cell in the range, and finish with the closing parenthesis.

=SUM(A1:A5)

![Formula to add a cell range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/SumRange-ExcelStructureFormulas.png) 

 Another symbol you may see in a formula is a quotation mark. This is commonly used when creating formulas for [working with text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/), although quotes are not exclusive to text. Here's an example.

Related: [9 Useful Microsoft Excel Functions for Working With Text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) 

 You can use the SUBSTITUTE function in Excel to replace certain text with new text. Using this formula, you can substitute Smith for Jones in cell A1:

=SUBSTITUTE(A1,"Jones","Smith")

 As you can see, both the current (Jones) and new (Smith) text are contained within quotation marks.

![Formula to substitute text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/SubstituteFormula-ExcelStructureFormulas.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Get Help From Excel

 It can take time and practice to get the hang of writing formulas. Luckily, Excel does offer some [help when you're using functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) in your formulas.

Related: [How to Find the Function You Need in Microsoft Excel](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
###  Start Your Formula

 If you plan to use a function, you can get a jumpstart on the formula.

 Select the cell where you want the formula, type the equal sign, and enter the first letter or two of the function you want to use. You'll see a drop-down [list of functions](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) that apply.

![Letters entered for a function to display the list](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/StartFunction-ExcelStructureFormulas.png) 

 Double-click the function you want and you'll see the syntax for the formula you need to create.

![Formula for SUM in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/SumSyntax-ExcelStructureFormulas.png) 

 You can then click an argument in the formula and enter or select what you want to use. Follow the formula you see by entering commas or other expected operators until you complete the formula.

![Using the formula for SUM in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/SumFormula-ExcelStructureFormulas.png) 

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  View the Function Library

 Even if you know the function you want, you can take a look at the syntax for the formula ahead of time. This helps you prepare the data if it's not ready.

 Go to the Formulas tab and click "Insert Function" on the left side of the ribbon.

![Insert Function on the Formulas tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/InsertFunctionRibbon-ExcelStructureFormulas.png) 

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Enter the function into the Search box at the top, hit "Go," and then select it from the results.

![Find a function box](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/InsertFunctionSearch-ExcelStructureFormulas.png) 

 You'll then see the expected syntax for the function near the bottom of the window. Plus, you get a description of the function for additional help. Below, you can see what you need for the [COUNT function](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/).

![COUNT function syntax and description in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/InsertFunctionSyntax-ExcelStructureFormulas.png) 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Hopefully these explanations and tips help you create the formulas you need in Microsoft Excel!

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/)

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
<li><a href="https://instagram-video-files.techidaily.com/new-from-start-up-to-success-how-to-register-a-professional-account-on-instagram-for-2024/"><u>[New] From Start-Up to Success  How to Register a Professional Account on Instagram for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-10-leading-non-gamer-screen-recording-alternatives/"><u>[New] In 2024, 10 Leading Non-Gamer Screen Recording Alternatives</u></a></li>
<li><a href="https://printer-issues.techidaily.com/solved-canon-pixma-mp620-printer-driver-not-found-on-windows-10/"><u>[Solved] Canon Pixma MP620 Printer Driver Not Found on Windows 10</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-dayz-keeps-crashing-quickly-and-easily/"><u>[Solved] DayZ Keeps Crashing | Quickly & Easily</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723010468510-solved-outriders-wont-start-on-pc-2022/"><u>[SOLVED] Outriders Won’t Start on PC 2022</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-immersive-storytelling-harnessing-top-10-text-innovations-in-videos/"><u>[Updated] 2024 Approved  Immersive Storytelling  Harnessing Top 10 Text Innovations in Videos</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-exploring-youtubes-regular-income-mechanism-for-2024/"><u>[Updated] Exploring YouTube's Regular Income Mechanism for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-innovative-approaches-to-fb-video-sharing-pcandroid-platforms/"><u>[Updated] In 2024, Innovative Approaches to FB Video Sharing  PC/Android Platforms</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-quick-visual-enhancements-using-portable-lut-tools/"><u>[Updated] Quick Visual Enhancements Using Portable LUT Tools</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-evaluating-inshot-is-it-truly-top-notch/"><u>2024 Approved  Evaluating InShot  Is It Truly Top-Notch?</u></a></li>
<li><a href="https://location-social.techidaily.com/4-most-known-ways-to-find-someone-on-tinder-for-vivo-v30-pro-by-name-drfone-by-drfone-virtual-android/"><u>4 Most-Known Ways to Find Someone on Tinder For Vivo V30 Pro by Name | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/apex-legends-troubleshooting-how-to-resolve-error-code-23-quickly/"><u>Apex Legends Troubleshooting: How to Resolve Error Code 23 Quickly</u></a></li>
<li><a href="https://win-answers.techidaily.com/beat-no-user-found-in-csgo-with-these-5-essential-troubleshooting-tips/"><u>Beat 'No User Found' In CSGO with These 5 Essential Troubleshooting Tips</u></a></li>
<li><a href="https://win-answers.techidaily.com/effective-strategies-to-fix-a-deadly-ark-error-tips-and-tricks/"><u>Effective Strategies to Fix a Deadly Ark Error - Tips & Tricks</u></a></li>
<li><a href="https://hardware-help.techidaily.com/efficiently-update-elan-smbus-drivers-on-windows-free-download-and-steps/"><u>Efficiently Update ELAN SMBus Drivers on Windows: Free Download and Steps</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-and-tricks-to-overcome-alan-wake-2s-persistent-crashes-a-2024-how-to-guide/"><u>Expert Tips and Tricks to Overcome Alan Wake 2'S Persistent Crashes - A 2024 How-To Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-msedgeexe-crashes-troubleshooting-steps-for-stable-edge-browser-experience/"><u>Fixing MsEdge.exe Crashes: Troubleshooting Steps for Stable Edge Browser Experience</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-corsair-icue-dilemma-in-windows-11-a-complete-guide/"><u>Fixing the Corsair iCUE Dilemma in Windows 11 - A Complete Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-frame-rate-drop-in-dying-light-how-gamers-overcame-fps-problems/"><u>Fixing the Frame Rate Drop in Dying Light - How Gamers Overcame FPS Problems</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-frame-rate-drop-in-dying-light-an-ultimate-solution/"><u>Fixing the Frame Rate Drop in Dying Light: An Ultimate Solution</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723004857007-football-manager-2020-stability-improvements-no-more-crashes/"><u>Football Manager 2020 Stability Improvements – No More Crashes</u></a></li>
<li><a href="https://win-answers.techidaily.com/game-changer-alert-solving-the-dark-souls-iii-unwanted-reboots-challenge/"><u>Game-Changer Alert: Solving the Dark Souls III Unwanted Reboots Challenge</u></a></li>
<li><a href="https://win-answers.techidaily.com/guide-fixing-the-issue-of-unresponsive-amd-radeon-graphic-drivers/"><u>Guide: Fixing the Issue of Unresponsive AMD Radeon Graphic Drivers</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-discord-crashing/"><u>How To Fix Discord Crashing</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-dota-2-launching-problems-and-bypass-the-endless-loading-screen/"><u>How to Fix Dota 2 Launching Problems and Bypass the Endless Loading Screen</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-repair-issues-when-using-the-clownfish-audio-alteration-device/"><u>How to Repair Issues When Using the Clownfish Audio Alteration Device</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-apple-iphone-14-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Detect and Remove Spyware on Apple iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-mastering-multimedia-posts-multiphotograph-and-video-uploads-on-instagram/"><u>In 2024, Mastering Multimedia Posts  Multiphotograph & Video Uploads on Instagram</u></a></li>
<li><a href="https://win-answers.techidaily.com/nier-gestalt-and-replicant-collection-boot-up-fixes-achieved/"><u>NieR Gestalt & Replicant Collection Boot-Up Fixes Achieved</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-visual-hitches-fixing-the-dark-display-fault-in-world-war-ii-call-of-duty-game-on-pc/"><u>Overcoming Visual Hitches: Fixing the Dark Display Fault in World War II - Call of Duty Game on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/pc-gaming-made-easy-solutions-for-stability-issues-in-robocop-rupture/"><u>PC Gaming Made Easy: Solutions for Stability Issues in 'Robocop: Rupture'</u></a></li>
<li><a href="https://win-answers.techidaily.com/preventing-your-game-from-crashing-a-guide-for-doom-eternal-players/"><u>Preventing Your Game From Crashing - A Guide for DOOM Eternal Players</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-fixing-issues-with-missing-textures-in-call-of-duty-warzone/"><u>Resolved: Fixing Issues with Missing Textures in Call of Duty: Warzone</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-the-connection-refused-by-anticheat-issue-in-escape-from-tarkov/"><u>Resolving the 'Connection Refused by Anticheat' Issue in Escape From Tarkov</u></a></li>
<li><a href="https://win-answers.techidaily.com/solutions-for-critical-development-bug-in-call-of-dutys-modern-warfare-and-warzone/"><u>Solutions for Critical Development Bug in Call of Duty's Modern Warfare and Warzone</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-tarkov-glitch-steps-to-resolve-the-e-103003-error/"><u>Solving Tarkov Glitch: Steps to Resolve the E-103003 Error</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-the-rainbow-six-siege-not-loading-issue-a-comprehensive-guide/"><u>Solving the 'Rainbow Six Siege Not Loading' Issue - A Comprehensive Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/stop-the-frustration-solving-constant-crashes-in-the-ascent-for-windows-users/"><u>Stop the Frustration: Solving Constant Crashes in 'The Ascent' For Windows Users</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-and-repairing-sons-of-the-forest-crashes-on-your-computer/"><u>Troubleshooting and Repairing Sons of the Forest Crashes on Your Computer</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-and-resolving-frame-rate-drops-in-ac-valhalla-for-windows-gamers/"><u>Troubleshooting and Resolving Frame Rate Drops in AC Valhalla for Windows Gamers</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-fixing-your-logiten-c920-webcam-issues/"><u>Troubleshooting Guide: Fixing Your Logiten C920 Webcam Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-hell-divers-the-twin-heroes-ii-bsod-issue-a-comprehensive-guide/"><u>Troubleshooting Hell Divers The Twin Heroes II BSoD Issue - A Comprehensive Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-steps-to-resolve-bloodhunt-game-lag-and-freezing-issues-on-your-computer/"><u>Troubleshooting Steps to Resolve Bloodhunt Game Lag and Freezing Issues on Your Computer</u></a></li>
<li><a href="https://extra-hints.techidaily.com/ultimate-guide-about-voice-memo/"><u>Ultimate Guide About Voice Memo</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-to-fix-disconnects-and-crashes-in-granblue-fantasy-for-pc-players/"><u>Ultimate Guide to Fix Disconnects and Crashes in Granblue Fantasy for PC Players</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-resolving-issues-with-game-finals-release/"><u>Ultimate Guide: Resolving Issues with Game Finals Release</u></a></li>
<li><a href="https://win-answers.techidaily.com/unlock-kodis-full-potential-address-and-fix-couldnt-retrieve-directory-info-issues-today/"><u>Unlock Kodi's Full Potential: Address and Fix 'Couldn't Retrieve Directory Info' Issues Today</u></a></li>
</ul></div>
