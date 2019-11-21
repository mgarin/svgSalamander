About this fork
==============
[![Latest Version](https://img.shields.io/maven-central/v/com.weblookandfeel/svg-salamander)](https://github.com/mgarin/svg/releases)
[![License](https://img.shields.io/github/license/mgarin/svgSalamander)](https://github.com/mgarin/weblaf/blob/master/LICENSE.txt)
[![Last Commit](https://img.shields.io/github/last-commit/mgarin/svgSalamander)](https://github.com/mgarin/weblaf/commits/master)
[![Chat on Gitter](https://img.shields.io/gitter/room/mgarin/weblaf?color=%2342ac8c)](https://gitter.im/mgarin/weblaf)

This fork of [blackears/svgSalamander](https://github.com/blackears/svgSalamander) library was made for Maven releases and minor fixes for the library.

To add latest release to your Maven project use next dependency:
```xml
<dependency>
  <groupId>com.weblookandfeel</groupId>
  <artifactId>svg-salamander</artifactId>
  <version>1.1.2.2</version>
</dependency>
```

You can find all other released versions on [search.maven.org](https://search.maven.org/search?q=g:com.weblookandfeel%20AND%20a:svg-salamander&core=gav).

Major, minor and patch versions of releases will be similar to ones on [official project releases](https://github.com/blackears/svgSalamander/releases), but will also contain my personal fixes added on this fork. Fourth version number will be added to any releases between official ones to reference changes I've made on this fork.


SVG Salamander
==============
SVG Salamander is an SVG engine for Java that's designed to be small, fast, and allow programmers to use it with a minimum of fuss. It's in particular targeted for making it easy to integrate SVG into Java games and making it much easier for artists to design 2D game content - from rich interactive menus to charts and graphcs to complex animations.

Features
--------
* Ant task to allow easy conversion from SVG to images from within Ant scripts
* SVGIcon class greatly simplifies loading and drawing images to screen
* A much smaller code foot print than Batik, and only one JAR file to include
* Direct access to the scene graph tree. You can use Java commands to manipulate it directly.
* An index of all named shapes in the SVG graph is easily accessible.
* Picking shapes given (x, y) coordinates is possible, and can be used to implement graphical buttons selected by the mouse
* Clip region sensitivity makes for fast rendering when only updating part of the image. This makes panning the camera quite efficient.
* Easy rendering to any Graphics2D or BufferedImage. Unlike Batik, the SVG Salamander engine does not own the graphics context, so you can pass it whatever graphics context you like.
* Internal and external links are implemented as URIs, which allows the engine to automatically import linked documents - even if they're stored on a remote server.
* SVG can be read from an InputStream, so you can create documents dynamicly from an in-program XSLT transformation.

Current status
--------------
SalamanderSVG is part of the Salamander project hosted on http://www.kitfox.com

Projects using SVG Salamander
-----------------------------
* [Apache Pivot](http://pivot.apache.org/) - An alternate crossplatform GUI for Java.
* [VisiCut](http://visicut.org/) - A tool for laser precision cutting.
* [Xoetrope](http://www.xoetrope.com/) - An alternate crossplatform GUI for Java.
* [Power Line](http://suchanek.name/programs/powerline/index.html) - A slide editor for SVG.
* [Tygron](http://www.tygron.com/) - Serious games illustrating urban planning and climate change.
* [NeoLogica](http://www.neologica.it/eng/Home.php) - Medical imaging.
* [JOSM](https://josm.openstreetmap.de/) - Java OpenStreetMap Editor.
* [Freeplane](http://freeplane.org) - Java program for working with Mind Maps

License
-------
SVG Salamander is avaible both under the [LGPL](https://svgsalamander.java.net/license/license-lgpl.txt) and [BSD](https://svgsalamander.java.net/license/license-bsd.txt) licenses.
