# <center><b>HTML : Hyper Text Markup Language</b></center>
##  :open_file_folder: *Listings and Instructions*
1. This is for absolute beginners who wants to get knowledge of HTML.
2. Stay tuned with us on Youtube for quality content and explanation [**Antern**](https://youtube.com/channel/UCIpbqdvNWx50J79KAG1Q21A) and follow Team Antern on LinkedIn for free contents [**LinkedIn**](https://www.linkedin.com/company/team-antern)
3. :memo: Keep taking notes of important points.
4. For Doubt Support and Suggestions join our [**Discord Community**](https://discord.gg/UVsX294GeW).
---

## :blue_book: *Content Index* 

*  [Introduction](#Introduction)
*  [HTML Elements](#Elements)
*  [HTML Attributes](#Attributes)
*  [Basic Structure](#Basic-Structure)
*  [Basic Tags](#Basic-Tags)
*  [Text/Paragraph](#TextParagraphs)
    *  [Code Snippet](#Code-Snippet)
* [Text Formatting](#Text-Formatting)
* [Code](#Code)
* [Lists](#Lists)
    * [Ordered Lists](#Ordered-Lists)
    * [Unordered Lists](#Unordered-Lists)
* [Links](#Links)
* [Tables](#Tables)
* [Media](#Media)
    * [Image](#Image)
    * [Audio](#Audio)
    * [Video](#Video)
* [Forms](#Forms)
* [Container Tags](#Container-Tags)
* [HTML Semantics](#HTML-Semantics)
* [Meta Properties](#Meta-Properties)

---


## Introduction

<h5>HTML is the very basic building block for a website. HTML is the bone of the website. We use it to structure our website then we style it using CSS(Cascading StyleSheet) and provide behaviour and interaction through JavaScript.</h5>

![Structure Example](https://i.imgur.com/iyZsjtv.jpg)

<h6>
HTML : Structure,<br>
CSS : Styling,<br>
JavaScript : Behaviour, Interaction, etc.
</h6>

## Elements
<h5>HTML Tags helps in creating elements and declaring web page information.
For understanding html elements easily let's say that tags are used to perform some functions.</h5>

<h5>Paragraphs are elements and they are created with "p" tag.
Tags have 3 parts:</h5>

<h5>Opening Tag - It helps to start the function performed by tag.</h5>

`<tagname>`

<h5>Closing Tag - It helps to end the function performed by a tag.</h5>

`</tagname>`

<h5>Content - It is the thing over which function is performed</h5>

<h5>Example</h5>

```htmlembedded=
<p>Content</p>
```

## Attributes
<h5>Attributes adds additional information about the HTML Elements.</h5>

<h4>Notes</h4>

* Attributes are specified within the starting tag
* All the html elements can have attributes

<h4>Example</h4>
<h5>Let's take an example of the image tag</h5>

```htmlembedded=
<img src="image.png" >
```

<h5>In this example img is the tag and src is the attribute</h5>
<h5>We would be exploring this img tag later on in this cheat sheet. But for now I would give a very basic idea what it does.</h5>
<h5>It basically helps us to add any sort of image in our html document.</h5>

## Basic Structure


```htmlmixed=
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta charset="UTF-8">
         <title>Document</title>
    </head>
    <body>

    </body>
</html>
```

## Basic Tags

* `<!DOCTYPE html>` : It's an information to the browser what type of document it is
* `<html></html>` : Creates an HTML Document
* `<head></head>` : This tag consists of MetaData, Title, etc.
* `<body></body>` : This tag is used to define the HTML Document’s body
* `<title></title>` : Used to give HTML Document a title
* `<style></style>` : Used to add internal css
* `<meta></meta>` : It is used to define META DATA about the HTML Document
* `<link rel="stylesheet" href="styles.css">` : It is used to add external resources to our html document such as StyleSheets

## Text/Paragraphs
### Code Snippet
```htmlembedded=
<h1>Header One</h1>
<h2>Header Two</h2>
<h3>Header Three</h3>
<h4>Header Four</h4>
<h5>Header Five</h5>
<h6>Header Six</h6>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

<p>Lorem ipsum dolor <br> sit amet</p>
<pre>Hello, Readers</pre>
```
<h4>There are total 6 heading tags availiable in HTML and amongst them h1 is the largest and h6 is the smallest.</h4>

* `<h1></h1>` : Heading 1
* `<h2></h2>` : Heading 2
* `<h3></h3>` : Heading 3
* `<h4></h4>` : Heading 4
* `<h5></h5>` : Heading 5
* `<h6></h6>` : Heading 6

<h4>There is one Paragraph tag that is used to write paragraphs in HTML</h4>

* `<p></p>` : Paragraph

<h4>To add line breaks we use br tag for it</h4>

* `<br>` : Break

<h4>In HTML we can also include pre formatted text</h4>

* `<pre></pre>` : Pre Formatted Text

## Text Formatting
<h4>In HTML we have multiple tags to format text, we can format text to italic, bold, etc.</h4>

```htmlmixed=
<b>bold</b>
<strong>strong</strong>
<i>italic</i>
<em>emphasized</em>
<sub>subscripted</sub>
<sup>super scripted</sup>
```

* `<b></b>` : To make the text <b>bold</b>
* `<strong></strong>` : <strong>strong</strong> is like <b>bold</b> but it is semantic
* `<i></i>` : To make the text <i>italic</i>
* `<em></em>` : <em>emphasized</em> is like <i>italic</i> but it is semantic
* `<sub></sub>` : To make the text <sub>subscripted</sub>
* `<sup></sup>` : To make the text <sup>super scripted</sup>

## Code
<h4>Code tag is used to show code snippets in html</h4>

```htmlembedded=
<code>print("Hello, Anternians")</code>
```

## Lists
<h4>Lists are basically used to list down items. There are multiple types of lists such as bullets, numbers, etc. In HTML there are 3 Tags ol, li, ul</h4>

<h3>Ordered Lists</h3>
<h4>Ordered Lists can be alphabetical or numerical. Inside of Ordered Lists we include list items.</h4>

* `<ol></ol>` : Ordered Lists
* `<li></li>` : List Items

```htmlembedded=
<ol>
    <li>Java</li>
    <li>Python</li>
    <li>JavaScript</li>
</ol>
```

<h3>Unordered Lists</h3>
<h4>Unordered Lists are bulleted lists. Inside of Unordered Lists we include list items.</h4>

* `<ul></ul>` : Unordered Lists
* `<li></li>` : List Items

```htmlembedded=
<ul>
    <li>Java</li>
    <li>Python</li>
    <li>JavaScript</li>
</ul>
```

## Links
<h4>Links are clickable and with that we can redirect to another page.</h4>

<h4>NOTE: </h4>
<h5>There are 2 types of URL</h5>

* Absolute URL: It basically is external urls
    * Example: https://antern.co/
* Relative URL: It basically is the location of a particular file within the folder
    * Example: ./pages/details.html


* `<a></a>` : With the help of Anchor tag we can add hyperlinks.

```htmlembedded=
<a href="https://antern.co/">Visit Antern Offical Website</a>
<a href="./pages/details.html">Details page</a>
```

## Tables
<h4>With the help of HTML Table we can arrange the data in tabular form. Tables are a collection of rows and columns</h4>

* `<table></table>` : This tag defines a table in the html document
* `<caption></caption>` : This tag defines a caption for the table
* `<th></th>` : This tag helps to add header of the table
* `<tr></tr>` : This tag helps to specify rows
* `<td></td>` : This tag helps to add table data
* `<thead></thead>` : Used to group all the header content of the table
* `<tbody></tbody>` : Used to group all the body content of the table
* `<tfoot></tfoot>` : Used to group all the footer content of the table

```htmlembedded=
<table border="2">
    <caption>Demo Table</caption>
    <thead>
        <th>Header 1</th>
        <th>Header 2</th>
    </thead>
    <tbody>
        <tr>
            <td>Data 1</td>
            <td>Data 2</td>
        </tr>
        <tr>
            <td>Data 3</td>
            <td>Data 4</td>
        </tr>
    </tbody>
    <tfoot>
        <tr>
            <td>Footer 1</td>
            <td>Footer 2</td>
        </tr>
    </tfoot>
</table>
```
![](https://i.imgur.com/qK9nyjp.png)


## Media
### Image

<h5>Should be known before learning media tags</h5>

* [Attributes](#Attributes)
* [Links](#Links)

<h5>We have already learnt a bit about img tag previouly in some sections. Here we would be looking into it with more depth</h5>
<h5>The image tag has 2 most important attributes: </h5>

* `src` : Specifies the url
* `alt` : Specifies the alternate message if the image is not loaded

```htmlembedded=
<img src="https://antern.co/images/textlogo.png" alt="antern-logo">
```

<h5>If somehow the image is not loaded then the alt text would be shown</h5>

### Audio

<h5>With the help of Audio tag we can add audio files in our html document</h5>
<h5>Within audio tag there's another tag called source tag it would help us to add the source of audio. One more thing there are some audio types/format that are not supported in some browser's. We can provide as many source tags we want but the browser will the pick the one whose audio type/format is supported in the browser</h5>

*  `<audio></audio>` : Embed sounds in the html document
*  `<source>` : We can provide the source of the audio

```htmlembedded=
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    <source src="audio2.ogg" type="audio/ogg">
    Your browser does not support the audio element.
</audio>
```

### Video

<h5>With the help of Video tag we can embed video files in our html document</h5>
<h5>Within video tag there's another tag called source tag it would help us to add the source of videos. One more thing there are some video types/format that are not supported in some browser's. We can provide as many source tags we want but the browser will the pick the one whose video type/format is supported in the browser</h5>

*  `<video></video>` : Embed videos in the html document
*  `<source>` : We can provide the source of the video

```htmlembedded=
<video width="512" height="512" controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video element.
</video>
```

## Forms
<h5>HTML Forms are used for entering data. Mostly it is sent to the servers for processing the collected data through froms.</h5>

* `<form></form>` : Used to create form element in HTML.
* `<input>` : Used to create input field in HTML
* `<label></label>` : Used to create labels

```htmlembedded=
<form>
  <label for="name">Name</label><br>
  <input type="text" id="name" name="name"><br>
  <label for="email">Email:</label><br>
  <input type="text" id="email" name="email">
  <input type="submit" value="Submit" />
</form>
```

<h5>As you can see in the input tag there are multiple types and all of these types does different things. All types are listed below.</h5>

#### Input Types

* `<input type="text">` : Creates a text input field
* `<input type="radio">` : Creates radio buttons
* `<input type="checkbox">` : Creates check boxes
* `<input type="submit">` : Creates a submit button
* `<input type="button">` : Creates a button

#### Radio Buttons

```htmlembedded=
<form>
  <input id="c1" name="c1" type="radio" />
  <label for="c1">BMW</label><br />
  <input id="c2" name="c2" type="radio" />
  <label for="c2">McLaren</label><br />
  <input id="c3" name="c3" type="radio" />
  <label for="c3">Audi</label>
</form>
```

#### Checkbox

```htmlembedded=
<form>
  <input id="c1" name="c1" type="checkbox" />
  <label for="c1">BMW</label><br />
  <input id="c2" name="c2" type="checkbox" />
  <label for="c2">McLaren</label><br />
  <input id="c3" name="c3" type="checkbox" />
  <label for="c3">Audi</label>
</form>
```

#### Text and Submit

```htmlembedded=
<form>
  <label for="c1">Name</label><br />
  <input id="c1" name="c1" type="Name" />
  <input type="submit" value="Submit">
</form>
```

## Container Tags
<h5>These tags are used to create seperate blocks or containers in html.</h5>

* `<div></div>` : It is used to create blocks/containers for content.
* `<span></span>` : It is used to create in-line containers/blocks

```htmlembedded=
<div>
  <p>Created a container</p>
  <p>Created a <span>in line container</span></p>
</div>
```

## HTML Semantics

<h5>HTML Semantics are self explanable tags. I mean just by reading the name of the semantic tags you can tell what it does.</h5>

<h4>Examples</h4>
<h5>Non Semantic Tags:</h5>

* `<div></div>`
* `<span></span>`

<h5>Semantic Tags:</h5>

* `<section></section>`
* `<aside></aside>`

![Semantic Chart](https://i.imgur.com/uu8Vexm.gif)

* `<section></section>` : It is used to create a section
* `<article></article>` : It represents self contained content
* `<aside></aside>` : It is used to create content that is to be place at the side.
* `<header></header>` : Specifies header in html document
* `<footer></footer>` : Used to create content to be placed in footer
* `<nav></nav>` : Used to create navigation links

<h4>Example Code</h4>

```htmlembedded=

<!DOCTYPE html>
<html>
<body>

<h1>HTML Semantics</h1>

<!-- Header -->
<header>
	<!-- Nav -->
	<nav>
    	<div class="Left">
        	<h1>HTML</h1>
        </div>
        <div class="Right">
        	<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">Blogs</a></li>
				<li><a href="#">Projects</a></li>
			</ul>
        </div>
    </nav>
</header>

<!-- Section -->
<section>

  <h1>This is a Section</h1>
  <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>

<section/>

<!-- Article -->
<article>
  <h1>This is an Article</h1>
  <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
</p>
</article>

<!-- Aside -->
<aside>
	<h1>Aside Content</h1>
	<ul>
		<li><a href="#">Home</a></li>
		<li><a href="#">Blogs</a></li>
		<li><a href="#">Projects</a></li>
	<ul>
</aside>

<!-- Footer -->

<footer>
  <h1>Footer</h1>
  <a href="mailto:example@gmail.com">Example Email</a>
</footer>

</body>
</html>


```

## Meta Properties

<h5>Meta tags helps to define meta data for our website. It is really helpful in multiple ways. Metadata is the information of our website.</h5>

```htmlmixed=
<head>
  <meta charset="UTF-8">
  <meta name="keywords" content="HTML, Cheat Sheet, Web Development">
  <meta name="description" content="HTML Cheat Sheet by Antern">
  <meta name="author" content="Priyanshu Bhattacharjee">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
```
* `<meta charset="UTF-8">` : Specifies the Character Encoding for the HTML Document
* `<meta name="keywords" content="HTML, Cheat Sheet, Web Development">` : Defines the keywords of the website.
* `<meta name="description" content="HTML Cheat Sheet by Antern">` : Adds description of the website
* `<meta name="author" content="Priyanshu Bhattacharjee">` : Adds authors name in the website
* `<meta name="viewport" content="width=device-width, initial-scale=1.0">` : Set's the viewport of the website