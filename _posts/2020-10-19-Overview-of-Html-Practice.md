---
layout: post
title: Overview of Html Practice
description: 
summary: 
tags: 
---

Today, Kajari instructed Celeste and I to work on Html practice. [This is the website we used](https://www.learn-html.org/en/Hello%2C_World%21) The task was for us to get practice on the coding we'll be using for web design and to take notes on the most important sections. 

* Hello, World! - The exercise focused on introducing the user to the `<title>` and `<p>` codes. To enable the `<title>` in the code, the user must write the code in the `<head>` section and must be written as followed: `<title>`Example`</title>`. To write any body paragraph or sentence, the user must write the code in the `<body>` section and must be written as followed: `<p>`Insert Example here`</p>`. the `</>` in codes are used as ending to the coding sequence and that the code full plugs in.
* Basic Elements - The excecise focused on introducing the user to Text headers and paragraphs. Tags are written within the `<body>` part. The basic elements of an HTML page are the following:
	* Text Headers - `<h1>`-`<h6>` tags are used to create the header of a paragraph or sentence.
	* Paragraph - `<p>` tag is used to allow a paragraph/sentence to be written after it is denoted.
	* Horizontal Ruler - another name for `<hr/>` to allow seperation between two page sections.
	* Link - `<a>` allows a link to be written.
	* List - `<ul>` allows an unordered list, `<ol>` allows an ordered list, and `<li>` allows the user to list elements.
	* Image - `<img>` enables image coding.
	* Divider - `<div>` enables the code.
	* Text Span - `<span>` enables the code.
* Images - The exercise focused on introducing the user on how to add an image code using Html. `<src>` is used to specify an image's location. 
	* Adding an image - `<img src="/static/img/code.jpg">`
	* Sizing the image - `<img src="/static/img/code.jpg" width="100">` to `<img src="/static/img/code.jpg" style="width: 100px">`.
	* Lossless Formats - (PNG) Useful for pixel perfect graphics such as logos.
	* Lossy Formats - (JPG) Useful for displaying rich images.
	* Animated Formats - (GIF) Useful for showing short animated images.
* Links - This section focused on introducing the user on creating a link with Html. `<a>` allows a link to be written.
	* Creating a link Example - `<a href="https://ww.google.com">`A link to google`</a>`.
	* Creating link within the section Example - `<a href="#faq">`Click here to read the Frequently Asked Questions`</p>`.
	* Element ID - Using the `<id>` tag: `<h3 id="faq">`Frequently asked questions`</h3>`
`<p>`The first rule about fight club is that you do not talk about fight club.`</p>`
* Lists - This section focuses on introducing the user to making lists in Html. `<ul>` allows an unordered list, `<ol>` allows an ordered list, and `<li>` allows the user to list elements.
	* Example of making an ordered list - 
	`<p>`Here is a list of ordered items:`</p>`
`<ol>`
    `<li>`First item`</li>`
    `<li>`Second item`</li>`
    `<li>`Third item`</li>`
`</ol>`
    * Example of using numbers in an ordered list - 
    `<p>`Here is a list of ordered items:`</p>`
`<ol type="1">`
    `<li>`First item`</li>`
    `<li>`Second item`</li>`
    `<li>`Third item`</li>`
`</ol>`
    * Example of making Upper case letters in an ordered list - 
    `<p>`Here is a list of ordered items:`</p>`
`<ol type="A">`
    `<li>`First item`</li>`
    `<li>`Second item`</li>`
    `<li>`Third item`</li>`
`</ol>`
    * Example of making Lower case letters in an ordered list - 
    `<p>`Here is a list of ordered items:`</p>`
`<ol type="a">`
   ` <li>`First item`</li>`
    `<li>`Second item`</li>`
   ` <li>`Third item`</li>`
`</ol>`
* Styles - This section focused on introducing the user to what is CSS and how is it used with Html. CSS (Cascading Style Sheets) is used as a virtual language of the web. CSS is cascading as it defines which styles to use with Html. Examples are (Browser Default, Styles, Element selector, Class and ID selector, Media type)
	* Defining CSS - `<style>` along with the code string `<p style="font-family: sans-serif">` for the font.
	* Using CSS tag - CSS inline isn't recommended, but CSS stylesheets and selectors are good for applying selectors.
	* Using a different stylesheet - CSS stylsheet can be defined in an external file with (.css extension). Loading it will require the `<link>` tag `<link rel="stylesheet" href="nice.css">`. Must be positioned in the `<head>` section.
* Classes - This section focused on using CSS classes to define CSS Styles and apply them to Html. The next class definition is used as a dot selector:
`<style>`
`.nice{`
	`font-family: sans-serif;`
`}`
`</style>`
* Selectors - This section focused on introducing the user to Querying (declare a style to apply to the CSS stylesheet, receive Html elements using the `<querySelector>` code.
* CSS Support - CSS selectors support the `<p>` and `<h1>`-`<h6>` tags
* Descendant and Child Selectors - Despite being able to specify and element type, ID, and class anme, creating selectors can be done using `<strong>` tags for the hierarchy of "strongblue" class example.
* UI Libraries - This is an overview of what are CSS libraries and how to do it. CSS libraries ease the process of creating a website with little CSS knowledge. THe libraies allow developers to crate websites early on with littl or no knowledge of CSS work.
* Bootstrap - This section focused on introducing the user to Bootstrap for designing UI. Bootstrap framework focuses on writing a plain HTML that makes the stylesheet different from the Bootstrap version. Bootstrap can be loaded by using the `<link>` tag: `<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">`. CDN stands for Content Delivery networks, used for fast download speeds, and are always available and reliant. 













