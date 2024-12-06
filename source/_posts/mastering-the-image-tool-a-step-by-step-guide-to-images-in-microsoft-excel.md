---
title: "Mastering the Image Tool: A Step-by-Step Guide to Images in Microsoft Excel"
date: 2024-12-02T18:57:51.446Z
updated: 2024-12-06T18:11:17.116Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/ff2e2b344a8396c6bab8264d1025798025a6c7a29bed97ca0ab60000543775d0.jpg
---

## Mastering the Image Tool: A Step-by-Step Guide to Images in Microsoft Excel

### Quick Links

* [About the IMAGE Function](https://tiktok-video-recordings.techidaily.com/updated-exploring-options-a-treasure-hunt-for-your-tiktok-symbol-for-2024/)
* [Use the IMAGE Function in Excel](https://some-skills.techidaily.com/sky-high-storage-cutting-edge-cloud-picks-for-2024/)

 If you want to [include an image in Excel](https://win-forum.techidaily.com/expert-advice-strengthen-windows-defenses-with-these-5-techniques/), like a company logo or product photo, you can add the image using the Insert tab. But, to keep the image within a particular cell, use the IMAGE function instead.

 With this handy function, you add the URL for the image, optionally include alternative text, and choose how you want the image sized within the cell.

 As of October 2022, the IMAGE function is available to [Office Insiders](https://tech-haven.techidaily.com/rethinking-ai-why-claude-3-surpasses-chatgpt-in-4-ways/) and will then roll out over time to Microsoft 365 subscribers on Windows, Mac, Android, iPhone, and the web.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  About the IMAGE Function

 The syntax for the function is 

        `IMAGE(url, alt_text, sizing, height, width)`
    
 where only the first argument is required. This argument is the URL for the image, which should be placed in quotation marks. Below are descriptions of the four optional arguments:

* **Alt\_text**: Include alternative (alt) text to improve accessibility; the text should be placed within quotes.
* **Sizing**: Enter one of four sizing options: 0 to fit the image in the cell and maintain the aspect ratio, 1 to fit the image in the cell and ignore the aspect ratio, 2 to maintain the original image size, or 3 to customize the size using the height and width arguments.
* **Height**: Use with 3 for the sizing and enter the height in pixels.
* **Width**: Use with 3 for the sizing and enter the width in pixels.

 You can insert BMP, GIF, ICO, JPG, PNG, TIFF, and WEBP image formats.

##  Use the IMAGE Function in Excel

 Now that you know how to build the formula and understand the supported image file formats, let's look at some examples using the IMAGE function with the picture below.

 The sample image is from our how-to on [overlaying images in Word](https://phone-solutions.techidaily.com/in-2024-prevent-cross-site-tracking-on-vivo-y200-and-browser-drfone-by-drfone-virtual-android/).

![Image example for the IMAGE function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/Image-ExcelIMAGEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 In this first example, we'll insert the image without alt text or optional sizing using this formula:

=IMAGE("https://www.howtogeek.com/wp-content/uploads/2021/10/MicrosoftWord-OverlayImages.png")

 Here, the image stays within the cell and maintains its aspect ratio as you resize the cell by [adjusting the row and column](https://easy-unlock-android.techidaily.com/in-2024-unlock-your-realme-11-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/). It's the same as using 0 for the `sizing` argument.

![IMAGE function in Excel with no optional arguments](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/Default-ExcelIMAGEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Next, we'll include the alt text "dog" and use the sizing option 1 to keep the image in the cell but ignore the aspect ratio with this formula:

=IMAGE("https://www.howtogeek.com/wp-content/uploads/2021/10/MicrosoftWord-OverlayImages.png","dog",1)

 You can see that if we change the size of the cell, the image is skewed per the sizing option.

![IMAGE function with alt text and sizing option 1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/Sizing1AltText-ExcelIMAGEFunction.png) 

 Now, we'll use the following formula with the alt text and sizing option 2 to keep the image's original size:

=IMAGE("https://www.howtogeek.com/wp-content/uploads/2021/10/MicrosoftWord-OverlayImages.png","dog",2)

 This is a large image (1,200 by 675 pixels), so it doesn't fit within the cell at the cell's current size. However, we wanted to demonstrate maintaining the original image size.

![IMAGE function with alt text and sizing option 2](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/Sizing2AltText-ExcelIMAGEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Finally, we'll remove the alt text leaving empty quotation marks for the argument. And we'll use a custom size for our image with 3 for the sizing, 280 pixels for the height, and 500 pixels for the width. Here's the formula:

=IMAGE("https://www.howtogeek.com/wp-content/uploads/2021/10/MicrosoftWord-OverlayImages.png","",3,280,500)

 If we resize the cell, the image maintains its aspect ratio for the dimensions we entered.

![IMAGE function without alt text and sizing option 3](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/10/Sizing3NoAltText-ExcelIMAGEFunction.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Adding an image in Excel was never difficult; however, the [introduction of the IMAGE function](https://sim-unlock.techidaily.com/in-2024-unlock-your-apple-iphone-se-2020-in-minutes-with-iccid-code-everything-you-need-to-know-by-drfone-ios/) means you can place a picture within a cell and keep it there in whatever size you want.

 For more on images in Excel, check out how to [quickly remove all pictures](https://fox-helps.techidaily.com/2024-approved-your-guide-to-the-top-8-tablets-for-next-level-photo-enhancements/) in your sheet or how to [get rid of the background in a picture](https://win-dash.techidaily.com/efficient-printing-with-toshiba-free-driver-downloads-for-windows-users/).

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
<li><a href="https://win-answers.techidaily.com/solved-satisfactory-fps-drops/"><u>[Solved] Satisfactory FPS Drops</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-10-top-must-have-gear-items-for-youtubers/"><u>[Updated] 10 Top Must-Have Gear Items for YouTubers</u></a></li>
<li><a href="https://win-answers.techidaily.com/diagnosis-and-repair-tips-for-grand-theft-auto-online-malfunctions/"><u>Diagnosis & Repair Tips for Grand Theft Auto Online Malfunctions</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-install-official-dell-g15-graphics-drivers-for-windows/"><u>Download & Install Official Dell G15 Graphics Drivers for Windows</u></a></li>
<li><a href="https://solve-latest.techidaily.com/guide-simple-et-facile-pour-transferer-des-fichiers-dvd-en-haute-definition-sur-mac/"><u>Guide Simple Et Facile Pour Transférer Des Fichiers DVD en Haute Définition Sur Mac</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-address-missing-textures-in-the-popular-battle-royale-warzone/"><u>How to Address Missing Textures in the Popular Battle Royale: Warzone</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722992717217-how-to-enjoy-the-classic-gaming-experience-with-la-noire-for-pc-now-available/"><u>How to Enjoy the Classic Gaming Experience with L.A. Noire for PC – Now Available</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-poco-c50-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Poco C50 | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-can-we-unlock-our-meizu-21-phone-screen-by-drfone-android/"><u>In 2024, How Can We Unlock Our Meizu 21 Phone Screen?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/have-filmmaking-tools-for-aspiring-youtubers-for-2024/"><u>Must-Have Filmmaking Tools for Aspiring YouTubers for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/no-signal-detected-from-finger-id-device/"><u>No Signal Detected From Finger ID Device</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-guide-fixing-startup-failures-for-starfield-on-steam-and-xbox/"><u>Step-by-Step Guide: Fixing Startup Failures for Starfield on Steam and Xbox</u></a></li>
<li><a href="https://win-answers.techidaily.com/tamper-proof-strategies-to-overcome-cod-warzone-error-6328-updates/"><u>Tamper-Proof Strategies to Overcome COD Warzone Error 6328 Updates</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-guide-to-smooth-video-extraction-via-funimate-for-2024/"><u>The Ultimate Guide to Smooth Video Extraction via Funimate for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-imei-unlokers-for-your-oppo-a79-5g-phone-by-drfone-android/"><u>Top IMEI Unlokers for Your Oppo A79 5G Phone</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-fixing-the-crash-error-in-mount-and-blade-bannerlord-game/"><u>Troubleshooting Guide - Fixing the Crash Error in Mount & Blade ˈBannerlord Game</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-guide-unstick-your-discord-stream-for-smooth-viewing/"><u>Troubleshooting Guide: Unstick Your Discord Stream for Smooth Viewing</u></a></li>
</ul></div>

