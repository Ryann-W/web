# h tag
h1 often used for main headings.

h2 generally used for subheadings 

also h3,h4,h5,h6 indicate different level of subheadings

# p tag

p elements are the preferred element for paragraph text on websites. p is short for "paragraph".

# HTML 5 elements

HTML5 introduces more descriptive HTML tags. These include main, header, footer, nav, video, article, section and others.

# a tag

You can use a (anchor) elements to link to content outside of your web page.

a elements need a destination web address called an href attribute. They also need anchor text. Here's an example:

<a href="https://freecodecamp.org">this links to freecodecamp.org</a>

a (anchor) elements can also be used to create internal links to jump to different sections within a webpage.

To create an internal link, you assign a link's href attribute to a hash symbol # plus the value of the id attribute for the element that you want to internally link to, usually further down the page. You then need to add the same id attribute to the element you are linking to. An id is an attribute that uniquely describes an element.

<!--
<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>

<p>
  Here's a <a target="_blank" href="http://freecodecamp.org"> link to freecodecamp.org</a> for you to follow.
</p>

Let's break down the example: Normal text is wrapped in the p element:
<p> Here's a ... for you to follow. </p> Next is the anchor element <a> (which requires a closing tag </a>):
<a> ... </a> target is an anchor tag attribute that specifies where to open the link and the value "_blank" specifies to open the link in a new tab href is an anchor tag attribute that contains the URL address of the link:
<a href="http://freecodecamp.org"> ... </a> The text, "link to freecodecamp.org", within the a element called anchor text, will display a link to click:
<a href=" ... ">link to freecodecamp.org</a> The final output of the example will look like this:

-->

