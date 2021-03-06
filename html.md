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
<pre><code>example:
&lt;b&gt;This text is bold&lt;/b&gt;
&lt;strong&gt;This text is strong&lt;/strong&gt;
</code></pre>
<h2 id="html-i-and-em-elements">HTML <code>&lt;i&gt;</code> and <code>&lt;em&gt;</code> Elements</h2>
<p>The HTML <code>&lt;i&gt;</code> element defines <em>italic</em> text, without any extra importance.</p>
<p>The HTML <code>&lt;em&gt;</code> element defines <em>emphasized</em> text, with added semantic importanc</p>
<pre><code>&lt;i&gt;This text is italic&lt;/i&gt;
&lt;em&gt;This text is emphasized&lt;/em&gt;
</code></pre>
<h2 id="html-small-element">HTML <code>&lt;small&gt;</code> Element</h2>
<p>The HTML <code>&lt;small&gt;</code> element defines smaller text:</p>
<pre><code>Example:
&lt;h2&gt;HTML &lt;small&gt;Small&lt;/small&gt; Formatting&lt;/h2&gt;
</code></pre>
<h2 id="html-mark-element">HTML <code>&lt;mark&gt;</code> Element</h2>
<p>The HTML <code>&lt;mark&gt;</code> element defines marked<br>
or highlighted text:</p>
<pre><code>&lt;p&gt;My favorite color is &lt;del&gt;blue&lt;/del&gt; red.&lt;/p&gt;
</code></pre>
<h2 id="html-ins-element">HTML <code>&lt;ins&gt;</code> Element</h2>
<p>The HTML <code>&lt;ins&gt;</code> element defines inserted (underline added) text.</p>
<pre><code>Example:
&lt;p&gt;My favorite &lt;ins&gt;color&lt;/ins&gt; is red.&lt;/p&gt;
</code></pre>
<h2 id="html-sub-element">HTML <code>&lt;sub&gt;</code> Element</h2>
<p>The HTML <code>&lt;sub&gt;</code> element defines subscripted  (the text size  will be reduced and bottom of the ilne) text.</p>
<pre><code>&lt;p&gt;This is &lt;sub&gt;subscripted&lt;/sub&gt; text.&lt;/p&gt;
</code></pre>
<h2 id="html-sup-element">HTML <code>&lt;sup&gt;</code> Element</h2>
<p>The HTML <code>&lt;sup&gt;</code> element defines superscripted(the text size  will be reduced and top of the ilne) text.</p>
<pre><code>Example:
&lt;p&gt;This is &lt;sup&gt;superscripted&lt;/sup&gt; text.&lt;/p&gt;
</code></pre>
<h1 id="html--quotation">HTML  Quotation</h1>
<h2 id="html-q-for-short-quotations">HTML <code>&lt;q&gt;</code> for Short Quotations</h2>
<p>The HTML  <code>&lt;q&gt;</code>  element defines a short quotation.</p>
<p>Browsers usually insert quotation marks around the  <code>&lt;q&gt;</code>  element.</p>
<pre><code>Example:
&lt;p&gt;WWF's goal is to: &lt;q&gt;Build a future where people live in harmony with nature.&lt;/q&gt;&lt;/p&gt;
</code></pre>
<h2 id="html-blockquote-for-quotation">HTML <code>&lt;blockquote&gt;</code> for Quotation</h2>
<p>The HTML  <code>&lt;blockquote&gt;</code>  element defines a section that is quoted from another source.</p>
<p>Browsers usually indent  <code>&lt;blockquote&gt;</code>  elements.</p>
<pre><code>Example:
&lt;p&gt;Browsers usually indent blockquote elements.&lt;/p&gt;

&lt;blockquote cite="http://www.worldwildlife.org/who/index.html"&gt;
For 50 years, WWF has been protecting the future of nature.
The world's leading conservation organization,
WWF works in 100 countries and is supported by
1.2 million members in the United States and
close to 5 million globally.
&lt;/blockquote&gt;
</code></pre>
<h2 id="html-abbr-for-abbreviations">HTML <code>&lt;abbr&gt;</code> for Abbreviations</h2>
<p>The HTML <code>&lt;abbr&gt;</code> element defines an abbreviation or an acronym.</p>
<pre><code>Example:
&lt;p&gt;The &lt;abbr title="World Health Organization"&gt;WHO&lt;/abbr&gt; was founded in 1948.&lt;/p&gt;
</code></pre>
<h2 id="html-address-for-contact-information">HTML <code>&lt;address&gt;</code> for Contact Information</h2>
<p>The HTML <code>&lt;address&gt;</code> element defines contact information (author/owner) of a document or an article.</p>
<p>The <code>&lt;address&gt;</code> element is usually displayed in italic.</p>
<pre><code>example:

&lt;address&gt;  
Written by John Doe.&lt;br&gt;  
Visit us at:&lt;br&gt;  
Example.com&lt;br&gt;  
Box 564, Disneyland&lt;br&gt;  
USA  
&lt;/address&gt;
</code></pre>
<h2 id="html-cite-for-work-title">HTML <code>&lt;cite&gt;</code> for Work Title</h2>
<p>The HTML  <code>&lt;cite&gt;</code>  element defines the title of a work.</p>
<p>Browsers usually display  <code>&lt;cite&gt;</code>  elements in italic.</p>
<pre><code>example:
&lt;p&gt;&lt;cite&gt;The Scream&lt;/cite&gt; by Edvard Munch. Painted in 1893.&lt;/p&gt;
</code></pre>
<h2 id="html-bdo-for-bi-directional-override">HTML <code>&lt;bdo&gt;</code> for Bi-Directional Override</h2>
<p>The HTML  <code>&lt;bdo&gt;</code>  element defines bi-directional override.</p>
<p>The  <code>&lt;bdo&gt;</code>  element is used to override the current text direction:</p>
<pre><code>Example
&lt;bdo dir="rtl"&gt;This text will be written from right to left&lt;/bdo&gt;
</code></pre>
<h1 id="html--comments">HTML  Comments</h1>
<h2 id="html-comment-tags">HTML Comment Tags</h2>
<p>Comment tags are used to insert comments in the HTML source code.</p>
<pre><code>format:
&lt;!-- This is a comment --&gt;  
  
&lt;p&gt;This is a paragraph.&lt;/p&gt;  
  
