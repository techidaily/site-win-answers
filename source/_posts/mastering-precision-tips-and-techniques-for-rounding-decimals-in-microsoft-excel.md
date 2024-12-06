---
title: "Mastering Precision: Tips & Techniques for Rounding Decimals in Microsoft Excel"
date: 2024-11-29T18:44:33.035Z
updated: 2024-12-06T18:37:29.684Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Round Off Decimal Values Using the ROUND Function

 The ROUND function rounds numbers to a certain number of decimal places that you configure. If the next digit to the right is between zero and four, it rounds down. So, for example, if you were rounding down to two decimal places, 8.532 would become 8.53\. If the next digit is between five and nine, it rounds up. So, 8.538 would become 8.54\. The ROUND function can round numbers to the right or left of the decimal point.

 You can apply the format to empty cells or to cells that already have numbers in them. You can also use ROUND as part of a more complicated formula if you want to. For example, you could create a formula that adds two columns together using the SUM function, and then rounds the result.

 For this example, we've got a column of numbers named "Values" that contains our raw numbers. We're creating a second column named "Results" that we're going to use to round down the numbers in the "Values" column to three digits.

![img_5b2ad361f3557](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad361f3557.png) 

 Select the cell where you want your rounded results to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

 Navigate to the "Formulas" menu on the main ribbon.

