
### images
____________________________________

You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.
Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.
You might think that your site
is likely to have images of all
different sizes, but a lot of sites
use the same sized image across
many of their pages.
For example, an e-commerce site
tends to show product photos
at the same size. Or, if your site
is designed on a grid, then you
might have a selection of image
sizes that are commonly used on
all pages, such as:
Small portrait: 220 x 360
Small landscape: 330 x 210
Feature photo: 620 x 400
Whenever you use consistently
sized images across a site,
you can use CSS to control
the dimensions of the
images, instead of putting the
dimensions in the HTML.
____________________________________________
![ tulip](https://ae01.alicdn.com/kf/HTB1YxAdaSBYBeNjy0Feq6znmFXaG/1PCS-pu-mini-tulip-flower-Real-Touch-wedding-flower-bouquet-artificial-silk-flowers-for-scrapbooking-home.jpg_Q90.jpg_.webp)

_____________________________________________
 #### AligNing images Using css 

 the float property can be used
to move an element to the left or
the right of its containing block,
allowing text to flow around it.
Rather than using the <img>
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:
1: The float property is added
to the class that was created to
represent the size of the image
(such as the small class in our
example).
2: New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.
In this example you can see the
align-left and align-right
classes used to align the image.
It is also common to add a
margin to the image to ensure
that the text does not touch their
edges.
_________________________________________
 #### Centering images using css
 By default, images are inline
elements. This means that they
flow within the surrounding text.
In order to center an image, it
should be turned into a blocklevel
element using the display
property with a value of block.
Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:
1: On the containing element,
you can use the text-align
property with a value of center.
2: On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.
You can specify class names
that allow any element to be
centered, in the same way that
you can for the dimensions or
alignment of images.
The techniques for specifying
image size and alignment of
images can also be used with
the HTML5 <figure> element,
which you met on page 119.
_____________________________
#### Background Images
background-image:
The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.
The path to the image follows
the letters url, and it is put
inside parentheses and quotes.
If you search online, you will
find lots of resources that offer
background textures that you
can use on your pages.
Background images are often
the last thing on the page to
load (which can make a website
seem slow to load). As with any
images you use online, if the
size of the file is large it will take
longer to download.
________________________________________
#### In every page of your website there are seven key places where keywords
(the words people might search on to find your site) can appear in order
to improve its findability
1: Page Title
The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the <title> element which lives
inside the <head> element.
2: URL / Web Address
The name of the file is part of
the URL. Where possible, use
keywords in the file name.
3: Headings
If the keywords are in a heading
<hn> element then a search
engine will know that this page is
all about that subject and give it
greater weight than other text.
4: Text
Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.
5: Link Text
Use keywords in the text that
create links between pages
(rather than using generic
expressions such as "click here").
6: Image Alt Text
Search engines rely on you
providing accurate descriptions
of images in the alt text. This
will also help your images show
up in the results of image-based
searches.
7: Page Descriptions
The description also lives inside
the <head> element and is
specified using a <meta> tag.
It should be a sentence that
describes the content of the
page. (These are not shown in
the browser window but they
may be displayed in the results
pages of search engines.)
Never try to fool search engines!
They will penalize you for it. For
example, never add text in the
same color as the background of
the page as they can detect this.
___________________________________

 ### How Many People Are Coming to Your Site?
 Visits
This is the number of times
people have come to your site. If
someone is inactive on your site
for 30 minutes and then looks at
another page on your site, it will
be counted as a new visit.
Unique Visits
This is the total number of
people who have visited your site
over the specified period. The
number of unique visits will be
lower than the number of visits
if people have been returning to
your site more than once in the
defined period.
Page Views
The total number of pages all
visitors have viewed on your site.
Pages per Visit
The average number of pages
each visitor has looked at on
your site per visit.
Av erage Time on Site
The average amount of time
each user has spent on the site
per visit.
Date Selector
Using the date selector in the top
right hand corner of the site, you
can change the period of time
the reports display. When you
log in, this is usually set to the
last month, but you can change
it to report on a specific time
period.
Export
The export link just above the
title that says "visitors overview"
allows you to export the
statistics on this page for other
applications such as Excel.

