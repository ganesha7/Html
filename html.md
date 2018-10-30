---


---

<h1 id="html-basic">HTML Basic</h1>
<h2 id="html-documents">HTML Documents</h2>
<p>All HTML documents must start with a document type declaration:<br>
<code>&lt;!DOCTYPE html&gt;</code>.<br>
The HTML document itself begins with  <code>&lt;html&gt;</code>  and ends with<br>
<code>&lt;/html&gt;</code>.</p>
<p>The visible part of the HTML document is between  <code>&lt;body&gt;</code>  and<br>
<code>&lt;/body&gt;</code>.</p>
<pre><code>Example:
    
&lt;!DOCTYPE html&gt;
&lt;html&gt;  
&lt;body&gt;
 &lt;h1&gt;My First Heading&lt;/h1&gt;  
 &lt;p&gt;My first paragraph.&lt;/p&gt;
 &lt;/body&gt;  
  &lt;/html&gt;
</code></pre>
<h2 id="html-headings">HTML Headings</h2>
<p>HTML headings are defined with the  <code>&lt;h1&gt;</code>  to  <code>&lt;h6&gt;</code>  tags.</p>
<p><code>&lt;h1&gt;</code>  defines the most important heading.  <code>&lt;h6&gt;</code>  defines the least important heading:</p>
<pre><code> Example:
 
 &lt;h1&gt;This is heading 1&lt;/h1&gt;  
 &lt;h2&gt;This is heading 2&lt;/h2&gt;  
 &lt;h3&gt;This is heading 3&lt;/h3&gt;
</code></pre>
<h2 id="html-paragraphs">HTML Paragraphs</h2>
<p>HTML paragraphs are defined with the <code>&lt;p&gt;</code> tag:</p>
<pre><code>Example:

&lt;p&gt;This is a paragraph.&lt;/p&gt;  
&lt;p&gt;This is another paragraph.&lt;/p&gt;
</code></pre>
<h2 id="html-links">HTML Links</h2>
<p>HTML links are defined with the <code>&lt;a&gt;</code> tag:</p>
<pre><code>Example:

&lt;a href="https://www.w3schools.com"&gt;This is a link&lt;/a&gt;
</code></pre>
<h2 id="html-images">HTML Images</h2>
<p>HTML images are defined with the  <code>&lt;img&gt;</code>  tag.</p>
<p>The source file (<code>src</code>), alternative text (<code>alt</code>),  <code>width</code>, and  <code>height</code>  are provided as attributes:</p>
<pre><code>Example:

&lt;img src="w3schools.jpg"  alt="W3Schools.com" 
width="104" height="142"&gt;
</code></pre>
<h2 id="html-buttons">HTML Buttons</h2>
<p>HTML buttons are defined with the <code>&lt;button&gt;</code> tag:</p>
<pre><code>Example:

&lt;button&gt;Click me&lt;/button&gt;
</code></pre>
<h2 id="html-lists">HTML Lists</h2>
<p>HTML lists are defined with the <code>&lt;ul&gt;</code> (unordered/bullet list) or the <code>&lt;ol&gt;</code> (ordered/numbered list) tag, followed by <code>&lt;li&gt;</code> tags (list items):</p>
<pre><code>Example:

&lt;ul&gt;  
&lt;li&gt;Coffee&lt;/li&gt;  
&lt;li&gt;Tea&lt;/li&gt;  
&lt;li&gt;Milk&lt;/li&gt;  
&lt;/ul&gt;

&lt;ol&gt;
&lt;li&gt;Coffee&lt;/li&gt;  
&lt;li&gt;Tea&lt;/li&gt;  
&lt;li&gt;Milk&lt;/li&gt;  
&lt;/ol&gt;
</code></pre>
<h2 id="html-elements">HTML Elements</h2>
<p>An HTML element usually consists of a <strong>start</strong> tag and <strong>end</strong> tag, with the content inserted in between:</p>
<pre><code>&lt;tagname&gt;Content goes here...&lt;/tagname&gt;
</code></pre>
<p><strong>Example:</strong></p>
<pre><code>&lt;h1&gt;My First Heading &lt;/h1&gt;
&lt;p&gt;My first paragraph.&lt;/p&gt;
&lt;br&gt;(which indicates a line break)
</code></pre>
<h2 id="nested-html-elements">Nested HTML Elements</h2>
<p>HTML elements can be nested (elements can contain elements).<br>
All HTML documents consist of nested HTML elements.</p>
<p><strong>Example:</strong></p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html&gt;  
&lt;body&gt;  

