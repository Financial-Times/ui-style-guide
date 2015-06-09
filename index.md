---
layout: default
title: Home
section: Section 1
---

![UI Style guide banner]({{site.baseurl}}/img/banner.png)

##Overview

<div class="o-techdocs-leadbody">
	This site lists component parts and elements that are used to create pages in Financial Times digital products. It provides style guidance on usage and layout, whilst describing options available to select within components. It's primarily aimed at designers and front-end developers wanting to find out how to make use of our Origami set of standards when building FT products.
	
	The companion to this site, the <a href="http://registry.origami.ft.com/components">Origami Registry</a>, contains the code and technical guidance needed to implement these components, and is aimed primarily at developers wishing to use Origami within a product.
	
	
	To find out more about Origami, including an overview, developer guide and syntax standards, go to the <a href="http://origami.ft.com">Origami homepage</a>.
</div>

##FT branding
A guide to the Financial Times' corporate branding is contained in a separate document, the <a href="http://financial-times.github.io/ui-style-guide/download/FT_BrandGuidelines2014.pdf">FT Brand Guidelines</a>. Guidance is given in the use of the logotypes, including correct placement and treatment. 

If you require an FT masthead or logo file, please contact the FT.com Design & UX team at [design@ft.com](mailto:design@ft.com).

##Origami Grid

The Origami grid is a responsive 12-column system. Resizing and formatting can be controlled as you reduce the viewport width up through the FT’s various breakpoints called "Layouts". Below are the four layouts (S, M, L, XL) which are used with o-grid.

<table style="width:100%;">
	<tbody>
		<tr>
			<th>Layout</th>
			<th>Layout Origami name</th>
			<th>Width (in px)</th>
		</tr>
		<tr>
			<td>Default</td>
			<td>default</td>
			<td>240+</td>
		</tr>
		<tr>
			<td>Small</td>
			<td>S</td>
			<td>490+</td>
		</tr>
		<tr>
			<td>Medium</td>
			<td>M</td>
			<td>730+</td>
		</tr>
		<tr>
			<td>Large</td>
			<td>L</td>
			<td>970+</td>
		</tr>
		<tr>
			<td>Extra Large</td>
			<td>XL</td>
			<td>1210</td>
		</tr>
	</tbody>
</table>


For technical implementation, setup and general parameters, please see <a href="http://registry.origami.ft.com/components/o-grid">Origami o-grid component</a>.

Below is a demo link of the grid with columns displayed. Note the following key design characteristics; the gutters are 10 pixels on page margins on left and right, which alter depending on the screen size.

<iframe height="700" frameborder="0" width="100%" src="http://registry.origami.ft.com/components/o-grid@3.1.3/demos/visual/demos/default.html?embed=1"></iframe>

<a href="http://build.origami.ft.com/files/o-grid/demos/default.html" target="_blank">Open the responsive grid in a new window</a>. Designers can resize this to get column widths for any fixed screen size they need.

For designers here is <a href="https://github.com/Financial-Times/ui-style-guide/raw/gh-pages/downloads/o-grid_4.psd">PSD</a> file showing the basic grid at the main breakpoints with guides.


##Link Styles

###Standard links

FT standard links are coloured FT Blue and turn black on hover. This applies to standard inline links in any product or app, unless other rules take precedence in a given situation.

<iframe height="136" frameborder="0" width="100%" src="comps/link-text.html"></iframe>

###Article headline links 
Article headline links use an inversion of the standard link colours, so appear black initially and turn blue on hover. These style links appear on the FT home page and section pages. 

Below is an example of how they typically appear. The grey text underneath is the lead body text, a secondary piece of text further describing the article content. 

<iframe height="92" frameborder="0" width="100%" src="comps/link-headline.html"></iframe>


##Header
The Origami header caters for various different use cases, mostly outlined in the Regsitry documentation. There are however a few UI pointers on those variations.

###Promo slot
in the top right-hand side of the header is a space for a marketing promo ad. This will usually be advertising FT products, new tools and services or a subscriptions prompt. This promo slot only appears on FT.com sites. External products or sites do not have to use this slot. 

