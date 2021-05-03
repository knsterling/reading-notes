CSS takes each element in HTML and positions them with elements such as:
_Block Level_ 
<!-- <h1> <p> <ul> <li> -->
and
_Inline_
<!-- <img> <b> <i> -->
It's like using the paragraph alignment and justification tabs in microsoft word. You can liken positioning paragraphs in HTML to hitting the space bar or the tab key but it's
much more complex than that. What's required is applying pixels to the positioning schemes.

_Some Positioning Schemes_

(Normal Flow) 
<!--body {
width: 750px;
font-family: Arial, Verdana, sans-serif;
color: #665544;}
h1 {
background-color: #efefef;
padding: 10px;}
p {
width: 450px;-->

(Relative Positioning)
<!--p.example {
position: relative;
top: 10px;
left: 100px;}-->

(Absolute Positioning)
<!--h1 {
position: absolute;
top: 0px;
left: 500px;
width: 250px;}
p {
width: 450px;}-->

(Fixed Positioning)
<!--h1 {
position: fixed;
top: 0px;
left: 50px;
padding: 10px;
margin: 0px;
width: 100%;
background-color: #efefef;}
p.example {
margin-top: 100px;}-->

Computer screens and mobile devices differ in sizes interchangable resolutions , so the web developer has to create 
pages with pixels to accomodate those displays. The higher the pixels, the smaller the text and images.  Thats better for
mobile devices. 

MY name is Kafele Sterling and here's the link to my github page: https://knsterling.github.io/reading-notes/


