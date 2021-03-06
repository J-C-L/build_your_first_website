# Building Your First Website

Now we will use the skills you've learned to build pages of an online book review website.

This is an individual, [stage 1](https://github.com/Ada-Developers-Academy/pedagogy/blob/master/rule-of-three.md) project.

##  Learning Goals:

-  Demonstrate an understanding of HTML Syntax  
-  Demonstrate an understanding of appropriate tag selection for specific content  
-  Demonstrate an ability to link local pages and remote pages
-  Demonstrate the creation of a external stylesheet  
-  Organize a site with [semantic](http://blog.teamtreehouse.com/use-html5-sectioning-elements) HTML


## Wave 1 - Creating Semantic HTML
### The Online Book Review Site

![Site Layout](images/layout.png "Site Layout")

In this exercise you will create the HTML to go along with content for 3 pages of HTML.  You will structure the content given in the content folder with semantic html tags providing meaning to the content.  

Each page will have a:
-  Doctype, Head, and Body of an HTML    
-  A Header/Title Section
-  Navigation Section with links for the site
-  A footer with a copyright notice and your name

The pages of your site will be the pieces of an online book review site.  __[Under no circumstances should you use inline html styles.](http://stackoverflow.com/questions/2612483/whats-so-bad-about-in-line-css)__

### Site Homepage

The homepage of your site is named `index.html`. This page will have:  
-  A Header section with the title for your book review site.
-  A section for navigation.
-  A main content section with an unordered list of the top-5 book images (see the images folder)
  - Each image should link to their page in Amazon.com or a book review page.  

### Book Review Pages
You will then create a book review page template, using Eloquent Ruby by Russ Olsen as your example.  The content for the page is provided in the content folder by the textfile `Eloquent_Ruby.txt`. The book review page will have the same overall structure as `index.html` except the main content section will structure the information inside of the text file.  The page should also include the image of the book, included in the images folder.

### Site Contact Page
You will include a contact page for visitors to provide feedback to the maintainers.  

This page will include:

-  A picture of the site maintainer. You can use a picture of yourself or use the goofy picture provided in the images folder.
-  A statement welcoming feedback on the site via e-mail, twitter or facebook.
-  A list of methods to contact the site maintainer via email, Twitter and Facebook.  

When you are finished, review the site with another student at your table explaining the design choices you made.

What sectioning/semantic tags did you use and where?
-  div
-  body
-  section
-  article
-  nav
-  aside
-  header
-  footer


Make adjustments where it seems appropriate.  

## Wave 2 - Adding CSS

In This wave you will add CSS styling to change the appearance of the site.  You will be adding an external stylesheet named `style.css`.

In the style sheet you will be practicing how to:

-  Place the Header/Title section across the top of the site with a border and appropriate background color
-  Provide an appropriate background color for the main content section
-  Select appropriate fonts & colors for text on the site  
-  Make the navigation links display different colors when the mouse rolls over the link  
-  Use CSS styling to hide the bullet-points of the unordered lists in the site  
-  Place the Footer section across the entire bottom of the site with a border and an appropriate background color


Page Specific Styling:
-  `index.html`
	-  use CSS styling to hide the bullet-points of the unordered list containing the book images
	-  use CSS styling to make all the images the same height
-  `eloquentRuby.html`
	-  The __Eloquent Ruby__ book image should be left-aligned with the details about the book to the right of it
-  `contact.html`
	-  The site maintainer photo should be left-aligned and the message about contacting the site maintainer to the right of it  

When you are finished review your changes with your tablemate.  

## Extensions
-  Create another page for a book you have found useful and link it into the navigation of the site.  
-  Attempt to create a more complex layout with content side-by-side as you feel appropriate.  