<iframe height="100" frameborder="0" width="100%" src="comps/header-promo.html"></iframe>

###Branded header
If you're creating a product or sub-brand of the FT, please follow the following instructions.

* The icon/logo for the product goes on the left
* The FT square must go as the last icon on the right-hand side. This also acts as a button taking users back to the FT.
* A tagline can be inserted in the middle, aligned either left or right.
* Use the shallow bar underneath the main header apply your product or brand colour.

<iframe height="100" frameborder="0" width="100%" src="comps/header-branded.html"></iframe>


###Tools icons
The header also caters for any tool icons you may want to insert, such as for Search or Account etc. These tools collapse into a Menu icon at smaller screen sizes.

View <a href="http://build.origami.ft.com/files/o-header@3.0.6/demos/header-no-secondary.html">demonstration site</a> here.

##Colour Palette

The FT's signature colour is FT Pink. It is strongly suggested that you use FT Pink when creating your design, product or app. For reference, all colours can be retrieved from the <a href="http://registry.origami.ft.com/components/o-colors">Origami o-color component.</a>

###Common colours

Below are the main colours used across FT pages. FT Pink is the main colour used to signify FT brand pages.

<table class="o-techdocs-table" style="width: 100%;">
	<tr>
		<th>Name</th>
		<th>Hex</th>
		<th>Colour swatch</th>
		<th>Example use</th>   
	</tr>
	<tr>
		<td class="no-wrap">FT Pink</td>
		<td>#fff1e0</td>
		<td><div style="width: 100px; height: 20px; background-color: #fff1e0"></div></td>
		<td>Background of FT.com, webapp and other FT products.</td>   
	</tr>
	<tr>
		<td class="no-wrap">FT Blue</td>
		<td>#2e6e9e</td>
		<td><div style="width: 100px; height: 20px; background-color: #2e6e9e"></div></td>
		<td>Used for link text and buttons</td>   
	</tr>
	<tr>
		<td class="no-wrap">FT Dark Blue</td>
		<td>#275e86</td>
		<td><div style="width: 100px; height: 20px; background-color: #275e86"></div></td>
		<td>Darker blue for hover on stand out buttons</td>   
	</tr>
	<tr>
		<td class="no-wrap">FT Pink Tint 1</td>
		<td>#f6e9d8</td>
		<td><div style="width: 100px; height: 20px; background-color: #f6e9d8"></div></td>
		<td>Used as subtle background colour for large areas of content, such as the right-hand rail on FT.com</td>
	</tr>
	<tr>
		<td class="no-wrap">FT Pink Tint 2</td>
		<td>#e9decf</td>
		<td><div style="width: 100px; height: 20px; background-color: #e9decf"></div></td>
		<td>Used as the background on module title headers</td>   
	</tr>
	<tr>
		<td class="no-wrap">FT Claret</td>
		<td>#9e2f50</td>
		<td><div style="width: 100px; height: 20px; background-color: #9e2f50"></div></td>
		<td>Accent colour</td>   
	</tr>
</table>

###Positive/Negative colours
These colours are generally used to indicate a positive or negative visually. They are used to indicate a rise or fall in value, for example of a stock price. They can be used for both text and accompanying graphics/arrows in this case.

They can also be used to indicate a confirmation or error, for example in form elements.

<table class="o-techdocs-table" style="width: 100%;">
	<tr>
		<th>Name</th>
		<th>Hex</th>
		<th>Colour swatch</th>
		<th>Example use</th>   
	</tr>
