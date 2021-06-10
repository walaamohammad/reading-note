### Images
__________________________________________
A picture can say a thousand words, and great
images help make the difference between an
average-looking site and a really engaging one.
![image](https://images.pexels.com/photos/556666/pexels-photo-556666.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500)

_________________________________________
* Images can be used to set the
tone for a site in less time than
it takes to read a description. If
you do not have photographs
to use on your website, there
are companies who sell stock
images; these are images you
pay to use (there is a list of stock
photography websites below).
Remember that all images are
subject to copyright, and you
can get in trouble for simply
taking photographs from
another website.
If you have a page that shows
several images (such as product
photographs or members of a
team) then putting them on a
simple, consistent background
helps them look better as
a group.
_______________________________________
To add an image into the page
you need to use an <img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
To add an image into the page
you need to use an <img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
To add an image into the page
you need to use an <img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
src
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
alt
This provides a text description
of the image which describes the
image if you cannot see it.
title
You can also use the title
attribute with the <img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.
Adding Images
The text used in the alt attribute
is often referred to as alt text.
It should give an accurate
description of the image content
so it can be understood by
screen reader software (used by
people with visual impairments)
and search engines.
If the image is just to make a
page look more attractive (and
it has no meaning, such as a
graphic dividing line), then the
alt attribute should still be used
but the quotes should be left
empty.
_________________________________________
### color
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:
rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)
 hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80
color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan
We look at these three different
ways of specifying colors on the
next double-page spread.
CSS3 has also introduced
another way to specify colors
called HSLA, which you will
meet near the end of this chapter
on page 255-256.
Foreground Color
color
Above each CSS rule in this
example you can see how CSS
allows you to add comments
to your CSS files. Anything
between the /* symbols and
the */ symbols will not be
interpreted by the browser.
They are shown in grey above.
The use of comments can help
you to understand a CSS file
(and organise it, by splitting a
long document into sections).
Here, we have used comments
to indicate which method is used
to specify each of the different
types of colors.
___________________________________________
### background-color
CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.
You can specify your choice of
background color in the same
three ways you can specify
foreground colors: RGB values,
hex codes, and color names
(covered on the next page).
If you do not specify a
background color, then the
background is transparent.
By default, most browser
windows have a white
background, but browser users
can set a background color for
their windows, so if you want
to be sure that the background
is white you can use the
background-color property on
the ( body ) element.
___________________________________________
### Text 
* There are properties to control the choice of font, size,
weight, style, and spacing.
* There is a limited choice of fonts that you can assume
most people will have installed.
* If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.
* You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.
* You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.
