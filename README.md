# About Coding Ju-X Website


## File Structure

- For development while, a little js code is used which is in escaper.js that simply loads navi.html and footer.html into each page, and at release time, they will be hand copy-pasted
- All html page files must sit at top level
- For customizing the look, use bootstyle.css
- All image files must sit in img folder
- bootstrap.css, bootstrap.min.js, portfolio.js, retina-1.1.0.js are for bootstrapping.


## Texting

### Never use a br tag to style text

<p>I am writing a short text on trello.<br/>
And I want this sentence to be on a new line, but it's all part of the same text</p>


### If you want more margin above or below a title or paragraph use the CSS margin property.

p {
	margin-bottom: 20px;
}


### Use h1 for title, h2 for paragraph title, and h3 for subtopic

<h1>This is the main title</h1>

<h2>This is a paragraph title for topic 1</h2>
<p>here comes some text</p>

<h3>subtopic1</h3>
<p>More text</p>

<h3>subtopic2</h3>
<p>More text</p>


### For some smaller text, use "small" P class
