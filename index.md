<link href="style.css" rel="stylesheet">

## Documentation
1. [Hey there!](#hey-there)
   - [Before we start...](#before-we-start)
2. [The Basics](#the-basics)
   - [Breakdown](#breakdown)
   - [Tags](#tags)
   - [Breakdown (cont.)](#breakdown-cont)
   - [The `<img>` tag](#the-img-tag)

## Hey there!

Ever wanted to code websites from scratch? This documentation will give you all that you need to begin coding in HTML and CSS! 

### Before we start...

Here are the things you will need:

* A computer (Windows or macOS)
* A text or code editor

Suggestions:

Text editor - Notepad or TextEdit for Windows or macOS, respectively.

Code editor - Visual Studio Code for both Windows and macOS.

>**Always remember to keep filename extensions ticked and to end the filename with _.html_.** <br/> 
>**Also remember that you need to put the HTML file in a folder if you're using a text editor.**

## The Basics

Before we can start, you need to create a new project (VS Code) or folder (Notepad/TextEdit) with all your HTML files.

Create a new folder/project called `learn-to-code`

Create a new file in the folder/project called `basic-website.html`.

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
And [this](html/example-1.html) is what it produces.

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

Last of all, the `<p>` tag is short for paragraph. It contains the text for a paragraph.<br/>
There are also other tags for different types of writing:
```
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>
```

All of these come together to create a simple web page.

Now, try copying the code for the simple page into the `basic-website.html` file and change the text and title. Run your `basic-website.html` file in your browser. What was the result?

### The `<img>` tag
For this lesson, create a new file in your folder/project called `img-tag.html`
As you can infer, the `<img>` tag allows you to add images to an HTML page. There is one atribute that we absolutely need to add to the tag: the `src` attribute. Attributes provide additional information about elements (including tags). 'src' is short for source and tells us where to get the image from.<br/>
There are two ways you can get an image into an HTML file. The first one involves downloading one yourself:
1. Upload the file to your folder or project.
2. Set the `src` attribute to the name of your file. So if the file is `thumbs-up.png` then you add `src="thumbs-up.png"` to the `<img>` tag like this:<br/>
`<img src="thumbs-up.png">`

The other option is to use a file hosting website (such as cubeupload), then set `src` to the URL of the image. This one takes more time than the other one.

Now the task for this part is to make a website like [this one](/html/img-tag.html) with this image from the Peanuts comic strip below:

<img src="https://github.com/user-attachments/assets/3d9140b5-df24-49b4-83e9-81ef5c9d8862" width=200><br/>
(The link is https://github.com/user-attachments/assets/3d9140b5-df24-49b4-83e9-81ef5c9d8862)
Also, due to that fact that this file is large, make sure to add another attribute `width` to make it smaller. Most favourably set it to 200.<br/>
Also, if you want a title in the website, use the `<h1>` tag that I mentioned earlier. If you're stuck, open devtools by pressing Ctrl + Shift + I (Windows) or ⌘ (Cmd) + ⌥ (Option) + I (Mac), then click 'Elements'.

Make sure to put it in the `img-tag.html` file!
