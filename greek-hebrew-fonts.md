---
layout: page
title: Greek & Hebrew Fonts
permalink: /greek-hebrew-fonts/
---

## Greek font vs. Unicode: What's the difference?

To use Greek and Hebrew in your documents, you can now choose between two different approaches:

1.  Use special fonts that display English letters as though they were Greek and Hebrew, such as the common fonts produced by BibleWorks: **bwgrkl** for Greek and **bwhebb** for Hebrew.
2.  Use Unicode to actually type Greek/Hebrew text alongside English. Many fonts support the full Unicode character set.

Whenever possible, use Unicode! Here's why:

-   Unicode is the international standard for handling characters for *all* foreign languages, not just Greek and Hebrew. 
-   Unicode text will print more reliably.
-   Unicode is the best way to post Greek/Hebrew to the web (see the examples of 2 Timothy 2:15 below).

    Unicode: <span lang="el">σπούδασον σεαυτὸν δόκιμον παραστῆσαι τῷ θεῷ, ἐργάτην ἀνεπαίσχυντον, ὀρθοτομοῦντα τὸν λόγον τῆς ἀληθείας.</span> (This line appears as Greek glyphs, regardless of which fonts you have installed on your computer.)


    BibleWorks font: <span style="font-family: bwgrkl;">spou,dason seauto.n do,kimon parasth/sai tw/| qew/|( evrga,thn avnepai,scunton( ovrqotomou/nta to.n lo,gon th/j avlhqei,ajÅ</span> (This line will only look like Greek if you have the BibleWorks font installed on your computer.)

Try copying and pasting each of these verses into a plain text editor like Windows Notepad, and you should see the difference between the actual Greek characters used by Unicode and the masked English characters used by the BibleWorks font.

This page aims to help you install, configure, and use the biblical languages using either approach.

## Installation and Usage Guides

See the pages listed below for further documentation.

<ul>
	{% for post in site.categories.unicode %}
		<li><a href="{{site.baseurl}}{{post.url}}">{{ post.title }}</a></li>
	{% endfor %}
</ul>




<style>
:lang(el) { font-family: Gentium, "SBL Greek", Cardo, "Palatino Linotype"; font-size: 15px; }

:lang(he) { font-family: "SBL Hebrew", "Ezra SIL", Cardo; font-size: 19px; text-align: right; }
</style>
