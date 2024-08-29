---
title: "Mastering Microsoft Excel: A Comprehensive Guide on Utilizing and Understanding the Outlier Feature"
date: 2024-08-27T23:56:21.679Z
updated: 2024-08-28T23:56:21.679Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/5dc08c7f44b75aa96c6e9b7584825b6a5a67a8f345c561509fddb26d5e877149.jpg
---

## Mastering Microsoft Excel: A Comprehensive Guide on Utilizing and Understanding the Outlier Feature

### Quick Links

* [A Quick Example](https://sound-issues.techidaily.com/how-to-fix-windows-speaker-sound-distortion-issue/)
* [How to Find Outliers in your Data](https://some-techniques.techidaily.com/hands-on-crafting-unique-movie-closures-for-pennies-for-2024/)
* [Ignoring the Outliers when Calculating the Mean Average](https://screen-sharing-recording.techidaily.com/new-essential-techniques-for-recording-and-preserving-itunes-videos-for-2024/)

## 

 An outlier is a value that is significantly higher or lower than most of the values in your data. When using Excel to analyze data, outliers can skew the results. For example, the mean average of a data set might truly reflect your values. Excel provides a few useful functions to help manage your outliers, so let's take a look.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
##  A Quick Example

 In the image below, the outliers are reasonably easy to spot---the value of two assigned to Eric and the value of 173 assigned to Ryan. In a data set like this, it's easy enough to spot and deal with those outliers manually.

![Range of values containing outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/dataset-border.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In a larger set of data, that will not be the case. Being able to identify the outliers and remove them from statistical calculations is important---and that's what we'll be looking at how to do in this article.

##  How to Find Outliers in your Data

 To find the outliers in a data set, we use the following steps:

1. Calculate the 1st and 3rd quartiles (we'll be talking about what those are in just a bit).
2. Evaluate the interquartile range (we'll also be explaining these a bit further down).
3. Return the upper and lower bounds of our data range.
4. Use these bounds to identify the outlying data points.

 The cell range on the right of the data set seen in the image below will be used to store these values.

![Range for quartiles](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/quartile-cells-border.png) 

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
 Let's get started.

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
###  Step One: Calculate the Quartiles

 If you divide your data into quarters, each of those sets is called a quartile. The lowest 25% of numbers in the range make up the 1st quartile, the next 25% the 2nd quartile, and so on. We take this step first because the most widely-used definition of an outlier is a data point that is more than 1.5 interquartile ranges (IQRs) below the 1st quartile, and 1.5 interquartile ranges above the 3rd quartile. To determine those values, we first have to figure out what the quartiles are.

 Excel provides a QUARTILE function to calculate quartiles. It requires two pieces of information: the array and the quart.

=QUARTILE(array, quart)

 The array is the range of values that you are evaluating. And the quart is a number that represents the quartile you wish to return (e.g., 1 for the 1st quartile, 2 for the 2nd quartile, and so on).

**Note:** In Excel 2010, Microsoft released the QUARTILE.INC and QUARTILE.EXC functions as improvements to the QUARTILE function. QUARTILE is more backward compatible when working across multiple versions of Excel.

 Let's return to our example table.

![Range for quartiles](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/quartile-cells-border.png) 

 To calculate the 1st Quartile we can use the following formula in cell F2.

=QUARTILE(B2:B14,1)

 As you enter the formula, Excel provides a list of options for the quart argument.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/quartile-with-border-1.png) 

 To calculate the 3rd quartile, we can enter a formula like the previous one in cell F3, but using a three instead of a one.

=QUARTILE(B2:B14,3)

 Now, we've got the quartile data points displayed in the cells.

![1st and 3rd quartile values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/1st-and-3rd-quartiles-border.png) 

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Step Two: Evaluate the Interquartile Range

 The interquartile range (or IQR) is the middle 50% of values in your data. It is calculated as the difference between the 1st quartile value and the 3rd quartile value.

 We're going to use a simple formula into cell F4 that subtracts the 1st quartile from the 3rd quartile:

=F3-F2

 Now, we can see our interquartile range displayed.

![Interquartile value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/iqr-border.png) 

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->
###  Step Three: Return the Lower and Upper Bounds

 The lower and upper bounds are the smallest and largest values of the data range that we want to use. Any values smaller or larger than these bound values are the outliers.

 We'll calculate the lower bound limit in cell F5 by multiplying the IQR value by 1.5 and then subtracting it from the Q1 data point:

=F2-(1.5*F4)

![Excel formula for lower bound value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/l-bound-border.png) 

<!-- affiliate ads begin -->
<a href="https://thefitville.pxf.io/c/5597632/1526796/15852" target="_top" id="1526796"><img src="//a.impactradius-go.com/display-ad/15852-1526796" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1526796/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Note:** The brackets in this formula are not necessary because the multiplication part will calculate before the subtraction part, but they do make the formula easier to read.

 To calculate the upper bound in cell F6, we'll multiply the IQR by 1.5 again, but this time add it to the Q3 data point:

=F3+(1.5*F4)

![Lower and upper bound values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/l-bound-and-u-bound-border.png) 

###  Step Four: Identify the Outliers

 Now that we've got all our underlying data set up, it's time to identify our outlying data points---the ones that are lower than the lower bound value or higher than the upper bound value.

 We'll use the [OR function](https://support.office.com/en-us/article/or-function-7d17ad14-8700-4281-b308-00b131e22af0) to perform this logical test and show the values that meet these criteria by entering the following formula into cell C2:

=OR(B2<$F$5,B2>$F$6)

![OR function to identify outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/or-function-border-1.png) 

 We'll then copy that value into our C3-C14 cells. A TRUE value indicates an outlier, and as you can see, we've got two in our data.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/found-outliers-border-224x300.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Ignoring the Outliers when Calculating the Mean Average

 Using the QUARTILE function let us calculate the IQR and work with the most widely used definition of an outlier. However, when calculating the mean average for a range of values and ignoring outliers, there is a quicker and easier function to use. This technique will not identify an outlier as before, but it will allow us to be flexible with what we might consider our outlier portion.

 The function we need is called TRIMMEAN, and you can see the syntax for it below:

=TRIMMEAN(array, percent)

 The array is the range of values you want to average. The percent is the percentage of data points to exclude from the top and bottom of the data set (you can enter it as a percentage or a decimal value).

 We entered the formula below into cell D3 in our example to calculate the average and exclude 20% of outliers.

=TRIMMEAN(B2:B14, 20%)

![TRIMMEAN formula for average excluding outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/trimmean-border.png) 

---

 There you have two different functions for handling outliers. Whether you want to identify them for some reporting needs or exclude them from calculations such as averages, Excel has a function to fit your needs.

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
<li><a href="https://win-answers.techidaily.com/elden-ring-performance-enhancement-6-steps-for-smooth-gaming-action/"><u>'Elden Ring' Performance Enhancement: 6 Steps for Smooth Gaming Action</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-effortless-subscriber-acquisition-for-enhanced-viewership/"><u>[New] 2024 Approved  Effortless Subscriber Acquisition for Enhanced Viewership</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-essential-bandicam-know-how-a-complete-review-for-2024/"><u>[New] Essential Bandicam Know-How - A Complete Review for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-digital-dynamics-pro-strategies-to-switch-shades/"><u>[Updated] 2024 Approved  Digital Dynamics  Pro Strategies to Switch Shades</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-full-guide-to-facebook-algorithm-change-are-you-ready-for-2024/"><u>[Updated] Full Guide to Facebook Algorithm Change   Are You Ready？ for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-the-rise-of-vidma-transforming-the-landscape-of-capture-technology/"><u>[Updated] In 2024, The Rise of Vidma  Transforming the Landscape of Capture Technology</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-step-by-step-screen-and-video-capture-on-android/"><u>[Updated] Step-by-Step  Screen and Video Capture on Android</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-solving-mysterious-oneself-appearing-in-video-conversations/"><u>2024 Approved  Solving Mysterious Oneself Appearing in Video Conversations</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-assisted-recruitment-discover-the-best-10-ways-to-utilize-gpt-on-linkedin-jobsites/"><u>AI Assisted Recruitment: Discover the Best 10 Ways to Utilize GPT on LinkedIn Jobsites</u></a></li>
<li><a href="https://win-answers.techidaily.com/apples-ultimate-guide-to-choosing-a-side-by-side-look-at-macbook-air-and-pro/"><u>Apple's Ultimate Guide to Choosing: A Side-by-Side Look at MacBook Air and Pro</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722148279824-are-these-8-chatgpt-ventures-legit-evaluating-the-prospects-of-side-income-generation/"><u>Are These 8 ChatGPT Ventures Legit? Evaluating the Prospects of Side Income Generation.</u></a></li>
<li><a href="https://win-answers.techidaily.com/avoid-vrchat-crashes-in-virtual-reality-8-crucial-fixes-for-gaming-smoothness-on-pc/"><u>Avoid VRChat Crashes in Virtual Reality: 8 Crucial Fixes for Gaming Smoothness on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/battling-freezing-frame-rates-in-fallout-4-discover-effective-solutions/"><u>Battling Freezing Frame Rates in Fallout 4? Discover Effective Solutions</u></a></li>
<li><a href="https://win-answers.techidaily.com/best-techniques-to-fix-unresponsiveness-in-minecraft-when-playing-on-computer-systems/"><u>Best Techniques to Fix Unresponsiveness in Minecraft when Playing on Computer Systems</u></a></li>
<li><a href="https://win-answers.techidaily.com/best-troubleshooting-tips-for-smooth-fallout-3-gaming-on-windows-11/"><u>Best Troubleshooting Tips for Smooth Fallout 3 Gaming on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-oppo-f23-5g-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Oppo F23 5G? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/comprehensive-guide-solving-pc-game-stuttering-issues-tips/"><u>Comprehensive Guide: Solving PC Game Stuttering Issues (Tips )</u></a></li>
<li><a href="https://win-answers.techidaily.com/crack-the-code-top-strategies-to-keep-among-us-running-smoothly/"><u>Crack the Code: Top Strategies to Keep 'Among Us' Running Smoothly</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/crafting-cinema-youtubes-compreranche-guide-for-filmmakers-for-2024/"><u>Crafting Cinema  YouTube's Compreranche Guide for Filmmakers for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/enhanced-destiny-2-performance-on-pc-no-more-unexpected-interruptions/"><u>Enhanced Destiny 2 Performance on PC - No More Unexpected Interruptions</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-to-overcome-the-missing-ping-issue-in-halo-infinite-gameplay/"><u>Expert Tips to Overcome the Missing Ping Issue in Halo Infinite Gameplay</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-common-problems-of-counter-strike-2-not-opening-properly/"><u>Fixing the Common Problems of Counter-Strike 2 Not Opening Properly</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-issue-overcoming-connection-errors-in-path-of-exile-a-comprehensive-guide/"><u>Fixing the Issue: Overcoming Connection Errors in Path of Exile – A Comprehensive Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-apples-music-app-when-your-iphone-wont-sync-with-windows-10-pc/"><u>How to Fix Apple's Music App When Your iPhone Won't Sync With Windows 10 PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/how-to-record-the-screen-with-adobe-captive-for-2024/"><u>How To Record The Screen With Adobe Captive for 2024</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-update-zexmte-bluetooth-adapter-on-windows-pcs-11-7-and-8/"><u>How to Update ZEXMTE Bluetooth Adapter on Windows PCs (11, 7 & 8)</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-accessing-trendsetting-background-images-for-tiktok/"><u>In 2024, Accessing Trendsetting Background Images for TikTok</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-vivo-s18e-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Vivo S18e to Protect Your Individual Information</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-avoiding-fatal-bugs-in-the-unreal-engine-4-insights-from-arise-games/"><u>Mastering Avoiding Fatal Bugs in the Unreal Engine 4 - Insights From Arise Games</u></a></li>
<li><a href="https://win-answers.techidaily.com/no-more-crashes-solving-the-kernelbasedll-dilemamo-with-swift-and-straightforward-techniques/"><u>No More Crashes: Solving the kernelbase.dll Dilemamo with Swift & Straightforward Techniques.</u></a></li>
<li><a href="https://win-answers.techidaily.com/pc-players-manual-ensuring-smooth-operation-of-vr-titles-without-crashes/"><u>PC Players' Manual: Ensuring Smooth Operation of VR Titles Without Crashes</u></a></li>
<li><a href="https://win-answers.techidaily.com/quick-fixes-for-a-frequently-crashing-google-chrome-browser/"><u>Quick Fixes for a Frequently Crashing Google Chrome Browser</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722999792283-quick-resolution-for-apex-legends-not-launching-master-these-fixes-today/"><u>Quick Resolution for Apex Legends Not Launching? Master These Fixes Today!</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-origin-issue-now-successfully-connected/"><u>Resolved: Origin Issue - Now Successfully Connected</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-the-windows-11-taskbar-glitch-tips-and-techniques-that-work/"><u>Resolving the Windows 11 Taskbar Glitch: Tips & Techniques That Work</u></a></li>
<li><a href="https://win-answers.techidaily.com/revitalized-audio-top-6-fixes-for-your-obs-microphone-issues/"><u>Revitalized Audio: Top 6 Fixes for Your Obs Microphone Issues</u></a></li>
<li><a href="https://extra-resources.techidaily.com/sharper-stars-in-iphone-nocturne-photos/"><u>Sharper Stars in iPhone Nocturne Photos</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-overcoming-launch-problems-in-red-dead-redemption-2/"><u>Solved! Overcoming Launch Problems in Red Dead Redemption 2</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-pc-issues-troubleshooting-overwatch-2-continuous-crashes/"><u>Solving PC Issues: Troubleshooting Overwatch 2 Continuous Crashes</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-remedies-for-boot-issues-in-davinci-resolve-across-windows-operating-platforms/"><u>Step-by-Step Remedies for Boot Issues in DaVinci Resolve Across Windows Operating Platforms</u></a></li>
<li><a href="https://win-answers.techidaily.com/tame-the-beast-conquering-cod-warzone-dev-error-6328-with-advanced-hacks-aficionados/"><u>Tame The Beast: Conquering Cod Warzone Dev Error #6328 with Advanced Hacks Aficionados</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-call-history-from-honor-90-pro-by-fonelab-android-recover-call-logs/"><u>The way to get back lost call history from Honor 90 Pro</u></a></li>
<li><a href="https://data-wizards.techidaily.com/troubleshooting-screen-distortion-after-win10-upgrade/"><u>Troubleshooting Screen Distortion After Win10 Upgrade</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-for-gray-zone-warfare-crashes-on-windows-computers/"><u>Troubleshooting Tips for Gray Zone Warfare Crashes on Windows Computers</u></a></li>
</ul></div>
