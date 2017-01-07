This is a website about a fictional charity named BeeKeeper - an organisation focussed on the preservation of the honeybee. I have attempted to replicate the sort of websites that I personally like to browse, aiming for a relatively simple design, lightweight feel etc. There are a few structural and design changes I would probably make if starting from scratch, but overall I feel as if I have achieved what I set out to do. The website is designed to be viewed on a screen of > 1000px, but can accommodate smaller screen sizes. 



The assignment criteria can be found in the following places: 


Links to both your own pages and external webpages. 
Link to my own page: index.html, line 59
link to external page: index.html, line 57

A navigation bar
All pages, line 17
At least one table
help.html, line 41
At least one form
index.html, line 49
At least one list (ordered or unordered)
info.html, line 46
At least one local or embedded video
info.html, line 41
At least two CSS3 and HTML5 element
CSS3 property (opacity): main.css, line 86
CSS3 property (box-shadow): main.css, line 210
HTML5 element (header): all pages, line 9
HTML5 element (footer): index.html, line 62
Make use of the CSS positional properties (e.g. position, float) 
(position) main.css, line 28, line 67, line 83 etc
(float) main.css, line 20, line 122, line 165 etc

Make use of both inline and block elements 
Block (div): all pages, line 8
Inline (img): index.html, line 48



Additional features

I explored a layout based on two columns, as it seems to be quite popular at the moment and affords a neat and functional appearance. 
 
This website is responsive, being viewable from a variety of screen sizes. I did this using mediaqueries and defining maximum screen sizes, and then adding different layouts based on these maximum sizes. The CSS allowing for this can be found on main.css from line 242 onwards.

When the screen is larger than 1000px the page has a two column layout, with the primary content in a wide column to the center-left, and secondary content in a thin colum to the right. If the size of the window is increased both columns will stay centered and the edges of the header and footer will stretch the full length of the screen. 

When the screen is smaller than 1000px the secondary content is moved to the bottom of the screen, with the primary content now centered. 

If the screen is smaller than 650px the navigation bar is replaced with a dropdown menu. As well as this, the layout is switched to a percentage based design to allow the content to fill the screen dynamically.

As well as the features listed above, I embedded a map on my contact.html page using the google maps API. You can find this on contact.html line 46.



