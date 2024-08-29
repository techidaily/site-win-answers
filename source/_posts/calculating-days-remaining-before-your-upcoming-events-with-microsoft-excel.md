---
title: Calculating Days Remaining Before Your Upcoming Events with Microsoft Excel
date: 2024-08-27T23:56:29.867Z
updated: 2024-08-28T23:56:29.867Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/excel-grey-background.png.png
---

## Calculating Days Remaining Before Your Upcoming Events with Microsoft Excel

### Quick Links

* [A Quick Summary of Date-Related Functions](https://extra-support.techidaily.com/is-there-a-business-model-for-shopping-blog-reviews-in-2024/)
* [Some Example Calculations](https://youtube-lab.techidaily.com/ed-juggling-youtube-success-and-full-time-work-a-guide-for-2024/)

 Excel treats dates as integers. This means you can add and subtract them, which can be useful for telling you how many days there are until that next deadline or event of yours. In this article, we will use Excel's DATE, YEAR, MONTH, DAY, and TODAY functions to show you how to calculate the number of days until your next birthday or any other annual event.

 Excel stores dates as integers. By default, Excel uses "1" to represent 01/01/1900 and each day after that is one greater. Type in 01/01/2000 and switch the format to "Number" and you'll see "36526" appear. If you subtract 1 from 36526, you can see that there were 36525 days in the 20th century. Alternatively, you could enter a future date and subtract the result of the TODAY function to see how many days away that date is from today.

##  A Quick Summary of Date-Related Functions

 Before we dive into some examples, we need to go over several simple date-related functions, including Excel's TODAY, DATE, YEAR, MONTH, and DAY functions.

###  TODAY

 Syntax: =TODAY()

 Result: The current date

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
###  DATE

 Syntax: =DATE(year,month,day)

 Result: The date designated by the year, month, and day entered

###  YEAR

 Syntax: =YEAR(date)

 Result: The year of the date entered

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  MONTH

 Syntax: =MONTH(date)

 Result: The numerical month of the date entered (1 through 12)

###  DAY

 Syntax: =DAY(date)

 Result: The day of the month of the date entered

##  Some Example Calculations

 We will look at three events that occur annually on the same day, calculate the date of their next occurrence, and determine the number of days between now and their next occurrence.

 Here is our sample data. We've got four columns set up: Event, Date, Next\_Occurrence, and Days\_Until\_Next. We have entered the dates of a random birth date, the date taxes are due in the U.S., and Halloween. Dates like birthdays, anniversaries, and some holidays occur on specific days each year and work well with this example. Other holidays---like Thanksgiving---occur on a particular weekday in a specific month; this example does not cover those types of events.

![Example Data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-01.png) 

 There are two options for filling in the 'Next\_Occurrence' column. You can hand-enter each date, but each entry will need to be manually updated in the future as the date passes. Instead, let's write an 'IF' statement formula so that Excel can do the work for you.

 Let's look at the birthday. We already know the month 

        `=MONTH(F3)`
    
 and day 

        `=DAY(F3)`
    
 of the next occurrence. That's easy, but what about the year? We need Excel to know whether the birthday has occurred in this year already or not. First, we need to calculate the date on which the birthday occurs in the present year using this formula:

=DATE(YEAR(TODAY()),MONTH(F3),DAY(F3))

 Next, we need to know if that date has already passed and you can compare that result to `TODAY()` to find out. If it is July and the birthday occurs every September, then the next occurrence is in the current year, shown with `=YEAR(TODAY())` . If it is December and the birthday occurs every May, then the next occurrence is in the next year, so `=YEAR(TODAY())+1` would give the next year. To determine which to use, we can use an 'IF' statement:

=IF(DATE(YEAR(TODAY()),MONTH(F3),DAY(F3))>=TODAY(),YEAR(TODAY()),YEAR(TODAY())+1)

 Now we can combine the results of the IF statement with the MONTH and DAY of the birthday to determine the next occurrence. Enter this formula into cell G3:

=DATE(IF(DATE(YEAR(TODAY()),MONTH(F3),DAY(F3))>=TODAY(),YEAR(TODAY()),YEAR(TODAY())+1),MONTH(F3),DAY(F3))

![Entering "=DATE(IF(DATE(YEAR(TODAY()),MONTH(F3),DAY(F3))>=TODAY(),YEAR(TODAY()),YEAR(TODAY())+1),MONTH(F3),DAY(F3))" into cell F3](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-02.png) 

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
 Hit Enter to see the result. (This article was written in late January 2019, so the dates will be...well...dated.)

 Fill this formula down into the cells below by highlighting the cells and pressing Ctrl+D.

![Next Occurrence Results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-03.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
 Now we can easily determine the number of days until the next occurrence by subtracting the result of the TODAY() function from the Next\_Occurrence results we just calculated. Enter the following formula into cell H3:

=G3-TODAY()

![Enter "=G3-TODAY()" into cell H3](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-04.png) 

 Press Enter to see the result and then fill this formula down into the cells below by highlighting the cells and pressing Ctrl+D.

![Days_Until_Next Results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-05.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
 You can save a workbook with the formulas in this example to keep track of whose birthday is coming up next or know how many days you have left to finish your Halloween costume. Each time you use the workbook, it will recalculate the results based on the current date because you've used the `TODAY()` function.

![Example Results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/Excel-Date-06.png) 

<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And yes, these are pretty specific examples that might or might not be useful to you. But, they also serve to illustrate the kinds of things you can do with date-related functions in Excel.

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
<li><a href="https://extra-skills.techidaily.com/new-quick-pace-facebook-videos-prime-extensions-tips-and-tricks-list/"><u>[New] Quick-Pace Facebook Videos  Prime Extensions, Tips & Tricks List</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-setting-the-stage-your-first-virtual-boardroom-with-google-for-2024/"><u>[New] Setting the Stage  Your First Virtual Boardroom with Google for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-dayz-keeps-crashing-quickly-and-easily/"><u>[Solved] DayZ Keeps Crashing | Quickly & Easily</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevate-your-online-presence-with-expert-streaming-guide-for-2024/"><u>[Updated] Elevate Your Online Presence with Expert Streaming Guide for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-banishing-facebook-broadcasts-from-laptoptablet/"><u>[Updated] In 2024, Banishing Facebook Broadcasts From Laptop/Tablet</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-skyline-of-success-stardews-top-7-upgrades-review/"><u>[Updated] Skyline of Success  Stardew's Top 7 Upgrades Review</u></a></li>
<li><a href="https://win-answers.techidaily.com/apex-legends-troubleshooting-how-to-resolve-error-code-23-quickly/"><u>Apex Legends Troubleshooting: How to Resolve Error Code 23 Quickly</u></a></li>
<li><a href="https://win-forum.techidaily.com/confronting-the-something-went-awry-message-comprehensive-solutions-for-windows-eon-users/"><u>Confronting the Something Went Awry Message: Comprehensive Solutions for Windows Eon Users</u></a></li>
<li><a href="https://win-answers.techidaily.com/diablo-4-stability-hacks-fixed-issues-on-pcps5xbox-with-these-7-steps/"><u>Diablo 4 Stability Hacks: Fixed Issues on PC/PS5/Xbox with These 7 Steps</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/dive-into-digital-innovations-at-toms-computer-chronicles-expert-electronics-evaluations/"><u>Dive Into Digital Innovations at Tom's Computer Chronicles: Expert Electronics Evaluations</u></a></li>
<li><a href="https://buynow-help.techidaily.com/expertly-selected-best-cable-modem-and-wireless-router-bundles-of-2024/"><u>Expertly Selected Best Cable Modem and Wireless Router Bundles of 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-corsair-icue-dilemma-in-windows-11-a-complete-guide/"><u>Fixing the Corsair iCUE Dilemma in Windows 11 - A Complete Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723004857007-football-manager-2020-stability-improvements-no-more-crashes/"><u>Football Manager 2020 Stability Improvements – No More Crashes</u></a></li>
<li><a href="https://win-answers.techidaily.com/game-changer-alert-solving-the-dark-souls-iii-unwanted-reboots-challenge/"><u>Game-Changer Alert: Solving the Dark Souls III Unwanted Reboots Challenge</u></a></li>
<li><a href="https://win-answers.techidaily.com/guide-fixing-the-issue-of-unresponsive-amd-radeon-graphic-drivers/"><u>Guide: Fixing the Issue of Unresponsive AMD Radeon Graphic Drivers</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-discord-crashing/"><u>How To Fix Discord Crashing</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-repair-an-unresponsive-microsoft-outlook-account/"><u>How to Repair an Unresponsive Microsoft Outlook Account</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-repair-issues-when-using-the-clownfish-audio-alteration-device/"><u>How to Repair Issues When Using the Clownfish Audio Alteration Device</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-stop-metro-exodus-from-crashing-on-windows-tips-and-solutions/"><u>How to Stop Metro Exodus From Crashing on Windows - Tips & Solutions</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-a-guide-samsung-galaxy-a05s-wireless-and-wired-screen-mirroring-drfone-by-drfone-android/"><u>In 2024, A Guide Samsung Galaxy A05s Wireless and Wired Screen Mirroring | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-funimate-pro-activation-guide-for-android-users/"><u>In 2024, Funimate Pro Activation Guide for Android Users</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/inside-the-circuitry-insightful-guidance-from-toms-tech-domain/"><u>Inside the Circuitry: Insightful Guidance From Tom's Tech Domain</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-filter-essentials-uncover-free-options-through-advanced-search/"><u>Instagram Filter Essentials – Uncover Free Options Through Advanced Search</u></a></li>
<li><a href="https://extra-information.techidaily.com/make-marine-scenes-fluidly-with-these-7-tricks/"><u>Make Marine Scenes Fluidly with These 7 Tricks</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-obstacles-how-to-get-gta-5-online-up-and-running-again/"><u>Overcoming Obstacles: How to Get GTA 5 Online Up and Running Again</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-visual-hitches-fixing-the-dark-display-fault-in-world-war-ii-call-of-duty-game-on-pc/"><u>Overcoming Visual Hitches: Fixing the Dark Display Fault in World War II - Call of Duty Game on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/pc-gaming-made-easy-solutions-for-stability-issues-in-robocop-rupture/"><u>PC Gaming Made Easy: Solutions for Stability Issues in 'Robocop: Rupture'</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/premier-9-multi-device-video-communication-tools-for-smartphones-for-2024/"><u>Premier 9 Multi-Device Video Communication Tools for Smartphones for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/recording-perfection-macbook-cam-tutorial/"><u>Recording Perfection  MacBook Cam Tutorial</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-the-rainbow-six-siege-not-loading-issue-a-comprehensive-guide/"><u>Solving the 'Rainbow Six Siege Not Loading' Issue - A Comprehensive Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-samsung-galaxy-m34-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Samsung Galaxy M34 Device</u></a></li>
<li><a href="https://change-location.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Samsung Galaxy S24 | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-fixing-your-logiten-c920-webcam-issues/"><u>Troubleshooting Guide: Fixing Your Logiten C920 Webcam Issues</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-hell-divers-the-twin-heroes-ii-bsod-issue-a-comprehensive-guide/"><u>Troubleshooting Hell Divers The Twin Heroes II BSoD Issue - A Comprehensive Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-to-fix-disconnects-and-crashes-in-granblue-fantasy-for-pc-players/"><u>Ultimate Guide to Fix Disconnects and Crashes in Granblue Fantasy for PC Players</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-oneplus-nord-n30-se-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your OnePlus Nord N30 SE Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win-answers.techidaily.com/wave-goodbye-to-black-screens-in-hitman-3-a-guide-for-windows-gamers/"><u>Wave Goodbye to Black Screens in Hitman #3 - A Guide for Windows Gamers</u></a></li>
<li><a href="https://win-answers.techidaily.com/wwe-2k20-pc-edition-troubleshooting-common-performance-issues-and-crashes/"><u>WWE 2K20 PC Edition - Troubleshooting Common Performance Issues and Crashes</u></a></li>
</ul></div>
