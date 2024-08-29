---
title: "Step-by-Step Guide: Transforming Text Into Dates Within Microsoft Excel"
date: 2024-08-27T23:57:59.953Z
updated: 2024-08-28T23:57:59.953Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/197c2ed369e4a9919f13d946f77f5157856e3dbfa0838cef669c3e3be16ac8df.jpg
---

## Step-by-Step Guide: Transforming Text Into Dates Within Microsoft Excel

### Quick Links

* [Dates that Contain a Full Stop/Period](https://instagram-video-recordings.techidaily.com/updated-in-2024-the-ultimate-guide-to-instagram-desktop-video-upload/)
* [Converting the yyyymmdd Format](https://extra-approaches.techidaily.com/in-2024-step-by-step-tailoring-your-way-to-youtube-subtitles-srt/)
* [DATEVALUE and VALUE Functions](https://hardware-tips.techidaily.com/experience-unmatched-speed-save-75-on-editors-pick-the-elegoo-neptune-4-pro-printer/)

 Analysis of business data often requires working with date values in Excel to answer questions such as "how much money did we make today" or "how does this compare to the same day last week?" And that can be hard when Excel doesn't recognize the values as dates.

 Unfortunately, this is not unusual, especially when multiple users are typing this information, copying and pasting from other systems and importing from databases.

 In this article, we will describe four different scenarios and the solutions to convert the text to date values.

##  Dates that Contain a Full Stop/Period

 Probably one of the most common mistakes beginners make when typing dates into Excel is doing so with the full stop character to separate the day, month, and year.

 Excel will not recognize this as a date value and will go ahead and store it as text. However, you can solve this problem with the Find and Replace tool. By replacing the full stops with slashes (/), Excel will automatically identify the values as dates.

 Select the columns on which you want to perform the find and replace.

![Dates with a full stop separator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/full-stop-dates.png) 

 Click Home > Find & Select > Replace---or press Ctrl+H.

![Find and select values in a column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/find-and-select-1.png) 

 In the Find and Replace window, type a full stop (.) in the "Find what" field and a slash (/) in the "Replace with" field. Then, click "Replace All."

![filling out the find and replace values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/find-and-replace-window-1.png) 

 All full stops are converted to slashes and Excel recognizes the new format as a date.

![Dates with a full stop separator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/full-stop-dates.png) 

 If your spreadsheet data is regularly changing, and you want an automated solution for this scenario, you could use [the SUBSTITUTE function](https://support.office.com/en-us/article/substitute-function-6434944e-a904-4336-a9b0-1e58df3bc332).

=VALUE(SUBSTITUTE(A2,".","/"))

 The SUBSTITUTE function is a text function, so cannot convert it to a date on its own. The VALUE function will convert the text value to a numeric value.

 The results are shown below. The value needs to be formatted as a date.

![SUBSTITUTE formula to convert text to dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/substitute-resized-1.png) 

 You can do this using the "Number Format" list on the "Home" tab.

![Formatting number as a date](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/number-format-2.png) 

 The example here of a full stop delimiter is typical. But you can use the same technique to replace or substitute any delimiter character.

##  Converting the yyyymmdd Format

 If you receive dates in the format shown below, it will require a different approach.

![Dates in the yyyymmdd format](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/yyyymmdd-format.png) 

 This format is quite standard in technology as it removes any ambiguity about how different countries store their date values. However, Excel will not initially understand it.

 For a quick manual solution, you could [use Text to Columns](https://ios-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-apple-iphone-14-pro-for-parents-drfone-by-drfone-virtual-ios/).

 Select the range of values you need to convert and then click Data > Text to Columns.

![Text to Columns button from the Data tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/text-to-columns-resized.png) 

 The Text to Columns wizard appears. Click "Next" on the first two steps so that you are at step three, as shown in the image below. Choose Date and then select the date format being used in the cells from the list. In this example, we are dealing with a YMD format.

![Text to Columns to convert 8 digit numbers to dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/text-to-columns-date-format-3.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you would like a formula solution, then you could use the Date function to construct the date.

 This would be used alongside the text functions Left, Mid and Right to extract the three parts of a date (day, month, year) from the cell contents.

 The formula below shows this formula using our sample data.

=DATE(LEFT(A2,4),MID(A2,5,2),RIGHT(A2,2))

![Using the DATE formula with 8 digit numbers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/date-formula-resized.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Using either of these techniques, you can convert any eight-digit number value. For example, you might receive the date in a ddmmyyyy format or a mmddyyyy format.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
##  DATEVALUE and VALUE Functions

 Sometimes the problem is not caused by a delimiter character but has an awkward date structure simply because it is stored as text.

 Below is a list of dates in a variety of structures, but they are all recognizable to us as a date. Unfortunately, they have been stored as text and need converting.

![Dates stored as text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/text-dates.png) 

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
 For these scenarios, it is easy to convert using a variety of techniques.

 For this article, I wanted to mention two functions to handle these scenarios. They are DATEVALUE and VALUE.

 The DATEVALUE function will convert text into a date value (probably saw that coming), while the VALUE function will convert text into a generic number value. The differences between them are minimal.

 In the image above, one of the values contains time information as well. And that will be a demonstration of the functions' minor differences.

 The DATEVALUE formula below would convert each one to a date value.

=DATEVALUE(A2)

![DATEVALUE function to convert to date values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/datevalue-resized.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 Notice how the time was removed from the result in row 4\. This formula strictly returns just the date value. The result will still need to be formatted as a date.

 The following formula uses the VALUE function.

=VALUE(A2)

![VALUE function to convert text to numeric values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/value-resized.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 This formula will produce the same results except for in row 4, where the time value is also maintained.

 The results can then be formatted as date and time, or as a date to hide the time value (but not remove).

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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-picture-in-progressive-screen-mastery-for-chrome-users-across-platforms/"><u>[New] 2024 Approved  Picture in Progressive Screen Mastery for Chrome Users Across Platforms</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-basic-win10-screen-save-program/"><u>[New] Basic Win10 Screen Save Program</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-step-by-step-placing-titles-on-video-clips-with-windows-photos/"><u>[New] Step-by-Step  Placing Titles on Video Clips with Windows Photos</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-mac-high-quality-video-and-audible-recording/"><u>[Updated] 2024 Approved  Mac High-Quality Video & Audible Recording</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-hidden-gems-galore-top-10-unique-meme-webpages-for-2024/"><u>[Updated] Hidden Gems Galore – Top 10 Unique Meme Webpages for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-crafting-a-journalistic-closing-statement/"><u>[Updated] In 2024, Crafting a Journalistic Closing Statement</u></a></li>
<li><a href="https://buynow-info.techidaily.com/asus-vivobook-11-review-the-ideal-choice-for-portability-and-cost-efficiency-in-a-sleek-package/"><u>ASUS VivoBook 11 Review: The Ideal Choice for Portability & Cost-Efficiency in a Sleek Package</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722995337258-avoid-crashing-vrchat-on-your-desktop-discover-the-ultimate-8-fixes/"><u>Avoid Crashing VRChat on Your Desktop: Discover the Ultimate 8 Fixes!</u></a></li>
<li><a href="https://win-answers.techidaily.com/beat-the-bug-effective-ways-to-prevent-titanfall-2-crashes-now/"><u>Beat the Bug: Effective Ways to Prevent Titanfall 2 Crashes Now</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723010058412-beat-the-lag-in-black-ops-cold-war-solve-your-shader-compiling-glitches-now/"><u>Beat the Lag in Black Ops Cold War - Solve Your Shader Compiling Glitches Now!</u></a></li>
<li><a href="https://win-answers.techidaily.com/cyberpunk-2077-performance-boosted-overcoming-previous-fps-drops/"><u>Cyberpunk 2077 Performance Boosted – Overcoming Previous FPS Drops</u></a></li>
<li><a href="https://win-answers.techidaily.com/dayz-frame-rate-booster-rapid-results-for-smoother-gameplay/"><u>DayZ Frame Rate Booster - Rapid Results for Smoother Gameplay!</u></a></li>
<li><a href="https://win-answers.techidaily.com/effective-solutions-for-unstoppable-freezing-problems-with-pacificdrive-pc-application/"><u>Effective Solutions for Unstoppable Freezing Problems with PacificDrive PC Application</u></a></li>
<li><a href="https://win-answers.techidaily.com/effortless-fix-for-ashen-hitch-quick-and-reliable-tips-inside/"><u>Effortless Fix for Ashen Hitch: Quick & Reliable Tips Inside</u></a></li>
<li><a href="https://win-answers.techidaily.com/escaping-frustration-a-comprehensive-fix-for-fortnite-error-84-party-connection-problems/"><u>Escaping Frustration: A Comprehensive Fix for Fortnite Error 84 - Party Connection Problems</u></a></li>
<li><a href="https://win-answers.techidaily.com/fix-high-latency-in-valheim-on-your-windows-pc-ultimate-guide/"><u>Fix High Latency in Valheim on Your Windows PC: Ultimate Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/groundwork-on-image-detail-a-novices-reference-for-2024/"><u>Groundwork on Image Detail  A Novice's Reference for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Nokia C300 | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-and-solve-modern-warfare-2-failure-to-launch-issue/"><u>How to Fix and Solve 'Modern Warfare 2 Failure to Launch Issue'</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-ryzen-master-driver-not-installed-properly/"><u>How to Fix Ryzen Master Driver Not Installed Properly</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Realme Narzo 60x 5G | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-simulate-gps-movement-in-ar-games-on-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>How to Simulate GPS Movement in AR games On Samsung Galaxy S23 Ultra? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-7-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 7 Plus Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/improved-stability-and-fewer-freezes-whats-freshly-updated-on-new-world/"><u>Improved Stability and Fewer Freezes: What's Freshly Updated on New World</u></a></li>
<li><a href="https://win-answers.techidaily.com/improving-graphics-stability-to-fix-frame-drops-in-fortnite-on-pc/"><u>Improving Graphics Stability to Fix Frame Drops in Fortnite on PC</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-excellent-text-plugin-compendium/"><u>In 2024, Excellent Text Plugin Compendium</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-oppo-a78-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Oppo A78? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/leading-6-low-cost-superior-4k-tv-projectors-for-2024/"><u>Leading 6 Low-Cost, Superior 4K TV Projectors for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/lenovo-100s-drivers-update-easily/"><u>Lenovo 100S Drivers Update Easily</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-combine-multiple-avi-files-into-one-10-best-free-freeware-for-2024/"><u>New Combine Multiple AVI Files Into One 10 Best Free Freeware for 2024</u></a></li>
<li><a href="https://driver-error.techidaily.com/optimize-bluetooth-drivers-make-windows-work-better/"><u>Optimize Bluetooth Drivers, Make Windows Work Better!</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcome-the-resolved-pc-issues-in-biomutant-essential-hacks-and-fixes/"><u>Overcome the [Resolved] PC Issues in Biomutant: Essential Hacks & Fixes</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-msvcr110dll-error-in-helldivers-2-a-detailed-walkthrough/"><u>Overcoming 'MSVCR110.dll' Error in Helldivers 2 - A Detailed Walkthrough</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-dolby-atmos-playback-errors-in-window-10-and-11-environments/"><u>Overcoming Dolby Atmos Playback Errors in Window 10 and 11 Environments</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-launch-problems-with-steam-titles-on-windows-11-systems/"><u>Overcoming Launch Problems with Steam Titles on Windows 11 Systems</u></a></li>
<li><a href="https://win-answers.techidaily.com/resident-evil-village-troubleshooting-get-the-game-running-smoothly-again/"><u>Resident Evil Village Troubleshooting: Get the Game Running Smoothly Again</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-issues-with-fifa-21-game-initialization-and-launch/"><u>Resolved: Issues with FIFA 21 Game Initialization and Launch</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-shadowplay-issues-how-to-fix-non-recording-problems-in-windows/"><u>Resolving ShadowPlay Issues: How to Fix Non-Recording Problems in Windows</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-oneplus-12-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For OnePlus 12</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723003273064-speeding-up-your-gameplay-in-assassins-creed-valhalla-fix-the-lags-swiftly/"><u>Speeding Up Your Gameplay in Assassin's Creed Valhalla: Fix the Lags Swiftly!</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/toms-tech-insights-comprehensive-guides-on-hardware/"><u>Tom's Tech Insights: Comprehensive Guides on Hardware</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-why-is-gpeditmsc-missing-on-your-windows-home-edition/"><u>Troubleshooting Guide: Why Is 'gpedit.msc' Missing on Your Windows Home Edition?</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-utorrent-issues-top-7-quick-fix-strategies-for-non-responsiveness/"><u>Troubleshooting Utorrent Issues: Top 7 Quick Fix Strategies for Non-Responsiveness</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-fixes-for-stuttering-and-crashing-during-zivf-dead-war-saves/"><u>Ultimate Fixes for Stuttering and Crashing During 'ZIVF: Dead War' Saves</u></a></li>
</ul></div>
