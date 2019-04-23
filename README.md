# Project 0

Web Programming with Python and JavaScript


I made for this project a small website with 4 html pages about coffee which content I took from wikipedia in absence of better idea.
All pages are divided into 3 main divs, top div, middle div and bottom div for buttons with container-fluid class from bootstrap instead of making my own.

For header with title and picture I used top div on all the pages where I defined style in css
For the main content I used middle div:

On index page middle div is one container-fluid with one row and one col from bootstrap in which are located link for the image and p for text.
I placed them together in one col so that I can place text around picture with text-align: justify.

On page 1 I divided middle div same as for index page as they are almost identical exerpt the text

On page 2 I divided middle div so that everything is inside one col which is inside one row which is inside one big container-fluid.
Page 2 contains two img src for pictures, three paragraphs and two tables. One table with 3 cols and 3 rows and one with 4 cols and 3 rows.

On page 3 I divided middle div to two rows inside of container-fluid, one row is list with one orderd list and unordered sublist, other
row is simple unordered list with a href links


In css I styled the main 3 divs all seperate where only middle div has different stylings across the pages, the other two divs don't change.

I made class .intro for styling the text across the pages which inherit the style defind in scss variable %main_text with some small changes.

For @media query I defined that some changes take place when width is 576px or less. The pages are made primarily for large displays and they shrink
when smaller display is used.

