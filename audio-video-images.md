**Controlling the size and alignment** 
Images using CSS keeps rules that
affect the presentation of your page out of the HTML markup.
You can also achieve several interesting effects using
background images.

● Specify the size and alignment of an image using

// <img src="images/magnolia-large.jpg"
 class="large" alt="Magnolia" />
<img src="images/magnolia-medium.jpg"
 class="medium" alt="Magnolia" />
<img src="images/magnolia-small.jpg"
 class="small" alt="Magnolia" /> //
 
 // img.large {
width: 500px;
height: 500px;}
img.medium {
width: 250px;
height: 250px;}
img.small {
width: 100px;
height: 100px;} //
*HTML & CSS Design and Build Websites page 409*

● Add background images to boxes

// body {
background-image: url("images/pattern.gif");} //

// p {
background-image: url("images/pattern.gif");} //
*HTML & CSS Design and Build Websites page 413*

● Create image rollovers in CSS

// <a class="button" id="add-to-basket">
Add to basket</a>
<a class="button" id="framing-options">
Framing options</a> //

// a.button {
height: 36px;
background-image: url("images/button-sprite.jpg");
text-indent: -9999px;
display: inline-block;}
a#add-to-basket {
width: 174px;
background-position: 0px 0px;}
a#framing-options {
width: 210px;
background-position: -175px 0px;}
a#add-to-basket:hover {
background-position: 0px -40px;}
a#framing-options:hover {
background-position: -175px -40px;}
a#add-to-basket:active {
background-position: 0px -80px;}
a#framing-options:active {
background-position: -175px -80px;} //
*HTML & CSS Design and Build Websites page 417*

**Search Engine Optimization**
This is how you give your website prominence. Trying
to help your site appear nearer
the top of search engine results
when people look for the topics
that your website covers. 

**Domain Names & Hosting**
Your domain name is your web address.
Web Hosts are special computers that are constantly connected to the
Internet. They are specially set up to serve web pages when they are requested.