&lt;!-- Remember to add more information here --&gt;
</code></pre>
<h1 id="html--colors">HTML  Colors</h1>
<h2 id="background-color">Background Color</h2>
<p>You can set the background color for HTML elements:</p>
<pre><code>Example:
&lt;h1 style="background-color:DodgerBlue;"&gt;Hello World&lt;/h1&gt;  
&lt;p style="background-color:Tomato;"&gt;Lorem ipsum...&lt;/p&gt;
</code></pre>
<h2 id="text-color">Text Color</h2>
<p>You can set the color of text:</p>
<pre><code>Example:
&lt;h1 style="color:Tomato;"&gt;Hello World&lt;/h1&gt;  
&lt;p style="color:DodgerBlue;"&gt;Lorem ipsum...&lt;/p&gt;  
&lt;p style="color:MediumSeaGreen;"&gt;Ut wisi enim...&lt;/p&gt;
</code></pre>
<h2 id="border-color">Border Color</h2>
<p>You can set the color of borders:</p>
<pre><code>example:
&lt;h1 style="border:2px solid Tomato;"&gt;Hello World&lt;/h1&gt;  
&lt;h1 style="border:2px solid DodgerBlue;"&gt;Hello World&lt;/h1&gt;  
&lt;h1 style="border:2px solid Violet;"&gt;Hello World&lt;/h1&gt;
</code></pre>
<h2 id="color-values">Color Values</h2>
<p>In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values:</p>
<pre><code>Example:
&lt;h1 style="background-color:rgb(255, 99, 71);"&gt;...&lt;/h1&gt;  
&lt;h1 style="background-color:#ff6347;"&gt;...&lt;/h1&gt;  
&lt;h1 style="background-color:hsl(9, 100%, 64%);"&gt;...&lt;/h1&gt;    
&lt;h1 style="background-color:rgba(255, 99, 71, 0.5);"&gt;...&lt;/h1&gt;  
&lt;h1 style="background-color:hsla(9, 100%, 64%, 0.5);"&gt;...&lt;/h1&gt;
</code></pre>
<h2 id="rgb-value">RGB Value</h2>
<p>In HTML, a color can be specified as an RGB value, using this formula:</p>
<p>rgb(<em>red,</em>  <em>green</em>,  <em>blue</em>)</p>
<pre><code>Example:
&lt;h1 style="background-color:rgb(255, 0, 0);"&gt;rgb(255, 0, 0)&lt;/h1&gt;
&lt;h1 style="background-color:rgb(0, 0, 255);"&gt;rgb(0, 0, 255)&lt;/h1&gt;
&lt;h1 style="background-color:rgb(60, 179, 113);"&gt;rgb(60, 179, 113)&lt;/h1&gt;
&lt;h1 style="background-color:rgb(238, 130, 238);"&gt;rgb(238, 130, 238)&lt;/h1&gt;
&lt;h1 style="background-color:rgb(255, 165, 0);"&gt;rgb(255, 165, 0)&lt;/h1&gt;
&lt;h1 style="background-color:rgb(106, 90, 205);"&gt;rgb(106, 90, 205)&lt;/h1&gt;
</code></pre>
<h2 id="hex-value">HEX Value</h2>
<p>In HTML, a color can be specified using a hexadecimal value in the form:</p>
<p>#<em>rrggbb</em></p>
<pre><code>Example:
&lt;h1 style="background-color:#ff0000;"&gt;#ff0000&lt;/h1&gt;
&lt;h1 style="background-color:#0000ff;"&gt;#0000ff&lt;/h1&gt;
&lt;h1 style="background-color:#3cb371;"&gt;#3cb371&lt;/h1&gt;
&lt;h1 style="background-color:#ee82ee;"&gt;#ee82ee&lt;/h1&gt;
&lt;h1 style="background-color:#ffa500;"&gt;#ffa500&lt;/h1&gt;
&lt;h1 style="background-color:#6a5acd;"&gt;#6a5acd&lt;/h1&gt;
</code></pre>
<h2 id="hsl-value">HSL Value</h2>
<p>In HTML, a color can be specified using hue, saturation, and lightness (HSL) in the form:</p>
<p>hsl(<em>hue</em>,  <em>saturation</em>,  <em>lightness</em>)</p>
<pre><code>Example:
&lt;h1 style="background-color:hsl(0, 100%, 50%);"&gt;hsl(0, 100%, 50%)&lt;/h1&gt;
&lt;h1 style="background-color:hsl(240, 100%, 50%);"&gt;hsl(240, 100%, 50%)&lt;/h1&gt;
&lt;h1 style="background-color:hsl(147, 50%, 47%);"&gt;hsl(147, 50%, 47%)&lt;/h1&gt;
&lt;h1 style="background-color:hsl(300, 76%, 72%);"&gt;hsl(300, 76%, 72%)&lt;/h1&gt;
&lt;h1 style="background-color:hsl(39, 100%, 50%);"&gt;hsl(39, 100%, 50%)&lt;/h1&gt;
&lt;h1 style="background-color:hsl(248, 53%, 58%);"&gt;hsl(248, 53%, 58%)&lt;/h1&gt;
</code></pre>
<h2 id="rgba-value">RGBA Value</h2>
<p>RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.</p>
<p>An RGBA color value is specified with:</p>
<p>rgba(<em>red,</em>  <em>green</em>,  <em>blue, alpha</em>)</p>
<pre><code>Example:
&lt;h1 style="background-color:rgba(255, 99, 71, 0);"&gt;rgba(255, 99, 71, 0)&lt;/h1&gt;
&lt;h1 style="background-color:rgba(255, 99, 71, 0.2);"&gt;rgba(255, 99, 71, 0.2)&lt;/h1&gt;
&lt;h1 style="background-color:rgba(255, 99, 71, 0.4);"&gt;rgba(255, 99, 71, 0.4)&lt;/h1&gt;
&lt;h1 style="background-color:rgba(255, 99, 71, 0.6);"&gt;rgba(255, 99, 71, 0.6)&lt;/h1&gt;
&lt;h1 style="background-color:rgba(255, 99, 71, 0.8);"&gt;rgba(255, 99, 71, 0.8)&lt;/h1&gt;
&lt;h1 style="background-color:rgba(255, 99, 71, 1);"&gt;rgba(255, 99, 71, 1)&lt;/h1&gt;
</code></pre>
<h2 id="hsla-value">HSLA Value</h2>
<p>HSLA color values are an extension of HSL color values with an alpha channel - which specifies the opacity for a color.</p>
<p>An HSLA color value is specified with:</p>
<p>hsla(<em>hue,</em>  <em>saturation</em>,  <em>lightness, alpha</em>)</p>
<pre><code>Example:
'&lt;h1 style="background-color:hsla(9, 100%, 64%, 0);"&gt;hsla(9, 100%, 64%, 0)&lt;/h1&gt;
&lt;h1 style="background-color:hsla(9, 100%, 64%, 0.2);"&gt;hsla(9, 100%, 64%, 0.2)&lt;/h1&gt;
&lt;h1 style="background-color:hsla(9, 100%, 64%, 0.4);"&gt;hsla(9, 100%, 64%, 0.4)&lt;/h1&gt;
&lt;h1 style="background-color:hsla(9, 100%, 64%, 0.6);"&gt;hsla(9, 100%, 64%, 0.6)&lt;/h1&gt;
&lt;h1 style="background-color:hsla(9, 100%, 64%, 0.8);"&gt;hsla(9, 100%, 64%, 0.8)&lt;/h1&gt;
&lt;h1 style="background-color:hsla(9, 100%, 64%, 1);"&gt;hsla(9, 100%, 64%, 1)&lt;/h1&gt;
</code></pre>
<h1 id="html--styles---css">HTML  Styles - CSS</h1>
<h2 id="styling-html-with-css">Styling HTML with CSS</h2>
<p><strong>CSS</strong>  stands for  <strong>C</strong>ascading  <strong>S</strong>tyle  <strong>S</strong>heets.</p>
<p>CSS describes  <strong>how HTML elements are to be displayed on screen, paper, or in other media</strong>.</p>
<p>CSS  <strong>saves a lot of work</strong>. It can control the layout of multiple web pages all at once.</p>
<p>CSS can be added to HTML elements in 3 ways:</p>
<ul>
<li><strong>Inline</strong>  - by using the style attribute in HTML elements</li>
<li><strong>Internal</strong>  - by using a  <code>&lt;style&gt;</code>  element in the  <code>&lt;head&gt;</code>  section</li>
<li><strong>External</strong>  - by using an external CSS file</li>
</ul>
<h2 id="inline-css">Inline CSS</h2>
<p>An inline CSS is used to apply a unique style to a single HTML element.</p>
<p>An inline CSS uses the style attribute of an HTML element.</p>
<pre><code>Example:
&lt;h1 style="color:blue;"&gt;This is a Blue Heading&lt;/h1&gt;
</code></pre>
<h2 id="internal-css">Internal CSS</h2>
<p>An internal CSS is used to define a style for a single HTML page.</p>
<p>An internal CSS is defined in the  <code>&lt;head&gt;</code>  section of an HTML page, within a  <code>&lt;style&gt;</code>  element:</p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html&gt;  
&lt;head&gt;  
&lt;style&gt;  
body  {background-color:  powderblue;}  
h1 {color:  blue;}  
p {color:  red;}  
&lt;/style&gt;  
&lt;/head&gt;  
&lt;body&gt;  
  
