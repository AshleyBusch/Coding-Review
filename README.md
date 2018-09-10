Review

Doctype: declares the document
HTML: all code needs to be inside of things
head: background part of your code
body: what I see on the Page






New

tags children to head tag
meta: helps for SED (doesn't require an end tag)
link: can be used for favicon (does not require an end tag)

tags children to the body tags
<div></div> : generic division - use this when you have nothing else to use
<main></main> : main content
<nav></nav> : used for your main menus and your navigation
<section></section> : breaking up thematic content
<article></article : used to break up an independent item of content

<header></header> : body title

<aside></aside> : not part of main content, but could be referencing
<footer></footer> : used for copyright info, contact info



Notes 2 HTML Structure Review
HTML structure will be used from now on


Text structure
<h?> elements - <h1> -> <h6> used for titles
<p></p> - used for boides of text from a word to full paragraph
<pre></pre> - used for preformatted text like quotes, poems, code
<span></span> - used for custom formatting of text

<br> : line break - no end tags
<wbr> : possible line break - no end tags
<hr> : horizontal rule - no end tags

<em></em> : stress something of importance - usually in italic unless changed
<strong></strong> : used to show importance - usually in bold
<i></i> : alternate voice or mood, technical terms - defaulted italic
<u></u> : representing unarticulated text - default is underline
<b></b> : indicate importance - default is bold


Links
<a href="index.html"></a> - anchor
href - hyperlink reference

<nav>
<a href="idex.html">Home</a>
 | 
 <a href="about.html">About</a>=
  | 
  Contact
   | 
   <a> href="http://www.google.com" target="_blank">Google</a>
   <a> href="contact.html" target="_self">Contact</a>
   <a href="mailto:(email address)" >Contact</a>
   <a href="contactForm.pdf" Download="true" >Contact</a>
   
</nav>

<body>
<header>
<h1 id="mainTitle">This is my main title</h1>
</header>

<main>
<section>
<article>
<p>
<a href=#mainTitle>Go back to top</a>
</p>
</article>

</section>

</main>

</body>


Images

<img src="myimage.jpg" width="250" height="350" alt="Picture of my family" srcset= sizes= crossorigin=>
- Never change both the width and the height
<img src="www.wikipedia/brownbeard.jpg">
<picture>



<figure>
<img src="myimage.jpg" width="250" alt="Picture of my family">
<figcaption>Picture of my family</figcaption>
</figure>



Lists
<dl>
<dl>RedBeard</dl>
<dd>A teacher at Licking Heights</dd>

</dl>


used exactly the same way
<ul></ul> - unordered Lists
<ol type="a"> or <ol type="a" reversed>
<li>I am a line item</li>
<li>I am a line item</li>
<li>I am a line item</li>
<li>I am a line item</li>
<li>I am a line item</li>
<li>I am a line item</li>


</ol> - ordered lists 

<blockquote>Item 1</blockquote> - when you don't want bullets or numbers

<details>
<summary>List of Books I've Read<summary>
<p>Dresden Files</p>
<p>Wheel of Time Series</p>
<p>The Dune Series</p>

</details>
