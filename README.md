- URL_TO_PUT

# html-css-javascript
You want to be able to undrestand the web developement and know the basics, follow me in this article to be autonomous.  

## Definitions
lets make some definitions
* **html (HyperText Markup Language) :** is used to define the structure of the webpage. For example defining that in the page there is a header then a paragraphe...
* **css (Cascading Style Sheets) :** is used to define the style of the webpage. For example specifying the color of a text or the position of an element in the page...
* **javascript :** is used to make the website dynamic. For example when clicking a button, then do an action, or when loading the page do onoter action...
> ⚠️**PS :** We will go deeper in each one of theme

## What we will build
To learn somthing, the best way is to practice it, we will build together a webpage for a calculator, this is the [final result](URL_TO_PUT). By the way, you will learn the basics of html, css and javascript.

## Requirements
Some tools are mondatory to build a webpage, but in generaly you have the needed tools builtin in most operating system.

* **Text editor / IDE (integrated development environment) :** You need any text editor to write the code, you can use the builtin text editor for your operating system or download one. The most used IDE for web developement is [visual studio code](https://code.visualstudio.com/), it will be helpfull in many programming context. For more detail, read more about [IDE](https://en.wikipedia.org/wiki/Integrated_development_environment)
* **Browser :** used to run the code after creating, the most known browser are [Google Chrome](https://www.google.fr/chrome), [Microsoft Edge](https://www.microsoft.com/edge), [Mozilla Firefox](https://www.mozilla.org/firefox) or [safari](https://www.apple.com/safari/)...
> ⚠️**PS :** Using an IDE is more productive and easier than using a normal text editor like [Notepad++](https://notepad-plus-plus.org/downloads/)

## Working folder
It's recomanded to work in a specific folder in your System. We will assume that you want to created a folder named `my-work` under your home directory
- **Windows :** create the folder under `C:\Users\YOUR_USER`. Change `YOUR_USER` with the name of the user in the System, you will find the folder under C:\Users). Open yor cmd
```sh
cd C:\Users\YOUR_USER
mkdir my-work
cd my-work
```
> ⚠️
> - **PS :** You can do the same creaing using windows expolorer unstead of using terminal
> - **PS :** You can use any location in your computer
- **linux / mac :** create the folder under your home `~`
```sh
cd ~
mkdir my-work
cd my-work
```

# HTML (HyperText Markup Language)
HTML stand for **HyperText Markup Language**, it's a text following the XML structure.
## Create your first html page
Create a file `index.html` under your working folder (`my-work`) and write the following code
```html
<!DOCTYPE html>
<html>
<head>
<title>My awsom page</title>
</head>
<body>

<h1>This is a html header H1</h1>
<hr/>
<p>This is a paragraph p</p>

</body>
</html>
```
 open the file in your browser. The result of the webpage is shown
 (IMAGE_RUN_BROWSE)[URL_TO_PUT] 

## HTML structure
The html text is a collection of xml tags. But what is a xml tag ? an Xml tag have two main types
* Having closing tag : `<TAG_NAME>CONTENT</TAGNAME>`

* Not having closing tag : <TAG_NAME/>
> - `TAG_NAME` is a [html tag](https://developer.mozilla.org/fr/docs/Web/HTML/Element). We will discover many html tags in this document
> - `CONTECT` is any content to put, it can be a simple text or HTML tag. 