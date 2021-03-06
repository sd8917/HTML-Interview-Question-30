# HTML-Interview-Question-30
### Q1. What is the difference between “display: none” and “visibility: hidden”, when used as 
attributes to the HTML element.

When we use the attribute “visibility: hidden” for an HTML element then that element will
be hidden from the webpage but still takes up space. Whereas, if we use the “display: none” 
attribute for an HTML element then the element will be hidden, and also it won’t take up any space on the webpage.<hr />

### Q2. How to specify the link in HTML and explain the target attribute?

HTML provides a hyperlink - <a> tag to specify the links in a webpage. The ‘href’ attribute 
is used to specify the link and the ‘target’ attribute is used to specify, where do we want
to open the linked document. The ‘target’ attribute can have the following values:

_self: This is a default value. It opens the document in the same window or tab as it was 
clicked.
_blank: It opens the document in a new window or tab.
_parent: It opens the document in a parent frame.
_top: It opens the document in a full-body window.<hr/>


### Q3.In how many ways can we specify the CSS styles for the HTML element?
There are three ways in which we can specify the styles for HTML elements:

Inline: Here we use the ‘style’ attribute inside the HTML element.
Internal: Here we use the <style> tag inside the <head> tag. To apply the style we bind the elements using ‘id’ or ‘class’ attributes.
External: Here we use the <link> tag inside <head> tag to reference the CSS file into our HTML code. Again the binding between elements 
and styles is done using ‘id’ or ‘class’ attributes.<hr/>

### Q4. What are some of the advantages of HTML5 over its previous versions?
Some advantages of HTML5 are:-

It has Multimedia Support.
It has the capabilities to store offline data using SQL databases and application cache.
Javascript can be run in the background.
HTML5 also allows users to draw various shapes like rectangles, circles, triangles, etc.
Included new Semantic tags and form control tags.<hr />

### Q5. What is the difference between <figure> tag and <img> tag?
The <figure> tag specifies the self-contained content, like diagrams, images, code snippets, etc. <figure> tag is used to semantically organize the 
contents of an image like image, image caption, etc., whereas the <img> tag is used to embed the picture in the HTML5 document.<hr/>

### Q6. Is the <datalist> tag and <select> tag same?
No. The <datalist> tag and <select> tag are different. In the case of <select> tag a user will have to choose from a list of options, whereas <datalist> when used 
along with the <input> tag provides a suggestion that the user selects one of the options given or can enter some entirely different value.<hr/>

### Q7. What are Semantic Elements?
Semantic elements are those which describe the particular meaning to the browser and the developer. 
Elements like <form>, <table>, <article>, <figure>, etc., are semantic elements.<hr/>

### Q8. What type of audio files can be played using HTML5?
HTML5 supports the following three types of audio file formats:

Mp3
WAV
Ogg<hr/>

### Q9. Explain the concept of web storage in HTML5.
This web storage helps in storing some of the static data in the local storage of the browser so that we do not need to fetch it from the server every time we need it. There is a size limit based on different browsers. This helps in decreasing the load time and a smooth user experience. There are two types of web storage that are used to store data locally in HTML5:

Local Storage - This helps in storing data that will be retained even though the user reopens the browser. It is stored for each webapp on different browsers.
Session Storage - This is used for one session only. After the user closes the browser this gets deleted.<hr/>

### Q10. What are Attributes and how do you use them?

Each tag has additional attributes that change the way the tag behaves or is displayed. For example, a <input> tag has a type attribute, 
which you can use to specify whether it’s a text field, checkbox, radio button or one of many more options.
Attributes are specified directly after the name of the tag, inside the two angled brackets. They should only ever appear in opening tags 
or in self-closing tags. But, they can never be in closing tags.<hr/>


### Q11. Name some common lists that are used when designing a page.
There are many common lists used for design a page. You can choose any or a combination of the following list types:

Ordered list – The ordered list displays elements in a numbered format. It is represented by <ol> tag.
Unordered list – The unordered list displays elements in a bulleted format. It is represented by <ul> tag.
Definition list – The definition list displays elements in definition form like in a dictionary. The <dl>, <dt> and <dd> tags are used to define description list.
<hr/>

### Q12. What is an image map?
An image map is used for linking many different web pages using a single image. It is represented by <map> tag. You can define shapes in images that you 
want to include as part of an image mapping.
<hr/>

### Q13. What is a marquee?
Marquee is used for the scrolling text on a web page. It scrolls the image or text up, down, left or right automatically. You should put the text which 
you want to scroll within the <marquee>……</marquee> tag.<hr/>

