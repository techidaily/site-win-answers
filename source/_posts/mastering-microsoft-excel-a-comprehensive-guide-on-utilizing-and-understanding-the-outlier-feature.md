---
title: "Mastering Microsoft Excel: A Comprehensive Guide on Utilizing and Understanding the Outlier Feature"
date: 2024-12-04T18:05:50.472Z
updated: 2024-12-06T18:38:59.390Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 

 An outlier is a value that is significantly higher or lower than most of the values in your data. When using Excel to analyze data, outliers can skew the results. For example, the mean average of a data set might truly reflect your values. Excel provides a few useful functions to help manage your outliers, so let's take a look.

##  A Quick Example

 In the image below, the outliers are reasonably easy to spot---the value of two assigned to Eric and the value of 173 assigned to Ryan. In a data set like this, it's easy enough to spot and deal with those outliers manually.

![Range of values containing outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/dataset-border.png) 

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Hpne0zPsZwU?si=yN5QDsG_WLb_Y3u-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Let's get started.

###  Step One: Calculate the Quartiles

 If you divide your data into quarters, each of those sets is called a quartile. The lowest 25% of numbers in the range make up the 1st quartile, the next 25% the 2nd quartile, and so on. We take this step first because the most widely-used definition of an outlier is a data point that is more than 1.5 interquartile ranges (IQRs) below the 1st quartile, and 1.5 interquartile ranges above the 3rd quartile. To determine those values, we first have to figure out what the quartiles are.

 Excel provides a QUARTILE function to calculate quartiles. It requires two pieces of information: the array and the quart.

=QUARTILE(array, quart)

 The array is the range of values that you are evaluating. And the quart is a number that represents the quartile you wish to return (e.g., 1 for the 1st quartile, 2 for the 2nd quartile, and so on).

**Note:** In Excel 2010, Microsoft released the QUARTILE.INC and QUARTILE.EXC functions as improvements to the QUARTILE function. QUARTILE is more backward compatible when working across multiple versions of Excel.

 Let's return to our example table.

![Range for quartiles](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/quartile-cells-border.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To calculate the 1st Quartile we can use the following formula in cell F2.

=QUARTILE(B2:B14,1)

 As you enter the formula, Excel provides a list of options for the quart argument.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/quartile-with-border-1.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xg3PHS_Ee80?si=fE_iGIqHjKvWFIN3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 To calculate the 3rd quartile, we can enter a formula like the previous one in cell F3, but using a three instead of a one.

=QUARTILE(B2:B14,3)

 Now, we've got the quartile data points displayed in the cells.

![1st and 3rd quartile values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/1st-and-3rd-quartiles-border.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4DJKH1uY7P0?si=tCG66XVlbwSKoATj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Step Two: Evaluate the Interquartile Range

 The interquartile range (or IQR) is the middle 50% of values in your data. It is calculated as the difference between the 1st quartile value and the 3rd quartile value.

 We're going to use a simple formula into cell F4 that subtracts the 1st quartile from the 3rd quartile:

=F3-F2

 Now, we can see our interquartile range displayed.

![Interquartile value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/iqr-border.png) 

###  Step Three: Return the Lower and Upper Bounds

 The lower and upper bounds are the smallest and largest values of the data range that we want to use. Any values smaller or larger than these bound values are the outliers.

 We'll calculate the lower bound limit in cell F5 by multiplying the IQR value by 1.5 and then subtracting it from the Q1 data point:

=F2-(1.5*F4)

![Excel formula for lower bound value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/l-bound-border.png) 

**Note:** The brackets in this formula are not necessary because the multiplication part will calculate before the subtraction part, but they do make the formula easier to read.

 To calculate the upper bound in cell F6, we'll multiply the IQR by 1.5 again, but this time add it to the Q3 data point:

=F3+(1.5*F4)

![Lower and upper bound values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/l-bound-and-u-bound-border.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

###  Step Four: Identify the Outliers

 Now that we've got all our underlying data set up, it's time to identify our outlying data points---the ones that are lower than the lower bound value or higher than the upper bound value.

 We'll use the [OR function](https://support.office.com/en-us/article/or-function-7d17ad14-8700-4281-b308-00b131e22af0) to perform this logical test and show the values that meet these criteria by entering the following formula into cell C2:

=OR(B2<$F$5,B2>$F$6)

![OR function to identify outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/or-function-border-1.png) 

 We'll then copy that value into our C3-C14 cells. A TRUE value indicates an outlier, and as you can see, we've got two in our data.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/found-outliers-border-224x300.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GFHH14XlFCk?si=2HcjQbDx5eG0ZQAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-discover-the-power-of-proportions-in-youtube-content-creation/"><u>[New] 2024 Approved Discover the Power of Proportions in YouTube Content Creation</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-premier-10-layouts-ae-text-edition/"><u>[Updated] Premier 10 Layouts AE Text Edition</u></a></li>
<li><a href="https://win-answers.techidaily.com/1722992127345-discord-and-javascript-woes-heres-how-to-fix-them/"><u>Discord and JavaScript Woes? Here’s How to Fix Them</u></a></li>
<li><a href="https://win11.techidaily.com/enhance-windows-application-speed-through-improved-networking/"><u>Enhance Windows Application Speed Through Improved Networking</u></a></li>
<li><a href="https://vp-tips.techidaily.com/green-canvas-essential-templates-to-enhance-your-cinematographic-journey/"><u>Green Canvas Essential Templates to Enhance Your Cinematographic Journey</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-stop-cyberpunk-2n77-from-crashing-on-your-pc-solutions-inside/"><u>How to Stop Cyberpunk 2N77 From Crashing on Your PC - Solutions Inside!</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcome-firefox-stutter-and-freeze-expert-advice-for-smooth-browsing/"><u>Overcome Firefox Stutter and Freeze: Expert Advice for Smooth Browsing</u></a></li>
<li><a href="https://win-answers.techidaily.com/proven-techniques-for-a-smooth-city-skylines-gaming-experience-amidst-2ebrs-technical-hurdles/"><u>Proven Techniques for a Smooth City Skylines Gaming Experience Amidst 2Ebr's Technical Hurdles</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ps5s-lackluster-launcher-an-underwhelming-review-of-godfall/"><u>PS5's Lackluster Launcher: An Underwhelming Review of Godfall</u></a></li>
<li><a href="https://win-answers.techidaily.com/starcraft-2-pc-compatibility-fixing-instances-of-the-game-shutting-down-unexpectedly/"><u>Starcraft 2 PC Compatibility: Fixing Instances of the Game Shutting Down Unexpectedly</u></a></li>
<li><a href="https://technical-tips.techidaily.com/top-rated-mini-tablets-of-2024-in-depth-comparison-and-reviews-by-tech-gurus/"><u>Top-Rated Mini Tablets of 2024 - In-Depth Comparison & Reviews by Tech Gurus</u></a></li>
</ul></div>

