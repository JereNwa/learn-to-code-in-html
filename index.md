<link href="style.css" rel="stylesheet">

## Documentation
1. [Hey there!](#hey-there)
   - [Before we start...](#before-we-start)
2. [The Basics](#the-basics)
   - [Breakdown](#breakdown)
   - [Tags](#tags)
   - [Breakdown (cont.)](#breakdown-cont)

## Hey there!

Ever wanted to code websites from scratch? This documentation will give you all that you need to begin coding in HTML and CSS! 

### Before we start...

Here are the things you will need:

* A computer (Windows or macOS)
* A text or code editor

Suggestions:

Text editor - Notepad or TextEdit for Windows or macOS, respectively.

Code editor - Visual Studio Code for both Windows and macOS.

>**Always remember to keep filename extensions ticked and to end the filename with _.html_.** 

## The Basics

To learn HTML, we're going to have to start with the basics.

Below is a simple piece of HTML code:


```
<!DOCTYPE html>
<html>
<head>
<title>Basic Website</title>
<body>
<p>This is a HTML test.</p>
</body>
</html>
```
And [this](example-1.html) is what it produces.

I'm now going to break down the code.

### Breakdown

The `<!DOCTYPE html>` declaration is at the start of every piece of HTML code. It tells the browser what document type to expect.
Next is the `<html>` tag. It's the root of an HTML document, containing all code in the document (excluding the `<!DOCTYPE html>` declaration).


Before we move on, I need to talk a bit about tags.

### Tags

> "Tags are comprised of elements and attributes. An element is an object on a page (such as a heading, paragraph, or image), and attributes are qualities that describe that element (such as width and height). Tags usually travel in pairs. An opening tag (`<tag>`) begins a section of page content, and a closing tag (`</tag>`) ends it."

_- University of Washington_

 Thus, all of the words that are embedded in '<>' are tags, excluding the `<!DOCTYPE html>` declaration which is not a tag.

 ### Breakdown (cont.)

Next is the `<head>` tag. This contains metadata (data about the HTML document). Metadata typically define the document title, styles, and scripts, though it does define more.

 The `<title>` tag contains the name of browser tab.

 The `<body>` tag contains the main part of the document, including text and images.

 Last of all, the `<p>` tag is short for paragraph. It contains the text for a paragraph.

 All of these come together to create a simple web page.

 Now, try copying the code for the simple page and change the text and title. Run your new code. What was the result?
