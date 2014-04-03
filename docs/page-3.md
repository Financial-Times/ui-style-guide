---
layout: default
title: Design UX Team
section: Section 1
permalink: /docs/page-3/
---

# Page 3 Design UX Team

You can put pages whereever you like in the folder structure, and they don't have to map to the URL you want to want to serve them on, but it makes sense to stick to it as much as possible.  Each page has some metadata at the top:

	layout: default
	title: Page 2
	section: Section 1
	permalink: /docs/page-2/

I've created this page as `/docs/page-2.md` (which tells me it's a Markdown file) and set its permalink to `/docs/page-2/`.  You can also set a `section`, which will then be available to you when you are highlighing sections in the navigation (see /_layouts/default.html).  You should set `title` to whatever you want to appear in the web browser's title bar  (also what you will be matching against when highlighting the navigation), and `layout` should always be set to 'default' (for the moment).