![img_5b2cd18c7eadf](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd18c7eadf.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click the "Math & Trig" formulas drop-down menu.

![img_5b2cd1c366409](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd1c366409.png) 

 On the "Math & Trig" drop-down menu, click the "ROUND" function.

![img_5b2cd1fd04448](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd1fd04448.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This pops up the Function Arguments window with the fields you'll use for setting the ROUND function.

![img_5b2cd2396400b](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd2396400b.png) 

 Use the "Number" field for the number you want to round. You can use type a straight up number in this field to round it, but more often you'll want to call a number from an existing cell in your sheet. Here, we're using B6 to specify the top cell in our "Values" column.

![img_5b2cd2b3cdd05](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd2b3cdd05.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 And then dragging to select the rest of the rows that you want to round.

![img_5b2cd3fe8560e](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd3fe8560e.png) 

 All of your values will now be rounded using the same properties you selected. You can also copy the cell to which you've already applied rounding, and then paste to other cells to copy the formula there.

![img_5b2cd431f381d](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd431f381d.png) 

 You can also do all this just using Excel's Function bar if you want.

 Select the column where you want your rounded numbers to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Click the Function bar to activate it.

![img_5b2cd5a995ad0](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5a995ad0.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Type in your formula using the syntax:

=ROUND(number,num_digits)

 Where "number" is the cell you want to round and "num\_digits" identifies the number of digits to which you want to round.

 For example, here's how we'd type the same rounding formula we previously applied using the dialog box.

![img_5b2cd5d70eb57](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5d70eb57.png) 

 Hit Enter (or Return) after typing your formula, and your number is now rounded.

![img_5b2cd5fc8316a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5fc8316a.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Round Numbers Up or Down Using the ROUNDUP or ROUNDDOWN Functions

 Sometimes, you may want your numbers to just round numbers up or down instead of having the next digit decide that for you. That's what the ROUNDUP and ROUNDDOWN functions are for, and and using them is pretty much identical to using the ROUND function.

 Click the cell where you want your rounded result to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

 Head to Formulas > Math & Trig, and then choose either the "ROUNDUP" or "ROUNDDOWN" function from the dropdown menu.

![Untitled](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/Untitled.png) 

 Enter the number (or cell) you want to round in the "Number" field. Enter the number of digits to which you want to round in the "Num\_digits" field. And the same rules apply as with the ROUND function. A positive integer rounds to the right of the decimal point, zero rounds to the nearest integer, and a negative integer rounds to the left of the decimal point.

 Click "OK" when you've got things set up.

![img_5b2cd7d91b50f](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd7d91b50f.png) 

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-optimizing-video-content-with-powerful-hashtags-on-youtube/"><u>[New] 2024 Approved Optimizing Video Content with Powerful Hashtags on YouTube</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-securing-speech-accuracy-techniques-for-perfect-translation/"><u>[New] 2024 Approved Securing Speech Accuracy Techniques for Perfect Translation</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-perfecting-game-capture-techniques-and-tricks/"><u>[New] Perfecting Game Capture Techniques & Tricks</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-investing-in-the-future-learning-to-proficiently-record-skype-calls-for-2024/"><u>[Updated] Investing in the Future Learning to Proficiently Record Skype Calls for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/complete-guide-to-fixing-the-disc-error-in-cod-warzone-version-50-and-31-on-pc/"><u>Complete Guide to Fixing the Disc Error in COD Warzone Version 5.0 and 3.1 on PC</u></a></li>
<li><a href="https://blog-min.techidaily.com/decouvrez-les-plus-performants-logiciels-gratuits-pour-dupliquer-des-dvd-completement-et-facilement/"><u>Découvrez Les Plus Performants Logiciels Gratuits Pour Dupliquer Des DVD - Complètement Et Facilement! 📀</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722998401221-destiny-2-pc-version-fixed-now-launching-successfully/"><u>Destiny 2 PC Version Fixed: Now Launching Successfully!</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-update-amd-radeon-rx-480-drivers-with-simple-steps/"><u>Download & Update AMD Radeon RX 480 Drivers with Simple Steps</u></a></li>
<li><a href="https://win-answers.techidaily.com/driver-problems-for-pc-outdated-or-corrupted-drivers-could-be-causing-a-black-screen-on-your-computer-updating-or-reinstalling-graphic-card-drivers-and-disp489/"><u>Driver Problems (for PC): Outdated or Corrupted Drivers Could Be Causing a Black Screen on Your Computer. Updating or Reinstalling Graphic Card Drivers and Display Adapter Software Might Resolve the Issue.</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/in-2024-building-rapport-an-interviewers-toolkit/"><u>In 2024, Building Rapport An Interviewer's Toolkit</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/leveraging-vlc-media-player-for-remote-streaming-for-2024/"><u>Leveraging VLC Media Player for Remote Streaming for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-the-setup-ensuring-smooth-minecraft-installs-on-windows-11-machines/"><u>Mastering the Setup: Ensuring Smooth Minecraft Installs on Windows 11 Machines</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/prime-voice-recorders-for-online-use/"><u>Prime Voice Recorders for Online Use</u></a></li>
<li><a href="https://win-answers.techidaily.com/solving-common-issues-with-thaumaturges-pc-launch-failures/"><u>Solving Common Issues with Thaumaturge's PC Launch Failures</u></a></li>
<li><a href="https://win-answers.techidaily.com/stabilize-starfield-gaming-experience-top-fixes-for-crashing-and-freezing-problems-in-pc-version/"><u>Stabilize 'Starfield' Gaming Experience: Top Fixes for Crashing & Freezing Problems in PC Version</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshoot-your-call-of-duty-warzone-flickering-issues-step-by-step-guide/"><u>Troubleshoot Your Call of Duty Warzone Flickering Issues - Step by Step Guide</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-high-cpu-drain-in-phasmophobia-effective-solutions/"><u>Troubleshooting High CPU Drain in Phasmophobia: Effective Solutions</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-the-ultimate-guide-to-video-editing-in-windows-tips-tricks-and-techniques-for-2024/"><u>Updated The Ultimate Guide to Video Editing in Windows Tips, Tricks, and Techniques for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/warzone-woes-crack-the-code-of-developer-error-5573-for-pc-and-console-systems-in-this-comprehensive-guide/"><u>Warzone Woes? Crack the Code of Developer Error 5573 for PC and Console Systems in This Comprehensive Guide</u></a></li>
</ul></div>

