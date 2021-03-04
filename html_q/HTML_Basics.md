<center> 
<h1> HTML - Problem Sheet </h1>
</center> 

<table style="width:100%">
<tr>
<th>Problem </th>
<th>Solution</th>
</tr>

<!-- =======================START======================= -->
<tr>
<td>
<!-- Title -->
Give a high level explanation of HTML
</td>
<td>
<details>
<summary>
Solution
</summary> 

<!-- Answer -->
```
- HTML stands for Hyper Text Markup Language
- Language of Browser, tells browser how content should be rendered
```
</details>
</td>
</tr>
<!-- =======================END========================= -->

<!-- =======================START======================= -->
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
<!-- =======================END========================= -->

<!-- =======================START======================= -->
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
<!-- =======================END========================= -->

<!-- =======================START======================= -->
<tr>
<td>
Give the file format(s) of a webpage
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
.html and .htm with the only difference being in the name
```
</details>
</td>
</tr>
<!-- =======================END========================= -->

<!-- =======================START======================= -->
<tr>
<td>
Give an example of an html link
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
<a href="https://www.w3schools.com">This is a link</a>
```
</details>
</td>
</tr>
<!-- =======================END========================= -->

<!-- =======================START======================= -->
<tr>
<td>
Give an example of an html image tag
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```
</details>
</td>
</tr>
<!-- =======================END========================= -->
</table>

## HTML Basics
<table  style="width:100%">
<tr>
<th>Problem </th>
<th>Solution</th>
</tr>
<!-- =======================START======================= -->
<tr>
<td>
Describe the different headers
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
h1 - h6
```
</details>
</td>
</tr>
<!-- =======================END========================= -->

<!-- =======================START======================= -->
<tr>
<td>
Describe Nesting
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
HTML elements can contain other html elements, which is refered to as nesting
```
</details>
</td>
</tr>
<!-- =======================END========================= -->

<!-- =======================START======================= -->
<tr>
<td>
Name caveats of the endtag
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
The end tag can be implied, although this is not best practice. Instead, you should always close tags
```
</details>
</td>
</tr>
<!-- =======================END========================= -->

<!-- =======================START======================= -->
<tr>
<td>
Describe empty HTML elements
</td>
<td>
<details>
<summary>
Solution
</summary> 

Elements without content are empty elements. Examples are
```
<br>
```
</details>
</td>
</tr>
<!-- =======================END========================= -->

<!-- =======================START======================= -->
<tr>
<td>
Describe case sensitivity of HTML
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
HTML elements are not case sensitive, but W3C recommends lower case in html and demands lowercase for stricter doctypes
```
</details>
</td>
</tr>
<!-- =======================END========================= -->

<!-- =======================START======================= -->
<tr>
<td>
Define the root of an html element
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
<html>
```
</details>
</td>
</tr>
<!-- =======================END========================= -->

<!-- =======================START======================= -->
<tr>
<td>
Describe HTML attributes
</td>
<td>
<details>
<summary>
Solution
</summary> 

```
- All HTML elements can have attributes
- Attributes provide additional information about elements
- Attributes are always specified in the start tag
- Attributes usually come in name/value pairs like: name="value"
```
</details>
</td>
</tr>
<!-- =======================END========================= -->
</table>

## Dev Format
```
<table>
<!-- =======================START======================= -->
<tr>
<td>
Question Statement
</td>
<td>
<details>
<summary>
Solution
</summary> 

<!-- ``` -->
Solution Statement
<!-- ``` -->
</details>
</td>
</tr>
<!-- =======================END========================= -->
</table>
```