&lt;h1&gt;This is a heading&lt;/h1&gt;  
&lt;p&gt;This is a paragraph.&lt;/p&gt;  
  
&lt;/body&gt;  
&lt;/html&gt;
</code></pre>
<h2 id="external-css">External CSS</h2>
<p>An external style sheet is used to define the style for many HTML pages.</p>
<p><strong>With an external style sheet, you can change the look of an entire web site, by changing one file!</strong></p>
<p>To use an external style sheet, add a link to it in the  <code>&lt;head&gt;</code>  section of the HTML page:</p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html&gt;  
&lt;head&gt;  
&lt;link rel="stylesheet"  href="styles.css"&gt;  
&lt;/head&gt;  
&lt;body&gt;  
  
&lt;h1&gt;This is a heading&lt;/h1&gt;  
&lt;p&gt;This is a paragraph.&lt;/p&gt;  
  
&lt;/body&gt;  
&lt;/html&gt;
</code></pre>
<p>Here is how the “styles.css” looks:</p>
<pre><code>body {  
background-color:  powderblue;  
}  
h1 {  
color:  blue;  
}  
p {  
color:  red;  
}
</code></pre>
<h2 id="css-fonts">CSS Fonts</h2>
<p>The CSS  <code>color</code>  property defines the text color to be used.</p>
<p>The CSS  <code>font-family</code>  property defines the font to be used.</p>
<p>The CSS  <code>font-size</code> property defines the text size to be us</p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html&gt;  
&lt;head&gt;  
&lt;style&gt;  
h1  {  
color:  blue;  
font-family:  verdana;  
font-size:  300%;  
}  
p {  
color:  red;  
font-family:  courier;  
font-size:  160%;  
}  
&lt;/style&gt;  
&lt;/head&gt;  
&lt;body&gt;  
  
&lt;h1&gt;This is a heading&lt;/h1&gt;  
&lt;p&gt;This is a paragraph.&lt;/p&gt;  
  
