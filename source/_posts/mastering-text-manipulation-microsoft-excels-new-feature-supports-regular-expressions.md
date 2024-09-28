---
title: "Mastering Text Manipulation: Microsoft Excel's New Feature Supports Regular Expressions"
date: 2024-08-27T23:57:45.094Z
updated: 2024-08-28T23:57:45.094Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/7fab9a6185158d097b206408c1b02e98fd2b514b00431bdf0c9ec5881d711d0e.jpg
---

## Mastering Text Manipulation: Microsoft Excel's New Feature Supports Regular Expressions

Regular expressions are a powerful way to detect and modify data strings, but Microsoft Excel has never natively supported them. That’s finally changing, with the introduction of regular expression functions in Excel.

[Regular expressions](https://instagram-clips.techidaily.com/discreetly-explore-instagram-stories-with-us-for-2024/), also known as “regex” or “regexp,” are strings used to match patterns in data strings. For example, the regular expression “\\b\[aA\]\\w\*\\b” could match every word in a string that starts with the letter “A,” or you could use “\\b-?\\d+(\\.\\d+)?\\b” to match any number in a string of text. You can then remove, replace, or extract the matches as needed. Regular expressions can be difficult to read and understand, but tools like [Regex101](https://regex101.com/) can be helpful as a guide, and generative AI chatbots like ChatGPT and Microsoft Copilot are great at writing them.

 Microsoft announced three new functions that use regular expressions, available now in the Excel Beta Channel. You can use [REGEXTEST](https://support.microsoft.com/topic/7d38200b-5e5c-4196-b4e6-9bff73afbd31) to check if the supplied text matches a regex pattern, [REGEXEXTRACT](https://support.microsoft.com/topic/4b96c140-9205-4b6e-9fbe-6aa9e783ff57) to extract a match, and [REGEXREPLACE](https://support.microsoft.com/topic/9c030bb2-5e47-4efc-bad5-4582d7100897) to replace a match.

![Excel screenshot using the REGEXEXTRACT function to extract names from a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/reg-function_2.png) 

[Microsoft](https://insider.microsoft365.com/en-us/blog/new-regular-expression-regex-functions-in-excel)

 Microsoft Excel already has functions for many of the popular use cases for regular expressions, but not necessarily _all_ of the use cases. Some people might also be more familiar with the syntax for regular expressions than Excel’s native functions, or they want to share regular expressions across different software (like a Python script and an Excel workbook). Until now, you needed to use workarounds like macros or add-ins to write macros, which aren’t available on all platforms.

 Microsoft also plans to add support for regular expressions to Excel’s [XLOOKUP](https://support.microsoft.com/en-us/office/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929) and [XMATCH](https://support.microsoft.com/en-us/office/xmatch-function-d966da31-7a6b-4a13-a1c6-5a33ed6a0312) functions. Presumably, that will allow searching across entire Excel workbooks for regular expression matches. There are a lot of potential uses for regular expressions, and it’s great to see Microsoft finally embracing them in Excel without the use of third-party tools or workarounds.

 The new functions are available in the Excel Beta Channel, starting with version 2406 (build 17715.20000) on Windows and version 6.86 (Build 24051422) on Mac. Microsoft says these are still preview functions that could change before being broadly released, so don’t use them in important documents for now.

 Source: [Microsoft 365 Insider](https://insider.microsoft365.com/en-us/blog/new-regular-expression-regex-functions-in-excel)

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
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->