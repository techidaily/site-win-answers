---
title: "Guide: Establishing Upper & Lower Boundaries with Excel's Range Limits"
date: 2024-11-29T18:16:29.951Z
updated: 2024-12-06T18:38:20.472Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/93fd3ecf6c0ec1cdbec9f4930fda0699ca8c617492c26f7c6f508a444f408426.jpg
---

## Guide: Establishing Upper & Lower Boundaries with Excel's Range Limits

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Finding Minimum and Maximum Values in Excel](https://facebook-video-footage.techidaily.com/updated-deciphering-user-insights-in-youtube-comments-for-2024/)
* [How to Produce a Result With a Minimum Value in Excel](https://remote-screen-capture.techidaily.com/updated-in-2024-the-7-best-stardew-valley-mods/)
* [How to Produce a Result With a Maximum Value in Excel](https://unlock-android.techidaily.com/lock-your-vivo-y100-5g-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/)
* [How to Produce Maximum or Minimum Results With Other Formulas in Excel](https://facebook.techidaily.com/unveiling-the-truth-7-pivotal-facebook-revelations/)

 When using Excel, you can create formulas that produce a minimum value or maximum value in a calculation. In this article, we will show you the potential uses of this simple Excel formula and how to implement it in your spreadsheet.

##  Finding Minimum and Maximum Values in Excel

 A more well-known function of Excel lets you [find the highest and/or lowest values](https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-xs-max-to-others-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/) within a range of numbers, handy if you are keeping track of bills in your budget. You can also combine these formulas to [find the range](https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-vivo-y77t-drfone-by-drfone-virtual-android/) (the largest minus the smallest) within that list of numbers if you're looking to produce statistical data. Both of these make use of the MIN and MAX functions in Excel.

 However, a less-known use of the MIN and MAX functions in Excel lets you cap numbers in a spreadsheet, or set a minimum value. Let's see how we can do this.

##  How to Produce a Result With a Minimum Value in Excel

 To produce a result with a minimum value in Excel, use the following formula:

=MAX(X,Y)

 where X is the numerical value or cell reference that determines the minimum value, and Y is the cell reference of the number you are looking to affect. Let's look at how to actually use it. 

 Let's say we own a grocery store, and we take pre-orders from our customers. Now that we have compiled the total number of orders for each fruit, we need to place the order with our wholesaler. However, the wholesaler insists that we order a minimum of 1500 for each fruit.

![Excel sheet containing a table with three columns. The first column contains fruit products, the second column contains customer orders, and the third column (blank) contains orders to make with the wholesaler (minimum 1500).](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/wholesale-orders-blank.png) 

 Therefore, we want Excel to tell us how many pieces of each fruit we need to order from the wholesale to both satisfy our customers' orders and meet the minimum requirement of the wholesaler. Begin by clicking the cell where you want the first calculation to be made (in this case, we're starting with bananas).

 Start to type the following formula:

=MAX(

 This might seem contradictory, as your intention is to provide a minimum result of 1500 in the final column, not a maximum result. However, the reason we type MAX is that we are telling Excel to find the maximum possible value in the calculation, with no upper limit.

 Next, inside the parentheses, we need to type the criterion (in this case, it's 1500):

=MAX(1500

 Finally, we need to add a comma, click or type the cell reference we are looking to affect (in our example, it's cell K20), and then press Enter:

=MAX(1500,J20)

 You can now see the number of bananas we need to order from the wholesaler.

![Excel sheet showing the use of the MAX formula to produce a minimum result of 1500 in the final column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/min-bananas.png) 

 If the minimum criterion is likely to change, instead of typing the minimum number into the formula above, we would type the minimum value into another cell and [use an absolute reference](https://some-approaches.techidaily.com/in-2024-unveiling-3dr-a-personal-perspective-on-printing-alone/) to tell Excel where to find the criterion:

=MAX($K$28,J20)

![Excel sheet showing the minimum value in cell K28 and the correct formula to use to produce a minimum result in the final column of the table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/abs-ref-minimum-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kx-Pb0otJCs?si=Mvr49yQVesmJA8-O" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you were to change "1500" to another number in cell K28, the minimum criterion would automatically change within your calculations in your table.

 We can now apply the same formula to the other cells in the table by [using Excel's AutoFill function](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/).

![Excel sheet showing the total orders in the rightmost column after having applied the minimum value and used AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/min-autofilled-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 We have now fulfilled our customers' orders while also meeting the wholesaler's minimum requirements for each fruit.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  How to Produce a Result With a Maximum Value in Excel

 To produce a result with a minimum value in Excel, use the following formula:

=MIN(X,Y)

 where X is the numerical value or cell reference that determines the maximum value, and Y is the cell reference of the number you are looking to affect. Let's look at this in more detail.

 Let's assume we own a business and offer bonus incentives to our employees. However, we want to cap the bonuses they can receive every two months to $5000.

![Excel sheet containing a table with five columns. The first column contains employee names, the second and third columns contain the respective bonuses to be paid for January and February, the fourth column contains the total bonuses, and the fifth column is headed 'Maximum bonus: 5000' with no values.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/bonus-payments-blank.png) 

 Firstly, type the following formula in the cell where you want the result to show:

=MIN(

 Again, this might seem confusing, as we are aiming to produce a capped value in the final column, not a minimum value. However, we type MIN because we are telling Excel to find the smallest possible value, with no lower limit.

 Next, inside the parentheses, type the criterion (in this example, it's 5000):

=MIN(5000

 Finally, add a comma, click or type the cell reference to be affected (in this case, we would click on cell M20), and press Enter.

=MIN(5000,L20)

 We can now see the maximum result for the first calculation we want to make:

![Excel sheet showing the use of the MIN formula to produce a maximum result of 5000 in the final column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/max-employee-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 If you are likely to change the value of the capped number, type the maximum value in another cell and [reference this cell using an absolute reference](https://some-approaches.techidaily.com/in-2024-unveiling-3dr-a-personal-perspective-on-printing-alone/), instead of typing the maximum value directly into the formula:

=MIN($M$28,L20)

![Excel sheet showing the maximum value in cell M28 and the correct formula to use to produce a minimum result in the final column of the table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/abs-ref-maximum-1.png) 

 As a result, if you were to amend the cap of 5000 in cell M28, the calculations in your table would automatically adjust to your new figure.

 Then, use AutoFill to apply the formula to the remaining cells.

![Excel sheet showing the total bonus in the rightmost column after having applied the maximum value and used AutoFill.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/max-autofilled-1.png) 

##  How to Produce Maximum or Minimum Results With Other Formulas in Excel

 Using a formula within your MIN or MAX calculation can help you to present your spreadsheet more succinctly. Let's say we want to remove the total bonus column altogether in the following table, and get Excel to work out the payment at the same time as considering the maximum value.

![Excel sheet containing a table with five columns. The first column contains employee names, the second and third columns contain the respective bonuses to be paid for January and February, the fourth column contains the total bonuses, and the fifth column is headed 'Maximum bonus: 5000' with no values.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/bonus-payments-blank.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Therefore, our table would initially look like this, and we need to tell Excel to add the totals together for each employee to work out what will go in the final column:

![Excel sheet containing a table with four columns. The first column contains employee names, the second and third columns contain the respective bonuses to be paid for January and February, and the fourth column is headed 'Max 5000' with no values.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/combined-blank-2.png) 

 To work out how much we're paying Tom, in the cell where you want the total to show (L20 in this example), type the following formula and press Enter:

=MIN(5000,(SUM(J20+K20)))

 See the previous sections for further information on how this formula works.

![Excel sheet showing the first result for a calculation where the values in two columns have been added together and a maximum has been applied.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/combined-first-result.png) 

 You can also type the criterion in another cell and [use absolute referencing](https://some-approaches.techidaily.com/in-2024-unveiling-3dr-a-personal-perspective-on-printing-alone/) to link to that cell, rather than the value itself, within your formula, and press Enter:

=MIN($L$28,(SUM(J20+K20)))

![Excel sheet showing the maximum value in cell L28 and the correct formula to use to produce a maximum result in the final column of the table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/abs-ref-combined.png) 

 Now, if you were to amend your cap of 5000 in cell L28, your formula would automatically pick up the newly inserted number.

 Finally, use AutoFill to complete your table.

![Excel sheet showing the totals in the rightmost column after having performed a calculation, applied the maximum value, and used AutoFill in that column.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/combined-autofilled.png) 

 The same method can be used for calculating a maximum number or a minimum number.

---

 Now you know how to cap results or set a minimum value in your Excel spreadsheet!

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
<li><a href="https://win-answers.techidaily.com/the-ascent-release-roadblocks-explained-behind-the-scenes-look-at-what-went-awry/"><u>'The Ascent' Release Roadblocks Explained: Behind-the-Scenes Look at What Went Awry</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-unleash-creativity-in-editing-leveraging-storyremix-with-windows-11-photos/"><u>[Updated] 2024 Approved Unleash Creativity in Editing Leveraging StoryRemix with Windows 11 Photos</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-avoid-ad-dollars-boost-your-view-count-for-free/"><u>[Updated] In 2024, Avoid Ad Dollars – Boost Your View Count for Free</u></a></li>
<li><a href="https://tech-hub.techidaily.com/algorithmic-insights-understanding-gpts-interpretation-engine/"><u>Algorithmic Insights: Understanding GPT's Interpretation Engine</u></a></li>
<li><a href="https://win-tricks.techidaily.com/como-comentar-e-gerenciar-tarefas-de-restauracao-no-windows-11-8-ou-7/"><u>Como Comentar E Gerenciar Tarefas De Restauração No Windows 11, 8 Ou 7</u></a></li>
<li><a href="https://win-answers.techidaily.com/effective-ways-to-troubleshoot-and-overcome-naraka-punishment-slowdowns/"><u>Effective Ways to Troubleshoot and Overcome Naraka: Punishment Slowdowns</u></a></li>
<li><a href="https://win-answers.techidaily.com/enhancing-frame-rates-in-dragons-dogma-2-a-guide-to-fixing-lags-and-pauses/"><u>Enhancing Frame Rates in Dragon's Dogma 2: A Guide to Fixing Lags and Pauses</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-guide-to-fixing-pacific-airspace-disruptions-in-call-of-duty-warzone-mobile/"><u>Expert Guide to Fixing Pacific Airspace Disruptions in Call of Duty: Warzone Mobile</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/how-to-fix-non-functional-links-post-conversion-to-flipbook-format-a-guide-using-flipbuilder/"><u>How to Fix Non-Functional Links Post Conversion to Flipbook Format - A Guide Using FlipBuilder</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-show-wi-fi-password-on-realme-11-proplus-by-drfone-android/"><u>How to Show Wi-Fi Password on Realme 11 Pro+</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-best-playstation-5-and-xbox-series-x-games-consoles-ranked/"><u>In 2024, Best PlayStation 5 & Xbox Series X Games Consoles Ranked</u></a></li>
<li><a href="https://win-answers.techidaily.com/samurai-warriors-5-stability-issues-fixes-and-solutions-for-pc-users/"><u>Samurai Warriors 5 Stability Issues: Fixes and Solutions for PC Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/significantly-shrink-videos-with-winxvideos-ai-achieve-up-to-90-size-reduction/"><u>Significantly Shrink Videos with Winxvideo's AI: Achieve Up to 90% Size Reduction</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-xiaomi-civi-3-disney-100th-anniversary-edition-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Xiaomi Civi 3 Disney 100th Anniversary Edition FRP</u></a></li>
<li><a href="https://win-answers.techidaily.com/understanding-and-solving-the-frequent-frostpunk-system-failures/"><u>Understanding and Solving the Frequent Frostpunk System Failures</u></a></li>
</ul></div>

