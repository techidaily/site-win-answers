---
title: "Step-by-Step Guide: Transforming Text Into Dates Within Microsoft Excel"
date: 2024-08-27T23:57:59.953Z
updated: 2024-08-28T23:57:59.953Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/197c2ed369e4a9919f13d946f77f5157856e3dbfa0838cef669c3e3be16ac8df.jpg
---

## Step-by-Step Guide: Transforming Text Into Dates Within Microsoft Excel

### Quick Links

* [Dates that Contain a Full Stop/Period](https://instagram-video-recordings.techidaily.com/updated-in-2024-the-ultimate-guide-to-instagram-desktop-video-upload/)
* [Converting the yyyymmdd Format](https://extra-approaches.techidaily.com/in-2024-step-by-step-tailoring-your-way-to-youtube-subtitles-srt/)
* [DATEVALUE and VALUE Functions](https://hardware-tips.techidaily.com/experience-unmatched-speed-save-75-on-editors-pick-the-elegoo-neptune-4-pro-printer/)

 Analysis of business data often requires working with date values in Excel to answer questions such as "how much money did we make today" or "how does this compare to the same day last week?" And that can be hard when Excel doesn't recognize the values as dates.

 Unfortunately, this is not unusual, especially when multiple users are typing this information, copying and pasting from other systems and importing from databases.

 In this article, we will describe four different scenarios and the solutions to convert the text to date values.

##  Dates that Contain a Full Stop/Period

 Probably one of the most common mistakes beginners make when typing dates into Excel is doing so with the full stop character to separate the day, month, and year.

 Excel will not recognize this as a date value and will go ahead and store it as text. However, you can solve this problem with the Find and Replace tool. By replacing the full stops with slashes (/), Excel will automatically identify the values as dates.

 Select the columns on which you want to perform the find and replace.

![Dates with a full stop separator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/full-stop-dates.png) 

 Click Home > Find & Select > Replace---or press Ctrl+H.

![Find and select values in a column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/find-and-select-1.png) 

 In the Find and Replace window, type a full stop (.) in the "Find what" field and a slash (/) in the "Replace with" field. Then, click "Replace All."

![filling out the find and replace values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/find-and-replace-window-1.png) 

 All full stops are converted to slashes and Excel recognizes the new format as a date.

![Dates with a full stop separator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/full-stop-dates.png) 

 If your spreadsheet data is regularly changing, and you want an automated solution for this scenario, you could use [the SUBSTITUTE function](https://support.office.com/en-us/article/substitute-function-6434944e-a904-4336-a9b0-1e58df3bc332).

=VALUE(SUBSTITUTE(A2,".","/"))

 The SUBSTITUTE function is a text function, so cannot convert it to a date on its own. The VALUE function will convert the text value to a numeric value.

 The results are shown below. The value needs to be formatted as a date.

![SUBSTITUTE formula to convert text to dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/substitute-resized-1.png) 

 You can do this using the "Number Format" list on the "Home" tab.

![Formatting number as a date](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/number-format-2.png) 

 The example here of a full stop delimiter is typical. But you can use the same technique to replace or substitute any delimiter character.

##  Converting the yyyymmdd Format

 If you receive dates in the format shown below, it will require a different approach.

![Dates in the yyyymmdd format](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/yyyymmdd-format.png) 

 This format is quite standard in technology as it removes any ambiguity about how different countries store their date values. However, Excel will not initially understand it.

 For a quick manual solution, you could [use Text to Columns](https://ios-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-apple-iphone-14-pro-for-parents-drfone-by-drfone-virtual-ios/).

 Select the range of values you need to convert and then click Data > Text to Columns.

![Text to Columns button from the Data tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/text-to-columns-resized.png) 

 The Text to Columns wizard appears. Click "Next" on the first two steps so that you are at step three, as shown in the image below. Choose Date and then select the date format being used in the cells from the list. In this example, we are dealing with a YMD format.

![Text to Columns to convert 8 digit numbers to dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/text-to-columns-date-format-3.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you would like a formula solution, then you could use the Date function to construct the date.

 This would be used alongside the text functions Left, Mid and Right to extract the three parts of a date (day, month, year) from the cell contents.

 The formula below shows this formula using our sample data.

=DATE(LEFT(A2,4),MID(A2,5,2),RIGHT(A2,2))

![Using the DATE formula with 8 digit numbers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/date-formula-resized.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 Using either of these techniques, you can convert any eight-digit number value. For example, you might receive the date in a ddmmyyyy format or a mmddyyyy format.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
##  DATEVALUE and VALUE Functions

 Sometimes the problem is not caused by a delimiter character but has an awkward date structure simply because it is stored as text.

 Below is a list of dates in a variety of structures, but they are all recognizable to us as a date. Unfortunately, they have been stored as text and need converting.

![Dates stored as text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/text-dates.png) 

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For these scenarios, it is easy to convert using a variety of techniques.

 For this article, I wanted to mention two functions to handle these scenarios. They are DATEVALUE and VALUE.

 The DATEVALUE function will convert text into a date value (probably saw that coming), while the VALUE function will convert text into a generic number value. The differences between them are minimal.

 In the image above, one of the values contains time information as well. And that will be a demonstration of the functions' minor differences.

 The DATEVALUE formula below would convert each one to a date value.

=DATEVALUE(A2)

![DATEVALUE function to convert to date values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/datevalue-resized.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 Notice how the time was removed from the result in row 4\. This formula strictly returns just the date value. The result will still need to be formatted as a date.

 The following formula uses the VALUE function.

=VALUE(A2)

![VALUE function to convert text to numeric values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/value-resized.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
 This formula will produce the same results except for in row 4, where the time value is also maintained.

 The results can then be formatted as date and time, or as a date to hide the time value (but not remove).

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


