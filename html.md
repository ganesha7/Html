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