&lt;/body&gt;  
&lt;/html&gt;
</code></pre>
<h2 id="css-border">CSS Border</h2>
<p>The CSS  <code>border</code>  property defines a border around an HTML element:</p>
<pre><code>p {  
border:  1px solid powderblue;  
}
</code></pre>
<h2 id="css-padding">CSS Padding</h2>
<p>The CSS  <code>padding</code>  property defines a padding (space) between the text and the border:</p>
<pre><code>p {  
border:  1px solid powderblue;  
padding:  30px;  
}
</code></pre>
<h2 id="css-margin">CSS Margin</h2>
<p>The CSS  <code>margin</code>  property defines a margin (space) outside the border:</p>
<pre><code>p {  
border:  1px solid powderblue;  
margin:  50px;  
}
</code></pre>
<h2 id="the-id-attribute">The id Attribute</h2>
<p>To define a specific style for one special element, add an  <code>id</code>  attribute to the element:</p>
<pre><code>&lt;p id="p01"&gt;I am different&lt;/p&gt;
</code></pre>
<p>then define a style for the element with the specific id:</p>
<pre><code>#p01  {  
color:  blue;  
}
</code></pre>
<h2 id="the-class-attribute">The class Attribute</h2>
<p>To define a style for special types of elements, add a  <code>class</code>  attribute to the element:</p>
<pre><code>&lt;p class="error"&gt;I am different&lt;/p&gt;
</code></pre>
<p>then define a style for the elements with the specific class:</p>
<pre><code>p.error {  
color:  red;  
}
</code></pre>
<h2 id="external-references">External References</h2>
<p>External style sheets can be referenced with a full URL or with a path relative to the current web page.</p>
<pre><code>&lt;link rel="stylesheet"  href="/html/styles.css"&gt;
</code></pre>
<h1 id="html--links">HTML  Links</h1>
<h2 id="html-links---hyperlinks">HTML Links - Hyperlinks</h2>
<p>HTML links are hyperlinks.</p>
<p>You can click on a link and jump to another document</p>
<h2 id="html-links---syntax">HTML Links - Syntax</h2>
<p>In HTML, links are defined with the  <code>&lt;a&gt;</code>  tag:</p>
<pre><code>&lt;a href="_url_"&gt;_link text_&lt;/a&gt;
</code></pre>
<p>example:</p>
<pre><code>&lt;a href="https://www.w3schools.com/html/"&gt;Visit our HTML tutorial&lt;/a&gt;
</code></pre>
<h2 id="local-links">Local Links</h2>
<p>The example above used an absolute URL (a full web address).</p>
<p>A local link (link to the same web site) is specified with a relative URL (without <a href="https://www">https://www</a>…).</p>
<pre><code>&lt;a href="html_images.asp"&gt;HTML Images&lt;/a&gt;
</code></pre>
<h2 id="html-link-colors">HTML Link Colors</h2>
<p>By default, a link will appear like this (in all browsers):</p>
<ul>
<li>An unvisited link is underlined and blue</li>
<li>A visited link is underlined and purple</li>
<li>An active link is underlined and red</li>
</ul>
<p>You can change the default colors, by using CSS:</p>
<pre><code>    &lt;style&gt;  
    a:link {  
    color:  green;  
    background-color:  transparent;  
       text-decoration:  none;  
     }  

     a:visited {  
    color:  pink;  
    background-color:  transparent;  
    text-decoration:  none;  
    }  

    a:hover {  
    color:  red;  
    background-color:  transparent;  
    text-decoration:  underline;  
    }  

     a:active {  
     color:  yellow;  
     background-color:  transparent;  
     text-decoration:  underline;  
    }  
    &lt;/style&gt;
</code></pre>
<h2 id="html-links---the-target-attribute">HTML Links - The target Attribute</h2>
<p>The  <code>target</code>  attribute specifies where to open the linked document.</p>
<p>The target attribute can have one of the following values:</p>
<ul>
<li>
<p>_blank - Opens the linked document in a new window or tab</p>
</li>
<li>
<p>_self - Opens the linked document in the same window/tab as it was clicked (this is default)</p>
</li>
<li>
<p>_parent - Opens the linked document in the parent frame</p>
</li>
<li>
<p>_top - Opens the linked document in the full body of the window</p>
</li>
<li>
<p><em>framename</em>  - Opens the linked document in a named frame</p>
<pre><code>&lt;a href="https://www.w3schools.com/"  target="_blank"&gt;Visit W3Schools!&lt;/a&gt;
</code></pre>
</li>
</ul>
<h2 id="html-links---image-as-link">HTML Links - Image as Link</h2>
<p>It is common to use images as links:</p>
<pre><code>&lt;a href="default.asp"&gt;  
&lt;img src="smiley.gif"  alt="HTML tutorial"  style="width:42px;height:42px;border:0;"&gt;  
&lt;/a&gt;
</code></pre>
<h2 id="link-titles">Link Titles</h2>
<p>The  <code>title</code>  attribute specifies extra information about an element. The information is most often shown as a tooltip text when the mouse moves over the element.</p>
<pre><code>&lt;a href="https://www.w3schools.com/html/"  title="Go to W3Schools HTML section"&gt;Visit our HTML Tutorial&lt;/a&gt;
</code></pre>
<h2 id="html-links---create-a-bookmark">HTML Links - Create a Bookmark</h2>
<p>HTML bookmarks are used to allow readers to jump to specific parts of a Web page.</p>
<p>Bookmarks can be useful if your webpage is very long.</p>
<p>To make a bookmark, you must first create the bookmark, and then add a link to it.</p>
<p>When the link is clicked, the page will scroll to the location with the bookmark.</p>
<p>First, create a bookmark with the  <code>id</code>  attribute:</p>
<pre><code>&lt;h2 id="C4"&gt;Chapter 4&lt;/h2&gt;
</code></pre>
<p>Then, add a link to the bookmark (“Jump to Chapter 4”), from within the same page:</p>
<pre><code>&lt;a href="#C4"&gt;Jump to Chapter 4&lt;/a&gt;
</code></pre>
<p>Or, add a link to the bookmark (“Jump to Chapter 4”), from another page:</p>
<pre><code>&lt;a href="html_demo.html#C4"&gt;Jump to Chapter 4&lt;/a&gt;
</code></pre>
<h1 id="html--images">HTML  Images</h1>
<h2 id="html-images-syntax">HTML Images Syntax</h2>
<p>In HTML, images are defined with the  <code>&lt;img&gt;</code>  tag.</p>
<p>The  <code>&lt;img&gt;</code>  tag is empty, it contains attributes only, and does not have a closing tag.</p>
<p>The  <code>src</code>  attribute specifies the URL (web address) of the image:</p>
<pre><code>&lt;img src="_url_"&gt;
</code></pre>
<h2 id="the-alt-attribute-1">The alt Attribute</h2>
<p>The  <code>alt</code>  attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader).</p>
<pre><code>&lt;img src="img_chania.jpg"  alt="Flowers in Chania"&gt;
</code></pre>
<h2 id="image-size---width-and-height">Image Size - Width and Height</h2>
<p>You can use the  <code>style</code>  attribute to specify the width and height of an image.</p>
<pre><code>&lt;img src="img_girl.jpg"  alt="Girl in a jacket"  style="width:500px;height:600px;"&gt;
</code></pre>
<h2 id="width-and-height-or-style">Width and Height, or Style?</h2>
<p>The  <code>width</code>,  <code>height</code>, and  <code>style</code>  attributes are valid in HTM</p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html&gt;  
&lt;head&gt;  
&lt;style&gt;  
img  {  
width:  100%;  
}  
&lt;/style&gt;  
&lt;/head&gt;  
&lt;body&gt;  
  
&lt;img src="html5.gif"  alt="HTML5 Icon"  width="128"  height="128"&gt;  
&lt;img src="html5.gif"  alt="HTML5 Icon"  style="width:128px;height:128px;"&gt;  
  
&lt;/body&gt;  
&lt;/html&gt;
</code></pre>
<h2 id="images-in-another-folder">Images in Another Folder</h2>
<p>If not specified, the browser expects to find the image in the same folder as the web page.</p>
<p>However, it is common to store images in a sub-folder. You must then include the folder name in the  <code>src</code>  attribute:</p>
<pre><code>&lt;img src="/images/html5.gif"  alt="HTML5 Icon"  style="width:128px;height:128px;"&gt;
</code></pre>
<h2 id="images-on-another-server">Images on Another Server</h2>
<p>Some web sites store their images on image servers.</p>
<p>Actually, you can access images from any web address in the world:</p>
<pre><code>&lt;img src="https://www.w3schools.com/images/w3schools_green.jpg"  alt="W3Schools.com"&gt;
</code></pre>
<h2 id="animated-images">Animated Images</h2>
<p>HTML allows animated GIFs:</p>
<pre><code>&lt;img src="programming.gif"  alt="Computer Man"  style="width:48px;height:48px;"&gt;
</code></pre>
<h2 id="image-as-a-link">Image as a Link</h2>
<p>To use an image as a link, put the  <code>&lt;img&gt;</code>  tag inside the  <code>&lt;a&gt;</code>  tag:</p>
<pre><code>&lt;a href="default.asp"&gt;  
&lt;img src="smiley.gif"  alt="HTML tutorial"  style="width:42px;height:42px;border:0;"&gt;  
&lt;/a&gt;
</code></pre>
<h2 id="image-floating">Image Floating</h2>
<p>Use the CSS  <code>float</code>  property to let the image float to the right or to the left of a text:</p>
<pre><code>&lt;p&gt;&lt;img src="smiley.gif"  alt="Smiley face"  style="float:right;width:42px;height:42px;"&gt;  
The image will float to the right of the text.&lt;/p&gt;  
  
&lt;p&gt;&lt;img src="smiley.gif"  alt="Smiley face"  style="float:left;width:42px;height:42px;"&gt;  
The image will float to the left of the text.&lt;/p&gt;
</code></pre>
<h2 id="image-maps">Image Maps</h2>
<p>The  <code>&lt;map&gt;</code>  tag defines an image-map. An image-map is an image with clickable areas.</p>
<p>In the image below, click on the computer, the phone, or the cup of coffee:</p>
<pre><code>&lt;img src="workplace.jpg"  alt="Workplace"  usemap="#workmap"&gt;  
  
