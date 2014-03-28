---
layout: default
title: Home
section: Section 1
---

# Title of page

Pages are written in Markdown. Surround words with *asterisks* for italics, and **double asterisks** for bold.

Paragraphs are separated by blank lines.

> You can include blockquotes like this

## Secondary heading

Heading levels are indicated by the number of `#` characters preceding the line.

You can also use tables, but you have to write HTML for those (in fact, any HTML works fine, Markdown is just a shortcut)

##Another heading



<table class='o-techdocs-table'>
<tr><th>Col 1 head</th><th>Col 2 head</th></tr>
<tr><td>Cell 1</td><td>Cell 2</td></tr>
<tr><td>Cell 1</td><td>Cell 2</td></tr>
</table>

Another thing you can use HTML for is an aside - a boxed bit of content, usually used for an example or an interesting point to note:

<aside>
	<h4>An interesting point</h4>
	Inside the <code>aside</code>, use <code>&lt;h4&gt;</code> to include a heading for your box.  When you're inside an HTML tag, you can't use Markdown, so if you want to make things <strong>bold</strong>, for example, you have to use the HTML tags.
</aside>

You can embed images too.  When you refer to other URLs within the repo, use `site.baseurl` in double curly braces to ensure that the file is linked correctly:

##And another heading


![This is the ALT text of the image]({{site.baseurl}}/img/panorama.jpg)

Finally, you can embed code samples, just indent them by 4 spaces or a tab.  Prefix with `<?prettify linenums=1?>` if you'd like line numbering and syntax highlighting:

<?prettify linenums=1?>
	Like this
	And this