&lt;h1&gt;My First Heading&lt;/h1&gt;  
&lt;p&gt;My first paragraph.&lt;/p&gt;  

&lt;/body&gt;  
&lt;/html&gt;
</code></pre>
<h1 id="html--attributes">HTML  Attributes</h1>
<ul>
<li>All HTML elements can have  <strong>attributes</strong></li>
<li>Attributes provide  <strong>additional   information</strong>  about an element</li>
<li>Attributes are always specified in  <strong>the start tag</strong></li>
<li>Attributes usually come in name/value pairs like:  <strong>name="value"</strong></li>
</ul>
<h2 id="the-href-attribute">The href Attribute</h2>
<p>HTML links are defined with the <code>&lt;a&gt;</code> tag. The link address is specified in the <code>href</code> attribute:</p>
<pre><code>Example:
&lt;a href="https://www.w3schools.com"&gt;
This is a link&lt;/a&gt;
</code></pre>
<h2 id="the-src-attribute">The src Attribute</h2>
<p>HTML images are defined with the  <code>&lt;img&gt;</code>  tag.<br>
The filename of the image source is specified in the  <code>src</code>  attribute:</p>
<pre><code>Example:
&lt;img src="img_girl.jpg"&gt;
</code></pre>
<h2 id="the-width-and-height-attributes">The width and height Attributes</h2>
<p>Images in HTML have a set of <strong>size</strong> attributes, which specifies the width and height of the image:</p>
<pre><code>Example:
&lt;img src="img_girl.jpg"  width="500"  height="600"&gt;
</code></pre>
<p>The image size is specified in pixels: Width=“500” means 500 pixels wide.</p>
<h2 id="the-alt-attribute">The alt Attribute</h2>
<p>The <code>alt</code> attribute specifies an alternative text to be used, when an image cannot be displayed.</p>
<pre><code>Example:
&lt;img src="img_girl.jpg"  alt="Girl with a jacket"&gt;
</code></pre>
<h2 id="the-style-attribute">The style Attribute</h2>
<p>The <code>style</code> attribute is used to specify the styling of an element, like color, font, size etc.</p>
<pre><code>Example:
&lt;p style="color:red"&gt;I am a paragraph&lt;/p&gt;
</code></pre>
<h2 id="the-lang-attribute">The lang Attribute</h2>
<p>The language of the document can be declared in the  <code>&lt;html&gt;</code>  tag.<br>
The language is declared with the  <code>lang</code>  attribute.</p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html lang="en-US"&gt;  
&lt;body&gt;  

...  

&lt;/body&gt;  
&lt;/html&gt;
</code></pre>
<p>The first two letters specify the language (en). If there is a dialect, use two more letters (US).</p>
<h2 id="the-title-attribute">The title Attribute</h2>
<p>Here, a <code>title</code> attribute is added to the <code>&lt;p&gt;</code> element. The value of the title attribute will be displayed as a tooltip when you mouse over the paragraph:</p>
<pre><code>&lt;p title="I'm a tooltip"&gt;  
This is a paragraph.  
&lt;/p&gt;
</code></pre>
<h2 id="quote-attribute-values">Quote Attribute Values</h2>
<p>The HTML5 standard does not require quotes around attribute values.</p>
<p>The  <code>href</code>  attribute, demonstrated above,  <em>can</em>  be written without quotes:</p>
<pre><code>Wrong:
&lt;a href=https://www.w3schools.com

