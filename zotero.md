---
layout: page
title: Zotero
permalink: /zotero/
---

[main-site]: http://www.zotero.org/

<div class="cta"><a class="button" href="https://www.zotero.org/download/">Download Now</a><br/><em>Available on Windows, Mac, and Linux</em></div>

[**Zotero**][main-site] is a free, easy-to-use tool to help you **collect, organize, cite, and share your research.** 

It allows you to easily gather and share reference information, and to incorporate that information into your footnotes and bibliographies. It is also completely free, and developed by an international community of developers and scholars which shapes its future roadmap.

## Benefits

- Free and easy to use!
- Attach PDFs, notes and images to your sources
- Organize collections for your different research projects
- Create bibliographies and insert footnotes using Word, LibreOffice, or [Google Docs](https://www.zotero.org/blog/google-docs-integration/)
- Automatically updates to work with new online sources and new bibliographic styles


## Links

* [Zotero site][main-site] - Home page for the Zotero project
* [Zotero Quick Start Guide](https://www.zotero.org/support/quick_start_guide) - To get you up and running.
* [Andy Naselli's blog post on organizing your Zotero collections](http://andynaselli.com/personal-theological-library/) - A must read. I wish I had taken his advice years ago and organized my Zotero collections into some sort of logical hierarchy of topics. Now I have an inchoate mess and just have to search it all the time, which means I may miss stuff if I use the wrong search terms. Of course, I'm to blame here, not the software.
* [Zotero blog](http://www.zotero.org/blog/) - Official blog of the Zotero project, great for current news on the project
* [Zotero tutorial videos](https://www.zotero.org/support/screencast_tutorials) - Zotero has produced several great how-to videos on their site that demonstrate step by step how to use Zotero's features.

I have several posts on this site with info (including some video) on Zotero. Keep in mind that the videos are pretty old (back when Zotero was primarily a Firefox plugin), but generally speaking the basic interface is still quite similar.

<ul>
	{% for post in site.categories.zotero %}
		<li><a href="{{site.baseurl}}{{post.url}}">{{ post.title }}</a></li>
	{% endfor %}
</ul>


<style>
    .cta {float: right; background-color: #efefef; text-align: center; padding: 1em; }
    .button {display: inline-block; text-align: center; vertical-align: middle; padding: 12px 24px; border: 1px solid #a12727; border-radius: 8px; background: #ff4a4a; background: -webkit-gradient(linear, left top, left bottom, from(#ff4a4a), to(#992727)); background: -moz-linear-gradient(top, #ff4a4a, #992727); background: linear-gradient(to bottom, #ff4a4a, #992727); text-shadow: #591717 1px 1px 1px; font: normal normal bold 20px arial; color: #ffffff; text-decoration: none; }
    .button:hover,
    .button:focus {background: #ff5959; background: -webkit-gradient(linear, left top, left bottom, from(#ff5959), to(#b62f2f)); background: -moz-linear-gradient(top, #ff5959, #b62f2f); background: linear-gradient(to bottom, #ff5959, #b62f2f); color: #ffffff; text-decoration: none; }
    .button:active {background: #982727; background: -webkit-gradient(linear, left top, left bottom, from(#982727), to(#982727)); background: -moz-linear-gradient(top, #982727, #982727); background: linear-gradient(to bottom, #982727, #982727); }
    .button:before{content:  "\0000a0"; display: inline-block; height: 24px; width: 24px; line-height: 24px; margin: 0 4px -6px -4px; position: relative; top: 0px; left: 0px; background: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAD2UlEQVRIiZ2VX4hUVRzHP+f3O2dmdlZnc1uHzUxSqR78UysWhtZLIRIKQQ9BBCHVQ/VUEEFvhU8RGEHQgw++WJEQmS70IIhEFrSUWor4p/XPKLq7zM6u2+7OzLnn9HDvrrvjjqIXfvzuvefc7+d+f+f+7jG0OTqWsr3nKV6dd9NkOc6fWx8lDA3wHjDRqmPbAQo9rH3u7UdfLxW6SYLHB08Sm4xNjzDRGJ03t3qKMDTAh/cEAFje9QSPdD1O3U8y7Sep+0kuxn+4WR/FZG5ivJMCyJ0GQ/AkwZPEhBCTLIdZcWDe+UJHWwfGGAyRGD3EhEgAAvMW4C5vf0eAGsGpIgZUDDYKiQh5dRRdB0kIs44w4T4Aoji1iIBisNEQRCm4PJ2uSIiBJAZ8SMhrA2jcqwMlpxYVAxhiFKIqBZunM9eZrkkI+JhQsHIfABHy1mLFYBCISkTosHl8LnMQEpKQULDtF6MtQIySUzcLMAgYS4fLE7jlIAmegkvuCnigdcBE05G3DieCGsUbizGBDpfHmOLsIqcOGgAlbq9TwwC58qPF/Vt3rn6xs7OIGEGMkMur7dv8WC6nnYToCbGJD00mmzUafook3gKMV6e5dGps0mcl88Fz7ex//viP1XfSNjEUN21fvu+Nj7a8vHRJL2LSzxMgxkCICSF6fGxS9xP40EjrHxNSUU8zeJqJpxmaDJ4cne7/YvDNkcH6N5pZaVbOjh+o3ri5as3G8rquRYtRUawYVAQVg0raD2rAimLVYsXhVNO5Js2Df41NHvj8/Gsjl+r7AXROvXzl/Nih4avjD617undDV6mEU8FKGiqClfTrcmqx6rBisxexWFFOHxse//6zU6+MVKb6Z0TnAgCSyoVaf+Xf0cV9m5Y9u6SrhFPFqmDFYDNxpy5zYHEZZOBwpbp31x87qjemjswVbAUAxGsXa4cvn6tq3zMrtvQ8WDJOFKtp4zl1tyCZ+NGD565//ekvL41X67+3ii0EAIhXL9WOXjgzNNW3ceUL5aVdxkkuq7nDiZ0ty6HvTl7+ateRbTdr9eMLCbUDpE6u1H79+8/K0JMbVm8r93aLGIcYS5qVb/f8dn73Jz9vnZxonGkn0goQ0o1RSZtQh6+Pnzg+cPHKmvWrti17uKxiLCEIe748fHr3rv7tzUZSmfPczP5iaPmZSyaYA4rAItLu7gbKQO+KleW39v308dTZ4b3x3Q92nFCV9dlYTza3lD1byLRkhjQX0C4EsN09pS2bn1+78+APx94HaoC/S4RWgLSKtuSZEsxsb7NCC5yHuQBaBGSBgNsBM9F6b+aa/wHFO6dWZs9S8wAAAABJRU5ErkJggg==") no-repeat left center transparent; background-size: 100% 100%; }
</style>