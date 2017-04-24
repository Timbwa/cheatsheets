### `<html>` ###
---

**Attributes:**
* `lang="language"` - Specifies language used in the document. Example lang="en-US".

### `<head>` ###
---

Contains title, style, script, meta informations of a page.

### `<meta>` ###
---

This tag can go inside `<head>` tag. It contains meta data of an HTML page.

**Attributes:**
* `charset="charset"` - Describe the character encoding used in the document. Eg. UTF-8.
* `name="type"` - Describe different information about the document. types for name can be
    * `application-name`
	* `author`
	* `description`
	* `keyword` - Keywords about the page. Useful for search engines.
	* `viewport` - Describe how the page will be shown in different devices. Very useful for portability.
* `http-equiv="type"` - Provieds an HTTP header for the information of the content attribute. type can be:
    * `refresh` - To set refresh time of a page.
* `content="value"` - Hold values for different types specified in `name` / `http-equiv` attribute.

**Examples:**
```html
<!-- Define keywords for search engines -->
<meta name="keyword" content="HTML, Cheetsheet, Tags, Attributes">

<!-- Define description of a web page -->
<meta name="description" content="This page is about html cheatsheet">

<!--To state author of the page>
<meta name="author" content="Aagontuk">

<!-- To set character encoding -->
<meta charset="UTF-8">

<!-- To refresh page in every 15 sec -->
<meta http-equiv="refresh" content="15">

<!-- To make the page look good in every device -->
<meta name="viewport" content="width=device-width, initial-scale="1.0"">
```

### `<body>` ###
---

**Attributes:**
* `alink="color"` - color of a link when it is clicked.
* `link="color"` - color of unvisited link.
* `vlink="color"` - color of visited link.
* `background="image.png"` - background image of a page if bgcolor not set.
* `bgcolor="color"` - background color of a page if background image not set.
* `text="color"` - color of the texts in the page.

### `<h1> to <h6>` ###
---

Creates headlines in html document.

### `<hr>` ###
---

Creates a horizontal line. Used for styling the document.

**Attributes:**
* `align` - Specifies alignment.
* `size="pixel"` - Specifies height in pixel. Eg. size="10"
* `width="x%"` - Specifies width in %. Eg. width="50%"
* noshed - Line will be of a solid color.

### `<p>` ###
---

Creates a paragraph. Omit any line breaks(extra space, tab etc).

### `<pre>` ###
---

Use fixed width font. Preserve line breaks.

### Formatting Tags ###
---

* `<b>` - Bold Text.
* `<i>` - Italic Text.
* `<u>` - Underline.
* `<strong>` - Strong Text.
* `<em>` - Emphasized Text.
* `<small>` - Samll Text.
* `<sup>` - Superscript.
* `<sub>` - Subscript.
* `<mark>` - Marked Text. Text with some background color.
* `<del>` - Deleted Text. Striked.
* `<ins>` - Inserted Text. Underlined.

### Quotations ###
---

#### Quoting with quotation mark ####

Texts under `<q>` tag are placed under quotation mark.

#### Quoting using `<blockquote>` ####

`<blockquote>` is used to quote text from another source.
Text under `<blockquote>` are indented.
```html
<p>Here is some information about Themis:</p>
<blockquote cite="https://en.wikipedia.org/wiki/Themis">
Themis is an ancient Greek Titaness. She is described as
"[the Lady] of good counsel", and is the personification of
divine order, fairness, law, natural law and custom.
Her symbols are the Scales of Justice, tools used to remain balanced and pragmatic.
</blockquote>
```

#### `<abbr>` for Abbreviation ####

`<abbr>` is used for abbreviation. Show full form under cursor.
```html
<p>
	Richard M. Stallman is the creator of the <abbr title="GNU is not Unix">GNU</abbr> system.
</p>
```

#### `<address>` for Contact Information ####

```html
<address>
Luke Skywalker</br>
Naboo System</br>
</address>
```

#### `<cite>` ####

`<cite>` is used for mentioning the title of someone's work.
```html
<p><cite>Star Wars</cite> directed by George Lucas</p>
```

### HTML Color ###

Color can be specified in three way.

1. Using color name.
```html
<p style="color: red">This is a red text</p>
```
[List of standard color names](https://www.w3schools.com/colors/colors_names.asp)
2. Using RGB value.
```html
<p style="color: rgb(0, 255, 0)">This is a green text</p>
```
3. Using hexadecimal value.
```html
<p style="color: #808080">This text is Ass</p>
```