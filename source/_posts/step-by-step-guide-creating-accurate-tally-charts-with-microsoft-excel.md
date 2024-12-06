---
title: "Step-by-Step Guide: Creating Accurate Tally Charts with Microsoft Excel"
date: 2024-12-04T17:49:48.359Z
updated: 2024-12-06T17:12:12.251Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/c44b3c2a949ed90a1a74d6b8f5c0458cbf8a943f8d64ce0fc757b91844bd2888.jpg
---

## Step-by-Step Guide: Creating Accurate Tally Charts with Microsoft Excel

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 We will create the tally graph using formulas and reference these two cells to display the correct tally marks.

##  Total the Groups of Five

 To total the groups of five, we will round the votes value down to the nearest multiple of five and then divide the result by five. We can use the function named FLOOR.MATH to round the value.

 In cell D3, enter the following formula:

=FLOOR.MATH(C3,5)/5

![Total the groups of five](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/floor.math_-1.png) 

 This rounds the value in C3 (23) down to the nearest multiple of 5 (20) and then divides that result by 5, giving the answer 4.

##  Total the Leftover Singles

 We now need to calculate what is left over after the groups of five. For this, we can use the MOD function. This function returns the remainder after two numbers are divided.

 In cell E3, enter the following formula:

=MOD(C3,5)

![Calculate the remainder with MOD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/singles.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Make the Tally Graph with a Formula

 We now know the number of groups of five and also the number of singles to display in the tally graph. We just need to combine them into one row of tally marks.

 To do this, we will use the REPT function to repeat the occurrences of each character the required number of times, and concatenate them.

 In cell F3, enter the following formula:

=REPT($D$1,D3)&REPT($E$1,E3)

![Create a tally graph with REPT](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/tally-graph-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_dOmuXhsV6Y?si=aT6vgPbDx4ajjvdr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The REPT function repeats text a specified number of times. We used the function to repeat the tally characters the number of times specified by the groups and singles formulas. We also used the ampersand (&) to concatenate them together.

##  Hide the Helper Columns

 To finish the tally graph, we will hide the helper columns D and E.

 Select columns D and E, right-click, and then choose "Hide."

![Hide the helper columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/hide-columns.png) 

 Our completed tally graph provides a nice visual presentation of the number of votes each person received.

![Completed tally graph in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/completed-tally-graph.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://win-answers.techidaily.com/solution-guide-defeat-dev-error-6068-mastering-the-fix-for-microsoft-wow64-issue-on-fortnite-battle-royale-2024-techniques/"><u>[Solution Guide] Defeat Dev Error #6068: Mastering the Fix for Microsoft WOW64 Issue on Fortnite Battle Royale - 2024 Techniques</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-social-stream-top-8-viral-videos/"><u>[Updated] 2024 Approved Social Stream Top 8 Viral Videos</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-step-by-step-guide-iphone-picture-perfection/"><u>[Updated] 2024 Approved Step-by-Step Guide IPhone Picture Perfection</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-seamless-integration-facebook-livestream-and-roku-connected-tv/"><u>2024 Approved Seamless Integration Facebook Livestream & Roku Connected TV</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-metodos-efectivos-para-comprimir-un-archivo-de-video-mov-y-minimizar-su-tamano/"><u>5 Métodos Efectivos Para Comprimir Un Archivo De Video MOV Y Minimizar Su Tamaño</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/clarifying-the-turing-test-concepts-and-future-contenders/"><u>Clarifying the Turing Test Concepts and Future Contenders</u></a></li>
<li><a href="https://win-answers.techidaily.com/comprehensive-teardown-troubleshooting-end-crash-issues-forever/"><u>Comprehensive Teardown Troubleshooting: End Crash Issues Forever!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/experience-the-ultimate-bargain-get-apple-airtags-for-24-less-per-pack-during-walmarts-labor-day-sale-featured-by-zdnet/"><u>Experience the Ultimate Bargain: Get Apple AirTags for $24 Less per Pack During Walmart’s Labor Day Sale, Featured by ZDNET!</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-advice-on-restarting-and-repairing-intel-graphics-assistant-functionality/"><u>Expert Advice on Restarting and Repairing Intel Graphics Assistant Functionality</u></a></li>
<li><a href="https://fox-that.techidaily.com/expert-tips-on-accessing-technical-support-for-your-iphone-via-apple-support-tool/"><u>Expert Tips on Accessing Technical Support for Your iPhone via Apple Support Tool</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/facebooks-prime-video-hits-the-best-of-five/"><u>Facebook's Prime Video Hits - The Best of Five</u></a></li>
<li><a href="https://win-answers.techidaily.com/instant-fix-for-your-sekiro-crashing-woes-a-user-friendly-guide/"><u>Instant Fix for Your Sekiro Crashing Woes - A User-Friendly Guide</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-from-snapshots-to-blockbusters-the-ultimate-video-enhancement-tool/"><u>New From Snapshots to Blockbusters The Ultimate Video Enhancement Tool</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723000200757-no-more-lags-resolving-fps-drops-eradicating-gameplay-hiccups-and-boosting-performance/"><u>No More Lags: Resolving FPS Drops, Eradicating Gameplay Hiccups & Boosting Performance.</u></a></li>
<li><a href="https://article-tips.techidaily.com/painting-with-light-an-experts-guide-to-color-grading/"><u>Painting with Light An Expert's Guide to Color Grading</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-cod-trailer-gone-wrong-fixing-modern-warfare-3-app-errors/"><u>Resolved: Cod Trailer Gone Wrong - Fixing 'Modern Warfare 3' App Errors</u></a></li>
<li><a href="https://win-answers.techidaily.com/the-division-2-enhancing-gameplay-by-tackling-low-fps-and-smoothing-out-stutters/"><u>The Division 2: Enhancing Gameplay by Tackling LOW FPS and Smoothing Out Stutters</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-why-fifa-21-wont-start-up/"><u>Troubleshooting: Why FIFA 21 Won't Start Up</u></a></li>
<li><a href="https://win-answers.techidaily.com/understanding-wsappx-solutions-to-address-excessive-disk-and-cpu-consumption/"><u>Understanding WSAPPX: Solutions to Address Excessive Disk & CPU Consumption</u></a></li>
</ul></div>

