# GitHub DITA-based Wiki {#topic_zn3_2bc_zw}

The [ghd-wiki](https://github.com/georgebina/ghd-wiki) project shows how we can combine DITA, Lightweight DITA and Markdown plus a few services like GitHub, GitHub Pages, Travis, oXygen XML Author, the DITA Open Toolkit with a few plugins for publishing WebHelp, handling Markdown as DITA topics, etc. in order to create basic Wiki-like website that allows anyone to contribute content in just a few clicks. Once a contribution is accepted it will automatically be live on the web, as soon as the web content is automatically regenerated by Travis.

The DITA content \(in XML or Markdown format\) is placed within the wiki folder and using an XSLT script we build automatically a DITA map that then we publish using the oXygen XML WebHelp DITA-OT plugin through Travis. The WebHelp HTML content is committed on the `gh-pages` branch which serves the content through GitHub Pages.

For more details on supported formats, along with standard DITA topics please see the [LW-DITA](topic.html) and [Markdown](markdown.html) pages.