&lt;map name="workmap"&gt;  
&lt;area shape="rect"  coords="34,44,270,350"  alt="Computer"  href="computer.htm"&gt;  
&lt;area shape="rect"  coords="290,172,333,250"  alt="Phone"  href="phone.htm"&gt;  
&lt;area shape="circle"  coords="337,300,44"  alt="Coffee"  href="coffee.htm"&gt;  
&lt;/map&gt;
</code></pre>
<p>The  <code>name</code>  attribute of the  <code>&lt;map&gt;</code>  tag is associated with the  <code>&lt;img&gt;</code>'s usemap attribute and creates a relationship between the image and the map.</p>
<p>The  <code>&lt;map&gt;</code>  element contains a number of  <code>&lt;area&gt;</code>  tags, that define the clickable areas in the image-map.</p>
<h2 id="background-image">Background Image</h2>
<p>To add a background image on an HTML element, use the CSS property <code>background-image</code>:</p>
<pre><code>&lt;body style="background-image:url('clouds.jpg')"&gt;  
  
&lt;h2&gt;Background Image&lt;/h2&gt;  
  
&lt;/body&gt;
</code></pre>
<p>another one example:</p>
<pre><code>&lt;body&gt; 
&lt;p style="background-image:url('clouds.jpg')"&gt;  
...  
&lt;/p&gt;  
  
&lt;/body&gt;
</code></pre>
<h2 id="the-picture-element">The <code>&lt;picture&gt;</code> Element</h2>
<p>HTML5 introduced the  <code>&lt;picture&gt;</code>  element to add more flexibility when specifying image resources.</p>
<p>The  <code>&lt;picture&gt;</code>  element contains a number of  elements, each referring to different image sources. This way the browser can choose the image that best fits the current view and/or device.</p>
<p>Each  <code>&lt;source&gt;</code>  element have attributes describing when their image is the most suitable.</p>
<p>The browser will use the first  <code>&lt;source&gt;</code>  element with matching attribute values, and ignore any following  <code>&lt;source&gt;</code>elements.</p>
<pre><code>&lt;picture&gt;  
&lt;source media="(min-width: 650px)"  srcset="img_pink_flowers.jpg"&gt;  
&lt;source media="(min-width: 465px)"  srcset="img_white_flower.jpg"&gt;  
&lt;img src="img_orange_flowers.jpg"  alt="Flowers"  style="width:auto;"&gt;  
&lt;/picture&gt;
</code></pre>
<h1 id="html--tables">HTML  Tables</h1>
<h2 id="defining-an-html-table">Defining an HTML Table</h2>
<p>An HTML table is defined with the  <code>&lt;table&gt;</code>  tag.</p>
<p>Each table row is defined with the  <code>&lt;tr&gt;</code>  tag. A table header is defined with the  <code>&lt;th&gt;</code>  tag. By default, table headings are bold and centered. A table data/cell is defined with the  <code>&lt;td&gt;</code>  tag.</p>
<pre><code>Example:

