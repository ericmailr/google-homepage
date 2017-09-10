09/09/2017

From The Odin Project's [curriculum](http://www.theodinproject.com/web-development-101/html-css)

Task: Recreate the front-end of google's homepage, then of its search results page.

WHAT I LEARNED:
I got to refamiliarize myself with a few commonly used html tags and css properties like: anchors, forms, images, lists,...,display, padding, margin, text-align.

Learned how to create a horizontal navigation bar.

????Learned how to create a footer that stays at the bottom:
bottom:0;position:absolute;width:100%;
????what about when results make you scroll down. footer is stuck, not at the very bottom.
*SOLVED: change position to relative.

Remember to do some css resetting such as: set html,body width to 100%, padding, margin to 0.

Minification: removes unnecessary characters in class/id names and such to reduce the amount of data transferred. Speeds things up.

overflow:auto; lets the background color show behind the float-ed child elements.
	(parent loses defined dimensions when children are taken out of the flow of the document
	with float.


PROBLEMS / QUESTIONS / WHAT TO DO DIFFERENTLY:

Things got messy quick. id's and classes got unorganized. Make sure to plan ahead in the future. Avoid redundant code. Need to learn best practices for organizing styles sheet.

Get into the habit of using dev tools in chrome as opposed to editing styles in the actual
document, guess-and-checking.

I gave the anchor links in the "nav bar" a padding of 8, which isn't ideal for these links.
(more ideal for a navigational bar)

For the results page, the google logo was indented from the left for some reason. Still not 
sure why. My temporary fix was to make the margin:-30px.

Should I always include parent class names when making a new css rule?