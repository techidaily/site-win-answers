---
title: "Step-by-Step Guide: Crafting Interdependent Combo Box Selections Within MS Excel"
date: 2024-12-05T18:23:24.119Z
updated: 2024-12-06T17:16:14.304Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/52b4eaebcfcbc6c7fedd891af89526f0d5ee168fe7bb540778411c3fb0605514.jpg
---

## Step-by-Step Guide: Crafting Interdependent Combo Box Selections Within MS Excel

### Quick Links

* [Getting Started](https://extra-lessons.techidaily.com/speeding-up-projects-without-compromising-quality/)
* [Adding and Naming Dependent Drop-Down List Items](https://youtube-clips.techidaily.com/new-cutting-edge-editors-scouting-the-ultimate-tools-for-youtube-shorts/)
* [Creating the Dependent Drop-Down List](https://fox-helps.techidaily.com/2024-approved-adding-captions-and-text-a-guide-for-photo-titles-in-microsoft-photos/)

 Does using a drop-down list in Microsoft Excel make data entry easier for you or your co-workers? If you said yes and want to go a step further, you can create a dependent drop-down list just as easily.

 With a dependent drop-down list, you select the item that you want in the first list, and that determines the items that display as choices in the second one. For example, you might select a product, like a shirt, and then pick a size, a food item, like ice cream, and then pick a flavor, or an album, and then pick a song.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Getting Started

 Obviously, you'll need your first drop-down list set up and ready to go before you can create the dependent list. We have a complete tutorial with all of the details you need to [create a drop-down list in Excel](https://hardware-updates.techidaily.com/download-and-install-the-newest-version-of-corsair-k55-drivers-today/) for a refresher, so be sure to check that out.

Related: [How to Add a Drop-Down List to a Cell in Excel](https://hardware-updates.techidaily.com/download-and-install-the-newest-version-of-corsair-k55-drivers-today/) 

 Since setting up the second list follows the same basic process, we'll start there. Then, we'll move on to the dependency setup.

##  Adding and Naming Dependent Drop-Down List Items

 For this tutorial, we'll use departments in our company for the first drop-down list, and then employees in each department for the second list.

 Our departments include Marketing, Finance, and Human Resources (HR), and each has three employees. These employees are who we need to add and name.

 List the items for the dependent list, and then select the cells. This places the cells in a group so that you can name the group. With the cells selected, go up to the Name Box on the left side of the Formula Bar and [enter a name for the cell group](https://fox-blue.techidaily.com/2024-approved-mastering-chroma-key-techniques-in-live-broadcasts/).

![Name a cell group in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/NameCellGroupDependentList-Excel.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The names for each group should match the list items in your first dropdown.

 Using our example, we'll name our groups with the departments in our first list: Marketing, Finance, and HR.

![Named cell groups](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/NamedCellGroupDependentList-Excel.png) 

 You can add the items for your dependent list on the same sheet where the list will reside or on a different one. For the purposes of this how-to, you'll notice that we have everything on the same sheet.

##  Creating the Dependent Drop-Down List

 Once all of your list items are in a sheet and named, it's time to create the second drop-down list. You'll use [the Data Validation feature in Excel](https://extra-lessons.techidaily.com/mastering-iphone-saving-and-utilizing-gifs-effectively/), just like when creating your first list.

 Select the cell where you want the list. Then, go to the Data tab and click "Data Validation" in the Data Tools section of the ribbon.

![Click Data Validation on the Data tab in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/DataTabValidationDependentList-Excel.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Choose the Settings tab in the pop-up window. Under Allow, pick "List," and to the right, check the box for In-Cell Dropdown. Optionally, you can check the box to Ignore Blank cells if you like.

![Select List and In-Cell Dropdown](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/DataValidationDependentList-Excel.png) 

 In the Source box, enter the formula below. Be sure to replace the cell reference in parentheses with the cell containing your first drop-down list.

=INDIRECT($B$6)

![Add INDIRECT as the Source](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/IndirectSourceDependentList-Excel.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_SbYznUy_zY?si=ThBkP934r3mizi48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The INDIRECT function "returns the reference specified by a text string." For additional details on this function, check out the [Microsoft Support](https://support.microsoft.com/en-us/office/indirect-function-474b3a3a-8a26-4f44-b491-92b6306fa261) page.

 If you'd like to include an Input Message or Error Alert, select those tabs in the pop-up window and enter the details. When you finish, click "OK" to add the drop-down list to the cell.

 Now, give your list a test. When you select an item in the first drop-down list, you should see the items pertaining to your selection as options in the second list.

![Dependent drop-down list in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/DependentDropdownList-Excel.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 For quicker data entry for yourself or your collaborators, try a dependent drop-down list in Excel!

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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-how-to-make-your-profile-cover-video-more-attractive/"><u>[New] In 2024, How to Make Your Profile Cover Video More Attractive</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-highlight-strategy-guide-10-must-try-tips-for-your-business/"><u>2024 Approved Highlight Strategy Guide 10 Must-Try Tips for Your Business</u></a></li>
<li><a href="https://win-answers.techidaily.com/banish-your-woes-in-star-wars-jedi-fallen-order-squadron-with-fixes-for-critical-errors/"><u>Banish Your Woes in Star Wars Jedi: Fallen Order Squadron with Fixes for Critical Errors!</u></a></li>
<li><a href="https://win-answers.techidaily.com/conquering-the-league-wont-start-error-expert-solutions-for-players-in-2eight-fourteen/"><u>Conquering the 'League Won't Start' Error: Expert Solutions for Players in 2Eight Fourteen</u></a></li>
<li><a href="https://win-answers.techidaily.com/diagnose-and-repair-error-0x803f8001-ensuring-smooth-gameplay-on-minecraft-launcher-in-windows-environments/"><u>Diagnose and Repair Error 0X803F8001: Ensuring Smooth Gameplay on Minecraft Launcher in Windows Environments</u></a></li>
<li><a href="https://win-answers.techidaily.com/effortless-solutions-repairing-pc-crashes-in-wwe-2k2e/"><u>Effortless Solutions: Repairing PC Crashes in WWE 2K2e</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-to-keep-a-record-of-your-chatgpt-sessions-with-these-4-amazing-extensions/"><u>How to Keep a Record of Your ChatGPT Sessions with These 4 Amazing Extensions</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/live-play-and-log-mobile-gaming-with-samsung/"><u>Live, Play & Log Mobile Gaming with Samsung</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-fcp-file-management-101-saving-and-organizing-your-projects/"><u>New In 2024, FCP File Management 101 Saving and Organizing Your Projects</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolved-why-battlefield-4-was-failing-to-start-on-your-windows-machine/"><u>Resolved: Why Battlefield 4 Was Failing to Start on Your Windows Machine</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-rated-computer-audio-cards-in-2eby-2024-your-ultimate-guide/"><u>Top-Rated Computer Audio Cards in 2Eby 2024: Your Ultimate Guide</u></a></li>
</ul></div>

