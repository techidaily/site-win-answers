---
title: "Step-by-Step Guide: Crafting a Flexible Dynamic Range in Microsoft Excel"
date: 2024-08-27T23:57:52.933Z
updated: 2024-08-28T23:57:52.933Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/94794ad0266b38c29cc913b5310b6833aba7a42cc29cc084bb2db9c76fd1be31.jpg
---

## Step-by-Step Guide: Crafting a Flexible Dynamic Range in Microsoft Excel

### Quick Links

* [Create a Dynamic Defined Range in Excel](https://screen-activity-recording.techidaily.com/updated-unveiling-the-art-of-smoothing-zoom-screenshots/)
* [Create a Two Way Dynamic Defined Range](https://instagram-video-files.techidaily.com/new-quicken-video-playback-on-instagram-apps-for-2024/)

 Your Excel data changes frequently, so it's useful to create a dynamic defined range that automatically expands and contracts to the size of your data range. Let's see how.

 By using a dynamic defined range, you will not need to manually edit the ranges of your formulas, charts, and PivotTables when data changes. This will happen automatically.

 Two formulas are used to create dynamic ranges: OFFSET and INDEX. This article will focus on using the INDEX function as it is a more efficient approach. OFFSET is a volatile function and can slow down large spreadsheets.

##  Create a Dynamic Defined Range in Excel

 For our first example, we have the single-column list of data seen below.

![Data range to make dynamic](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/one-column-list.png) 

 We need this to be dynamic so that if more countries are added or removed, the range automatically updates.

 For this example, we want to avoid the header cell. As such, we want the range $A$2:$A$6, but dynamic. Do this by clicking Formulas > Define Name.

![Create a defined name in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/define-name-2.png) 

 Type "countries" in the "Name" box and then enter the formula below in the "Refers to" box.

=$A$2:INDEX($A:$A,COUNTA($A:$A))

 Typing this equation into a spreadsheet cell and then copying it into the New Name box is sometimes quicker and easier.

![Using a formula in a defined name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/define-name-details.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
###  How Does This Work?

 The first part of the formula specifies the start cell of the range (A2 in our case) and then the range operator (:) follows.

=$A$2:

 Using the range operator forces the INDEX function to return a range instead of the value of a cell. The INDEX function is then used with the COUNTA function. COUNTA counts the number of non-blank cells in column A (six in our case).

INDEX($A:$A,COUNTA($A:$A))

 This formula asks the INDEX function to return the range of the last non-blank cell in column A ($A$6).

 The final result is $A$2:$A$6, and because of the COUNTA function, it is dynamic, as it will find the last row. You can now use this "countries" defined name inside a Data Validation rule, formula, chart, or wherever we need to reference the names of all the countries.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
##  Create a Two Way Dynamic Defined Range

 The first example was only dynamic in height. However, with a slight modification and another COUNTA function, you can create a range that is dynamic by both height and width.

 In this example, we will be using the data shown below.

![Data for a two way dynamic range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/data-for-two-way-1.png) 

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This time, we will create a dynamic defined range, which includes the headers. Click Formulas > Define Name.

![Create a defined name in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/define-name-2.png) 

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Type '"sales" in the "Name" box and enter the formula below in the "Refers To" box.

=$A$1:INDEX($1:$1048576,COUNTA($A:$A),COUNTA($1:$1))

![Two way dynamic defined range formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/01/second-formula.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 This formula uses $A$1 as the start cell. The INDEX function then uses a range of the entire worksheet ($1:$1048576) to look in and return from.

 One of the COUNTA functions is used to count the non-blank rows, and another is used for the non-blank columns making it dynamic in both directions. Although this formula started from A1, you could have specified any start cell.

 You can now use this defined name (sales) in a formula or as a chart data series to make them dynamic.

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
<li><a href="https://fox-http.techidaily.com/new-audience-accumulation-expedition-tutorials-1mplus-milestone-for-2024/"><u>[New] Audience Accumulation Expedition  Tutorial's 1M+ Milestone for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-mastering-the-art-of-facebook-seo-top-ten-must-knows-for-2024/"><u>[New] Mastering the Art of Facebook SEO  Top Ten Must-Knows for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/eizing-youtubes-algorithm-advantage-with-smart-seo-tactics-for-2024/"><u>[New] Seizing YouTube's Algorithm Advantage with Smart SEO Tactics for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-essential-guide-to-creating-effective-video-loops-on-instagram-for-2024/"><u>[New] The Essential Guide to Creating Effective Video Loops on Instagram for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-visual-polishing-in-meetings-blurring-backgrounds-on-teammeeting/"><u>[New] Visual Polishing in Meetings  Blurring Backgrounds on TeamMeeting</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-warzone-not-using-gpu-on-windows-11/"><u>[SOLVED] Warzone Not Using GPU on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-film-lovers-ultimate-selection-of-stop-motion-works/"><u>[Updated] Film Lovers' Ultimate Selection of Stop-Motion Works</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-next-level-hd-screen-recording-best-brands-showcased/"><u>[Updated] In 2024, Next-Level HD Screen Recording  Best Brands Showcased</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-ae-plug-ins-enhance-your-visual-storytelling/"><u>[Updated] Top AE Plug-Ins  Enhance Your Visual Storytelling</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/2-ways-to-monitor-apple-iphone-7-plus-activity-drfone-by-drfone-virtual-ios/"><u>2 Ways to Monitor Apple iPhone 7 Plus Activity | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-invisible-enthusiast-of-facebook-episodes/"><u>2024 Approved  Invisible Enthusiast of Facebook Episodes</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-visual-effects-to-elevate-your-film-cutting/"><u>2024 Approved  Top Visual Effects to Elevate Your Film Cutting</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-zte-nubia-flip-5g-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix ZTE Nubia Flip 5G System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/ai-integration-microsofts-new-taskbar-helper-in-windows-11-streamlines-tasks/"><u>AI Integration: Microsoft's New Taskbar Helper in Windows 11 Streamlines Tasks</u></a></li>
<li><a href="https://win-answers.techidaily.com/comprehensive-fixes-what-to-do-when-your-razer-synapse-wont-launch/"><u>Comprehensive Fixes: What To Do When Your Razer Synapse Won't Launch</u></a></li>
<li><a href="https://win-answers.techidaily.com/comprehensive-strategies-to-solve-your-discord-app-malfunctions/"><u>Comprehensive Strategies to Solve Your Discord App Malfunctions</u></a></li>
<li><a href="https://win-answers.techidaily.com/cracking-down-on-catastrophe-effective-strategies-for-resolving-ark-game-ending-errors/"><u>Cracking Down on Catastrophe: Effective Strategies for Resolving ARK Game-Ending Errors</u></a></li>
<li><a href="https://win-answers.techidaily.com/eliminate-chrome-stalls-and-glitches-on-windows-10-simple-fix-tips-for-seamless-browsing/"><u>Eliminate Chrome Stalls and Glitches on Windows 10 – Simple Fix Tips for Seamless Browsing</u></a></li>
<li><a href="https://win-answers.techidaily.com/experience-smooth-gaming-with-these-quick-fixes-for-black-ops-4-initial-launch-hiccups/"><u>Experience Smooth Gaming with These Quick Fixes for 'Black Ops 4' Initial Launch Hiccups</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-on-fixing-timeout-during-your-file-download-sessions/"><u>Expert Tips on Fixing 'Timeout' During Your File Download Sessions</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixes-and-solutions-how-to-stop-immortals-of-fenyx-rising-from-crashing/"><u>Fixes and Solutions: How to Stop Immortals of Fenyx Rising From Crashing</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-steady-solutions-improving-your-utorrents-downloading-speeds/"><u>Fixing Steady Solutions: Improving Your uTorrent's Downloading Speeds</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-video-card-error-in-the-sims-4-expert-tips-and-tricks/"><u>Fixing the 'Video Card Error' In The Sims 4: Expert Tips & Tricks</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-issue-unlocking-your-steam-game-files-successfully/"><u>Fixing the Issue: Unlocking Your Steam Game Files Successfully</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/garmin-vivosmart-4-review/"><u>Garmin Vivosmart 4 Review</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-combat-high-cpu-and-disk-usage-by-wsappx-a-step-by-step-guide/"><u>How to Combat High CPU & Disk Usage by WSAPPX – A Step-by-Step Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-improve-your-farming-simulator-22-experience-by-boosting-pc-fps-performance/"><u>How To Improve Your Farming Simulator 22 Experience by Boosting PC FPS Performance</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-permanently-stop-shadowy-downfall-from-happening-on-your-computer/"><u>How to Permanently Stop 'Shadowy Downfall' From Happening on Your Computer</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-advanced-techniques-in-developing-compelling-customer-success-narratives/"><u>In 2024, Advanced Techniques in Developing Compelling Customer Success Narratives</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/in-2024-coherent-and-curated-youtube-playlists-online-and-mobile-assembly-guide/"><u>In 2024, Coherent and Curated YouTube Playlists  Online & Mobile Assembly Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-expertly-curated-5-best-android-screen-capture-options/"><u>In 2024, Expertly Curated 5 Best Android Screen Capture Options</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-fusiontv-services-international-and-home-viewing-unite/"><u>In 2024, FusionTV Services  International & Home Viewing Unite</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-planning-to-use-a-pokemon-go-joystick-on-xiaomi-redmi-note-12-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Planning to Use a Pokemon Go Joystick on Xiaomi Redmi Note 12 4G? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-play-your-srt-files-easily-winmac-tips/"><u>In 2024, Play Your SRT Files Easily  Win/Mac Tips</u></a></li>
<li><a href="https://screen-capture.techidaily.com/inexpensive-pcs-optimized-obs-configuration/"><u>Inexpensive PCs  Optimized OBS Configuration</u></a></li>
<li><a href="https://win-answers.techidaily.com/los-santos-confidential-resolved-the-missing-pc-release-of-la-noire/"><u>Los Santos Confidential: Resolved – The Missing PC Release of L.A. Noire</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-stability-how-to-prevent-common-titanfall-2-game-crashes/"><u>Mastering Stability: How to Prevent Common Titanfall 2 Game Crashes</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721476677741-no-more-headaches-fix-your-iphones-non-detection-issue-with-itunes-or-finder-today/"><u>No More Headaches: Fix Your iPhone's Non-Detection Issue with iTunes or Finder Today!</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-armored-core-vi-not-launching-problems-expert-advice-and-fixes/"><u>Overcoming Armored Core VI Not Launching Problems: Expert Advice & Fixes</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-overwatch-launch-errors-solutions-for-the-infamous-black-screen-trouble/"><u>Overcoming Overwatch Launch Errors: Solutions for the Infamous Black Screen Trouble</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/proven-methods-for-sensational-instagram-puzzle-creation-for-2024/"><u>Proven Methods for Sensational Instagram Puzzle Creation for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/proven-solutions-for-improving-sims-4-performance-on-pc-updated-guide/"><u>Proven Solutions for Improving Sims 4 Performance on PC (Updated Guide)</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-the-4201-glitch-in-genshin-impact-a-comprehensive-guide/"><u>Resolving the 4201 Glitch in Genshin Impact: A Comprehensive Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722982418689-robocop-rogue-city-stuttering-and-crashes-here-are-your-top-fixes-for-smooth-gameplay-on-pc/"><u>RoboCop: Rogue City Stuttering & Crashes? Here Are Your Top Fixes for Smooth Gameplay on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-your-problems-with-non-launching-of-call-of-duty-modern-warfare-ii/"><u>Solving Your Problems with Non-Launching of Call of Duty: Modern Warfare II</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-guide-preventing-manor-lords-from-crashing-on-your-computer/"><u>Step-by-Step Guide: Preventing Manor Lords From Crashing on Your Computer</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-solutions-for-players-struggling-with-pathfinder-wrath-of-the-righteous-startup-issues/"><u>Step-by-Step Solutions for Players Struggling with Pathfinder: Wrath of the Righteous Startup Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/terraria-continues-to-glitch-heres-how-you-can-fix-it-with-simple-hacks/"><u>Terraria Continues to Glitch? Here's How You Can Fix It with Simple Hacks</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-photo-keepers-companion-unlimited-free-options-and-elite-subscription-saviors-for-2024/"><u>The Photo Keeper’s Companion  Unlimited Free Options & Elite Subscription Saviors for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-soundscape-of-influence-altering-voice-on-stories-and-reels/"><u>The Soundscape of Influence  Altering Voice on Stories & Reels</u></a></li>
<li><a href="https://win-answers.techidaily.com/top-strategies-for-a-smooth-sims/"><u>Top Strategies for a Smooth Sims</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transforming-household-routines-a-guide-to-6-productive-applications-for-chatgpt/"><u>Transforming Household Routines: A Guide to 6 Productive Applications for ChatGPT</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-ue4-madness-how-to-overcome-outriders-process-crashes-and-keep-playing/"><u>Troubleshooting 'UE4-Madness': How to Overcome Outriders Process Crashes and Keep Playing</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-and-repairing-steams-troublesome-error-130-issue/"><u>Troubleshooting and Repairing Steam's Troublesome Error 130 Issue</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-logitech-settings-malfunctions-on-pcs/"><u>Troubleshooting Logitech Settings Malfunctions on PCs</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-steps-resolving-internet-explorer-has-crashed-error/"><u>Troubleshooting Steps: Resolving 'Internet Explorer Has Crashed' Error</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-resolving-qbittorrents-performance-issues/"><u>Troubleshooting Tips: Resolving qBittorrent's Performance Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-resolving-vray-application-crashes-on-your-computer/"><u>Ultimate Guide: Resolving 'VRay' Application Crashes on Your Computer</u></a></li>
<li><a href="https://win-answers.techidaily.com/understanding-and-resolving-version-check-issues-in-ffxiv/"><u>Understanding and Resolving Version Check Issues in FFXIV</u></a></li>
<li><a href="https://win-answers.techidaily.com/unlock-smoother-gaming-6-expert-methods-to-increase-frames-per-second-fps-in-apex-legends/"><u>Unlock Smoother Gaming: 6 Expert Methods to Increase Frames Per Second (FPS) in Apex Legends</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-microsoft-video-editor-for-dummies-a-step-by-step-guide-for-2024/"><u>Updated Microsoft Video Editor for Dummies A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/why-isnt-my-pacific-drive-working-diagnose-and-repair-strategies/"><u>Why Isn't My Pacific Drive Working? Diagnose and Repair Strategies</u></a></li>
<li><a href="https://sound-issues.techidaily.com/1723016475106-windows-11-audio-restoration-how-to-bring-back-the-buzz-and-boom/"><u>Windows 11 Audio Restoration: How to Bring Back the Buzz and Boom!</u></a></li>
</ul></div>
