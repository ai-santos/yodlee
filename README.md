# yodlee
Wireframes Assignment
README
Details:
=======
Attached are 3 wireframes which we want you to implement using CSS3 and JS/jQuery/JS Frameworks. You can also refer to Twitter iPad application for reference for overlapping vertical columns design pattern.
 
This exercise has two parts:

Part-1:
======
a. As Per the attached wireframe, each vertical column has list items. 
b. When you select any list item, next vertical column is presented per wireframe 2. 

**Note that the 2nd column slightly overlaps with the first one. Likewise selecting any list item in the vertical column brings up another vertical column.

-----------------------


Part-2:
=======
When you load these pages over mobile or smaller width browser, it should show One full page and on click would show another full page instead of overlapping of col. In other words, responsive layout; full view per wireframes without any overlapping for smaller screen but overlapping views for tablet or larger screen sizes.


Additional tips: 

There is no limitation on the CSS or JS frameworks. You are free to choose whichever framework you want to utilize. 
You can put static data for all three views. No need to feed this data via template or any backend API logic.
Main purpose here is to validate knowledge about HTML, CSS and JS optimal use. Therefore, we expect that you make all three views with all necessary dummy or static data and add necessary user interaction behavior(overlapping of columns on click or touch by user).
You will need to work on styling and presentation of data as well as view’s behavior. 
No need to add or provide data via any api or backend support rather focus on having all the three views content as part of stand alone web app.




Part 1

Step 1:
HTML (PAGE 1 - Accounts page)
1. Create a table with rows 
2. Create check boxes along side each row
3. Create a title above each row 
    a. Cash
    b. Credit Cards
    c. Bills
    d. Investments 
4. Create a progress bar (total amount from maximum)

HTML (PAGE 2 - Credit Card Summary Page)
1. Progress bar
2. Check boxes next to each category
3. Categories
    a. Minimum payment due on 03/26/2016
    b. Total current balance 
    c. Total available credit
4. Dollar amount $000.00
5. Credit Cards
    a. Campus Edge
    b. Primary credi card

HTML (PAGE 3 - Paid Accounts)
1. Bed Bath & Beyond, Angel Island, Freshroll, Lyft, Whole Foods, Starbucks
2. Amounts next to each item $285.57
3. Check boxes next to each amounts
4. Dates


JAVASCRIPT
1. On click of an item on Page 1 it links to Summary Page / covering 25% of the last page
2. On click of an item on Page 2 it links to Paid Accounts