&lt;table style="width:100%"&gt;  
&lt;tr&gt;  
&lt;th&gt;Firstname&lt;/th&gt;  
&lt;th&gt;Lastname&lt;/th&gt;  
&lt;th&gt;Age&lt;/th&gt;  
&lt;/tr&gt;  
&lt;tr&gt;  
&lt;td&gt;Jill&lt;/td&gt;  
&lt;td&gt;Smith&lt;/td&gt;  
&lt;td&gt;50&lt;/td&gt;  
&lt;/tr&gt;  
&lt;tr&gt;  
&lt;td&gt;Eve&lt;/td&gt;  
&lt;td&gt;Jackson&lt;/td&gt;  
&lt;td&gt;94&lt;/td&gt;  
&lt;/tr&gt;  
&lt;/table&gt;
</code></pre>
<h2 id="html-table---adding-a-border">HTML Table - Adding a Border</h2>
<p>If you do not specify a border for the table, it will be displayed without borders.</p>
<p>A border is set using the CSS  <code>border</code>  property:</p>
<pre><code>Example:
table, th, td {  
border:  1px solid black;  
}
</code></pre>
<h2 id="html-table---collapsed-borders">HTML Table - Collapsed Borders</h2>
<p>If you want the borders to collapse into one border, add the CSS  <code>border-collapse</code>  property:</p>
<pre><code>Example:
table, th, td {
    border: 1px solid black;
    border-collapse: collapse;
}
</code></pre>
<h2 id="html-table---adding-cell-padding">HTML Table - Adding Cell Padding</h2>
<p>Cell padding specifies the space between the cell content and its borders.</p>
<p>If you do not specify a padding, the table cells will be displayed without padding.</p>
<p>To set the padding, use the CSS  <code>padding</code>  property:</p>
<pre><code>Example:
th, td {  
padding:  15px;  
}
</code></pre>
<h2 id="html-table---left-align-headings">HTML Table - Left-align Headings</h2>
<p>By default, table headings are bold and centered.</p>
<p>To left-align the table headings, use the CSS  <code>text-align</code>  property:</p>
<pre><code>th {  
text-align:  left;  
}
</code></pre>
<h2 id="html-table---adding-border-spacing">HTML Table - Adding Border Spacing</h2>
<p>Border spacing specifies the space between the cells.</p>
<p>To set the border spacing for a table, use the CSS  <code>border-spacing</code>  property:</p>
<pre><code>table {  
border-spacing:  5px;  
}
</code></pre>
<h2 id="html-table---cells-that-span-many-columns">HTML Table - Cells that Span Many Columns</h2>
<p>To make a cell span more than one column, use the  <code>colspan</code>  attribute:</p>
<pre><code>&lt;table style="width:100%"&gt;  
&lt;tr&gt;  
&lt;th&gt;Name&lt;/th&gt;  
&lt;th colspan="2"&gt;Telephone&lt;/th&gt;  
&lt;/tr&gt;  
&lt;tr&gt;  
&lt;td&gt;Bill Gates&lt;/td&gt;  
&lt;td&gt;55577854&lt;/td&gt;  
&lt;td&gt;55577855&lt;/td&gt;  
&lt;/tr&gt;  
&lt;/table&gt;
</code></pre>
<h2 id="html-table---cells-that-span-many-rows">HTML Table - Cells that Span Many Rows</h2>
<p>To make a cell span more than one row, use the  <code>rowspan</code>  attribute:</p>
<pre><code>&lt;table style="width:100%"&gt;  
&lt;tr&gt;  
&lt;th&gt;Name:&lt;/th&gt;  
&lt;td&gt;Bill Gates&lt;/td&gt;  
&lt;/tr&gt;  
&lt;tr&gt;  
&lt;th rowspan="2"&gt;Telephone:&lt;/th&gt;  
&lt;td&gt;55577854&lt;/td&gt;  
&lt;/tr&gt;  
&lt;tr&gt;  
&lt;td&gt;55577855&lt;/td&gt;  
&lt;/tr&gt;  
&lt;/table&gt;
</code></pre>
<h2 id="html-table---adding-a-caption">HTML Table - Adding a Caption</h2>
<p>To add a caption to a table, use the  <code>&lt;caption&gt;</code>  tag:</p>
<pre><code>&lt;table style="width:100%"&gt;  
&lt;caption&gt;Monthly savings&lt;/caption&gt;  
&lt;tr&gt;  
&lt;th&gt;Month&lt;/th&gt;  
&lt;th&gt;Savings&lt;/th&gt;  
&lt;/tr&gt;  
&lt;tr&gt;  
&lt;td&gt;January&lt;/td&gt;  
&lt;td&gt;$100&lt;/td&gt;  
&lt;/tr&gt;  
&lt;tr&gt;  
&lt;td&gt;February&lt;/td&gt;  
&lt;td&gt;$50&lt;/td&gt;  
&lt;/tr&gt;  
&lt;/table&gt;
</code></pre>
<h2 id="a-special-style-for-one-table">A Special Style for One Table</h2>
<p>To define a special style for a special table, add an  <code>id</code>  attribute to the table:</p>
<pre><code>&lt;table id="t01"&gt;  
&lt;tr&gt;  
&lt;th&gt;Firstname&lt;/th&gt;  
&lt;th&gt;Lastname&lt;/th&gt;  
&lt;th&gt;Age&lt;/th&gt;  
&lt;/tr&gt;  
&lt;tr&gt;  
&lt;td&gt;Eve&lt;/td&gt;  
&lt;td&gt;Jackson&lt;/td&gt;  
&lt;td&gt;94&lt;/td&gt;  
&lt;/tr&gt;  
&lt;/table&gt;
</code></pre>
<p>Now you can define a special style for this table:</p>
<pre><code>table#t01  {  
width:  100%;  
background-color:  #f1f1c1;  
}
</code></pre>
<p>add more styles:</p>
<pre><code>table#t01 tr:nth-child(even) {  
background-color:  #eee;  
}  
table#t01 tr:nth-child(odd) {  
background-color:  #fff;  
}  
table#t01 th {  
color:  white;  
background-color:  black;  
}
</code></pre>
<h1 id="html--lists">HTML  Lists</h1>
<h2 id="unordered-html-list">Unordered HTML List</h2>
<p>An unordered list starts with the  <code>&lt;ul&gt;</code>  tag. Each list item starts with the  <code>&lt;li&gt;</code>  tag.</p>
<p>The list items will be marked with bullets (small black circles) by default:</p>
<pre><code>&lt;ul&gt;  
&lt;li&gt;Coffee&lt;/li&gt;  
&lt;li&gt;Tea&lt;/li&gt;  
&lt;li&gt;Milk&lt;/li&gt;  
&lt;/ul&gt;
</code></pre>
<h3 id="unordered-html-list---choose-list-item-marker">Unordered HTML List - Choose List Item Marker</h3>
<p>The CSS  <code>list-style-type</code>  property is used to define the style of the list item marker:</p>
<ul>
<li>
<p>disc</p>
</li>
<li>
<p>square</p>
</li>
<li>
<p>circle</p>
</li>
<li>
<p>none</p>
<pre><code>&lt;ul style="list-style-type:disc"&gt;  
&lt;li&gt;Coffee&lt;/li&gt;  
&lt;li&gt;Milk&lt;/li&gt;  
&lt;/ul&gt;
</code></pre>
</li>
</ul>
<h3 id="ordered-html-list">Ordered HTML List</h3>
<p>An ordered list starts with the  <code>&lt;ol&gt;</code>  tag. Each list item starts with the  <code>&lt;li&gt;</code>  tag.</p>
<p>The list items will be marked with numbers by default:</p>
<pre><code>&lt;ol&gt;  
&lt;li&gt;Coffee&lt;/li&gt;  
&lt;li&gt;Tea&lt;/li&gt;  
&lt;li&gt;Milk&lt;/li&gt;  
&lt;/ol&gt;
</code></pre>
<h2 id="ordered-html-list---the-type-attribute">Ordered HTML List - The Type Attribute</h2>
<p>The  <code>type</code>  attribute of the  <code>&lt;ol&gt;</code>  tag, defines the type of the list item marker:</p>
<ol>
<li>
<p>type=“1”</p>
</li>
<li>
<p>type=“A”</p>
</li>
<li>
<p>type=“a”</p>
</li>
<li>
<p>type=“I”</p>
</li>
<li>
<p>type=“i”</p>
<pre><code>&lt;ol type="1"&gt;  
&lt;li&gt;Coffee&lt;/li&gt;  
&lt;li&gt;Tea&lt;/li&gt;  
&lt;li&gt;Milk&lt;/li&gt;  
&lt;/ol&gt;
</code></pre>
</li>
</ol>
<h2 id="html-description-lists">HTML Description Lists</h2>
<p>HTML also supports description lists.</p>
<p>A description list is a list of terms, with a description of each term.</p>
<p>The  <code>&lt;dl&gt;</code>  tag defines the description list, the  <code>&lt;dt&gt;</code>  tag defines the term (name), and the  <code>&lt;dd&gt;</code>  tag describes each term:</p>
<pre><code>&lt;dl&gt;  
&lt;dt&gt;Coffee&lt;/dt&gt;  
&lt;dd&gt;- black hot drink&lt;/dd&gt;  
&lt;dt&gt;Milk&lt;/dt&gt;  
&lt;dd&gt;- white cold drink&lt;/dd&gt;  
&lt;/dl&gt;
</code></pre>
<h2 id="nested-html-lists">Nested HTML Lists</h2>
<p>List can be nested (lists inside lists):</p>
<pre><code>&lt;ul&gt;  
&lt;li&gt;Coffee&lt;/li&gt;  
&lt;li&gt;Tea  
&lt;ul&gt;  
&lt;li&gt;Black tea&lt;/li&gt;  
&lt;li&gt;Green tea&lt;/li&gt;  
&lt;/ul&gt;  
&lt;/li&gt;  
&lt;li&gt;Milk&lt;/li&gt;  
&lt;/ul&gt;
</code></pre>
<h2 id="control-list-counting">Control List Counting</h2>
<p>By default, an ordered list will start counting from 1. If you want to start counting from a specified number, you can use the  <code>start</code>  attribute:</p>
<pre><code>&lt;ol start="50"&gt;  
&lt;li&gt;Coffee&lt;/li&gt;  
&lt;li&gt;Tea&lt;/li&gt;  
&lt;li&gt;Milk&lt;/li&gt;  
&lt;/ol&gt;
</code></pre>
<h2 id="horizontal-list-with-css">Horizontal List with CSS</h2>
<p>HTML lists can be styled in many different ways with CSS.</p>
<p>One popular way is to style a list horizontally, to create a navigation menu:</p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html&gt;  
&lt;head&gt;  
&lt;style&gt;  
ul  {  
list-style-type:  none;  
margin:  0;  
padding:  0;  
overflow:  hidden;  
background-color:  #333333;  
}  
  
li  {  
float:  left;  
}  
  
li a  {  
display:  block;  
color:  white;  
text-align:  center;  
padding:  16px;  
text-decoration:  none;  
}  
  
li a:hover  {  
background-color:  #111111;  
}  
&lt;/style&gt;  
&lt;/head&gt;  
&lt;body&gt;  
  
&lt;ul&gt;  
&lt;li&gt;&lt;a href="#home"&gt;Home&lt;/a&gt;&lt;/li&gt;  
&lt;li&gt;&lt;a href="#news"&gt;News&lt;/a&gt;&lt;/li&gt;  
&lt;li&gt;&lt;a href="#contact"&gt;Contact&lt;/a&gt;&lt;/li&gt;  
&lt;li&gt;&lt;a href="#about"&gt;About&lt;/a&gt;&lt;/li&gt;  
&lt;/ul&gt;  
  
