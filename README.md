=======================================================================
Introduction to CSS Grid
=======================================================================

What is CSS Grid Layout?
- CSS Grid Layout allows for the creation of two-dimentional layouts of a web-page.
- Grid/table system which allows for aligning items in both columns and rows.
- Many layouts are now possible or easier with CSS grid such as overlapping elements.
- Allows for creating dynamic/responsive webpages (i.e. mobile, tablet, PCs).
- All browsers support Grid Layouts.

-----------------------------------------------------------------------
Flexbox vs CSS Grid:
- Flexbox is for one dimentional layouts in columns OR rows.
- CSS Grid is for two dimentional layouts in columns AND rows.

Flexbox:             CSS Grid:
--------->           --------->  
__________           __________  |
|  |  |  |           |__|_____|  |
|  |  |  |           |_____|  |  |
|__|__|__|           |__|__|__|  v
One Dimensional      Two Dimensional

-----------------------------------------------------------------------
CSS Grid Properties, Functions, Units:
CSS Grid Properties:       CSS Grid Functions:        CSS Grid Units:
grid-template-columns      repeat()                   fr = Fractions
grid-template-rows         minmax()
grid-template-areas        fit-content()
grid-template
grid-auto-columns
grid-auto-rows
grid-auto-flow
grid
grid-column-start
grid-column-end
grid-row-start
grid-row-end
grid-column
grid-row
grid-area
grid-column-gap
grid-row-gap
grid-gap

-----------------------------------------------------------------------
CSS Grid Layout Cheatsheet Reference:
The tutorial have been split into smaller html files to demonstrate the syntax of CSS Grid and how we can use CSS grid to make webpages more responsive. Each html files builds on each other to give an overall foundation knowledge on CSS Grid Layouts.

-----------------------------------------------------------------------
Important Note:
When creating responsive webpages you should always create for mobile first and then tablet/PCs. This will make developing for all platforms easier without breaking the content layout for the webpage due to CSS margin/padding layout for the various page sizes.

-----------------------------------------------------------------------
Useful CSS Grid Links/References:
https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout
https://www.w3schools.com/css/css_grid.asp
https://css-tricks.com/snippets/css/complete-guide-grid/
http://mmtuts.net/course.php?c=htmlcss&l=1
https://www.youtube.com/watch?v=jV8B24rSN5o&index=4&list=PLillGF-RfqbZTASqIqdvm1R5mLrQq79CU (Traversey Media)
https://www.youtube.com/watch?v=rErAwncfzVs (mmtuts)