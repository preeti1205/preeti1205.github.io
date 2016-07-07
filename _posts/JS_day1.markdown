---
title:  "Javascript Journey Day 1"
date:   2016-07-07 19:04:23
categories: [javascript]
---

This is my Javascript journal. I am using this to document the learnings as I go.
I am going to use markdown to document it.

>Introduction : Javascript is used to modify the HTML document. It is used to program the
>behaviour of web pages

An example: [here](http://www.w3schools.com/js/tryit.asp?filename=tryjs_intro_style)

```
<!DOCTYPE html>
<html>
<body>

<h1>What Can JavaScript Do?</h1>

<p id="demo">JavaScript can change the style of an HTML element.</p>

<button type="button" onclick="document.getElementById('demo').style.fontSize='35px'">Click Me!</button>


</body>
</html>

```
Javascript can be placed in head or body(or both, but keeping all code in one place is a good habit) sections of HTML page.
Since Javascript is the default scripting language in HTML enclosing Javascript code within the
<script> tag will identify it as javascript code. e.g:

```
<script>
document.getElementById("demo").innerHTML = "My First JavaScript";
</script>

```

# Javascript function and events

A JS function is a code that is executed when an event occurs.
An example of function and JS in head section of HTML page is as follows:

```
<!DOCTYPE html>
<html>

<head>
<script>
function myFunction() {
   document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>
</head>

<body>

<h1>My Web Page</h1>

<p id="demo">A Paragraph</p>

<button type="button" onclick="myFunction()">Try it</button>

</body>
</html> 
```
