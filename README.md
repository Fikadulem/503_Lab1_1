# Lab 1.1: Make a Website from a blank canvas

##Introduction

In lab 1 part 1, we will be learning the basics of HTML, CSS, JavaScript, and File Transfer Protocol (FTP). **Think of HTML as the noun, CSS as the adjective and JavaScript as the verb.** HTML holds the content that the browser reads, the CSS describes how each feature on your site will look and JavaScript describes the actions and interaction. I will describe how to build each of these files, and together we will build a very basic website. Next week, in part 2, we will download a HTML5, CSS3 template, but before we do that, let’s learn and execute the basics and write code by hand. It is going to be fun! We will work through <a href="http://slides.com/brittaricker-1/make-a-website-together-by-hand#/">the following slides together in class</a>, you are welcome to use these as reference. When you follow this tutorial, you will end up with a website that looks something like <a href="http://faculty.washington.edu/bricker0/basic.html">this</a>. 

I will not be providing extensive explainations regarding the fundamentals of HTML, CSS, and JavaScript. 

To gain a deeper understanding of HTML, CSS and JavaScript on your own, I suggest going through some online tutorials. Here are a few examples, there are countless tutorials available online. These are just a few that are helpful for references. 

<a href="http://www.w3schools.com/html/">W3Schools Learn HTML</a><br>
<a href="http://www.w3schools.com/css/">W3Schools Learn CSS</a><br>
<a href="http://www.w3schools.com/js/"> W3Schools Learn JavaScript </a><br>


##For this assignment, you will demonstrate the ability to:

•	Write fundamental HTML, CSS and JavaScript files<Br>
•	Create home page, maps page and about page using HTML<br>
•	Build a CSS file to style your website<br>
•	Add basic interaction to your website using JavaScript<br>
•	Post your website to UW server OR Github pages so others can access it on the internet!<br>

##Software Required
•	Text Editor: I recommend Sublime Text.  Alternatives include Notepad ++, DreamWeaver (not free), Kompozer <br>
•	FTP Client of your choice. I use FileZilla or a Github account if you will be using GitHub Pages. (We will talk about the pros and cons of each in class)<br>


##1. Activate your UW web space (do this on your own)
UW provides free web space to all students. To activate your web hosting account through UW follow the directions here http://www.washington.edu/itconnect/connect/web-publishing/shared-hosting/activating-shared-web-hosting/
Your “MyUW Manage” screen should show you your domain name.<br> 
It should be something like http://students.washington.edu/yournetid<br> 
My domain name is http://faculty.washington.edu/bricker0/<br> 

###Resources from University of Washington IT Connect<br>
Basic information about Web Publishing using UW resources can be found here:
http://www.washington.edu/itconnect/connect/web-publishing/
Guidelines for Publishing on the UW Web site can be found here:
http://www.washington.edu/webguides/
<br>Appropriate Use of web space guidelines and legal issues can be found here:
http://www.washington.edu/itconnect/work/appropriate-use/

##2. Create Html, CSS, and Javascript files

##A few tips before you get started
•	Organization is key! Keep your files organized, backup, and coherently named.<br>
•	Working “locally” means working on files that are saved on your local hard drive rather than the files that are live on the web, outward facing UW servers. <br>
•	**CASE SENSTIVE** HTML, CSS and JavaScript are case sensitive! Remember this! <br> 
•	Close tags in the order that you open them

```
<html>
//I first opened the html document, see the tag above
<p>This is an open paragraph tag and after the period is a close paragraph tag. </p>
</html>
```
•	If you have any questions about HTML, CSS or anything else, first Google IT!! Typically, you will be able to find the answers online.<br> 
•	Do not have spaces in the file names use _ when required<br> 
•	A few important tags include bold b <p>I am talking to <b>you.</b></p>
```
<p>I am talking to <b>you.</b></p>
```
line break looks like this
```
<br>
```
Turn a word into an active link like this one to <a href="http://faculty.washington.edu/bricker0/">my awesome website.</a>


```
<a href="http://faculty.washington.edu/bricker0/>my awesome website.</a>
```

###Create a directory or a folder
The aim is to get and stay organized! Create a local directory called "website" In that directory create a sub-folder called "scripts."

###Create an Html File
Open your text editor, like Sublime. Create a new file called "index.html" save this in your new folder called "website" your index.html is where your website visitors will land when they click on your domain, it is the default page, the landing page. 
<br>
Tell the browser it is reading HTML by adding an html tag and then closing it. All of your code will go between these tags. <br>
```
<html>


</html>
```

Create a header container. The header element represents a container for introductory content or a set of navigational links.<br>

A header element typically contains: one or more heading elements, logo or icon, authorship information, it is possible to have several header elements in one document, like reference to different js libraries.

<br>Next, open the body of your document/webpages. Add a title, which will be visible in the tab of the browser when the page is open. Next tell the user what they are reading about in the heading. The heading is the title.
Then tell them more about what they are looking at in the paragraph. Then close all the tags you opened in the order you opened them!. Your code should look something like this. 

```
<html>
<head>
<title>Britta's Website</title>

</head>
<body>

<h1>Hello World</h1>

<p>I Love Geospatial Technologies! My Name is Britta Ricker and I am a professor of Urban Studies at University of Washington Tacoma. Contact me at bricker0 at uw.edu
This is my website where I present my work to the world. 
</p>

</body>
</html>
```
Great job! You wrote your first HTML document. Open this file in an internet browswer of your choice. Might I suggest Chrome or Firefox. Notice your site is lacking style! Let's work on that now!


###Create a CSS File

