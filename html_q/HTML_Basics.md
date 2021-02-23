<center> 
<h1> HTML - Problem Sheet </h1>
</center> 

<table style="width:100%">
<tr>
<th>Problem  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</th>
<th>Solution</th>
</tr>
<!-- START -->
<tr>
<td>
Give a high level explanation of HTML
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
- HTML stands for Hyper Text Markup Language
- Language of Browser, tells browser how content should be rendered
```
</details>
</td>
</tr>
<!-- END -->

<!-- START -->
<tr>
<td>
Describe the format of an html element
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
<tagname option1="value" option2="value"> Content </(close) tagname>
```
</details>
</td>
</tr>
<!-- END -->

<!-- START -->
<tr>
<td>
Explain each element (tag) of this html page along with the doctype

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
<meta name="hostname" content="gist.github.com">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
- Doctype defines that document is an HTML 5 Doc (There are elements specifics to html 5)
- The <html> element is the root element of an HTML page
- The <head> element contains meta information about the HTML page
- The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The <h1> element defines a large heading
- The <p> element defines a paragraph
```
</details>
</td>
</tr>
<!-- END -->


</table>

## Introductions
<!-- START -->
<details>
<summary>
Give a high level explanation of HTML
</summary> 

```
- HTML stands for Hyper Text Markup Language
- Language of Browser, tells browser how content should be rendered
```
</details>
<!-- END -->

<!-- START -->
<details>
<summary>
Describe the format of an html element
</summary> 

```
<tagname option1="value" option2="value"> Content </(close) tagname>
```
</details>
<!-- END -->

<!-- START -->
<details>
<summary>
Explain each element (tag) of this html page along with the doctype

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
<meta name="hostname" content="gist.github.com">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
</summary> 

```
- Doctype defines that document is an HTML 5 Doc (There are elements specifics to html 5)
- The <html> element is the root element of an HTML page
- The <head> element contains meta information about the HTML page
- The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
- The <h1> element defines a large heading
- The <p> element defines a paragraph
```
</details>
<!-- END -->

<!-- START -->
<details>
<summary>
Give the file format(s) of a webpage
</summary> 

```
.html and .htm with the only difference being in the name
```
</details>
<!-- END -->

<!-- START -->
<details>
<summary>
Give an example of an html link
</summary> 

```
<a href="https://www.w3schools.com">This is a link</a>
```
</details>
<!-- END -->

<!-- START -->
<details>
<summary>
Give an example of an html image tag
</summary> 

```
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```
</details>
<!-- END -->

## HTML Basics
<!-- START -->
<details>
<summary>
Describe the different headers
</summary> 

```
h1 - h6
```
</details>
<!-- END -->

<!-- START -->
<details>
<summary>
Describe Nesting
</summary> 

```
HTML elements can contain other html elements, which is refered to as nesting
```
</details>
<!-- END -->

<!-- START -->
<details>
<summary>
Name caveats of the endtag
</summary> 

```
The end tag can be implied, although this is not best practice. Instead, you should always close tags
```
</details>

<!-- START -->
<details>
<summary>
Describe empty HTML elements
</summary> 

Elements without content are empty elements. Examples are
```
<br>
```
</details>

<!-- START -->
<details>
<summary>
Describe case sensitivity of HTML
</summary> 

```
HTML elements are not case sensitive, but W3C recommends lower case in html and demands lowercase for stricter doctypes
```
</details>
<!-- END -->

<!-- END -->
<!-- END -->

## Dev Format
```
<!-- START -->
<details>
<summary>
Text
</summary> 

Text
</details>
<!-- END -->
```