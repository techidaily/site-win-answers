---
title: "Consolidate Text Entries: A Step-by-Step Guide to Joining Content Across Several Excel Cells Into One"
date: 2024-08-28 20:36:40
updated: 2024-08-29 12:48:58
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4f70e3d531e042394d8511ca88c9ecd662d4633e7d60fe2b42adcca98c8caef1.png
---

## Consolidate Text Entries: A Step-by-Step Guide to Joining Content Across Several Excel Cells Into One

If you have a large worksheet in an Excel workbook in which you need to combine text from multiple cells, you can breathe a sigh of relief because you don't have to retype all that text. You can easily concatenate the text.

 Concatenate is simply a fancy way ot saying "to combine" or "to join together" and there is a special CONCATENATE function in Excel to do this. This function allows you to combine text from different cells into one cell. For example, we have a worksheet containing names and contact information. We want to [combine the Last Name and First Name columns](https://article-helps.techidaily.com/updated-2024-approved-elevate-your-drone-game-with-top-tier-lipo-tech/) in each row into the Full Name column.

 To begin, select the first cell that will contain the combined, or concatenated, text. Start typing the function into the cell, starting with an equals sign, as follows.

=CONCATENATE(

![01_entering_concatenate_function](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/01_entering_concatenate_function.png) 

 Now, we enter the arguments for the CONCATENATE function, which tell the function which cells to combine. We want to combine the first two columns, with the First Name (column B) first and then the Last Name (column A). So, our two arguments for the function will be B2 and A2.

 There are two ways you can enter the arguments. First, you can type the cell references, separated by commas, after the opening parenthesis and then add a closing parenthesis at the end:

=CONCATENATE(B2,A2)

 You can also click on a cell to enter it into the CONCATENATE function. In our example, after typing the name of the function and the opening parenthesis, we click on the B2 cell, type a comma after B2 in the function, click on the A2 cell, and then type the closing parenthesis after A2 in the function.

 Press Enter when you're done adding the cell references to the function.

![02_adding_cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/02_adding_cells.png) 

 Notice that there is no space in between the first and last name. That's because the CONCATENATE function combines exactly what's in the arguments you give it and nothing more. There is no space after the first name in B2, so no space was added. If you want to add a space, or any other punctuation or details, you must tell the CONCATENATE function to include it.

![03_no_space_in_name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/03_no_space_in_name.png) 

 To add a space between the first and last names, we add a space as another argument to the function, in between the cell references. To do this, we type a space surrounded by double quotes. Make sure the three arguments are separated by commas.

=CONCATENATE(B2," ",A2)

 Press Enter.

![04_adding_space](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/04_adding_space.png) 

 That's better. Now, there is a space between the first and last names.

![05_concatenated_name_with_space](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/05_concatenated_name_with_space.png) 

Related: [How to Automatically Fill Sequential Data into Excel with the Fill Handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) 

 Now, you're probably thinking you have to type that function in every cell in the column or manually copy it to each cell in the column. Actually, you don't. We've got another neat trick that will help you quickly copy the CONCATENATE function to the other cells in the column (or row). Select the cell in which you just entered the CONCATENATE function. The small square on the lower-right corner of the selected is called the fill handle. The fill handle allows you to [quickly copy and paste content to adjacent cells](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) in the same row or column.

![06_fill_handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/06_fill_handle.png) 

 Move your cursor over the fill handle until it turns into a black plus sign and then click and drag it down.

![07_double_clicking_fill_handle](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/07_double_clicking_fill_handle.png) 

 The function you just entered is copied down to the rest of the cells in that column, and the cell references are changed to match the row number for each row.

![08_column_filled](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/11/08_column_filled.png) 

 You can also concatenate text from multiple cells using the ampersand (&) operator. For example, you can enter `=B2&" "&A2` to get the same result as `=CONCATENATE(B2," ",A2)` . There's no real advantage of using one over the other. although using the ampersand operator results in a shorter entry. However, the CONCATENATE function may be more readable, making it easier to understand what's happening in the cell.

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
