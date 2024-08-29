---
title: "Consolidate Text Entries: A Step-by-Step Guide to Joining Content Across Several Excel Cells Into One"
date: 2024-08-27T23:56:31.011Z
updated: 2024-08-28T23:56:31.011Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4f70e3d531e042394d8511ca88c9ecd662d4633e7d60fe2b42adcca98c8caef1.png
---

## Consolidate Text Entries: A Step-by-Step Guide to Joining Content Across Several Excel Cells Into One

If you have a large worksheet in an Excel workbook in which you need to combine text from multiple cells, you can breathe a sigh of relief because you don't have to retype all that text. You can easily concatenate the text.

 Concatenate is simply a fancy way ot saying "to combine" or "to join together" and there is a special CONCATENATE function in Excel to do this. This function allows you to combine text from different cells into one cell. For example, we have a worksheet containing names and contact information. We want to [combine the Last Name and First Name columns](https://article-helps.techidaily.com/updated-2024-approved-elevate-your-drone-game-with-top-tier-lipo-tech/) in each row into the Full Name column.

 To begin, select the first cell that will contain the combined, or concatenated, text. Start typing the function into the cell, starting with an equals sign, as follows.

=CONCATENATE(

![01_entering_concatenate_function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/01_entering_concatenate_function.png) 

 Now, we enter the arguments for the CONCATENATE function, which tell the function which cells to combine. We want to combine the first two columns, with the First Name (column B) first and then the Last Name (column A). So, our two arguments for the function will be B2 and A2.

 There are two ways you can enter the arguments. First, you can type the cell references, separated by commas, after the opening parenthesis and then add a closing parenthesis at the end:

=CONCATENATE(B2,A2)

 You can also click on a cell to enter it into the CONCATENATE function. In our example, after typing the name of the function and the opening parenthesis, we click on the B2 cell, type a comma after B2 in the function, click on the A2 cell, and then type the closing parenthesis after A2 in the function.

 Press Enter when you're done adding the cell references to the function.

![02_adding_cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/02_adding_cells.png) 

 Notice that there is no space in between the first and last name. That's because the CONCATENATE function combines exactly what's in the arguments you give it and nothing more. There is no space after the first name in B2, so no space was added. If you want to add a space, or any other punctuation or details, you must tell the CONCATENATE function to include it.

![03_no_space_in_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/03_no_space_in_name.png) 

 To add a space between the first and last names, we add a space as another argument to the function, in between the cell references. To do this, we type a space surrounded by double quotes. Make sure the three arguments are separated by commas.

=CONCATENATE(B2," ",A2)

 Press Enter.

![04_adding_space](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/04_adding_space.png) 

 That's better. Now, there is a space between the first and last names.

![05_concatenated_name_with_space](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/05_concatenated_name_with_space.png) 

Related: [How to Automatically Fill Sequential Data into Excel with the Fill Handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) 

 Now, you're probably thinking you have to type that function in every cell in the column or manually copy it to each cell in the column. Actually, you don't. We've got another neat trick that will help you quickly copy the CONCATENATE function to the other cells in the column (or row). Select the cell in which you just entered the CONCATENATE function. The small square on the lower-right corner of the selected is called the fill handle. The fill handle allows you to [quickly copy and paste content to adjacent cells](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) in the same row or column.

![06_fill_handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/06_fill_handle.png) 

 Move your cursor over the fill handle until it turns into a black plus sign and then click and drag it down.

![07_double_clicking_fill_handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/07_double_clicking_fill_handle.png) 

 The function you just entered is copied down to the rest of the cells in that column, and the cell references are changed to match the row number for each row.

![08_column_filled](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/08_column_filled.png) 

 You can also concatenate text from multiple cells using the ampersand (&) operator. For example, you can enter `=B2&" "&A2` to get the same result as `=CONCATENATE(B2," ",A2)` . There's no real advantage of using one over the other. although using the ampersand operator results in a shorter entry. However, the CONCATENATE function may be more readable, making it easier to understand what's happening in the cell.

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
<li><a href="https://win-answers.techidaily.com/1723010468510-solved-outriders-wont-start-on-pc-2022/"><u>[SOLVED] Outriders Won’t Start on PC 2022</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-compreeved-guide-to-creating-stellar-youtube-outros/"><u>[Updated] In 2024, Compreeved Guide to Creating Stellar YouTube Outros</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-mastering-video-integration-with-apple-music-for-2024/"><u>[Updated] Mastering Video Integration with Apple Music for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-seamless-gif-converters-online-5-rated-highly/"><u>[Updated] Seamless GIF Converters Online, 5 Rated Highly</u></a></li>
<li><a href="https://win-answers.techidaily.com/beat-no-user-found-in-csgo-with-these-5-essential-troubleshooting-tips/"><u>Beat 'No User Found' In CSGO with These 5 Essential Troubleshooting Tips</u></a></li>
<li><a href="https://techidaily.com/different-methods-for-resetting-honor-magic-5-lite-phones-with-screen-locked-and-not-drfone-by-drfone-reset-android-reset-android/"><u>Different Methods for Resetting Honor Magic 5 Lite Phones with Screen Locked and Not | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-samsung-galaxy-a15-5g-support-mkv-video-files-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Does Samsung Galaxy A15 5G support MKV video files?</u></a></li>
<li><a href="https://win-answers.techidaily.com/effective-strategies-to-fix-a-deadly-ark-error-tips-and-tricks/"><u>Effective Strategies to Fix a Deadly Ark Error - Tips & Tricks</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-and-tricks-to-overcome-alan-wake-2s-persistent-crashes-a-2024-how-to-guide/"><u>Expert Tips and Tricks to Overcome Alan Wake 2'S Persistent Crashes - A 2024 How-To Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-msedgeexe-crashes-troubleshooting-steps-for-stable-edge-browser-experience/"><u>Fixing MsEdge.exe Crashes: Troubleshooting Steps for Stable Edge Browser Experience</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-frame-rate-drop-in-dying-light-how-gamers-overcame-fps-problems/"><u>Fixing the Frame Rate Drop in Dying Light - How Gamers Overcame FPS Problems</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixing-the-frame-rate-drop-in-dying-light-an-ultimate-solution/"><u>Fixing the Frame Rate Drop in Dying Light: An Ultimate Solution</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-dota-2-launching-problems-and-bypass-the-endless-loading-screen/"><u>How to Fix Dota 2 Launching Problems and Bypass the Endless Loading Screen</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-icloud-activation-lock-and-icloud-account-from-apple-iphone-11-pro-by-drfone-ios/"><u>How to Unlock iCloud Activation Lock and iCloud Account From Apple iPhone 11 Pro?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/meme-magic-unleashed-top-humorous-creations-for-the-metaverse-world/"><u>Meme Magic Unleashed  Top Humorous Creations for the Metaverse World</u></a></li>
<li><a href="https://win-answers.techidaily.com/nier-gestalt-and-replicant-collection-boot-up-fixes-achieved/"><u>NieR Gestalt & Replicant Collection Boot-Up Fixes Achieved</u></a></li>
<li><a href="https://win-answers.techidaily.com/preventing-your-game-from-crashing-a-guide-for-doom-eternal-players/"><u>Preventing Your Game From Crashing - A Guide for DOOM Eternal Players</u></a></li>
<li><a href="https://extra-skills.techidaily.com/quick-guide-integrating-titles-into-videos-within-windows-photos-for-2024/"><u>Quick Guide  Integrating Titles Into Videos Within Windows Photos for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-fixing-issues-with-missing-textures-in-call-of-duty-warzone/"><u>Resolved: Fixing Issues with Missing Textures in Call of Duty: Warzone</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-the-connection-refused-by-anticheat-issue-in-escape-from-tarkov/"><u>Resolving the 'Connection Refused by Anticheat' Issue in Escape From Tarkov</u></a></li>
<li><a href="https://extra-support.techidaily.com/revolutionize-streaming-top-converters-transform-4k-content-for-2024/"><u>Revolutionize Streaming  Top Converters Transform 4K Content for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/solutions-for-critical-development-bug-in-call-of-dutys-modern-warfare-and-warzone/"><u>Solutions for Critical Development Bug in Call of Duty's Modern Warfare and Warzone</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-tarkov-glitch-steps-to-resolve-the-e-103003-error/"><u>Solving Tarkov Glitch: Steps to Resolve the E-103003 Error</u></a></li>
<li><a href="https://win-answers.techidaily.com/stop-the-frustration-solving-constant-crashes-in-the-ascent-for-windows-users/"><u>Stop the Frustration: Solving Constant Crashes in 'The Ascent' For Windows Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-balancing-act-weighing-up-chatgpts-role-in-innovative-narratives/"><u>The Balancing Act: Weighing Up ChatGPT’s Role in Innovative Narratives</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-and-repairing-sons-of-the-forest-crashes-on-your-computer/"><u>Troubleshooting and Repairing Sons of the Forest Crashes on Your Computer</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-and-resolving-frame-rate-drops-in-ac-valhalla-for-windows-gamers/"><u>Troubleshooting and Resolving Frame Rate Drops in AC Valhalla for Windows Gamers</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-steps-to-resolve-bloodhunt-game-lag-and-freezing-issues-on-your-computer/"><u>Troubleshooting Steps to Resolve Bloodhunt Game Lag and Freezing Issues on Your Computer</u></a></li>
<li><a href="https://win-answers.techidaily.com/ultimate-guide-resolving-issues-with-game-finals-release/"><u>Ultimate Guide: Resolving Issues with Game Finals Release</u></a></li>
<li><a href="https://win-answers.techidaily.com/unlock-kodis-full-potential-address-and-fix-couldnt-retrieve-directory-info-issues-today/"><u>Unlock Kodi's Full Potential: Address and Fix 'Couldn't Retrieve Directory Info' Issues Today</u></a></li>
<li><a href="https://technical-tips.techidaily.com/what-to-expect-from-the-new-samsung-galaxy-z-fold-rumored-pricing-launch-dates-and-feature-set/"><u>What to Expect From the New Samsung Galaxy Z Fold: Rumored Pricing, Launch Dates, and Feature Set</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->