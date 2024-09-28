---
title: Effective Strategies to Reduce CPU Load in Excel with VBA
date: 2024-08-27T23:56:11.531Z
updated: 2024-08-28T23:56:11.531Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-00.jpg
---

## Effective Strategies to Reduce CPU Load in Excel with VBA

### Quick Links

* [The Question](https://facebook-video-footage.techidaily.com/updated-in-2024-channel-success-strategy-standard-studio-or-beta-edge/)
* [The Answer](https://desktop-recording.techidaily.com/new-innovative-ways-to-record-without-background-sounds-for-2024/)

 If you have a VBA function that turns Microsoft Excel into a CPU munching beast, is it possible to tame things down so that you can continue to use your computer for other activities while Excel is finishing up? Today's SuperUser Q&A post comes to the rescue to help a frustrated reader get Excel back under control.

 Today’s Question & Answer session comes to us courtesy of SuperUser—a subdivision of Stack Exchange, a community-driven grouping of Q&A web sites.

 Alien warrior clip art courtesy of [Clker.com](http://www.clker.com/clipart-alien-warrior.html).

##  The Question

 SuperUser reader learningAsIGo wants to know if there is a way to limit Microsoft Excel's CPU usage while running a VBA script on his computer:

> Is there a way to limit Microsoft Excel's CPU usage when it is running? I have a VBA script that calculates a large amount of giant array formulas. The entire set of calculations takes approximately twenty minutes to complete and uses 100 percent of my CPU. I am unable to use my computer during this time and would rather have Excel 'running in the background' while using about 50 percent of my CPU's capacity so that I can continue to do other things.
> 
> Any suggestions? My computer's operating system is Windows 7 Enterprise 64-bit with a 2007 32-bit version of Excel installed on it.

 Is there a way to limit Microsoft Excel's CPU usage while running VBA functions?

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  The Answer

 SuperUser contributor mtone has the answer for us:

> If a VBA function is called from several formulas or if your script generates or forces the recalculation of several formulas, then this should definitely make use of the multi-threaded calculation feature in Microsoft Excel. Respectively, this would either run multiple instances of your VBA function for each formula, or recalculate multiple cells simultaneously while your VBA script is running on a single thread.
> 
> You can limit the number of threads used by Excel to recalculate formulas by going to Options and selecting the Advanced Section, then scrolling down until you reach the Formulas sub-section.
> 
> ![how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
---

 Have something to add to the explanation? Sound off in the comments. Want to read more answers from other tech-savvy Stack Exchange users? [Check out the full discussion thread here](http://superuser.com/questions/1025428/limit-excel-cpu-usage).

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