Good:
&lt;a href="https://www.w3schools.com"&gt;
</code></pre>
<h1 id="html--headings">HTML  Headings</h1>
<p>Headings are defined with the <code>&lt;h1&gt;</code> to <code>&lt;h6&gt;</code> tags.</p>
<p><code>&lt;h1&gt;</code>  defines the most important heading.  <code>&lt;h6&gt;</code>  defines the least important heading.</p>
<pre><code>Example:
&lt;h1&gt;Heading 1&lt;/h1&gt;  
&lt;h2&gt;Heading 2&lt;/h2&gt;  
&lt;h3&gt;Heading 3&lt;/h3&gt;  
&lt;h4&gt;Heading 4&lt;/h4&gt;  
&lt;h5&gt;Heading 5&lt;/h5&gt;  
&lt;h6&gt;Heading 6&lt;/h6&gt;
</code></pre>
<h2 id="bigger-headings">Bigger Headings</h2>
<p>Each HTML heading has a default size. However, you can specify the size for any heading with the <code>style</code> attribute, using the CSS <code>font-size</code> property:</p>
<pre><code>Example:
&lt;h1 style="font-size:60px;"&gt;Heading 1&lt;/h1&gt;
</code></pre>
<h2 id="html-horizontal-rules">HTML Horizontal Rules</h2>
<p>The  <code>&lt;hr&gt;</code>  tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.</p>
<p>The  <code>&lt;hr&gt;</code>  element is used to separate content (or define a change) in an HTML page:</p>
<pre><code>Example:
&lt;h1&gt;This is heading 1&lt;/h1&gt;  
&lt;p&gt;This is some text.&lt;/p&gt;  
&lt;hr&gt;  
&lt;h2&gt;This is heading 2&lt;/h2&gt;  
&lt;p&gt;This is some other text.&lt;/p&gt;  
&lt;hr&gt;
</code></pre>
<h2 id="the-html-head-element">The HTML  Element</h2>
<p>The HTML  <code>&lt;head&gt;</code>  element has nothing to do with HTML headings.</p>
<p>The  <code>&lt;head&gt;</code>  element is a container for metadata. HTML metadata is data about the HTML document. Metadata is not displayed.</p>
<p>The  <code>&lt;head&gt;</code>  element is placed between the  <code>&lt;html&gt;</code>  tag and the  <code>&lt;body&gt;</code>  tag</p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html&gt;  

&lt;head&gt;  
&lt;title&gt;My First HTML&lt;/title&gt;  
&lt;meta charset="UTF-8"&gt;  
&lt;/head&gt;  

&lt;body&gt;  
....
....
&lt;/body&gt;
&lt;/html&gt;
</code></pre>
<h1 id="html--paragraphs">HTML  Paragraphs</h1>
<p>The HTML <code>&lt;p&gt;</code> element defines a <strong>paragraph</strong>:</p>
<pre><code>Example:
&lt;p&gt;This is a paragraph.&lt;/p&gt;  
&lt;p&gt;This is another paragraph.&lt;/p&gt;
</code></pre>
<h2 id="html-line-breaks">HTML Line Breaks</h2>
<p>The HTML  <code>&lt;br&gt;</code>  element defines a  <strong>line break</strong>.</p>
<p>Use  <code>&lt;br&gt;</code>  if you want a line break (a new line) without starting a new paragraph:</p>
<pre><code>Example:
&lt;p&gt;This is&lt;br&gt;a paragraph&lt;br&gt;with line breaks.&lt;/p&gt;
</code></pre>
<p>The <code>&lt;br&gt;</code> tag is an empty tag, which means that it has no end tag.</p>
<h2 id="the-html-pre-element">The HTML <code>&lt;pre&gt;</code> Element</h2>
<p>The HTML  <code>&lt;pre&gt;</code>  element defines preformatted text.</p>
<p>The text inside a  <code>&lt;pre&gt;</code>  element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:</p>
<pre><code>&lt;pre&gt;  
My Bonnie lies over the ocean.  

My Bonnie lies over the sea.  

My Bonnie lies over the ocean.  

