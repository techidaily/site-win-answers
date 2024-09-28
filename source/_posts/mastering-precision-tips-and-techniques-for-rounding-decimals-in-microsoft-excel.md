---
title: "Mastering Precision: Tips & Techniques for Rounding Decimals in Microsoft Excel"
date: 2024-08-27T23:57:43.049Z
updated: 2024-08-28T23:57:43.049Z
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

##  Round Off Decimal Values Using the ROUND Function

 The ROUND function rounds numbers to a certain number of decimal places that you configure. If the next digit to the right is between zero and four, it rounds down. So, for example, if you were rounding down to two decimal places, 8.532 would become 8.53\. If the next digit is between five and nine, it rounds up. So, 8.538 would become 8.54\. The ROUND function can round numbers to the right or left of the decimal point.

 You can apply the format to empty cells or to cells that already have numbers in them. You can also use ROUND as part of a more complicated formula if you want to. For example, you could create a formula that adds two columns together using the SUM function, and then rounds the result.

 For this example, we've got a column of numbers named "Values" that contains our raw numbers. We're creating a second column named "Results" that we're going to use to round down the numbers in the "Values" column to three digits.

![img_5b2ad361f3557](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad361f3557.png) 

 Select the cell where you want your rounded results to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

 Navigate to the "Formulas" menu on the main ribbon.

![img_5b2cd18c7eadf](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd18c7eadf.png) 

 Click the "Math & Trig" formulas drop-down menu.

![img_5b2cd1c366409](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd1c366409.png) 

 On the "Math & Trig" drop-down menu, click the "ROUND" function.

![img_5b2cd1fd04448](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd1fd04448.png) 

 This pops up the Function Arguments window with the fields you'll use for setting the ROUND function.

![img_5b2cd2396400b](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd2396400b.png) 

 Use the "Number" field for the number you want to round. You can use type a straight up number in this field to round it, but more often you'll want to call a number from an existing cell in your sheet. Here, we're using B6 to specify the top cell in our "Values" column.

![img_5b2cd2b3cdd05](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd2b3cdd05.png) 

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

 And then dragging to select the rest of the rows that you want to round.

![img_5b2cd3fe8560e](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd3fe8560e.png) 

 All of your values will now be rounded using the same properties you selected. You can also copy the cell to which you've already applied rounding, and then paste to other cells to copy the formula there.

![img_5b2cd431f381d](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd431f381d.png) 

 You can also do all this just using Excel's Function bar if you want.

 Select the column where you want your rounded numbers to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

 Click the Function bar to activate it.

![img_5b2cd5a995ad0](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5a995ad0.png) 

 Type in your formula using the syntax:

=ROUND(number,num_digits)

 Where "number" is the cell you want to round and "num\_digits" identifies the number of digits to which you want to round.

 For example, here's how we'd type the same rounding formula we previously applied using the dialog box.

![img_5b2cd5d70eb57](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5d70eb57.png) 

 Hit Enter (or Return) after typing your formula, and your number is now rounded.

![img_5b2cd5fc8316a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5fc8316a.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Round Numbers Up or Down Using the ROUNDUP or ROUNDDOWN Functions

 Sometimes, you may want your numbers to just round numbers up or down instead of having the next digit decide that for you. That's what the ROUNDUP and ROUNDDOWN functions are for, and and using them is pretty much identical to using the ROUND function.

 Click the cell where you want your rounded result to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
 Head to Formulas > Math & Trig, and then choose either the "ROUNDUP" or "ROUNDDOWN" function from the dropdown menu.

![Untitled](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/Untitled.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
 Enter the number (or cell) you want to round in the "Number" field. Enter the number of digits to which you want to round in the "Num\_digits" field. And the same rules apply as with the ROUND function. A positive integer rounds to the right of the decimal point, zero rounds to the nearest integer, and a negative integer rounds to the left of the decimal point.

 Click "OK" when you've got things set up.

![img_5b2cd7d91b50f](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd7d91b50f.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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


