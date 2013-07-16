# Simple HAML
Ever wanted to use excellent HAML syntax on any project even the small one? Me too, so I made one! HAML is intended for 'elegant' markup, eliminating the reptetive tags of HTML. I like to use Haml because it eliminates superfluous markup including closing tag. View code is much easier to read. What's in the package are basic responsive website template with HAML, Bourbon and Neat.

# About the language
Here's an example of HAML markup looks like before compiling to HTML markup.

Just class
 
**HAML**

	.tupperware Hello, World!

**HTML**

	<div class='tupperware'>Hello, World!</div>

Another example with class and ID

**HAML** 

	%h2.headline#myID This is a headline
	%p This is a paragraph.
	%ul
    	%li List item one
    	%li List item two
    	%li List item three
	%p Another paragraph can go here.

**HTML**
	
	<h2 class='headline' id='myID'>This is a headline</h2>
	<p>This is a paragraph.</p>
	<ul>
  		<li>List item one</li>
  		<li>List item two</li>
  		<li>List item three</li>
	</ul>
	<p>Another paragraph can go here.</p>
	
# Docs
 * `index.haml` contains all stuffs including CDN modernizr that compiled to `index.html`.
 * `scss` folder includes bourbon, neat and custom folders (normalize, etc.) that compiled to `css` folder.
 * `favicons.psd` HTML5 boilerplate favicon photoshop template
 
# How to use it
The [HAML reference](http://haml.info/tutorial.html) is the most complete documentation for HAML. It contains information on every language feature is a great place to start if you aren't familiar with the language. It goes over the basic syntax for elements, etc.

If you're already familiar with compilers like [CodeKit](http://incident57.com/codekit/) or [Koala](http://koala-app.com/) then you're on the right track. If not, check them out. To complie `haml` file, select the `index.haml` file and set the output path to `index.html` in the same directory.  To compile `scss` file, select the `scss/base.scss` file and set the output path to `css/base.css`. I used `favicons.psd` to update the favicon only once. Pretty nifty, eh?

### Credits
 * [Bourbon](http://bourbon.io) - a simple and lightweight mixin library for Sass
 * [Neat](http://neat.bourbon.io) - a lightweight semantic grid framework for Sass and Bourbon
 * [Favicon PSD](http://drublic.de/blog/html5-boilerplate-favicons-psd-template/) - by Hans Christian
 * [Sublime Text](http://www.sublimetext.com/) - awesome web editor
 * [Mou](http://mouapp.com) - the missing Markdown editor for web developers
 
### License
Simple Haml is released under a [Creative Commons Attribution-Share Alike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/). This means you can copy, distribute, transmit and adapt the work to your own personal and commercial projects.