&lt;/body&gt;  
&lt;/html&gt;
</code></pre>
<h1 id="html--block-and-inline-elements">HTML  Block and Inline Elements</h1>
<h2 id="block-level-elements">Block-level Elements</h2>
<p>A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).</p>
<p>The <code>&lt;div&gt;</code> element is a block-level element.</p>
<pre><code>&lt;div&gt;Hello&lt;/div&gt;  
&lt;div&gt;World&lt;/div&gt;
</code></pre>
<p>Block level elements in HTML:</p>
<pre><code>[&lt;address&gt;][&lt;article&gt;][&lt;aside&gt;][&lt;blockquote&gt;][&lt;canvas&gt;][&lt;dd&gt;][&lt;div&gt;]
[&lt;dl&gt;][&lt;dt&gt;][&lt;fieldset&gt;][&lt;figcaption&gt;][&lt;figure&gt;][&lt;footer&gt;][&lt;form&gt;][&lt;h1&gt;-&lt;h6&gt;][&lt;header&gt;]
[&lt;hr&gt;][&lt;li&gt;][&lt;main&gt;]
[&lt;nav&gt;][&lt;noscript&gt;]
[&lt;ol&gt;][&lt;output&gt;]
[&lt;p&gt;][&lt;pre&gt;]
[&lt;section&gt;][&lt;table&gt;]
[&lt;tfoot&gt;][&lt;ul&gt;][&lt;video&gt;]
</code></pre>
<h2 id="inline-elements">Inline Elements</h2>
<p>An inline element does not start on a new line and only takes up as much width as necessary.</p>
<p>This is  an inline <code>&lt;span&gt;</code> element inside  a paragraph.</p>
<pre><code>&lt;span&gt;Hello&lt;/span&gt;  
&lt;span&gt;World&lt;/span&gt;
</code></pre>
<p>Inline elements in HTML:</p>
<pre><code>[&lt;a&gt;]
[&lt;abbr&gt;]
[&lt;acronym&gt;]
[&lt;b&gt;]
[&lt;bdo&gt;]
[&lt;big&gt;]
[&lt;br&gt;]
[&lt;button&gt;]
[&lt;cite&gt;]
[&lt;code&gt;]
[&lt;dfn&gt;]
[&lt;em&gt;
[&lt;i&gt;]
[&lt;img&gt;]
[&lt;input&gt;]
[&lt;kbd&gt;]
[&lt;label&gt;]
[&lt;map&gt;]
[&lt;object&gt;]
[&lt;q&gt;]
[&lt;samp&gt;]
[&lt;script&gt;]
[&lt;select&gt;]
[&lt;small&gt;]
[&lt;span&gt;]
[&lt;strong&gt;]
[&lt;sub&gt;]
[&lt;sup&gt;]
[&lt;textarea&gt;]
[&lt;var&gt;]
</code></pre>
<h2 id="the-div-element">The <code>&lt;div&gt;</code> Element</h2>
<p>The  <code>&lt;div&gt;</code>  element is often used as a container for other HTML elements.</p>
<p>The  <code>&lt;div&gt;</code>  element has no required attributes, but  <code>style</code>,  <code>class</code>  and  <code>id</code>  are common.</p>
<p>When used together with CSS, the  <code>&lt;div&gt;</code>  element can be used to style blocks of content:</p>
<pre><code>&lt;div style="background-color:black;color:white;padding:20px;"&gt;  
&lt;h2&gt;London&lt;/h2&gt;  
&lt;p&gt;London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.&lt;/p&gt;  
&lt;/div&gt;
</code></pre>
<h2 id="the-span-element">The <span> Element</span></h2>
<p>The  <code>&lt;span&gt;</code>  element is often used as a container for some text.</p>
<p>The  <code>&lt;span&gt;</code>  element has no required attributes, but  <code>style</code>,  <code>class</code>  and  <code>id</code>  are common.</p>
<p>When used together with CSS, the  <code>&lt;span&gt;</code>  element can be used to style parts of the text:</p>
<pre><code>&lt;h1&gt;My &lt;span style="color:red"&gt;Important&lt;/span&gt; Heading&lt;/h1&gt;
</code></pre>
<h2 id="html-grouping-tags">HTML Grouping Tags</h2>
<p><code>&lt;div&gt;</code> Defines a section in a document (block-level)<br>
<code>&lt;span&gt;</code>Defines a section in a document (inline)</p>
<h1 id="html--the-class-attribute">HTML  The class Attribute</h1>
<h2 id="using-the-class-attribute">Using The class Attribute</h2>
<p>The HTML  <code>class</code>  attribute is used to define equal styles for elements with the same class name.</p>
<p>So, all HTML elements with the same  <code>class</code>  attribute will have the same format and style.</p>
<p>Here we have three  <code>&lt;div&gt;</code>  elements that point to the same class name:</p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html&gt;  
&lt;head&gt;  
&lt;style&gt;  
.cities  {  
background-color:  black;  
color:  white;  
margin:  20px;  
padding:  20px;  
}  
&lt;/style&gt;  
&lt;/head&gt;  
&lt;body&gt;  
  
&lt;div class="cities"&gt;  
&lt;h2&gt;London&lt;/h2&gt;  
&lt;p&gt;London is the capital of England.&lt;/p&gt;  
&lt;/div&gt;  
  
&lt;div class="cities"&gt;  
&lt;h2&gt;Paris&lt;/h2&gt;  
&lt;p&gt;Paris is the capital of France.&lt;/p&gt;  
&lt;/div&gt;  
  
&lt;div class="cities"&gt;  
&lt;h2&gt;Tokyo&lt;/h2&gt;  
&lt;p&gt;Tokyo is the capital of Japan.&lt;/p&gt;  
&lt;/div&gt;  
  
&lt;/body&gt;  
&lt;/html&gt;
</code></pre>
<h2 id="using-the-class-attribute-on-inline-elements">Using The class Attribute on Inline Elements</h2>
<p>The HTML  <code>class</code>  attribute can also be used on inline elements:</p>
<pre><code>&lt;!DOCTYPE html&gt;  
&lt;html&gt;  
&lt;head&gt;  
&lt;style&gt;  
span.note  {  
font-size:  120%;  
color:  red;  
}  
&lt;/style&gt;  
&lt;/head&gt;  
&lt;body&gt;  
  
&lt;h1&gt;My &lt;span class="note"&gt;Important&lt;/span&gt; Heading&lt;/h1&gt;  
&lt;p&gt;This is some &lt;span class="note"&gt;important&lt;/span&gt; text.&lt;/p&gt;  
  
&lt;/body&gt;  
&lt;/html&gt;
</code></pre>
<h2 id="select-elements-with-a-specific-class">Select Elements With a Specific Class</h2>
<p>In CSS, to select elements with a specific class, write a period (.) character, followed by the name of the class:</p>
<pre><code>&lt;style&gt;  
**.city**  {  
background-color:  tomato;  
color:  white;  
padding:  10px;  
}  
&lt;/style&gt;  
  
&lt;h2 **class="city"**&gt;London&lt;/h2&gt;  
&lt;p&gt;London is the capital of England.&lt;/p&gt;  
  
&lt;h2 **class="city"**&gt;Paris&lt;/h2&gt;  
&lt;p&gt;Paris is the capital of France.&lt;/p&gt;  
  
&lt;h2 **class="city"**&gt;Tokyo&lt;/h2&gt;  
&lt;p&gt;Tokyo is the capital of Japan.&lt;/p&gt;
</code></pre>
<h2 id="multiple-classes">Multiple Classes</h2>
<p>HTML elements can have more than one class name, each class name must be separated by a space.</p>
<pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;style&gt;
.city {
    background-color: tomato;
    color: white;
    padding: 10px;
} 

.main {
    text-align: center;
}
&lt;/style&gt;
&lt;body&gt;

&lt;h2&gt;Multiple Classes&lt;/h2&gt;
&lt;p&gt;All three headers have the class name "city". In addition, London also have the class name "main", which center-aligns the text.&lt;/p&gt;

&lt;h2 class="city main"&gt;London&lt;/h2&gt;
&lt;h2 class="city"&gt;Paris&lt;/h2&gt;
&lt;h2 class="city"&gt;Tokyo&lt;/h2&gt;

&lt;/body&gt;
&lt;/html&gt;
</code></pre>
<h2 id="different-tags-can-share-same-class">Different Tags Can Share Same Class</h2>
<p>Different tags, like  <code>&lt;h2&gt;</code>  and  <code>&lt;p&gt;</code>, can have the same class name and thereby share the same style:</p>
<pre><code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;style&gt;
.city {
  background-color: tomato;
  color: white;
  padding: 10px;
} 
&lt;/style&gt;
&lt;body&gt;

&lt;h2&gt;Same Class, Different Tag&lt;/h2&gt;
&lt;p&gt;Even if the two elements do not have the same tag name, they can have the same class name, and get the same styling:&lt;/p&gt;

&lt;h2 class="city"&gt;Paris&lt;/h2&gt;
&lt;p class="city"&gt;Paris is the capital of France.&lt;/p&gt;

&lt;/body&gt;
&lt;/html&gt;
</code></pre>
<h1 id="html--the-id-attribute">HTML  The id Attribute</h1>
<p>'----------</p>
<h2 id="using-the-id-attribute">Using The id Attribute</h2>
<p>The  <code>id</code>  attribute specifies a unique id for an HTML element (the value must be unique within the HTML document).</p>
<p>The id value can be used by CSS and JavaScript to perform certain tasks for a unique element with the specified id value.</p>
<p>In CSS, to select an element with a specific id, write a hash (#) character, followed by the id of the element:</p>
<p>Use CSS to style an element with the id “myHeader”:</p>
<pre><code>&lt;style&gt;  
**#myHeader**  {  
background-color:  lightblue;  
color:  black;  
padding:  40px;  
text-align:  center;  
}  
&lt;/style&gt;  
  
&lt;h1 id="myHeader"&gt;My Header&lt;/h1&gt;
</code></pre>
<h2 id="difference-between-class-and-id">Difference Between Class and ID</h2>
<p>An HTML element can only have one unique id that belongs to that single element, while a class name can be used by multiple elements:</p>
<pre><code>&lt;style&gt;  
/* Style the element with the id "myHeader" */  
**#myHeader**  {  
background-color:  lightblue;  
color:  black;  
padding:  40px;  
text-align:  center;  
}  
  