<!--
	<tr>
		<td class="no-wrap">Orange tint1</td>
		<td>#eda45e</td>
		<td><div style="width: 100px; height: 20px; background-color: #eda45e"></div></td>
		<td>Interactive graphics and other such uses</td>   
	</tr>
		
	<tr>
		<td class="no-wrap">Yellow tint1</td>
		<td>#eed485</td>
		<td><div style="width: 100px; height: 20px; background-color: #eed485"></div></td>
		<td>Interactive graphics and other such uses</td> 
	</tr>
		
	<tr>
		<td class="no-wrap">Bluegreen tint1</td>
		<td>#819e9a</td>
		<td><div style="width: 100px; height: 20px; background-color: #819e9a"></div></td>
		<td>Interactive graphics and other such uses</td> 
	</tr>
		
	<tr>
		<td class="no-wrap">Purple tint1</td>
		<td>#936971</td>
		<td><div style="width: 100px; height: 20px; background-color: #936971"></div></td>
		<td>Interactive graphics and other such uses</td> 
	</tr>
		
		
	<tr>
		<td class="no-wrap">Purple tint2</td>
		<td>#737e7e</td>
		<td><div style="width: 100px; height: 20px; background-color: #737e7e"></div></td>
		<td>Interactive graphics and other such uses</td> 
	</tr>

	<tr>
		<td class="no-wrap">Brown tint1</td>
		<td>#94826b</td>
		<td><div style="width: 100px; height: 20px; background-color: #94826b"></div></td>
		<td>Interactive graphics and other such uses</td> 
	</tr>
		
	<tr>
		<td class="no-wrap">Green tint1</td>
		<td>#a6a471</td>
		<td><div style="width: 100px; height: 20px; background-color: #a6a471"></div></td>
		<td>Interactive graphics and other such uses</td> 
	</tr>
		
	<tr>
		<td class="no-wrap">Silver tint1</td>
		<td>#c1b8b4</td>
		<td><div style="width: 100px; height: 20px; background-color: #c1b8b4"></div></td>
		<td>Interactive graphics and other such uses</td> 
	</tr>
-->
	<tr>
		<td class="no-wrap">Red</td>
		<td>#c00</td>
		<td><div style="width: 100px; height: 20px; background-color: #cc0000"></div></td>
		<td>Errors and negative alerting messages. Also a decrease in value, eg of a stock price.</td> 
	</tr>
		
	<tr>
		<td class="no-wrap">Green</td>
		<td>#458b00</td>
		<td><div style="width: 100px; height: 20px; background-color: #458b00"></div></td>
		<td>Affirmative input and feedback e.g. forms. Also an increase in value, eg of a stock price</td> 
	</tr>

</table>



###Tints
Use a combination of these tints to create your page elements and differentiate page elements within your design. These tints are carefully selected to compliment the FT pink background colour. If you are looking to encapsulate certain page elements with borders, boxes or background colours, you shouldt use these tints. These tints are preferred to the FT grey palette in most cases.

Below is a table of the FT Tints, numbered by increasing density.

<table class="o-techdocs-table" style="width: 100%;">
	<tr>
		<th>Name</th>
		<th>Hex</th>
		<th>Colour swatch</th>
		<th>Example use</th>   
	</tr>
	<tr>
		<td class="no-wrap">Pink tint 1</td>
		<td>#f6e9d8</td>
		<td><div style="width: 100px; height: 20px; background-color: #f6e9d8"></div></td>
		<td>Right rail on FT.com</td>   
	</tr>
	<tr>
		<td class="no-wrap">Pink tint 2</td>
		<td>#e9decf</td>
		<td><div style="width: 100px; height: 20px; background-color: #e9decf"></div></td>
		<td>FT.com footer</td> 
	</tr>
	<tr>
		<td class="no-wrap">Pink tint 3</td>
		<td>#cec6b9</td>
		<td><div style="width: 100px; height: 20px; background-color: #cec6b9"></div></td>
		<td>Video tabs</td> 
	</tr>
	<tr>
		<td class="no-wrap">Pink tint 4</td>
		<td>#a7a59b</td>
		<td><div style="width: 100px; height: 20px; background-color: #a7a59b"></div></td>
		<td>FT.com nav bar</td> 
	</tr>
	<tr>
		<td class="no-wrap">Pink tint 5</td>
		<td>#74736c</td>
		<td><div style="width: 100px; height: 20px; background-color: #74736c"></div></td>
		<td>FT.com nav bar</td> 
	</tr>
</table> 


###Greys
Greys can be used on pages that employ a reversed colour scheme or dark styling. An example is video.ft.com They're also used for the FT's secondary button styles.

