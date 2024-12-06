---
title: Effective Strategies to Reduce CPU Load in Excel with VBA
date: 2024-12-01T19:05:38.059Z
updated: 2024-12-06T17:25:26.628Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-00.jpg
---

## Effective Strategies to Reduce CPU Load in Excel with VBA

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [The Question](https://facebook-video-footage.techidaily.com/updated-in-2024-channel-success-strategy-standard-studio-or-beta-edge/)
* [The Answer](https://desktop-recording.techidaily.com/new-innovative-ways-to-record-without-background-sounds-for-2024/)

 If you have a VBA function that turns Microsoft Excel into a CPU munching beast, is it possible to tame things down so that you can continue to use your computer for other activities while Excel is finishing up? Today's SuperUser Q&A post comes to the rescue to help a frustrated reader get Excel back under control.

 Today’s Question & Answer session comes to us courtesy of SuperUser—a subdivision of Stack Exchange, a community-driven grouping of Q&A web sites.

 Alien warrior clip art courtesy of [Clker.com](http://www.clker.com/clipart-alien-warrior.html).

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  The Question

 SuperUser reader learningAsIGo wants to know if there is a way to limit Microsoft Excel's CPU usage while running a VBA script on his computer:

> Is there a way to limit Microsoft Excel's CPU usage when it is running? I have a VBA script that calculates a large amount of giant array formulas. The entire set of calculations takes approximately twenty minutes to complete and uses 100 percent of my CPU. I am unable to use my computer during this time and would rather have Excel 'running in the background' while using about 50 percent of my CPU's capacity so that I can continue to do other things.
> 
> Any suggestions? My computer's operating system is Windows 7 Enterprise 64-bit with a 2007 32-bit version of Excel installed on it.

 Is there a way to limit Microsoft Excel's CPU usage while running VBA functions?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  The Answer

 SuperUser contributor mtone has the answer for us:

> If a VBA function is called from several formulas or if your script generates or forces the recalculation of several formulas, then this should definitely make use of the multi-threaded calculation feature in Microsoft Excel. Respectively, this would either run multiple instances of your VBA function for each formula, or recalculate multiple cells simultaneously while your VBA script is running on a single thread.
> 
> You can limit the number of threads used by Excel to recalculate formulas by going to Options and selecting the Advanced Section, then scrolling down until you reach the Formulas sub-section.
> 
> ![how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-essential-travel-vloggers-the-ultimate-10-list/"><u>[Updated] In 2024, Essential Travel Vloggers The Ultimate 10 List</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-tailor-the-rhythm-of-youtube-videos-desktopmobile-way/"><u>[Updated] Tailor the Rhythm of YouTube Videos - Desktop/Mobile Way</u></a></li>
<li><a href="https://win-answers.techidaily.com/fix-your-discord-playback-issues-effective-strategies-for-stable-streaming-setups/"><u>Fix Your Discord Playback Issues: Effective Strategies for Stable Streaming Setups</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixes-for-spellbreak-game-crashes-on-windows-computers/"><u>Fixes for 'Spellbreak' Game Crashes on Windows Computers</u></a></li>
<li><a href="https://win-answers.techidaily.com/guide-to-overcoming-hurdles-preventing-human-progress-and-advancement/"><u>Guide to Overcoming Hurdles Preventing Human Progress and Advancement</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-honor-x50-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Honor X50 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-prime-gear-for-traditional-animators-needs/"><u>In 2024, Prime Gear for Traditional Animators' Needs</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-youtube-rights-vs-cc-licensing/"><u>In 2024, YouTube Rights Vs. CC Licensing</u></a></li>
<li><a href="https://extra-support.techidaily.com/luminance-hd-evaluation-the-ultimate-decision-for-2024/"><u>Luminance-HD Evaluation The Ultimate Decision for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-incorporating-sound-effects-into-presentations-with-powerpoint-strategies-for-both-windows-and-apple-systems/"><u>New 2024 Approved Incorporating Sound Effects Into Presentations with PowerPoint Strategies for Both Windows and Apple Systems</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-overcoming-ies-webpage-display-issues/"><u>Resolved: Overcoming IE's Webpage Display Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-game-crashes-dealing-with-genshin-impact-error-4201/"><u>Resolving Game Crashes: Dealing with 'Genshin Impact Error #4201'</u></a></li>
<li><a href="https://win-answers.techidaily.com/the-ultimate-guide-overcoming-modern-warfare-e2024s-pc-launch-glitches/"><u>The Ultimate Guide: Overcoming Modern Warfare E2024's PC Launch Glitches</u></a></li>
</ul></div>

