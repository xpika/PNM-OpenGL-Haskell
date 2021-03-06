Haskell PNM Viewer
==================

The PNM format is beautiful. Never before have I seen such a simple practical format.
[Here is the specification.](http://en.wikipedia.org/wiki/Netpbm\_format)

Wow, typing that link would probably have taken longer than giving an informal specification...

Why isn't this format available on everything ever?

The one program I found that could play with PNM files nicely was
[ToyViewer](http://www7a.biglobe.ne.jp/~ogihara/software/OSX/toyv-eng.html)
which is OS X only.

## Introducing: --- The Haskell PNM Viewer --- ##

![Screenshot of the PNM viewer in action](https://raw.githubusercontent.com/sordina/PNM-OpenGL-Haskell/master/screenshots/proof_of_concept.png)

## To Do: ##

* Write parsers for formats other than 'P3'
* Cater for missing 'max' values
* Use bytestrings along with Parsec for a speed boost
* Use OpenGL textures rather than pixels for awesome texture-loading goodness (and speed)
