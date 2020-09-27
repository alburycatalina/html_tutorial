## The Basics

### What is HTML?

HTML: hypertext markup language 
* Backbone of the web
* Describes the stucture of a webpage
* Labels pieces of content (this is a heade, this is text body, etc.)

### HTML Elements

Defined by start tag, some content, and an end tag. These can be nested within each other.

```
<tagname>Content goes here...</tagname>
```

### Example

```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

### Web Browsers

A web browser will show you your webpage as you intend. 

Paste the above code into VScode and save as index.html. Notice the syntax highlighting. Right click it and open with your browser. 

### HML Documents

* All HTML documents must start with a document type declaration: ```<!DOCTYPE html>```.

* The HTML document itself begins with ```<html>``` and ends with ```</html>```.

* The visible part of the HTML document is between ```<body>``` and ```</body>```.

### 1. Edit your webpage heading and body text.



### HTML Headings

Headings are ranked by importance, from 1 to 6. More important headings appear larger

```
<h1> Most important heading (1) </h1>
<h2> Kinda important (2) </h2>
<h3> Least important (3) </h3>
```

### Paragraphs

Paragraphs use the ```<p>``` tag

```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

### Links

Links use the <a> tag
 
```
<a href="https://www.github.com">This is a link</a>
```

### Images

Images have a more complex structure. They need you to tell the code:
* what the source image is (what the file is called on your computer) : ```src```
* alternative text to describe the image: ```alt```
* height you want the image to appear as: ```height```
```
<img src="cat.jpg" alt="Cat" width="104" height="142">
```




