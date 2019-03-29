<!--
  UPDATE THIS:
-->

Guide for attendees who are starting to learn HTML and CSS.

!> For **newbies / beginners** please read, understand and follow this starter kit. 
It might take 2-3 hrs or more to finish this. Please try your best to follow all the activities, we know you can do it. :)

!> For **attendees who already knows the _basics/fundamentals of HTML & CSS_**, you don’t need to read it all but we recommend to do the final activity - My First Blog Site before attending the study group. 

### Creating your Personal Blog Site

We will guide you to your journey of learning HTML/CSS and our objective is to create your **first Personal Blog Site**. 

!> Note:
Please read all the supporting references in this starter kit. Explore the links provided for further reading.  Let’s practice ourselves in reading the documentation. It will help you to learn more :) 

### What is a Blog?

“A blog (shortening of “weblog”) is an online journal or informational website displaying information in the reverse chronological order, with latest posts appearing first. It is a platform where a writer or even a group of writers share their views on an individual subject.” 
Source: https://firstsiteguide.com/what-is-blog/ 

## My First Hello World! 

### Try it Yourself: My First Hello World! 

1. Open a text editor. (Notepad, Notepad++, Sublime or any text editor that you have).
2. Type the code below in your text editor:
```
<html>
	<head>
		<title>My First Hello World</title>
</head>
<body>
	<h1> Hello World!</h1>
	<p> This is my first paragraph! </p>
</body>	
</html>
```
3. Save it as MyFirstHelloWorld.html
4. Open it with any browser that you have. (Google Chrome, Firefox, IE, etc)

Congratulations on your First Hello World! :tada: :clap:	
You successfully run your first HTML page.


### Understanding the Code

Let’s check and understand the codes from your MyFirstHelloWorld.html. 

HTML stands for **Hyper Text Markup Language**.
In web, webpages are made up of **HTML** and **CSS**. 

![HTML & CSS Layer](../_media/htmlcss_layer.png)

Photo credit © https://sites.google.com/a/st-anns.ca/mrs-nichol/html/html-and-css 


HTML provides the structure, while CSS provides the appearance.
And the structure is composed of elements and tags. 

Going back to our code, each words that starts with ‘<’ and ends with ‘>’ are **tags**.

**HTML tags** are element names surrounded by angle brackets:
`<tagname>content goes here...</tagname>`

Example:

![HTML Element Structure](../_media/element_structure.png)

Photo Credit © https://learn.shayhowe.com 

In the example above:
* The **HTML `<a>` element (or anchor element)** creates a hyperlink to link one page or file to another.
* The _opening tag_ is **`<a href=”http://shayhowe.com/”>`**. Opening tag is used to start an element. 
* The _content_ is **'Shay Howe'**. It is the information displayed in your browser. 
* The _closing tag_ is **`</a>`**. Closing tag is used to end an element. 
* '**href=”http://shayhowe.com”**' is an example of an attribute 'href' with value of 'http://shayhowe.com'. 


### Try it Yourself: Explore HTML Elements, Tags and Attributes

1. Please read this link to understand more about the elements, tags and attributes:

   https://learn.shayhowe.com/html-css/building-your-first-web-page/ 
   