Below is a table of the FT Greys, numbered by increasing density.

<table class="o-techdocs-table" style="width: 100%;">
	<tr>
		<th>Name</th>
		<th>Hex</th>
		<th>Colour swatch</th>
		<th>Example use</th>   
	</tr>
	<tr>
		<td class="no-wrap">Grey tint 1</td>
		<td>#b0b0b0</td>
		<td><div style="width: 100px; height: 20px; background-color: #b0b0b0"></div></td>
		<td>Desciption on video.ft.com</td>   
	</tr>
	<tr>
		<td class="no-wrap">Grey tint 2</td>
		<td>#999</td>
		<td><div style="width: 100px; height: 20px; background-color: #999999"></div></td>
		<td>n/a</td> 
	</tr>
	<tr>
		<td class="no-wrap">Grey tint 3</td>
		<td>#777</td>
		<td><div style="width: 100px; height: 20px; background-color: #777777"></div></td>
		<td>Date, bylines, bullets</td> 
	</tr>
	<tr>
		<td class="no-wrap">Grey tint 4</td>
		<td>#505050</td>
		<td><div style="width: 100px; height: 20px; background-color: #505050"></div></td>
		<td>Lead body text</td> 
	</tr>
	<tr>
		<td class="no-wrap">Grey tint 5</td>
		<td>#333</td>
		<td><div style="width: 100px; height: 20px; background-color: #333333"></div></td>
		<td>Article body text</td> 
	</tr>
	<tr>
		<td class="no-wrap">Black</td>
		<td>#000000</td>
		<td><div style="width: 100px; height: 20px; background-color: #000000"></div></td>
		<td>FT.com nav bar</td> 
	</tr>
</table>

###FT Weekend Colours
These colours are only to be used for sections within FT weekend to represent editorial sections.

<table class="o-techdocs-table" style="width:100%;">
	<tr>
		<th>Name</th>
		<th>Hex</th>
		<th>Colour swatch</th>
		<th>Use</th>   
	</tr>
	<tr>
		<td class="no-wrap">Section Green</td>
		<td>#09a25c</td>
		<td><div style="width: 100px; height: 20px; background-color: #09a25c"></div></td>
		<td>House and Home</td>   
	</tr>
	<tr>
		<td class="no-wrap">Section Light Green</td>
		<td>#a1dbb2</td>
		<td><div style="width: 100px; height: 20px; background-color: #a1dbb2"></div></td>
		<td>House and Home</td> 
	</tr>
	<tr>
		<td class="no-wrap">Section Red</td>
		<td>#cc0033</td>
		<td><div style="width: 100px; height: 20px; background-color: #cc0033"></div></td>
		<td>FT Money</td> 
	</tr>
	<tr>
		<td class="no-wrap">Section Purple</td>
		<td>#92288f</td>
		<td><div style="width: 100px; height: 20px; background-color: #92288f"></div></td>
		<td>Life and Arts</td> 
	</tr>
	<tr>
		<td class="no-wrap">Section Light Purple</td>
		<td>#ebcaec</td>
		<td><div style="width: 100px; height: 20px; background-color: #ebcaec"></div></td>
		<td>Life and Arts</td> 
	</tr>
	<tr>
		<td class="no-wrap">Section Blue</td>
		<td>#0e6dcc</td>
		<td><div style="width: 100px; height: 20px; background-color: #0e6dcc"></div></td>
		<td>FT Weekend Magazine</td> 
	</tr>
	<tr>
		<td class="no-wrap">Section Light Blue</td>
		<td>#c5d4e8</td>
		<td><div style="width: 100px; height: 20px; background-color: #c5d4e8"></div></td>
		<td>FT Weekend Magazinee</td> 
	</tr>
</table>


##Spacing

A standard FT spacing unit is 20px.

When laying out your product please give enough room to the page elements. Vertical spacing between elements should be consistent. 

Horizontal spacing, gutters and margins should be controlled by the Origami grid. For vertical spacing you should use the FT spacing unit.


