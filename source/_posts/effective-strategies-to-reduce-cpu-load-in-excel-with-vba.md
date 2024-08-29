---
title: Effective Strategies to Reduce CPU Load in Excel with VBA
date: 2024-08-27T23:56:11.531Z
updated: 2024-08-28T23:56:11.531Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-00.jpg
---

## Effective Strategies to Reduce CPU Load in Excel with VBA

### Quick Links

* [The Question](https://facebook-video-footage.techidaily.com/updated-in-2024-channel-success-strategy-standard-studio-or-beta-edge/)
* [The Answer](https://desktop-recording.techidaily.com/new-innovative-ways-to-record-without-background-sounds-for-2024/)

 If you have a VBA function that turns Microsoft Excel into a CPU munching beast, is it possible to tame things down so that you can continue to use your computer for other activities while Excel is finishing up? Today's SuperUser Q&A post comes to the rescue to help a frustrated reader get Excel back under control.

 Today’s Question & Answer session comes to us courtesy of SuperUser—a subdivision of Stack Exchange, a community-driven grouping of Q&A web sites.

 Alien warrior clip art courtesy of [Clker.com](http://www.clker.com/clipart-alien-warrior.html).

##  The Question

 SuperUser reader learningAsIGo wants to know if there is a way to limit Microsoft Excel's CPU usage while running a VBA script on his computer:

> Is there a way to limit Microsoft Excel's CPU usage when it is running? I have a VBA script that calculates a large amount of giant array formulas. The entire set of calculations takes approximately twenty minutes to complete and uses 100 percent of my CPU. I am unable to use my computer during this time and would rather have Excel 'running in the background' while using about 50 percent of my CPU's capacity so that I can continue to do other things.
> 
> Any suggestions? My computer's operating system is Windows 7 Enterprise 64-bit with a 2007 32-bit version of Excel installed on it.

 Is there a way to limit Microsoft Excel's CPU usage while running VBA functions?

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  The Answer

 SuperUser contributor mtone has the answer for us:

> If a VBA function is called from several formulas or if your script generates or forces the recalculation of several formulas, then this should definitely make use of the multi-threaded calculation feature in Microsoft Excel. Respectively, this would either run multiple instances of your VBA function for each formula, or recalculate multiple cells simultaneously while your VBA script is running on a single thread.
> 
> You can limit the number of threads used by Excel to recalculate formulas by going to Options and selecting the Advanced Section, then scrolling down until you reach the Formulas sub-section.
> 
> ![how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
---

 Have something to add to the explanation? Sound off in the comments. Want to read more answers from other tech-savvy Stack Exchange users? [Check out the full discussion thread here](http://superuser.com/questions/1025428/limit-excel-cpu-usage).

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
<li><a href="https://win-answers.techidaily.com/2024-tips-rocket-league-keeps-crashing/"><u>[2024 Tips] Rocket League Keeps Crashing</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-adjusting-screenshots-why-does-imovie-alter-video-sizes-in-2024/"><u>[Updated] Adjusting Screenshots  Why Does iMovie Alter Video Sizes, In 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-extents-of-vr-technology/"><u>[Updated] Exploring the Extents of VR Technology</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-honor-x50i-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Honor X50i | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-cutting-edge-tactics-for-flawless-iphones-and-podcast-downloads/"><u>2024 Approved  Cutting-Edge Tactics for Flawless iPhones and Podcast Downloads</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-evaluationcast-breakdown/"><u>2024 Approved  EvaluationCast Breakdown</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-perfect-poster-design-removing-borders-from-canva-images/"><u>2024 Approved  Perfect Poster Design  Removing Borders From Canva Images</u></a></li>
<li><a href="https://win-answers.techidaily.com/comprehensive-strategies-to-solve-your-discord-app-malfunctions/"><u>Comprehensive Strategies to Solve Your Discord App Malfunctions</u></a></li>
<li><a href="https://win-answers.techidaily.com/cracking-down-on-catastrophe-effective-strategies-for-resolving-ark-game-ending-errors/"><u>Cracking Down on Catastrophe: Effective Strategies for Resolving ARK Game-Ending Errors</u></a></li>
<li><a href="https://win-answers.techidaily.com/dead-by-daylight-update-2024-comprehensive-guide-to-resolving-persistent-crashes/"><u>Dead by Daylight Update 2024: Comprehensive Guide to Resolving Persistent Crashes</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-canon-dr-c225-printer-drivers-compatible-with-windows-11-10-and-8/"><u>Download the Canon DR-C225 Printer Drivers: Compatible with Windows 11, 10 & 8</u></a></li>
<li><a href="https://win-answers.techidaily.com/elevate-experience-swift-solutions-to-combat-stutter-and-enhance-fps-in-elden-ring/"><u>Elevate Experience: Swift Solutions to Combat Stutter & Enhance FPS in Elden Ring</u></a></li>
<li><a href="https://win-answers.techidaily.com/eliminate-chrome-stalls-and-glitches-on-windows-10-simple-fix-tips-for-seamless-browsing/"><u>Eliminate Chrome Stalls and Glitches on Windows 10 – Simple Fix Tips for Seamless Browsing</u></a></li>
<li><a href="https://win-answers.techidaily.com/enhanced-battlefield-2042-experience-resolving-the-notorious-pc-lag-and-stuttering-woes/"><u>Enhanced Battlefield 2042 Experience: Resolving the Notorious PC Lag & Stuttering Woes</u></a></li>
<li><a href="https://win-answers.techidaily.com/experience-smooth-gaming-with-these-quick-fixes-for-black-ops-4-initial-launch-hiccups/"><u>Experience Smooth Gaming with These Quick Fixes for 'Black Ops 4' Initial Launch Hiccups</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-on-fixing-timeout-during-your-file-download-sessions/"><u>Expert Tips on Fixing 'Timeout' During Your File Download Sessions</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-issues-how-to-get-your-logitech-g-hub-running-on-windows-again/"><u>Fixing Issues: How To Get Your Logitech G Hub Running On Windows Again</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-issue-unlocking-your-steam-game-files-successfully/"><u>Fixing the Issue: Unlocking Your Steam Game Files Successfully</u></a></li>
<li><a href="https://network-issues.techidaily.com/fixing-the-notorious-gtx-950-code-43-issue-in-windows-11-a-step-by-step-solution/"><u>Fixing the Notorious GTX 950 'Code 43' Issue in Windows 11: A Step-by-Step Solution</u></a></li>
<li><a href="https://win-answers.techidaily.com/forza-horizon-4-startup-problems-beat-them-with-these-proven-techniques/"><u>Forza Horizon 4 Startup Problems? Beat Them with These Proven Techniques</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-combat-high-cpu-and-disk-usage-by-wsappx-a-step-by-step-guide/"><u>How to Combat High CPU & Disk Usage by WSAPPX – A Step-by-Step Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-improve-your-farming-simulator-22-experience-by-boosting-pc-fps-performance/"><u>How To Improve Your Farming Simulator 22 Experience by Boosting PC FPS Performance</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-honor-magic-6-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Honor Magic 6 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-overcome-launch-errors-in-modern-warfare-2-expert-advice-and-fixes/"><u>How to Overcome Launch Errors in Modern Warfare 2: Expert Advice and Fixes</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-troubleshoot-and-fix-pc-issues-in-dragons-dogma-2-crashes/"><u>How to Troubleshoot and Fix PC Issues in Dragon's Dogma 2 Crashes</u></a></li>
<li><a href="https://win-answers.techidaily.com/improved-fps-in-lost-ark-fixing-the-previous-lagging-issues/"><u>Improved FPS in Lost Ark - Fixing the Previous Lagging Issues</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-tecno-pop-7-pro-drfone-by-drfone-virtual/"><u>In 2024, 9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-complete-guide-webinar-software-10-best-webinar-software/"><u>In 2024, Complete Guide Webinar Software  10 Best Webinar Software</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-innovation-unleashed-experience-our-6-best-signature-removers/"><u>In 2024, Innovation Unleashed – Experience Our 6 Best Signature Removers</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-your-disabled-apple-iphone-6-without-itunes-in-5-ways-drfone-by-drfone-ios/"><u>In 2024, Unlock Your Disabled Apple iPhone 6 Without iTunes in 5 Ways | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/los-santos-confidential-resolved-the-missing-pc-release-of-la-noire/"><u>Los Santos Confidential: Resolved – The Missing PC Release of L.A. Noire</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-stability-how-to-prevent-common-titanfall-2-game-crashes/"><u>Mastering Stability: How to Prevent Common Titanfall 2 Game Crashes</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-the-art-of-biomutant-gameplay-overcoming-pc-crashes-with-new-2024-tips-and-techniques/"><u>Mastering the Art of Biomutant Gameplay: Overcoming PC Crashes with New 2024 Tips and Techniques</u></a></li>
<li><a href="https://win-answers.techidaily.com/maximize-performance-addressing-and-resolving-outriders-lag-issues/"><u>Maximize Performance: Addressing and Resolving Outriders' Lag Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723012680848-maximizing-your-experience-in-mass-effect-legendary-edition-unlocking-spectacular-frame-per-second-bonuses/"><u>Maximizing Your Experience in Mass Effect Legendary Edition - Unlocking Spectacular Frame-Per-Second Bonuses</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-armored-core-vi-not-launching-problems-expert-advice-and-fixes/"><u>Overcoming Armored Core VI Not Launching Problems: Expert Advice & Fixes</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-obstacles-comprehensive-fix-for-black-screen-dilemma-in-persona-5-strikers-game/"><u>Overcoming Obstacles: Comprehensive Fix for Black Screen Dilemma in Persona 5 Strikers Game</u></a></li>
<li><a href="https://win-answers.techidaily.com/proven-solutions-for-improving-sims-4-performance-on-pc-updated-guide/"><u>Proven Solutions for Improving Sims 4 Performance on PC (Updated Guide)</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-google-frp-lock-on-asus-rog-phone-8-by-drfone-android-unlock-remove-google-frp/"><u>Remove Google FRP Lock on Asus ROG Phone 8</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-step-by-step-guide-on-reducing-your-back-4-blood-lag/"><u>Resolved: Step-by-Step Guide on Reducing Your 'Back 4 Blood' Lag</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-your-problems-with-non-launching-of-call-of-duty-modern-warfare-ii/"><u>Solving Your Problems with Non-Launching of Call of Duty: Modern Warfare II</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-solution-dealing-with-thaumaturge-game-freezing-on-your-computer/"><u>Step-by-Step Solution: Dealing with Thaumaturge Game Freezing on Your Computer</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-tutorial-for-repairing-battlenet-not-opening/"><u>Step-by-Step Tutorial for Repairing 'Battle.net Not Opening'</u></a></li>
<li><a href="https://win-answers.techidaily.com/swift-solution-guide-fixing-unable-to-start-fortnite-issues/"><u>Swift Solution Guide: Fixing 'Unable to Start Fortnite' Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/top-strategies-for-a-smooth-sims/"><u>Top Strategies for a Smooth Sims</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-ue4-madness-how-to-overcome-outriders-process-crashes-and-keep-playing/"><u>Troubleshooting 'UE4-Madness': How to Overcome Outriders Process Crashes and Keep Playing</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-and-repairing-steams-troublesome-error-130-issue/"><u>Troubleshooting and Repairing Steam's Troublesome Error 130 Issue</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-steps-resolving-internet-explorer-has-crashed-error/"><u>Troubleshooting Steps: Resolving 'Internet Explorer Has Crashed' Error</u></a></li>
<li><a href="https://win-answers.techidaily.com/understanding-and-resolving-version-check-issues-in-ffxiv/"><u>Understanding and Resolving Version Check Issues in FFXIV</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/watch-dogs-legion-evaluation-the-next-chapter-in-a-beloved-franchise/"><u>Watch Dogs: Legion Evaluation – The Next Chapter in a Beloved Franchise</u></a></li>
<li><a href="https://win-answers.techidaily.com/why-isnt-my-pacific-drive-working-diagnose-and-repair-strategies/"><u>Why Isn't My Pacific Drive Working? Diagnose and Repair Strategies</u></a></li>
</ul></div>