/* Style all elements with the class name "city" */  
**.city** {  
background-color:  tomato;  
color:  white;  
padding:  10px;  
}  
&lt;/style&gt;  
  
&lt;!-- A unique element --&gt;  
&lt;h1 id="myHeader"&gt;My Cities&lt;/h1&gt;  
  
&lt;!-- Multiple similar elements --&gt;  
&lt;h2 class="city"&gt;London&lt;/h2&gt;  
&lt;p&gt;London is the capital of England.&lt;/p&gt;  
  
&lt;h2 class="city"&gt;Paris&lt;/h2&gt;  
&lt;p&gt;Paris is the capital of France.&lt;/p&gt;  
  
&lt;h2 class="city"&gt;Tokyo&lt;/h2&gt;  
&lt;p&gt;Tokyo is the capital of Japan.&lt;/p&gt;
</code></pre>
<h2 id="bookmarks-with-id-and-links">Bookmarks with ID and Links</h2>
<p>HTML bookmarks are used to allow readers to jump to specific parts of a Web page.</p>
<p>Bookmarks can be useful if your webpage is very long.</p>
<p>To make a bookmark, you must first create the bookmark, and then add a link to it.</p>
<p>When the link is clicked, the page will scroll to the location with the bookmark.</p>
<p>First, create a bookmark with the  <code>id</code>  attribute:</p>
<pre><code>&lt;h2 id="C4"&gt;Chapter 4&lt;/h2&gt;
</code></pre>
<p>Then, add a link to the bookmark (“Jump to Chapter 4”), from within the same page:</p>
<pre><code>&lt;a href="#C4"&gt;Jump to Chapter 4&lt;/a&gt;
</code></pre>
<p>Or, add a link to the bookmark (“Jump to Chapter 4”), from another page:</p>
<pre><code>&lt;a href="html_demo.html#C4"&gt;Jump to Chapter 4&lt;/a&gt;
</code></pre>
<h1 id="html--iframes">HTML  Iframes</h1>
<h2 id="iframe-syntax">Iframe Syntax</h2>
<p>An HTML iframe is defined with the  <code>&lt;iframe&gt;</code>  tag:</p>
<pre><code>&lt;iframe src="_URL_"&gt;&lt;/iframe&gt;
</code></pre>
<p>The  <code>src</code>  attribute specifies the URL (web address) of the inline frame page.</p>
<h2 id="iframe---set-height-and-width">Iframe - Set Height and Width</h2>
<p>Use the  <code>height</code>  and  <code>width</code>  attributes to specify the size of the iframe.</p>
<p>The attribute values are specified in pixels by default, but they can also be in percent (like “80%”).</p>
<pre><code>&lt;iframe src="demo_iframe.htm"  height="200"  width="300"&gt;
</code></pre>
<h2 id="iframe---remove-the-border">Iframe - Remove the Border</h2>
<p>By default, an iframe has a border around it.</p>
<p>To remove the border, add the  <code>style</code>  attribute and use the CSS  <code>border</code>  property:</p>
<pre><code>&lt;iframe src="demo_iframe.htm"  style="border:none;"&gt;&lt;/iframe&gt;
</code></pre>
<h2 id="iframe---target-for-a-link">Iframe - Target for a Link</h2>
<p>An iframe can be used as the target frame for a link.</p>
<p>The  <code>target</code>  attribute of the link must refer to the  <code>name</code>  attribute of the iframe:</p>
<pre><code>&lt;iframe src="demo_iframe.htm"  name="iframe_a"&gt;&lt;/iframe&gt;  
  
&lt;p&gt;&lt;a href="https://www.w3schools.com"  target="iframe_a"&gt;W3Schools.com&lt;/a&gt;&lt;/p&gt;
</code></pre>