##Fonts/Typefaces

###Serif typefaces

Serif fonts are generally used to display editorial headlines and body copy. They may also be used for large titles on other products occasionally, but despite a general impression that the FT uses serif fonts for all or most text across its digital products, this generally isn't the case and they tend to be reserved to indicate editorial content.

__Miller Display Bold__ and __Miller Display Bolder__

Miller is used for titles. This could be article headlines or, less commonly, a page or product title. It is generally used at a minimum of 16px. Where headlines are displayed smaller than this, a sans-serif font is generally used instead, even for article headlines, for example in a list within a module or on a search results page.

Where custom fonts can't be used, Georgia is used as a fallback.

__Clarion__

Clarion is used for article body copy only on some products, such as the FT Web App. Where custom fonts can't be used, Georgia is used as a fallback.

__Georgia__

Georgia is the standard article body font and fallback for Miller and Clarion where custom fonts can't be used.


###Sans-serif typefaces

Sans-serif fonts are used widely for non-editorial text. This includes module titles, bylines and date stamps etc within editorial articles, as well as all other content such as navigation, footers and service and tool pages.

When article headlines are shown at a size below 16px, sans-serif fonts are used in preference to Miller or Georgia.

__Benton Sans__ 

Benton is used widely as our preferred sans-serif font. Where custom fonts can't be used, Arial is used as a fallback.

__Arial__

Arial is used as a fallback for Benton where custom fonts can't be used

All fonts can be retrieved from the <a href="http://registry.origami.ft.com/components/o-fonts">Origami o-fonts component.</a>


###Implementation Names

Below is a table of the Origami CSS names used for the various fonts and weights. Under contractual agreement copies of these fonts cannot be distributed to third parties.

<table class="o-techdocs-table">
	<tr>
		<th>CSS font name</th>
		<th>Actual Font</th>  
	</tr>
	<tr>
		<td class="no-wrap">Bentonsans lighter</td>
		<td>Benton Sans Light</td>
	</tr>
	<tr>
		<td class="no-wrap">Bentonsans bold</td>
		<td>Benton Sans Bold</td>
	</tr>
	<tr>
		<td class="no-wrap">Millerdisplay normal</td>
		<td>Miller Display Regular</td>
	</tr>
	<tr>
		<td class="no-wrap">Millerdisplay bold</td>
		<td>Miller Display Semibold</td>
	</tr>
	<tr>
		<td class="no-wrap">Millerdisplay bolder</td>
		<td>Miller Display Bold</td>
	</tr>
	<tr>
		<td class="no-wrap">Clarion normal</td>
		<td>Clarion</td>
	</tr>
	<tr>
		<td class="no-wrap">Clarion bold</td>
		<td>Clarion Bold</td>
	</tr>
	<tr>
		<td class="no-wrap">Clarion italic</td>
		<td>Clarion Italic</td>
	</tr>
</table>


##Buttons

__Legacy buttons__

Please note there are a set of <a href="http://financial-times.github.io/ft-velcro">legacy</a> buttons widely in use. These are primarly for FT.com and have been deprecated in Origami.

All Origami button styles can be retrieved from the <a href="http://registry.origami.ft.com/components/o-buttons">Origami o-buttons component.</a>

###Origami Buttons

Buttons are designed to not be preset with any colour. If your product uses a specific colour palette you can colour your buttons accordingly. Below are the recommended default settings.


####Standard Origami Button

These buttons have hollow colouring and are the default for standard button interactions.

<iframe style="width: 100%" frameborder="0" scrolling="no" src="http://registry.origami.ft.com/components/o-buttons@2.0.3/demos/visual/demos/individual.html?embed=1"></iframe>



####Call-to-action Button

These buttons are only used for pages which require affirmative action. Examples would be on marketing pages, product purchasing pages, sign-up pages and as sign-in buttons.

<iframe style="width: 100%" frameborder="0" scrolling="no" src="http://registry.origami.ft.com/components/o-buttons@2.0.3/demos/visual/demos/individual-standout.html?embed=1"></iframe>

####Pagination