Oh, bring back my Bonnie to me.  
&lt;/pre&gt;
</code></pre>
<h1 id="html--styles">HTML  Styles</h1>
<h2 id="the-html-style-attribute">The HTML Style Attribute</h2>
<p>Setting the style of an HTML element, can be done with the  <code>style</code>  attribute.</p>
<p>The HTML  <code>style</code>  attribute has the following  <strong>syntax</strong>:</p>
<pre><code>Syntax:
&lt;tagname style="_property_:_value;_"&gt;

Example:
&lt;h1 style="color:red;&gt;heading&lt;/h1&gt;
</code></pre>
<h2 id="html-background-color">HTML Background Color</h2>
<p>The <code>background-color</code> property defines the background color for an HTML element.</p>
<pre><code>Example:

&lt;body style="background-color:powderblue;"&gt;  

&lt;h1&gt;This is a heading&lt;/h1&gt;  
&lt;p&gt;This is a paragraph.&lt;/p&gt;  

 &lt;/body&gt;
</code></pre>
<h2 id="html-text-color">HTML Text Color</h2>
<p>The <code>color</code> property defines the text color for an HTML element:</p>
<pre><code>Example:

&lt;h1 style="color:blue;"&gt;This is a Heading&lt;/h1&gt;  
&lt;p style="color:red;"&gt;This is a paragraph.&lt;/p&gt;
</code></pre>
<h2 id="html-fonts">HTML Fonts</h2>
<p>The <code>font-family</code> property defines the font to be used for an HTML element</p>
<pre><code>Example:

&lt;h1 style="font-family:verdana;"&gt;This is a heading&lt;/h1&gt;  
&lt;p style="font-family:courier;"&gt;This is a paragraph.&lt;/p&gt;
</code></pre>
<h2 id="html-text-size">HTML Text Size</h2>
<p>The <code>font-size</code> property defines the text size for an HTML element:</p>
<pre><code>Example:

&lt;h1 style="font-size:300%;"&gt;This is a heading&lt;/h1&gt;  
&lt;p style="font-size:160%;"&gt;This is a paragraph.&lt;/p&gt;
</code></pre>
<h2 id="html-text-alignment">HTML Text Alignment</h2>
<p>The <code>text-align</code> property defines the horizontal text alignment for an HTML element:</p>
<pre><code>Example:

&lt;h1 style="text-align:center;"&gt;Centered Heading&lt;/h1&gt;  
&lt;p style="text-align:center;"&gt;Centered paragraph.&lt;/p&gt;
</code></pre>
<h1 id="html--text-formatting">HTML  Text Formatting</h1>
<h2 id="html-formatting-elements">HTML Formatting Elements</h2>
<p>In the previous chapter, you learned about the HTML  <strong>style attribute</strong>.</p>
<p>HTML also defines special  <strong>elements</strong>  for defining text with a special  <strong>meaning</strong>.</p>
<p>HTML uses elements like  <code>&lt;b&gt;</code>  and  <code>&lt;i&gt;</code>  for formatting output, like  <strong>bold</strong>  or  <em>italic</em>  text.</p>
<p>Formatting elements were designed to display special types of text:</p>
<ul>
<li><code>&lt;b&gt;</code>  - Bold text</li>
<li><code>&lt;strong&gt;</code>  - Important text</li>
<li><code>&lt;i&gt;</code>  - Italic text</li>
<li><code>&lt;em&gt;</code>  - Emphasized text</li>
<li><code>&lt;mark&gt;</code>  - Marked text</li>
<li><code>&lt;small&gt;</code>  - Small text</li>
<li><code>&lt;del&gt;</code>  - Deleted text</li>
<li><code>&lt;ins&gt;</code>  - Inserted text</li>
<li><code>&lt;sub&gt;</code>  - Subscript text</li>
<li><code>&lt;sup&gt;</code>  - Superscript text</li>
</ul>
<h2 id="html-b-and-strong-elements">HTML <code>&lt;b&gt;</code> and <code>&lt;strong&gt;</code> Elements</h2>
<p>The HTML <code>&lt;b&gt;</code> element defines <strong>bold</strong> text, without any extra importance.</p>

