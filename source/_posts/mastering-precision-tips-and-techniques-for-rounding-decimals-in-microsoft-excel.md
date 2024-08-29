---
title: "Mastering Precision: Tips & Techniques for Rounding Decimals in Microsoft Excel"
date: 2024-08-27T23:57:43.049Z
updated: 2024-08-28T23:57:43.049Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f080364c9fd10c7a5fc9c9d8f37fc816490a2b5446a3998c55dc9f0ed4866d4c.jpg
---

## Mastering Precision: Tips & Techniques for Rounding Decimals in Microsoft Excel

### Quick Links

* [Round Off Decimal Values Using the ROUND Function](https://extra-support.techidaily.com/in-2024-instantaneous-darkness-creation/)
* [Round Numbers Up or Down Using the ROUNDUP or ROUNDDOWN Functions](https://remote-screen-capture.techidaily.com/new-privacy-protection-in-videos-a-guide-to-obscuring/)

 If you don't want to show decimal values in Excel, you can simplify your numerical data using the ROUND functions. Excel offers three functions: ROUND, ROUNDUP, and ROUNDDOWN. Let's take a look at how they work.

 Using the ROUND functions in Excel is different than changing the number's format. When you change how a number is formatted, you're just changing how it looks in your workbook. When you change a number using the ROUND functions, you're changing how it looks and how it's stored.

 The ROUND function rounds numbers to a specified number of decimal places. It rounds a number down if the digit in the next decimal place to the right is between zero and four, and it rounds up if that digit is five to nine. And as you might expect, the ROUNDUP function always rounds up and the ROUNDDOWN function always rounds down.

##  Round Off Decimal Values Using the ROUND Function

 The ROUND function rounds numbers to a certain number of decimal places that you configure. If the next digit to the right is between zero and four, it rounds down. So, for example, if you were rounding down to two decimal places, 8.532 would become 8.53\. If the next digit is between five and nine, it rounds up. So, 8.538 would become 8.54\. The ROUND function can round numbers to the right or left of the decimal point.

 You can apply the format to empty cells or to cells that already have numbers in them. You can also use ROUND as part of a more complicated formula if you want to. For example, you could create a formula that adds two columns together using the SUM function, and then rounds the result.

 For this example, we've got a column of numbers named "Values" that contains our raw numbers. We're creating a second column named "Results" that we're going to use to round down the numbers in the "Values" column to three digits.

![img_5b2ad361f3557](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad361f3557.png) 

 Select the cell where you want your rounded results to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

 Navigate to the "Formulas" menu on the main ribbon.

![img_5b2cd18c7eadf](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd18c7eadf.png) 

 Click the "Math & Trig" formulas drop-down menu.

![img_5b2cd1c366409](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd1c366409.png) 

 On the "Math & Trig" drop-down menu, click the "ROUND" function.

![img_5b2cd1fd04448](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd1fd04448.png) 

 This pops up the Function Arguments window with the fields you'll use for setting the ROUND function.

![img_5b2cd2396400b](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd2396400b.png) 

 Use the "Number" field for the number you want to round. You can use type a straight up number in this field to round it, but more often you'll want to call a number from an existing cell in your sheet. Here, we're using B6 to specify the top cell in our "Values" column.

![img_5b2cd2b3cdd05](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd2b3cdd05.png) 

 Use the "Num\_Digits" field to specify how many digits the resulting number should have. You have some choices here:

* **Positive Integer:** Use a positive integer (such as 1, 2, and so on) to specify the number of digits _after_ the decimal place to which you want to round. For example, entering "3" would round to three places after the decimal point.
* **Zero:** Enter "0" to round to the nearest integer.
* **Negative Integer:** Use a negative integer (such as -1, -2, and so on) to round to left of the decimal place. For example, if you were rounding the number 328.25 and input "-1" here, it would round you number to 330.

 In our example, we're inputting "3" so that it will round our result to three places after the decimal point.

![img_5b2cd3206405a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd3206405a.png) 

 When you're done, click the "OK" button.

![img_5b2cd34191bd1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd34191bd1.png) 

 And as you can see, our number is now rounded in the Results column.

![img_5b2cd362a665a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd362a665a.png) 

 You can easily apply this formula to the rest of the numbers in your set by first clicking on the bottom right corner of the cell.

![img_5b2cd3c46b79d](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd3c46b79d.png) 

 And then dragging to select the rest of the rows that you want to round.

![img_5b2cd3fe8560e](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd3fe8560e.png) 

 All of your values will now be rounded using the same properties you selected. You can also copy the cell to which you've already applied rounding, and then paste to other cells to copy the formula there.

![img_5b2cd431f381d](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd431f381d.png) 

 You can also do all this just using Excel's Function bar if you want.

 Select the column where you want your rounded numbers to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

 Click the Function bar to activate it.

![img_5b2cd5a995ad0](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5a995ad0.png) 

 Type in your formula using the syntax:

=ROUND(number,num_digits)

 Where "number" is the cell you want to round and "num\_digits" identifies the number of digits to which you want to round.

 For example, here's how we'd type the same rounding formula we previously applied using the dialog box.

![img_5b2cd5d70eb57](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5d70eb57.png) 

 Hit Enter (or Return) after typing your formula, and your number is now rounded.

![img_5b2cd5fc8316a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5fc8316a.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Round Numbers Up or Down Using the ROUNDUP or ROUNDDOWN Functions

 Sometimes, you may want your numbers to just round numbers up or down instead of having the next digit decide that for you. That's what the ROUNDUP and ROUNDDOWN functions are for, and and using them is pretty much identical to using the ROUND function.

 Click the cell where you want your rounded result to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
 Head to Formulas > Math & Trig, and then choose either the "ROUNDUP" or "ROUNDDOWN" function from the dropdown menu.

![Untitled](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/Untitled.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
 Enter the number (or cell) you want to round in the "Number" field. Enter the number of digits to which you want to round in the "Num\_digits" field. And the same rules apply as with the ROUND function. A positive integer rounds to the right of the decimal point, zero rounds to the nearest integer, and a negative integer rounds to the left of the decimal point.

 Click "OK" when you've got things set up.

![img_5b2cd7d91b50f](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd7d91b50f.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 And just like with the ROUND function, you can also set up the ROUNDUP and ROUNDDOWN functions by typing them into the Function bar, and you can use them as parts of a larger formula.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-establishing-an-individual-identity-on-youtube-platform-for-2024/"><u>[New] Establishing an Individual Identity on YouTube Platform for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-maximize-impact-mastering-instagram-video-transforms-into-mp4-for-2024/"><u>[Updated] Maximize Impact  Mastering Instagram Video Transforms Into MP4 for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-infinix-note-30-vip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Infinix Note 30 VIP | Dr.fone</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/15-types-of-camera-shots-in-film-beginners-need-to-know-for-2024/"><u>15 Types of Camera Shots in Film Beginners Need to Know for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-choosing-the-right-medium-audio-vs-video-based-platforms/"><u>2024 Approved  Choosing the Right Medium  Audio vs Video-Based Platforms</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-preferred-speech-to-text-ipad-apps-3/"><u>2024 Approved  Preferred Speech-to-Text iPad Apps #3</u></a></li>
<li><a href="https://win-answers.techidaily.com/best-practices-to-prevent-and-fix-zoom-from-crashing-on-windows-pcs-windows-11-and-10-in-202n4/"><u>Best Practices to Prevent and Fix Zoom From Crashing on Windows PCs (Windows 11 & 10) in 202N4</u></a></li>
<li><a href="https://win-answers.techidaily.com/effective-solutions-for-preventing-adobe-premiere-crashes-on-windows-11-and-10-systems/"><u>Effective Solutions for Preventing Adobe Premiere Crashes on Windows 11 & 10 Systems</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-guide-to-repairing-the-malfunctioning-msi-enchantment-light-on-pcs/"><u>Expert Guide to Repairing the Malfunctioning MSI Enchantment Light on PCs</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-for-stabilizing-virtual-reality-gaming-experience-and-preventing-pc-malfunctions/"><u>Expert Tips for Stabilizing Virtual Reality Gaming Experience and Preventing PC Malfunctions</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723011181210-far-cry-6-wont-boot-heres-how-to-resolve-your-pc-installation-problems/"><u>Far Cry ^6 Won't Boot? Here's How to Resolve Your PC Installation Problems!</u></a></li>
<li><a href="https://win-answers.techidaily.com/fast-solutions-overcoming-challenges-in-optimizing-shaders-for-star-wars-battlefront-ii/"><u>Fast Solutions: Overcoming Challenges in Optimizing Shaders for Star Wars Battlefront II</u></a></li>
<li><a href="https://win-answers.techidaily.com/fix-your-google-chrome-when-it-wont-launch-proven-solutions/"><u>Fix Your Google Chrome When It Won't Launch: Proven Solutions!</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-life-threatening-software-issues-a-guide-to-modern-warfare-and-warzone-patches/"><u>Fixing Life-Threatening Software Issues: A Guide to Modern Warfare & Warzone Patches</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-issue-how-to-stop-microsoft-edge-from-crashing-on-windows-11/"><u>Fixing the Issue: How to Stop Microsoft Edge From Crashing on Windows 11</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-kernelbasedll-fault-a-fast-and-straightforward-guide/"><u>Fixing the KernelBase.dll Fault: A Fast and Straightforward Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723008584254-forza-horizon-npc-engine-optimization-how-i-overcame-the-frame-rate-drop-issue/"><u>Forza Horizon nPC Engine Optimization: How I Overcame the Frame Rate Drop Issue</u></a></li>
<li><a href="https://article-helps.techidaily.com/free-mindset-audio-selection-for-2024/"><u>Free Mindset Audio Selection for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722997419516-guilty-gear-strive-trouble-heres-how-to-stop-pc-game-crashes-in-5-easy-steps/"><u>Guilty Gear Strive Trouble? Here's How to Stop PC Game Crashes in 5 Easy Steps</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-avatar-frontiers-of-pandora-low-fps-and-stuttering/"><u>How to FIX Avatar: Frontiers of Pandora Low FPS and Stuttering</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-outriders-freezing-and-stuttering-on-pc/"><u>How to Fix Outriders Freezing & Stuttering on PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-vivo-v30-pro-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Vivo V30 Pro</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-itel-s23plus-phone-without-pin-by-drfone-android/"><u>In 2024, How to Unlock Itel S23+ Phone without PIN</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-honor-play-7t-drfone-by-drfone-virtual-android/"><u>In 2024, Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Honor Play 7T | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-the-scribes-solution-recording-modern-television/"><u>In 2024, The Scribe's Solution  Recording Modern Television</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-the-undisclosed-secrets-to-growth-on-social-media/"><u>In 2024, The Undisclosed Secrets to Growth on Social Media</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-vivo-y78t-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Vivo Y78t Users</u></a></li>
<li><a href="https://win-answers.techidaily.com/master-guide-eliminating-game-interruptions-in-fifa-21-for-pc-users/"><u>Master Guide: Eliminating Game Interruptions in FIFA 21 for PC Users</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-game-continuity-fixing-frequent-pc-crashes-in-manor-lords/"><u>Mastering Game Continuity: Fixing Frequent PC Crashes in Manor Lords</u></a></li>
<li><a href="https://win-answers.techidaily.com/optimized-solution-for-high-memory-usage-by-google-chrome-now-solved/"><u>Optimized Solution for High Memory Usage by Google Chrome Now Solved</u></a></li>
<li><a href="https://win-answers.techidaily.com/quick-guide-to-resolving-lengthy-wait-times-for-fallout-4-startup/"><u>Quick Guide to Resolving Lengthy Wait Times for Fallout 4 Startup</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-battlefields-bfv-warzone-gameplay-interruption-fixing-the-infamous-50-and-31-disc-read-glitches-on-pc/"><u>Resolving Battlefield's BFV Warzone Gameplay Interruption: Fixing the Infamous [5.0] and [3.1] Disc Read Glitches on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-city-skylines-2-pc-crashes-troubleshooting-guide/"><u>Resolving City Skylines 2 PC Crashes – Troubleshooting Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/solution-found-fixing-disconnection-issues-from-blizzard-game-servers/"><u>Solution Found: Fixing Disconnection Issues From Blizzard Game Servers</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-ultimate-guide-on-fixing-phoenix-point-game-crashes/"><u>Solved: Ultimate Guide on Fixing Phoenix Point Game Crashes</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-pc-crashes-in-granblue-fantasy-the-ultimate-guide-to-re-link-fix/"><u>Solving PC Crashes in Granblue Fantasy: The Ultimate Guide to Re-Link Fix</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-sword-and-fairy-vii-crashes-during-playtime-on-windows/"><u>Solving Sword and Fairy VII Crashes During Playtime on Windows</u></a></li>
<li><a href="https://win-answers.techidaily.com/the-ultimate-fixes-for-connection-lost-error-on-the-escape-from-tarkov-server-platform/"><u>The Ultimate Fixes for 'Connection Lost' Error on the Escape From Tarkov Server Platform</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723006404737-troubleshoot-control-crashes-effortlessly-with-these-tips-and-tricks/"><u>Troubleshoot Control Crashes Effortlessly with These Tips & Tricks</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-alan-wake-2-release-problems-a-comprehensive-guide/"><u>Troubleshooting Alan Wake 2 Release Problems – A Comprehensive Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-when-cant-warframe-load/"><u>Troubleshooting Guide – When Can't Warframe Load</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-repairing-your-pathfinder-gamepad-controls/"><u>Troubleshooting Guide: Repairing Your Pathfinder Gamepad Controls</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-made-easy-top-strategies-when-genshin-stalls-on-start-up/"><u>Troubleshooting Made Easy: Top Strategies When Genshin Stalls on Start-Up</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-tips-for-when-outlook-refuses-to-start-up/"><u>Troubleshooting Tips for When Outlook Refuses to Start Up</u></a></li>
<li><a href="https://win-answers.techidaily.com/world-of-warcraft-performance-boost-top-fixes-for-lagging-frame-rates/"><u>World of Warcraft Performance Boost: Top Fixes for Lagging Frame Rates</u></a></li>
</ul></div>