Used for paging through content. e.g. search results. There are two scales depending on whether you're creating something for touch or not.

<iframe style="width: 100%" frameborder="0" scrolling="no" src="http://registry.origami.ft.com/components/o-buttons@2.0.3/demos/visual/demos/pagination.html?embed=1"></iframe>


####Toggle buttons / multi toggle

Simple on / off interactions will use the following design.

<iframe style="width: 100%" frameborder="0" scrolling="no" src="http://registry.origami.ft.com/components/o-buttons@2.0.3/demos/visual/demos/grouped.html?embed=1"></iframe>

##Forms

Forms are designed to be responsive at different screen sizes. It’s very important that ample layout and spacing is given to ensure ease of use on touch devices.

All the form elements can be retrieved from the <a href="http://registry.origami.ft.com/components/o-forms">Origami o-forms component</a>.

###Text input

We suggest always prepopulating the form field with suggestive text to help the user.

<div class="o-forms-group" style="background-color: #fff1e0; padding-top: 10px; padding-bottom: 10px;">
	<label class="o-forms-label">Sign in</label>
	<small class="o-forms-additional-info">Username or email address</small>
	<input type="text" placeholder="e.g. john.ridding@ft.com" class="o-forms-text" />
</div>

###Multi column layout

When laying out input fields in a form all fields must stack vertically. This is the easiest way to read and complete a form. 

In exceptional cases a two column form can be used. For example, if your form is a simple request for a name and email these two fields can be placed horizontally. When your form has more than four fields it's advised to use a single column layout. Design discretion is advised as you don't want to make your form difficult to read.


###Input error message

These will always appear underneath the input field. The error message should be understandable to the average user and give them a clue how to correct any mistake.

<div class="o-forms-group o-forms--error" style="background-color: #fff1e0; padding-top: 10px; padding-bottom: 10px;">
	<label class="o-forms-label">Phone number</label>
	<input type="tel" placeholder="e.g. 07858963709" class="o-forms-text" value="123"></input>
	<div class="o-forms-errortext">Sorry, 123 isn't a valid phone number.</div>
</div>

##Overlays

FT.com currently uses a series of legacy overlay styles. Do not in any circumstances reproduce any of these legacy overlays. Code can be retrieved from <a href="http://registry.origami.ft.com/components/o-overlay">Origami o-overlay component.</a>

###Content inside overlays

Use the o-typography component to create text inside an overlay. Buttons should always appear aligned in bottom right as per the example below.

<iframe height="500" frameborder="0" width="100%" src="comps/overlay1.html"></iframe>

The width and height will be controlled by the content inside these overlays.

###Modal Overlays

These overlays are needed to deliver interactions and FT tools and services. Examples are things such as FT Clippings (our save-for-later service), social sharing options, email this and gift article. Only use this overlay if you want to specifically interupt the users flow - you must have a valid reason for this. 

<iframe height="400" frameborder="0" width="100%" src="comps/overlay2.html"></iframe>

Users who arrive at the FT and haven't registered their email will get a barrier overlay. these overlays contain marketing information explaining why they cannot see the page content and paywall information with subscription information.

**Closing** - users can click on the close button in the top right __or__ click off the box.

**Width** - recommended width for desktop is **500px**. While the code is allowed to be flexible to any width do not let overlays strecth to be full width of the screen.

**Height** - there is no restriction on height but likewise with width please start with a min-height of 200px

**Heading** - all modal overlays should have a heading. Keep the title short as long titles will not play nice at smaller screen sizes.  


###Compact Overlays

These overlays are used for minor page interactions. Similiar to tooltips these should be small and just pop up over a small area that the user has interacted with. They should never be implemented as hover. 

An arrow should appear pointing to the original point where the user clicked. This arrow can be placed on the top or bottom or left and right of the overlay.

<iframe height="250" frameborder="0" width="100%" src="comps/overlay3.html"></iframe>

**Closing** - users can click on the close button in the top right or click off the box.

**Heading** - a heading with a coloured background is NOT to be used.

**Scale** - as the name says do not make compact overlays too big in proportion to your products screensize