2. List down 5 examples of elements with at least 1 attribute. Understand how they works.

   Example:
      * Element: `<a>`
      * Attributes: href, target

   You can find the list of html elements here:
      * [W3Schools](https://www.w3schools.com/tags/default.asp)
      * [Mozilla MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
	  
3. Try the html elements from your list. Explore on how they works. 
   If you have questions, you can ask us in our [gitter chat](https://gitter.im/WWCodeManila/HTML-CSS) or list down your question and ask it during the study group. We will try our best to answer your questions. 

4. Share your answers during our study group. Don’t be shy, ok :wink:


!> Note:
Do you have a question :question: Is there something that confuse you or you don’t understand :question: 
Feel free to post your questions here: https://gitter.im/WWCodeManila/HTML-CSS.  Ask our community, we will help you.  


### Challenge 1: Find the bugs!

Can you solve this? Try it! Challenge yourself.

1. Copy the code block below on your text editor.
```
<html>
	<head>
		</title>My First Hello World<title>
	</head>
<body>
	<h1> Hello World!/h1>
	<p> My name is _________. I am a/an ____________. I love to _____________ everyday. <p>
	</p> Today, I am challenging myself to solve this problem. Let’s do this! :) <p>
</body>	
</html>
```
2. This code block has 5 bugs, find them to make your page work.
3. Don’t forget to save your work as Challenge1.html


## Let’s make it Red!

Now that you have your MyFirstHelloWorld.html, let’s add colors to it. 
Let’s learn what is CSS and how it works. 

### Try it Yourself: Beautify Me!

1. Open your MyFirstHelloWorld.html in your browser.
2. Observe it’s current look.
3. In the same folder/directory of your MyFirstHelloWorld.html, Create a new file and name it as style.css.
   *Note:* This will be your CSS File. All css files have an extension of *.css
4. Inside the `<head>` tag under the `<title>` tag, insert this `<link>` tag:
```
<link rel="stylesheet" type="text/css" href="style.css">
```
   Read more about HTML <link> tag [here](https://www.w3schools.com/tags/tag_link.asp).
   Familiarize yourself with [CSS syntax](https://www.w3schools.com/css/css_syntax.asp).
```
element {
    property: value;
}
```
5. Style the h1 tag by giving it a property of color with a value of DarkSlateGray.
6. Style the p tag by giving it a color black and a font-size of 16px.
7. Save your changes. 
8. Open your MyFirstHelloWorld.html or refresh it from your browser.

Congratulations! Your First Website have colors in it. :clap:	

### Understanding Cascading Style Sheet (CSS)

In the previous activity, we asked you to add this line below inside the <head> tag:
`<link rel="stylesheet" type="text/css" href="style.css">`,
this line of code connects our newly created style.css file to our html file (MyFirstHelloWorld.html). 

Check this photo below:

![CSS Structure](../_media/css_structure.png)

Photo Credit © https://www.w3schools.com/css/css_syntax.asp 

In CSS, there are different selectors. H1 from the example is an element selector. 
Read more about CSS selectors [here](https://www.w3schools.com/css/css_syntax.asp).


### Challenge 2: Experiment your MyFirstHelloWorld.html

1. There are 3 ways to add styles to your html file. Discover and learn the differences between: inline, internal and external CSS styles. 
   References:
     * https://www.w3schools.com/html/html_css.asp, 
     * https://www.javatpoint.com/how-to-add-css 

2. Create 3 versions of your MyFirstHelloWorld.html demonstrating each ways to add your styles (inline, internal and external css). 
3. Change the font-size of the heading text into 36px and add a line-height with a value of 3em. 
4. Explore the different CSS properties that you can do in each element.  Add at least three new html elements (aside from `<h1>`, `<p>`, `<a>`) and add styles to each new elements. 
   Example: 
```
<span style=”font-weight:bold;”>Hello</span>
```
5. Save your work with following format, for example: Challenge2 - Inline CSS. html


## My First Blog Site

Please finish all the previous activities before doing this activity. 

### Final Challenge: My First Blog Site

1. Create a folder in your computer and named it “My First Blog Site” or any folder name you want. 
2. Inside your folder, open a text editor and create an index.html file. 
3. Review the basic tags from previous activities, in your index.html file it should contain the following tags: `<html>`, `<head>`, `<title>` and `<body>`.
4. Inside your folder, create style.css file. 
5. Go back to your index.html file. Inside the <head> tag, link your external css file. 
6. Inside the `<body>` tag, add a title of your blog (example: your name) and wrap it inside the `<h1>` tag. 
7. After your title, add your photo or avatar. 
8. Add a background color in your blog site. Choose any color that you like.
9. Make a short paragraph and tell us about yourself. 
10. Make a list of your hobbies or things that you like.
11. In the last part of your blog site, add a way to contact you and link it to your email address or you can used this placeholder value = ‘mailto:myemail@gmail.com’.
12. Play with colors and other attributes to beautify your blog. Apply any elements and their attributes that you like. Express your creativity.
13. Share your work with us in the study group. Be proud of it.  

Example of the personal blog site that you can do:

![HTML & CSS Layer](../_media/finalblogexample.png)