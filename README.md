# Hack of the day: Table Zebra Striping (Horizontal - Vertical) methods

Many of us have seen strips on the table with bootstrap which is horizontal. How can we have it either horizontally or vertically with only CSS?
Well, I have two answers:

1. The First one is with CSS3 which can't be used with IE7,6 and earlier versions

For horizontal zebra-striping style, I use the nth-child pseoudo class i.e. `table1 tr:nth-child(even)`
for vertical zebra-strip style, I use the nth-child pseoudo class i.e. `table2 tr td:nth-child(even)`

2.The second one is with JQuery: JQuery has the advantage of covering old IE versions
So after adding its script to the project, the JQuery selectors are:
`$(#table1 tr:even)` for horzontal strip. and `$(table2 tr td:even)` for vertical strip

reference : [CSS Cookbook by Christopher Schmitt](http://shop.oreilly.com/product/9780596155940.do)
