---
title: "Step-by-Step Guide: Creating Accurate Tally Charts with Microsoft Excel"
date: 2024-08-27T23:57:54.094Z
updated: 2024-08-28T23:57:54.094Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/c44b3c2a949ed90a1a74d6b8f5c0458cbf8a943f8d64ce0fc757b91844bd2888.jpg
---

## Step-by-Step Guide: Creating Accurate Tally Charts with Microsoft Excel

### Quick Links

* [Create the Tally system](https://visual-screen-recording.techidaily.com/updated-2024-approved-segmentviewer-study-notes/)
* [Total the Groups of Five](https://tech-recovery.techidaily.com/the-insiders-roadmap-to-online-viewing-how-to-catch-every-moment-of-the-summer-olympics-in-2-groovy-ways/)
* [Total the Leftover Singles](https://facebook-video-share.techidaily.com/scripted-sentiments-for-show-summation-for-2024/)
* [Make the Tally Graph with a Formula](https://extra-tips.techidaily.com/2024-approved-boosting-tiktok-quality-with-smart-zoom-use/)
* [Hide the Helper Columns](https://techidaily.com/best-fixes-for-vivo-y200e-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/)

 A tally graph is a table of tally marks to present the frequency in which something occurred. Microsoft Excel has a large number of built-in chart types available, but it does not have a tally graph option. Fortunately, this can be created using Excel formulas.

 For this example, we want to create a tally graph to visualize the votes received by each person on a list.

![Sample data for the tally graph](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/tally-data.png) 

##  Create the Tally system

 A tally graph is normally presented as four lines followed by a diagonal strikethrough line for the fifth tally. This provides a nice visual grouping.

 It is difficult to replicate this in Excel, so instead, we will group the values by using four pipe symbols and then a hyphen. The pipe symbol is the vertical line above the backslash character on the U.S. or U.K. keyboard.

 So, each group of five will be shown as:

||||-

 And then a single pipe symbol for a single occurrence (1) will appear as:

|

 Type these symbols into cells D1 and E1 on the spreadsheet.

![tally marks in a cell for formula referencing](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/tally-marks.png) 

 We will create the tally graph using formulas and reference these two cells to display the correct tally marks.

##  Total the Groups of Five

 To total the groups of five, we will round the votes value down to the nearest multiple of five and then divide the result by five. We can use the function named FLOOR.MATH to round the value.

 In cell D3, enter the following formula:

=FLOOR.MATH(C3,5)/5

![Total the groups of five](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/floor.math_-1.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
 This rounds the value in C3 (23) down to the nearest multiple of 5 (20) and then divides that result by 5, giving the answer 4.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Total the Leftover Singles

 We now need to calculate what is left over after the groups of five. For this, we can use the MOD function. This function returns the remainder after two numbers are divided.

 In cell E3, enter the following formula:

=MOD(C3,5)

![Calculate the remainder with MOD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/singles.png) 

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
##  Make the Tally Graph with a Formula

 We now know the number of groups of five and also the number of singles to display in the tally graph. We just need to combine them into one row of tally marks.

 To do this, we will use the REPT function to repeat the occurrences of each character the required number of times, and concatenate them.

 In cell F3, enter the following formula:

=REPT($D$1,D3)&REPT($E$1,E3)

![Create a tally graph with REPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/tally-graph-1.png) 

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The REPT function repeats text a specified number of times. We used the function to repeat the tally characters the number of times specified by the groups and singles formulas. We also used the ampersand (&) to concatenate them together.

<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Hide the Helper Columns

 To finish the tally graph, we will hide the helper columns D and E.

 Select columns D and E, right-click, and then choose "Hide."

![Hide the helper columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/hide-columns.png) 

 Our completed tally graph provides a nice visual presentation of the number of votes each person received.

![Completed tally graph in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/completed-tally-graph.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532"><img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-androidiphone-instruction-adding-music-files-to-fb-profile/"><u>[New] In 2024, Android/iPhone Instruction  Adding Music Files to FB Profile</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-keep-your-feed-free-no-fb-vids-here/"><u>[New] In 2024, Keep Your Feed Free  No FB Vids Here</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-world-of-tanks-blitz-keeps-crashing/"><u>[Solved] World of Tanks Blitz Keeps Crashing</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/1716068740162-updated-2024-approved-obs-full-screen-no-more-problem/"><u>[Updated] 2024 Approved  Obs Full-Screen No More Problem!</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-navigating-to-past-facebook-stories-a-step-by-step-mobile-and-laptop-guide/"><u>[Updated] Navigating to Past Facebook Stories  A Step-by-Step Mobile & Laptop Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/affordable-mp3-recording-skype-calls-saved-for-2024/"><u>Affordable MP3 Recording  Skype Calls Saved for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/avoid-compatibility-issues-confirming-your-system-meets-the-new-minimum-cpu-specs-for-vanguard/"><u>Avoid Compatibility Issues: Confirming Your System Meets the New Minimum CPU Specs for Vanguard</u></a></li>
<li><a href="https://win-answers.techidaily.com/banishing-the-blackout-effective-remedies-for-mtg-arena-display-issues/"><u>Banishing the Blackout: Effective Remedies for MTG Arena Display Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/black-ops-cold-war-troubleshooting-guide-overcoming-error-code-887a0005/"><u>Black Ops Cold War Troubleshooting Guide: Overcoming Error Code 887A0005</u></a></li>
<li><a href="https://win-answers.techidaily.com/bug-resolution-keeping-your-gas-station-simulation-stable-on-windows-pcs/"><u>Bug Resolution: Keeping Your Gas Station Simulation Stable on Windows PCs</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-vivo-y100a-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Vivo Y100A Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/common-fixes-for-the-persona-3-reload-failure-to-start-dilemma/"><u>Common Fixes for the Persona 3 Reload Failure to Start Dilemma</u></a></li>
<li><a href="https://win-answers.techidaily.com/complete-solution-for-stable-dauntless-play-on-your-windows-computer/"><u>Complete Solution for Stable Dauntless Play on Your Windows Computer</u></a></li>
<li><a href="https://win-answers.techidaily.com/conquering-startup-hiccups-the-definitive-fixes-for-overwatch-2/"><u>Conquering Startup Hiccups: The Definitive Fixes for Overwatch 2</u></a></li>
<li><a href="https://win-answers.techidaily.com/effortless-fixes-for-common-fortnite-login-errors-get-back-in-the-game-now/"><u>Effortless Fixes for Common Fortnite Login Errors – Get Back in the Game Now!</u></a></li>
<li><a href="https://win-answers.techidaily.com/farewell-to-frames-dropping-deathloops-pc-version-finally-seamless-after-fixes/"><u>Farewell to Frames Dropping - Deathloop's PC Version Finally Seamless After Fixes</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723010281172-fix-unable-to-connect-to-the-live-configuration-servers-error/"><u>Fix: ‘Unable to Connect to the Live Configuration Servers’ Error</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-game-bugs-a-guide-to-correcting-ring-of-elysium-tomb-raider-crashes/"><u>Fixing Game Bugs: A Guide to Correcting Ring of Elysium (Tomb Raider) Crashes</u></a></li>
<li><a href="https://win-answers.techidaily.com/getting-thx-spatial-sound-working-again-in-windows-111n-operating-systems/"><u>Getting Thx Spatial Sound Working Again in Windows 11/1N Operating Systems</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-resolve-the-dark-display-problem-with-epic-games-launcher/"><u>How to Resolve the Dark Display Problem with Epic Games Launcher</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-watch-hulu-outside-us-on-samsung-galaxy-a54-5g-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-spark-creativity-30-unique-video-projects/"><u>In 2024, Spark Creativity  30 Unique Video Projects</u></a></li>
<li><a href="https://win-answers.techidaily.com/master-the-art-of-stable-gaming-top-8-fixes-to-stop-hogwarts-legacy-crash-on-pc-startup/"><u>Master the Art of Stable Gaming: Top 8 Fixes to Stop Hogwarts Legacy Crash on PC Startup</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-stability-in-destiny-2-how-to-deal-with-sudden-server-disconnects/"><u>Mastering Stability in Destiny 2: How to Deal with Sudden Server Disconnects</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-the-pre-launch-fixing-division-2-errors-and-maximizing-performance-for-game-enthusiasts-advice/"><u>Mastering the Pre-Launch: Fixing Division 2 Errors and Maximizing Performance for Game Enthusiasts ( Advice)</u></a></li>
<li><a href="https://win-answers.techidaily.com/optimizing-fps-for-a-smoother-forza-horizon-5-experience-on-computer/"><u>Optimizing FPS for a Smoother Forza Horizon 5 Experience on Computer</u></a></li>
<li><a href="https://win-answers.techidaily.com/outriders-performance-optimization-eliminating-lag-on-your-console-or-pc/"><u>Outriders Performance Optimization: Eliminating Lag on Your Console or PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/smooth-gameplay-ensured-fixing-the-crashes-in-naraka-bladepoint-successfully/"><u>Smooth Gameplay Ensured - Fixing the Crashes in Naraka: Bladepoint Successfully</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722988665527-solve-your-screens-persistent-flutter-fix-the-annoying-flicker/"><u>Solve Your Screen's Persistent Flutter: Fix the Annoying Flicker!</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-troubleshooting-for-battlefield-2e22-and-directx-conflicts/"><u>Step-by-Step Troubleshooting for Battlefield 2E22 and DirectX Conflicts</u></a></li>
<li><a href="https://win-answers.techidaily.com/stop-oxygen-not-included-from-crashing-comprehensive-troubleshooting-guide/"><u>Stop 'Oxygen Not Included' From Crashing - Comprehensive Troubleshooting Guide</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/tech-upgrade-essentials-experience-the-best-with-a-dell-screen-top-tier-anc-earpieces-and-high-definition-webcam/"><u>Tech Upgrade Essentials: Experience the Best with a Dell Screen, Top-Tier ANC Earpieces, and High-Definition Webcam</u></a></li>
<li><a href="https://win-answers.techidaily.com/top-tips-for-preventing-elex-ii-game-crashes-on-pc-solved/"><u>Top Tips for Preventing Elex II Game Crashes on PC – Solved</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-for-update-problems-with-minecraft-native-installer/"><u>Troubleshooting Guide for Update Problems with Minecraft Native Installer</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-fixing-the-dreaded-steamvr-error-308/"><u>Troubleshooting Guide: Fixing the Dreaded SteamVR Error #308</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-cyberpunk-2077-wont-utilize-graphics-card-in-windows-10/"><u>Troubleshooting: Cyberpunk 2077 Won't Utilize Graphics Card in Windows 10</u></a></li>
<li><a href="https://win-answers.techidaily.com/understanding-the-impact-of-season-8-updates-on-fortnites-frame-rate-and-gameplay-experience/"><u>Understanding the Impact of Season 8 Updates on Fortnite's Frame Rate and Gameplay Experience</u></a></li>
<li><a href="https://win-answers.techidaily.com/unlock-your-palworld-account-top-6-hacks-for-fixing-eos-login-difficulties/"><u>Unlock Your Palworld Account: Top 6 Hacks for Fixing EOS Login Difficulties</u></a></li>
<li><a href="https://win-answers.techidaily.com/unstick-your-mass-effect-game-expert-advice-on-eliminating-voice-choppiness-in-legendary-edition/"><u>Unstick Your Mass Effect Game: Expert Advice on Eliminating Voice Choppiness in Legendary Edition</u></a></li>
</ul></div>
