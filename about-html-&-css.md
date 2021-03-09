# Basic HTML & CSS Concepts 

Elements, tags, and attributes are basic concepts in HTML.

## HTML element is a main structural unit of a web page. HTML tags are used to define HTML elements, and attributes provide additional information about these elements.

### About HTML Tags

HTML tags are used to structure website content (text, hyperlinks, images, media, etc). 
Tags are not displayed in the browsers, they only “instruct” browsers how to show the content of the web page.

*HTML tags are written in angle brackets (e.g <html>).*

- Most of HTML tags comes in pairs, like <p> </p> tags. 
- The first tag in a pair called the start (opening) tag, and the second tag is the end (closing) tag. 
- The information is written between opening and closing tags.

``` 
However, there are unpaired, or empty tags, which only have opening tag. (for ex. <img/>).
```


### HTML Attributes
HTML attributes are added to an HTML element to provide additional information about it. 
For example, if you define an image with <img/> tag, you can use src, height, width attributes to provide information about its source, height, width correspondingly.


### Structure of an HTML Document
The <!DOCTYPE html> declaration specifies the HTML version used in the document. 
Every HTML document should start with this declaration so that the browsers can render the page compliant with HTML standards.

*There exist several types of <!DOCTYPE> defined for each HTML version.*

All the content on the webpage is written between <html> </html> tags.
- The html element is used to give information to the browsers that it is an HTML document.

- The head element contains metadata (data about the HTML document), character set, document title, styles, etc. This data is not shown to viewers.

- The title displays the title of the website in the browser tab when the page is loaded. The title is written between <title> </title> tags.

- The meta tags are snippets of text that describe a page's content; they don't appear on the page itself, but only in the page's source code. Meta tags are essentially little content descriptors that help tell search engines what a web page is about.

### Why use UTF-8? 
 `An HTML page can only be in one encoding. You cannot encode different parts of a document in different encodings. `
 `A Unicode-based encoding such as UTF-8 can support many languages and can accommodate pages and forms in any mixture of those languages.`

- The body element contains the content of the webpage (text, images, videos, etc). The content is written between <body> </body>.

```
Heading elements contain different types of headings. 
There are six heading levels - <h1>-<h6>,  where <h1> is the most important and <h6> least important tags.
The <p> element contains paragraphs of the text. The content is written between <p> and </p> tags.
 ```
- [Useful resource](https://html.com/wp-content/uploads/html-cheat-sheet.pdf)
- [Html theories and practice materials](https://www.tutorialspoint.com/html/index.htm)
---------------------

## CSS information
### There are three types of stylesheets:
1. Internal - Placed right on the page whose interface it will affect.`within the <style></style> tags`
2. External - Placed in a separate file.`maybe fetched from a different source or placed as a separate file in a folder/repository`
3. Inline - Placed inside a tag it will affect.`specific attributes for the section they are intended for`

- [CSS resource](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
 ![Reference image](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/css-declaration-small.png)
---------------------
 
 ## Tips for blending markdown and html code
 `
It is possible to put HTML inside markdown. For that,we add markdown="1" to your html element to tell the markdown parser to parse that as markdown.`
```
# Heading 1

<div class="something" markdown="1">
  ## Heading 2
  Some **bold** text.
</div>
```
- [Useful resource](https://css-tricks.com/little-stuff-markdown-always-forget-google/)
