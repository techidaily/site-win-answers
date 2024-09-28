---
title: How to Export and Save Spreadsheets Using Special Characters Like Pipes as Separators Rather Than Commas
date: 2024-08-27T23:56:49.543Z
updated: 2024-08-28T23:56:49.543Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/07/image121.png
---

## How to Export and Save Spreadsheets Using Special Characters Like Pipes as Separators Rather Than Commas

If you're working with some awful corporate system that should have been retired in the dark ages, you might have had to produce a file from Excel with some weird delimiters other than comma or tab-delimited to import into the system. Here's the trick on how to do it.

 Naturally, this isn't the type of article that most people will need to use, hopefully ever---but if you do need to know how to do it, the solution isn't really obvious at first.

## **Exporting Excel Files as Pipe Delimited** 

 For the purposes of this example, we'll use this silly little Excel file.

 To save the file as Delimited, you'll need to click the Office button and choose Save As --> Other Formats.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/07/image122.png) 

 Then select CSV (Comma delimited)(\*.csv) from the drop-down list, and give it a name.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/07/image123.png) 

 Now here's where the interesting part happens... Excel by default will use a comma as the delimiter, but if you open up Control Panel --> Region and Language, and then click the Additional settings button on the bottom...

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/07/image124.png) 

 Now look very closely at the "List separator" item, which normally has a comma in the field, but for the purposes of illustration I've switched it to a Pipe character.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/07/image125.png) 

 Once you hit Apply, and then save your Excel file, you'll notice that your file now has pipe characters as the delimiter.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2010/07/image126.png) 

 You'll probably want to change the List separator back to a comma just in case some other application needs it.

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



<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->