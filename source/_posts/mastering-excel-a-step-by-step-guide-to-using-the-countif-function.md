---
title: "Mastering Excel: A Step-by-Step Guide to Using the COUNTIF Function"
date: 2024-12-03T18:22:13.366Z
updated: 2024-12-06T18:56:10.880Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a6017269d4c04c5e1e1b5dd34c08e1f92a0a41c1ec409bdbe7a0807e99cdc6f4.jpg
---

## Mastering Excel: A Step-by-Step Guide to Using the COUNTIF Function

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [What Is the COUNTIF function?](https://some-knowledge.techidaily.com/updated-flawless-illustration-from-photographs-cross-platform-compatibility/)
* [How to Use the COUNTIF Formula in Microsoft Excel](https://on-screen-recording.techidaily.com/updated-review-and-compare-streamlabs-and-embedding-platforms/)
* [How to Count the Number of Multiple Values](https://some-guidance.techidaily.com/the-seekers-manual-a-comprehensive-approach-to-purchasing-high-definition-monitors-for-2024/)
* [Limitations of the COUNTIF Formula](https://youtube-data.techidaily.com/ed-best-practices-for-boosting-views-on-freefire-gaming-channels/)

 In Microsoft Excel, 

        `COUNTIF`
    
 is one of the most widely used formulas. It counts all cells in a range that matches a single condition or multiple conditions, and it's equally useful in counting cells with numbers and text in them.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  What Is the COUNTIF function?

        `COUNTIF`
    
 allows users to count the number of cells that meet certain criteria, such as the number of times a part of a word or specific words appears on a list. In the actual formula, you'll tell Excel where it needs to look and what it needs to look for. It counts cells in a range that meets single or multiple conditions, as we'll demonstrate below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l4R7_qNIQvY?si=2zJOPfEcm6_3udzn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Use the COUNTIF Formula in Microsoft Excel

 For this tutorial, we will use simple two-column inventory chart logging school supplies and their quantities.

 In an empty cell, type 

        `=COUNTIF`
    
 followed by an open bracket. The first argument "range" asks for the range of cells you would like to check. The second argument "criteria" asks for what exactly you want Excel to count. This is usually a text string. So, in double-quotes, add the string you want to find. Be sure to add the closing quotemark and the closing bracket.

 So in our example, we want to count the number of times "Pens" appears in our inventory, which includes the range 

        `G9:G15`
    
 . We'll use the following formula.

=COUNTIF(G9:G15,"Pens")

![countif formula example](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/countif-formula.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 You can also count the number of times a specific number appears by putting the number in the criteria argument without quotes. Or you can use operators with numbers inside of quotes to determine results, like `"<100"` to get a count of all numbers less than 100.

Related: [How to Count Colored Cells in Microsoft Excel](https://facebook-video-recording.techidaily.com/new-2024-approved-the-cryptic-collection-of-2023-auction-for-anonymity-artifacts/) 

##  How to Count the Number of Multiple Values

 To count the number of multiple values (e.g. the total of pens and erasers in our inventory chart), you may use the following formula.

=COUNTIF(G9:G15, "Pens")+COUNTIF(G9:G15, "Erasers")

![countif multiple example formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/08/countif-multiple.jpg) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This counts the number of erasers and pens. Note, this formula uses COUNTIF twice since there are multiple criteria being used, with one criterion per expression.

##  Limitations of the COUNTIF Formula

 If your COUNTIF formula uses criteria matched to a string longer than 255 characters, it will return an error. To fix this, use the CONCATENATE function to match strings longer than 255 characters. You can avoid typing out the full function by simply using an ampersand (&), as demonstrated below.

=COUNTIF(A2:A5,"long string"&"another long string")

Related: [How to Use the FREQUENCY Function in Excel](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) 

 One behavior of COUNTIF functions to be aware of is that it disregards upper and lower case strings. Criteria that include a lower case string (e.g. "erasers") and an upper case string (e.g. "ERASERS") will match the same cells and return the same value.

 Another behavior of COUNTIF functions involves the use of wildcard characters. Using an asterisk in COUNTIF criteria will match any sequence of characters. For example, `=COUNTIF(A2:A5, "*eraser*")` will count all cells in a range that contain the word "eraser."

 When you're counting values in a range, you may be interested in [highlighting the top- or bottom-ranked values](https://hardware-updates.techidaily.com/1722966983711-ultimate-solution-to-get-your-epson-et-4550-up-and-running-on-windows-with-proven-techniques/).

| |  Mastering Excel Functions |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |  |
| Functions                    | [AVERAGE](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) **·** [CONCATENATE](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) **·** [COUNT](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) **·** [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) **·** [DATEDIF](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/) **·** [FILTER](https://youtube-sure.techidaily.com/024-approved-the-ultimate-guide-to-youtube-live-streaming/) **·** [FREQUENCY](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) **·** [FV](https://on-screen-recording.techidaily.com/updated-2024-approved-enhancing-gaming-experience-with-steam-switch-control/) **·** [HYPERLINK](https://some-guidance.techidaily.com/updated-the-minimalists-guide-to-aerial-imagery-with-dji-spark/) **·** [IF](https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/) **·** [IFS](https://screen-recording.techidaily.com/updated-ultimate-techniques-for-precise-iptv-screen-imaging/) **·** [IMAGE](https://screen-mirror.techidaily.com/top-10-airplay-apps-in-xiaomi-redmi-note-12-5g-for-streaming-drfone-by-drfone-android/) **·** [INDEX](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) **·** [IS](https://win-amazing.techidaily.com/new-release-gtx-1650-super-driver-updates-compatible-with-windows-11/) **·** [LEN](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) **·** [MATCH](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) **·**[MEDIAN](https://some-techniques.techidaily.com/in-2024-from-novice-to-expert-the-complete-powerdirector-journey/) **·** [RAND](https://instagram-video-recordings.techidaily.com/updated-master-igtv-edits-top-10-tools-ranked/) **·** [ROUND](https://youtube-zero.techidaily.com/ed-2024-approved-the-quick-pathway-to-establishing-a-video-channel-on-your-phone/) **·** [RRI](https://vp-tips.techidaily.com/2024-approved-quick-cash-on-reddit-here-are-13-ways-for-new-users/) **·** [SORT](https://some-techniques.techidaily.com/2024-approved-gopro-versus-polaroid-editing-faces-vs-cameras-that-shoot-them/) **·** [SQRT](https://screen-video-capture.techidaily.com/in-2024-master-guide-ultimate-tips-for-maximizing-mobizens-screen-capture/) **·** [SUBSTITUTE](https://screen-sharing-recording.techidaily.com/updated-maiden-shoot-revelations-and-critique-for-2024/) **·** [SUBTOTAL](https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-a78-5g-drfone-by-drfone-virtual-android/) **·** [SUM](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) **·** [SUMIF](https://on-screen-recording.techidaily.com/pinnacle-platforms-transforming-online-interaction/) **·** [TODAY](https://some-guidance.techidaily.com/2024-approved-unlock-spark-ars-full-potential-with-personalized-lut-implementations/) **·** [TRIM](https://graphic-issues.techidaily.com/regaining-access-to-nvidia-writable-displays/) **·** [TRUNC](https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/) **·** [VLOOKUP](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) **·** [WEEKDAY](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) **·** [XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) **·** [YEAR](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) |  |
| Types                        | [Basic](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) **·** [Budgeting](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) **·** [Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) **·** [Logical](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) **·** [Text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) **·** [Time and Date](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |  |
| Explained                    | [Copying Formulas](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) **·** [Evaluating Formulas](https://youtube-blog.techidaily.com/ed-the-role-of-youtube-images-in-video-promotion-and-discovery-for-2024/) **·** [Finding Functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) **·** [Fixing Formula Errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) **·** [Functions vs Formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) **·** [Comparing Lookup Functions](https://tech-revival.techidaily.com/examining-codegpts-capabilities-in-tech-innovation/) **·** [Locking Formulas](https://some-guidance.techidaily.com/in-2024-unveiling-effective-sales-methods/) **·** [Structuring Formulas](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) **·** [Translating Formulas](https://extra-tips.techidaily.com/techniques-to-reduce-nausea-while-in-vr/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  |

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
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-the-ultimate-manual-for-minecraft-playbacks-on-mac/"><u>[New] In 2024, The Ultimate Manual for Minecraft Playbacks on Mac</u></a></li>
<li><a href="https://win-answers.techidaily.com/solved-civ-6-not-launching-on-windows-10/"><u>[SOLVED] Civ 6 Not Launching on Windows 10</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-chuckle-away-with-premium-complimentary-meme-templates/"><u>[Updated] In 2024, Chuckle Away with Premium Complimentary Meme Templates</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/different-methods-to-unlock-your-apple-iphone-14-by-drfone-ios/"><u>Different Methods To Unlock Your Apple iPhone 14</u></a></li>
<li><a href="https://win-answers.techidaily.com/fix-recurrent-collapses-of-thunder-tier-i-game-on-windows-systems/"><u>Fix Recurrent Collapses of Thunder Tier I Game on Windows Systems</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-4-ways-to-unlock-iphone-13-pro-to-use-usb-accessories-without-passcode-drfone-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock iPhone 13 Pro to Use USB Accessories Without Passcode | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-oppo-reno-10-proplus-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Oppo Reno 10 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-the-challenge-of-lost-arcs-server-connection-error/"><u>Overcoming the Challenge of Lost Arc's Server Connection Error</u></a></li>
<li><a href="https://win-web3.techidaily.com/resolved-overcoming-the-challenge-with-seagate-discwizard-unreadable-by-drives/"><u>Resolved: Overcoming the Challenge with Seagate DiscWizard - Unreadable by Drives</u></a></li>
<li><a href="https://win-answers.techidaily.com/roblox-audio-fixes-for-windows-users-overcoming-the-silent-challenge-in-versions-11-and-10/"><u>Roblox Audio Fixes for Windows Users: Overcoming the Silent Challenge in Versions 11 & 10</u></a></li>
<li><a href="https://win-answers.techidaily.com/1723009147445-star-citizen-no-longer-causes-system-crashes-on-windows-fixed/"><u>Star Citizen No Longer Causes System Crashes on Windows - Fixed</u></a></li>
<li><a href="https://win-answers.techidaily.com/take-preventative-medications-if-you-are-prone-to-recurrent-utis-talk-to-your-doctor-about-the-possibility-of-taking-a-low-dose-of-antibiot5-day-regimen-for447/"><u>Take Preventative Medications: If You Are Prone to Recurrent UTIs, Talk to Your Doctor About the Possibility of Taking a Low Dose of Antibiot#5-Day Regimen for Women with Frequent UTIs and May Be Beneficial in Preventing Future Episodes.</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/technique-to-capture-fb-videos-flawlessly-on-both-systems/"><u>Technique to Capture FB Videos Flawlessly on Both Systems</u></a></li>
</ul></div>

