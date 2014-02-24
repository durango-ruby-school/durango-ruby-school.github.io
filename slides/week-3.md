---
layout: slide-deck
title: 'Week 3 - Beginning Rails, HTML, CSS and Bootstrap'
theme: sky
transition: default
---

<section>
  <h1>Week 3</h1>
  <h3>Beginning Rails, HTML, CSS, and Bootstrap</h3>
</section>

<section>
  <h2>Homework Questions?</h2>
</section>

<section>
  <section>
    <h2>Starting With Rails</h2>
  </section>

  <section>
    <h3>Installing Rails</h3>
    `$ gem install rails -v 3.2.17`
  </section>
</section>

<section>
  <section>
    <h2>HTML</h2>
  </section>

  <section>
    <h3>View Source</h3>
  </section>

  <section>
    <h3>Tags</h3>

```
<p id="welcome-paragraph">Welcome to Durango Ruby</p>
```
  </section>

  <section>
    <h3>Tags need to be closed</h3>

```
<!-- With a closing tag -->
<p>Hello world</p>

<!-- Self closing -->
<img src="ruby.jpg" />
```
  </section>

  <section>
    <h3>Last Opened, First Closed</h3>

```
<!-- Invalid -->
<p> Ruby is <i>really cool</p></i>

<!-- Valid -->
<p>Ruby is <i>really cool</i></p>
```
  </section>

  <section>
    <h3>Important Tags</h3>

```
<html>
<head>
<body>
```
  </section>

  <section>
    <h3>Text Formatting</h3>

```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<p>Paragraph</p>
<i>Italic</i>
<b>Bold</b>
```
  </section>

  <section>
    <h3>Lists</h3>

```
<ul>
  <li>Bulleted list item</li>
</ul>

<ol>
  <li>Numbered List Item</li>
  <li>Numbered List Item</li>
</ol>

<dl>
  <dt>Definition Title</dt>
  <dd>Definition Data</dd>
  <dt>Ruby</dt>
  <dd>A cool programming language</dd>
</dl>
```
  </section>

  <section>
    <h3>Tables</h3>

```
<table>
  <tr>
    <th>First Name</th>
    <th>Last Name</th>
  </tr>
  <tr>
    <td>Aaron</td>
    <td>Renner</td>
  </tr>
</table>
```
  </section>

  <section>
    <h3>Generic Elements</h3>

```
<div>
<span>
```
  </section>

  <section>
    <h3>A basic document</h3>

```
<!DOCTYPE html>
<html>
  <head>
    <title>Title in Browser</title>
  </head>

  <body>
    <!-- Visible content goes here -->
  </body>
</html>
```
  </section>

  <section>
    <h3>Build a Durango Ruby School Page</h3>
    <ul>
      <li>Create in public/test.html</li>
      <li>Navigate to http://your-nitrous-box/test</li>
      <li>Add Page title, heading, and 2 paragraphs</li>
    </ul>
  </section>
</section>

<section>
  <section>
    <h1>CSS</h1>
  </section>
  <section>
    <h3>Styling your page</h3>

```
<p style="color:green; font-style: italic">Welcome to Durango ruby School</p>
```
  </section>

  <section>
    <h3>Sharing Styles</h3>

```
<!DOCTYPE html>
<html>
  <head>
    <title>Durango Ruby School</title>

    <style>
      p {
        color: green;
        font-style: italic;
      }
    </style>
  </head>

  <body>
    <h1>Welcome to Durango Ruby School</h1>

    <p>It's a great place to learn ruby</p>
    <p>What else should I write</p>
  </body>
</html>
```
  </section>

  <section>
    <h3>Element Selector</h3>

```
<p>Welcome message</p>
```

```
p{
  color: #ff0000;
}
```
  </section>

  <section>
    <h3>Class Selector</h3>

```
<p class="welcome">Welcome message</p>
```

```
.welcome{
  background-color: red;
 }
```

Can have multiple elements with the same class per page
  </section>

  <section>
    <h3>Id Selector</h3>

```
<h1 id="page-title">Durango Ruby School</h1>
```

```
#page-title{
  font-weight: bold;
 }
```

Only one element per id per page
  </section>

  <section>
    <h2>Style your page</h2>
    <ul>
      <li>1 Element selector</li>
      <li>1 Class selector</li>
      <li>1 id selector</li>
    </ul>

 ```
font-weight: bold;
font-style: italic;
text-decoration: underline;
color: #0000ff;
background-color: #00CC00;
```
  </section>

  <section>
    <h3>External Stylesheets</h3>

```
<link href="/style.css" rel="stylesheet" type="text/css" />
```

```
body{
  background-color: #dddddd;
}

#welcome-message{
  color: #333333;
}
```
  </section>

  <section>
    <h3>Chrome Developer Tools</h3>
  </section>
</section>

<section>
  <h2>Rails Views and Controllers</h2>
</section>

<section>
  <h2>Bootstrap</h2>
  https://github.com/twbs/bootstrap-sass
</section>