### Q14.What is the difference between DIV and SPAN in HTML?
The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line,such as inside a 
paragraph. Whereas, a div or division element is block-line which is equivalent to having a line-break before and after it and used to group larger chunks of code.

Example:

<div id="HTML">
This is <span class="Web Dev">interview</span>
</div><hr/>


### Q15. What is the purpose of using alternative texts in images?
The purpose of using alternative texts is to define what the image is about. During an image mapping, it can be confusing and difficult to understand what
 hotspots correspond to a particular link. These alternative
 texts come in action here and put a description at each link which makes it easy for users to understand the hotspot links easily.<hr/>

### Q16.What is the hierarchy that is being followed when it comes to style sheets?
If a single selector includes three different style definitions, the definition that is closest to the actual tag takes precedence. 
Inline style takes priority over embedded style sheets, which takes priority over external style sheets.<hr/>

### Q17.How do you create text on a webpage that allows you to send an email when clicked ?
To change the text into a clickable link to send an email, you need to use the mailto command within the href tag. You can write it in the following way:

<a href=”mailto:youremailaddress”>text to be clicked</a><hr/>

Q18.what is the advantage of grouping several checkboxes together?
The checkboxes don’t affect one another. But, grouping these checkboxes together help to organize them. Checkbox buttons can have their name and 
do not need to belong to a group. A single web page can have many different groups of checkboxes.<hr/>

Q19. What are the limits of the text field size?
The default size for a text field is around 13 characters. However, if you include the size attribute, you can set the size value to be as low as 1. 
The maximum size value will be determined by the browser width.  Also, if the size attribute is set to 0, the size will be set to the default size of 13 characters.<hr/>

Q20. What is Cell Spacing and Cell Padding?
Cell Spacing is referred to as the space or gap between the two cells of the same table. Whereas, Cell Padding is referred to as the gap or space between the content 
of the cell and cell wall or cell border.

Example:
1. <table border cellspacing=3>
2. <table border cellpadding=3>
3. <table border cellspacing=3 cellpadding=3><hr/>


###Q21. Who invented HTML?
The inventor of HTML Tim Berners-Lee.<hr/>

###Q22. How to add favicon in HTML?
You can create a .png image and then use f the following snippets between the <head> tags for the static HTML documents:

1. <link rel="icon" type="image/png" href="/favicon.png"/> 
2. <link rel="icon" type="image/png" href="https://example.com/fav<hr/>

###Q22. How can you insert a copyright symbol in HTML webpage?
 To insert the copyright symbol you can use the “&#169” as well as “&copy” in the HTML file.<hr/>

###Q23. What are void elements in HTML?
Some elements in HTML only need an opening tag, without the need for a close tag, and these are known as void elements. Some examples are <br />, 
<img />, <hr />, etc.<hr/>

###Q24.What are data- attributes good for?
The HTML5 data attribute lets you assign custom data to an element. When we want to store more information/data about the 
element when no suitable HTML5 element or attribute exists<hr/>

###Q25.. What are the semantic tags available in html5?
HTML5 semantic tags define the function and the category of your text, simplifying the work for browsers and search engines, as well as developers.

HTML5 offers new semantic elements to define different parts of a web page:

<article>
<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time><hr/>

###Q26. Can a web page contain multiple <header> elements? What about <footer> elements?
Yes, header elements can be used multiple times in documents. A <header> tag must be present for 
all articles, sections, and pages, although a <footer> tag is not necessary.<hr/>

### Q27.What is Character Encoding?
Character encoding is a method of converting bytes into characters. To validate or display an HTML document properly, a program must choose a proper
 character encoding. This is specified in the tag:

<meta charset="utf-8"/>
UTF-8: A Unicode Translation Format that comes in 8-bit units that is, it comes in bytes. A character in UTF8 can be from 1 to 4 bytes long, making UTF8 
variable width.<hr/>

###Q28.What does enctype='multipart/form-data' mean?
The enctype attribute specifies how the form-data should be encoded when submitting it to the server.<hr/>

###Q29. How to make page responsive?
Responsive Web Design is about using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones).

1. Setting the viewport
2. Responsive Images

3. Show different Images depending on Browser Width
4. Responsive Text Size
5. Media Queries<hr/>



###Q30.Meter Tag
Indicates a numeric value that falls within a range. The tag supports a number of attributes: value: If you don't specify a value, the first numeric value inside the <meter></meter> pair becomes the value.

max: The maximum possible value of the item.
min: The minimum possible value of the item.
high: If the value can be defined as a range, this is the high end of the range.
low: If the value can defined as a range, this is the low end of that range.
optimum: The optimal value of the element.
optimum: The optimal value of the element.<hr />





