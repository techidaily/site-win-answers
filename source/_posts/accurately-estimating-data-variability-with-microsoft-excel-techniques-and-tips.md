---
title: "Accurately Estimating Data Variability with Microsoft Excel: Techniques & Tips"
date: 2024-08-28 22:24:47
updated: 2024-08-29 12:39:50
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/965654acbd64cd762e18be6423e980e53d1c3fa7dd1512b5cfdc18b0e2b93a57.jpg
---

## Accurately Estimating Data Variability with Microsoft Excel: Techniques & Tips

### Quick Links

* [Arithmetic Mean of Values](https://blog-min.techidaily.com/how-can-you-transfer-files-from-vivo-y27s-to-iphone-151413-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [Standard Deviation of the Values](https://extra-skills.techidaily.com/navigating-sales-for-inexpensive-gopros-for-2024/)
* [Calculate the Standard Error](https://games-able.techidaily.com/harmonizing-fun-and-safety-in-childs-steam-world/)
* [Using Error Bars to Present Uncertainty in Charts](https://facebook-record-videos.techidaily.com/updated-in-2024-elevating-your-music-crafting-stunning-lyric-videos-using-lyric-video-maker/)

 There is doubt surrounding the accuracy of most statistical data---even when following procedures and using efficient equipment to test. Excel lets you calculate uncertainty based on your sample's standard deviation.

 There are statistical formulas in Excel we can use to calculate uncertainty. And in this article, we will calculate the arithmetic mean, standard deviation and the standard error. We will also look at how we can plot this uncertainty on a chart in Excel.

 We will use the following sample data with these formulas.

![Sample data to calculate uncertainty](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/sample-data-1.png) 

 This data shows five people that have taken a measurement or reading of some kind. With five different readings, we have uncertainty over what the real value is.

##  Arithmetic Mean of Values

 When you have uncertainty over a range of different values, taking the average (arithmetic mean) can serve as a reasonable estimate.

 This is easy to do in Excel with the AVERAGE function.

 We can use the following formula on the sample data above.

=AVERAGE(B2:B6)

![Mean average of a set of measurements](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/mean-average-1.png) 

##  Standard Deviation of the Values

 The standard deviation functions show how widely spread your data is from a central point (the mean average value we calculated in the last section).

 Excel has a few different standard deviation functions for various purposes. The two main ones are STDEV.P and STDEV.S.

 Each of these will calculate the standard deviation. The difference between the two is that STDEV.P is based on you supplying it with the entire population of values. STDEV.S works on a smaller sample of that population of data.

 In this example, we're using all five of our values in the data set, so we will work with STDEV.P.

 This function works in the same way as AVERAGE. You can use the formula below on this sample of data.

=STDEV.P(B2:B6)

![Standard deviation of a set of values using STDEV.P](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/standard-deviation-1.png) 

 The result of these five different values is 0.16\. This number tells us how different each measurement typically is from the average value.

##  Calculate the Standard Error

 With the standard deviation calculated, we can now find the standard error.

 The standard error is the standard deviation divided by the square root of the number of measurements.

 The formula below will calculate the standard error on our sample data.

=D5/SQRT(COUNT(B2:B6))

![Calculate the standard error](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/standard-error-1.png) 

##  Using Error Bars to Present Uncertainty in Charts

 Excel makes it wonderfully simple to plot the standard deviations or margins of uncertainty on charts. We can do this by adding error bars.

 Below we have a column chart from a sample data set showing a population measured over five years.

![Column chart showing population data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/column-chart-2.png) 

 With the chart selected, click Design > Add Chart Element.

 Then choose from the different error types available.

![Select an error bar type for your chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/error-bars-1.png) 

 You can show a standard error or standard deviation amount for all values as we calculated earlier in this article. You can also display a percentage error change. The default is 5%.

 For this example, we chose to show the percentage.

![Error bars showing percentage margin](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/percentage-error.png) 

 There are some further options to explore to customize your error bars.

 Double-click an error bar in the chart to open the Format Error Bars pane. Select the "Error Bars Options" category if it is not already selected.

 You can then adjust the percentage, standard deviation value, or even select a custom value from a cell that may have been produced by a statistical formula.

![Format error bars to customise them further](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/format-error-bars.png) 

 Excel is an ideal tool for statistical analysis and reporting. It provides many ways to calculate uncertainty so that you get what you need.

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