We are going to create a style guide so that all of the styles are uniform across each webpage. We are going to create a style for the background, the heading, and the paragraph font. In the example I provide below, you will se h1 means heading 1, p means paragraph. The body of my page will have a background color of orange, the number represents the RGB value, red value of 20, green value of 5 and 0 blue. You can figure this out by looking at the number that represents the color. I provide example code here. Please change the defaults to style your site as you would like. There are several style reference and guides available online like this one called <a href="http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF">paletton</a> 

Open a text editor, create a new document, save it as "basic.css" and make sure you put it in your scripts folder. Cut and paste the following code into this file. Change this to style your website!

```
body {
    background-color: #140500;
    font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif; 
   font-weight: 300;
   text-align: center;
}

h1 {
    color: red;
    text-align: center;
}

p {
    
    font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif; 
   font-weight: 300;
    text-align: center;
    color: orange;
    font-size: 20px;
}
```

###Create a JavaScript File

We will learn more JavaScript next week, but let's get our first taste of what is to come. Here we are just going to build a navigation bar using javascript. We are going to build a script that builds tabs for navigation. There will be a button for the user to navigate between pages on your site. 

Open a new file in your text editor, save it as "basic.js" make sure to save it in your scripts folder. Add the following. Make sure you stick with the naming conventions. You may change the names of your files, just be sure to keep track of the names! 

```
document.getElementById("nav01").innerHTML =
"<ul id='menu'>" +
"<li><a href='index.html'>Home</a></li>" +
"<li><a href='about.html'>About</a></li>" +
"<li><a href='maps.html'>Maps</a></li>" +
"</ul>";
```

I don't mean to scare you, but javascript gets complex really quick. You will be responsible for <a href="https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f#.90d87dclb">keeping up</a> with this as much or as little as you want in the future. 

###Back to Html
In your index file, you need to reference both the js file and the css file to see any changes to the style and to see the menu! Add the following to the head sections in each of your .html files. 

```
<link href="scripts/basic.css" rel="stylesheet">
```

The position of the script influences page load speed. We will talk more about this late. For now, place the following just after the paragrapg tag in your html documents.
```
<script src="scripts/basic.js"></script> 
```

You made two other html files but never put anything in them. In your "about.html" file, add whatever you would like on this page. In the "maps.html" file, this will be used to display your maps! This first week, let's simply add a map! Let's add a map from Google Maps, the Graphical User Interface (GUI). I am obsessed with Zimbabwe this week because I have a friend moving there next month. I would like to put a map of Zimbabwe on my maps page, you should add a different place. 

To do this I first navigate to maps.google.com in the search bar I type "Zimbabwe" and I get a map of Zimbabwe, then I click the share icon. A popup window shows me what the end user will see and generates some code for me to cut and paste into my html file. Pick a place you would like to be featured on your first maps page. This is an iFrame.

I enter the following into my maps.html document

```
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3862917.0150770936!2d26.903819959755154!3d-19.002974384150612!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1931a4e706b17161%3A0xa1c0385fc5cbbfee!2sZimbabwe!5e0!3m2!1sen!2sus!4v1475602984430" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

```
Now, your index.html will be the landing page for your visitors, maps page will have a navigation menu and a map, and the about page will have a navigation menu and information all about you. 

###Add a map!
Since this is for a web mapping course, you need to add a map! If you are feeling completely overwhelemed you can simply add a google map using an iFrame. For example, you may include this code to add a Mapbox map. However, notice at the end of the link is the lat long of the center point and the zoom level, please change that to somewhere that is meaningful for you. <iframe width="100%" height="450" frameborder="0" style="border:0"
src="https://a.tiles.mapbox.com/v3/eleanor.mnyzxgvi.html?secure#3/20.55/-374.59">"></iframe>

###Back to the CSS
When you render your page now, you will see that the links on the navigation bar are ugly! Change the style in the CSS file. Change the hover, links and menu. You can see my example, but you are expected to come up with your own style!

## 3. Final step: Moving files onto the server
Directions to do this can be found here: http://www.washington.edu/itconnect/connect/web-publishing/shared-hosting/sftp/
<br>Open your favorite FTP client, mine is Filezilla. Enter the following to connect to UW!

Hostname/Server: vergil.u.washington.edu 

Port: 22

Protocol: SFTP/SSH

Username: NetID

Password: NetID Password

Directory: Leave blank; if required, try public_html

Once you are connected, you need to drag the file from your local machine onto the server.
In this case, you will need to move your file called “index.html” and the folder called “scripts”. When you have moved all of these files online, you should be able to navigate to http://students.washington.edu/yournetid/index.html
And your website should render beautifully! If it doesn’t, double check your work…
Everything needs to be placed exactly where you stated they are located in the directory you reference! Make sure all paths work correctly or else they will not be referenced.

#For Homework Submission
You are to submit a link to your working website. I will be grading on HTML Files, CSS files, JavaScript. Did you follow these directions? Leave notes for yourself? Change your code so it doesn't match mine completely? See the rubric on canvas.
In the online directions with example code, you were to make a home page called “index” This will act as your home page. Here please put your name and the purpose of this website (portfolio of your work for the Master of Geospatial Technologies degree!). 
As mentioned before, normally, your home page should always be called “index.html” that is the default file in your directory, so when someone comes to your website they will go straight there and they don’t have to add more file names to the path to find you. Next week we will change these files dramatically in Lab 1 part 2.<br>
You were also to make two more HTML files. One called “maps.html” and another called “about.html”
On the about page, please tell the reader about yourself. Please be professional. This website will reflect you and your work. It will also reflect our program and your peers. Here is my about page http://faculty.washington.edu/bricker0/about.html. This week I don’t expect your style to be perfect (we will use a template like mine next week) nor do I require pictures this week. However, I do expect a professional description of yourself. You are welcome to share some personal information as well (ie. I like to go running and hiking). If you have questions, please post them to the tips and tricks discussion board. 

#submit a working link to your webpage on canvas! 




