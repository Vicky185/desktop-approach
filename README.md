# First desktop-first-approach

Attempted to create new workspace to try out the desktop-first approach and identify the differences between this and the mobile-first approach.

Turns out that the desktop-approach predominantly focues on max-width, whereas mobile-first approach focuses on min-width. 

Tested in this space to see what the differences are:
* includes -> working our way down but from the maximum/largest to minimum/smallest
*start with the default style setting on CSS then make our way down and use media queries which can override style - unless you override a style further down the file, any filethat can apply will still apply until you override it.
*default style is set for desktop then moves down to tablet style then to mobile

## Challenge

In this challenge (which wasn't entirely clear on what we had to do as we'd been led to believe that we needed to utilise media queries where in this example we didn't need those...)
We had to follow the below:
### Instructions:

Apply the following changes to a webpage. In the hint tab, you'll find a link to boilerplate files to help get you started.

* Make a section full-height
* Remove margins and paddings from the body and html elements

### Solutions:
* Needed to amend HTML structure: rather than divs, using <main> and <section> tags
* in the CSS we needed to style the HTML, <body>, <main> and <section> - ensuring that all was height = 100% of the page and that there were no margins/paddings etc
* Result was that the entire page was a block colour no matter the size of the screen. 