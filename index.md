---
layout: default
title: Home
section: Section 1
---

![UI Style guide banner]({{site.baseurl}}/img/banner.png)

##Overview

<div class="o-techdocs-leadbody">
            The following pages show all the component parts and elements that go to create a Financial Times web page. The sister site, the <a href="http://registry.origami.ft.com/components">Origami Registry</a>, contains the physical code needed to make the parts of an FT app, website or digital product. This site describes the rules on layout, structure and how to present the various components.
            
</div>

##FT square
The FT's brand is generally presented according to the rules outlined in the <a href="http://financial-times.github.io/ui-style-guide/dwnld/FT_BrandGuidelines2014.pdf">FT Brand Guidelines</a>. White space, correct placement and other rules are outlined in that document. 

If you require an FT masthead or logo please contact the FT.com Design team at design@ft.com 

##Origami Grid

The Origami grid is designed to be responsive and works on a 12 column system. Margins and between each column is controlled by the grid. Outer margin on the left and right are also controlled by the grid. If your design has several elements which are flush left and flush right to the edge of the viewport that they align using the grid. Resizing and formatting can be simply controlled as you reduce the viewport width down through the FT’s various breakpoints.

Below are the four breakpoints which come with o-grid

<table style="width:100%;">
                <tbody>
                <tr>
                <th>Scale name</th>
                <th>o-grid indicator</th>
                <th>Widths</th>
                </tr>

                <tr>
                <td>Small</td>
                <td>S</td>
                <td>0 - 600</td>
                </tr>
                <tr>
                <td>Medium</td>
                <td>M</td>
                <td>600 - 1000</td>
                </tr>
                
                <tr>
                <td>Large</td>
                <td>L</td>
                <td>1000 - 1400</td>
                </tr>
                
                <tr>
                <td>Extra Large</td>
                <td>XL</td>
                <td>1400+</td>
                </tr>
</tbody>
</table>


For technical implementation, setup and general paramters please see <a href="http://registry.origami.ft.com/components/o-grid">Origami o-grid component.</a>

Below is a demo link of the grid with columns displayed. Note the following key design characteristics. The gutters are 20 pixels and page margins on left and right alter depending on the screen size.

<iframe height="700" frameborder='0' width="100%" src='http://registry.origami.ft.com/components/o-grid@2.1.0/demos/visual/demos/silent.html?embed=1'></iframe>

<a href="http://build.origami.ft.com/files/o-grid@2.1.0/demos/silent.html">Click here</a> to see a seperate page showing the this responsive grid. Designers can resize this to get column widths for any fixed screen size they need.

If you require a PSD showing the basic grid at the main breakpoints please <a href="http://membership.ft.com/ui-style-guide/o-grid-demo.psd">click here.</a>


##Link Styles

###Standard Links

FT standard links are always FT blue and turn black on hover. This applies to all links in content or in any apps.

<iframe width="100%" frameborder='0' scrolling='no' src='comps/demo-links.html'></iframe>

###Article Links 
Article links are an inversion of standard links so appear black and turn blue on hover. These style links appear on the FT home page and section pages. 

Below is an example of how they typically appear. The grey text underneath is the lead body text. This is usually a secondary piece of text further describing the article title. 

<iframe width="100%" frameborder='0' scrolling='no' src='comps/article-link1.html'></iframe>

###FT top twenty links
FT.com uses shows a list of articles on its section pages. This list is called the top 20. The first story is given more prominance with a larger size the following articles are reduced.

Below is an example of how the first story appears in the top 20.

<iframe width="100%" frameborder='0' scrolling='no' src='comps/article-link2.html'></iframe>

Below is an example of how articles appear for the rest of the top 20.

<iframe width="100%" frameborder='0' scrolling='no' src='comps/article-link1.html'></iframe>

##Header
The Origami header caters for various different types mostly outlined in the regsitry documentation. There are however a few UI pointers on those variations.

###Promo slot
in the top right-hand side of the header is a space for a marketing promo ad. This will usually be advertising FT products, new tools and services or a subscriptions prompt. This promo slot only appears on FT.com sites. External products or sites do not have to use this slot. 

<a class="jsbin-embed" href="http://jsbin.com/niyelo/8/edit?output">o-ft-header: branded demo</a><script src="http://static.jsbin.com/js/embed.js"></script>

###Branded header
If you're creating a product or sub-brand of the FT please follow the following instructions.

* The icon/logo for the product goes on the left
* The FT square must go as the last icon on the right-hand side. This also acts as a button taking users back to the FT.
* A tagline can be inserted in the middle aligned left or right.
* Use the small narrow bar underneath the main header apply your product or brand colour.

<a class="jsbin-embed" href="http://jsbin.com/niyelo/10/edit?output">o-ft-header: branded demo</a><script src="http://static.jsbin.com/js/embed.js"></script>

###Tools icons
The header also caters for any tool icons you may want to insert such as search or account etc. These tools collapse under a menu icon at smaller screen sizes.

View <a href="http://jsbin.com/cuposo/1">demonstration site</a> here.





##Colour Palette

The FT's signature colour is FT pink. It is strongly suggested that you use FT pink when creating your design, product or app. For reference all colours can be retrieved from the <a href="http://registry.origami.ft.com/components/o-colors">Origami o-color component.</a>

###Common Colours

Below are the 4 main colours used to layout FT pages. FT pink is the main coloured used to signify FT brand pages.

<table class='o-techdocs-table' style="width:100%;">
                <tr>
                <th>Name</th>
                <th>Hex</th>
                <th>Colour swatch</th>
                <th>Example use</th>   
                </tr>
                
                <tr>
                <td>FT Pink</td>
                <td>#fff1e0</td>
                <td><div style="width:100px;height:20px;background-color:#fff1e0"></div></td>
                <td>Background of FT.com, webapp and all FT products.</td>   
                </tr>
                
                <tr>
                <td>FT Blue</td>
                <td>#2e6e9e</td>
                <td><div style="width:100px;height:20px;background-color:#2e6e9e"></div></td>
                <td>Used for all links</td>   
                </tr>
                
                <tr>
                <td>FT dark Blue</td>
                <td>#275e86</td>
                <td><div style="width:100px;height:20px;background-color:#275e86"></div></td>
                <td>Darker blue for hover on stand out buttons</td>   
                </tr>
                
                <tr>
                <td>FT Pink Tint 1</td>
                <td>#f6e9d8</td>
                <td><div style="width:100px;height:20px;background-color:#f6e9d8"></div></td>
                <td>Used on the right-hand rail background colour</td>   
                </tr>
                
                <tr>
                <td>FT Pink Tint 2</td>
                <td>#e9decf</td>
                <td><div style="width:100px;height:20px;background-color:#e9decf"></div></td>
                <td>Used for background on headers in the right-hand rail</td>   
                </tr>
                
                <tr>
                <td>FT Claret</td>
                <td>#9e2f50</td>
                <td><div style="width:100px;height:20px;background-color:#9e2f50"></div></td>
                <td>Accent colour</td>   
                </tr>
</table>

###Ancillary Colours
These colours are generally used to create interactive graphics or for ancillary widgets, components and page elements outside of standard editorial content. These colours should never be used on article text, headings or section pages.

<table class='o-techdocs-table' style="width:100%;">
                <tr>
                <th>Name</th>
                <th>Hex</th>
                <th>Colour swatch</th>
                <th>Example use</th>   
                </tr>
                <!--
                <tr>
                <td>Orange tint1</td>
                <td>#eda45e</td>
                <td><div style="width:100px;height:20px;background-color:#eda45e"></div></td>
                <td>Interactive graphics and other such uses</td>   
                </tr>
                
                <tr>
                <td>Yellow tint1</td>
                <td>#eed485</td>
                <td><div style="width:100px;height:20px;background-color:#eed485"></div></td>
                <td>Interactive graphics and other such uses</td> 
                </tr>
                
                <tr>
                <td>Bluegreen tint1</td>
                <td>#819e9a</td>
                <td><div style="width:100px;height:20px;background-color:#819e9a"></div></td>
                <td>Interactive graphics and other such uses</td> 
                </tr>
                
                <tr>
                <td>Purple tint1</td>
                <td>#936971</td>
                <td><div style="width:100px;height:20px;background-color:#936971"></div></td>
                <td>Interactive graphics and other such uses</td> 
                </tr>
                
                
                <tr>
                <td>Purple tint2</td>
                <td>#737e7e</td>
                <td><div style="width:100px;height:20px;background-color:#737e7e"></div></td>
                <td>Interactive graphics and other such uses</td> 
                </tr>

                <tr>
                <td>Brown tint1</td>
                <td>#94826b</td>
                <td><div style="width:100px;height:20px;background-color:#94826b"></div></td>
                <td>Interactive graphics and other such uses</td> 
                </tr>
                
                <tr>
                <td>Green tint1</td>
                <td>#a6a471</td>
                <td><div style="width:100px;height:20px;background-color:#a6a471"></div></td>
                <td>Interactive graphics and other such uses</td> 
                </tr>
                
                <tr>
                <td>Silver tint1</td>
                <td>#c1b8b4</td>
                <td><div style="width:100px;height:20px;background-color:#c1b8b4"></div></td>
                <td>Interactive graphics and other such uses</td> 
                </tr>
                -->
                <tr>
                <td>Red</td>
                <td>#c00</td>
                <td><div style="width:100px;height:20px;background-color:#c00"></div></td>
                <td>Errors and negative alerting messages.</td> 
                </tr>
                
                <tr>
                <td>Green</td>
                <td>#458b00</td>
                <td><div style="width:100px;height:20px;background-color:#458b00"></div></td>
                <td>Affirmative input and feedback e.g. forms</td> 
                </tr>

            </table>



###Tints
Use a combination of these tints to create your page elements and differentiate different page elements of your design. These tints are carefully slected to compliment the FT pink backgruond colour. If you are looking to encapsulate certain page elements with borders, boxes or background colours you must use these tints. These tints are preferred to the FT grey pallette.

Below is a table of the FT tints following the numbering system.

<table class='o-techdocs-table' style="width:100%;">
                <tr>
                <th>Name</th>
                <th>Hex</th>
                <th>Colour swatch</th>
                <th>Example use</th>   
                </tr>
                <tr>
                <td>Pink tint 1</td>
                <td>#f6e9d8</td>
                <td><div style="width:100px;height:20px;background-color:#f6e9d8"></div></td>
                <td>Right rail on FT.com</td>   
                </tr>
                
                <tr>
                <td>Pink tint 2</td>
                <td>#e9decf</td>
                <td><div style="width:100px;height:20px;background-color:#e9decf"></div></td>
                <td>FT.com footer</td> 
                </tr>
                
                <tr>
                <td>Pink tint 3</td>
                <td>#cec6b9</td>
                <td><div style="width:100px;height:20px;background-color:#cec6b9"></div></td>
                <td>Video tabs</td> 
                </tr>
                
                <tr>
                <td>Pink tint 4</td>
                <td>#a7a59b</td>
                <td><div style="width:100px;height:20px;background-color:#a7a59b"></div></td>
                <td>FT.com nav bar</td> 
                </tr>
                
                <tr>
                <td>Pink tint 5</td>
                <td>#74736c</td>
                <td><div style="width:100px;height:20px;background-color:#74736c"></div></td>
                <td>FT.com nav bar</td> 
                </tr>
            </table> 


###Greys
Greys can be used on pages that employ a reversed colour scheme or dark styling. An example is video.ft.com They're also used for the FT's secondary button styles.

Below is a table of the FT Greys following the numbering system.

<table class='o-techdocs-table' style="width:100%;">
                <tr>
                <th>Name</th>
                <th>Hex</th>
                <th>Colour swatch</th>
                <th>Example use</th>   
                </tr>
                <tr>
                <td>Grey tint 1</td>
                <td>#b0b0b0</td>
                <td><div style="width:100px;height:20px;background-color:#b0b0b0"></div></td>
                <td>Desciption on video.ft.com</td>   
                </tr>
                
                <tr>
                <td>Grey tint 2</td>
                <td>#999</td>
                <td><div style="width:100px;height:20px;background-color:#999"></div></td>
                <td>n/a</td> 
                </tr>
                
                <tr>
                <td>Grey tint 3</td>
                <td>#777</td>
                <td><div style="width:100px;height:20px;background-color:#777"></div></td>
                <td>Date, bylines, bullets</td> 
                </tr>
                
                <tr>
                <td>Grey tint 4</td>
                <td>#505050</td>
                <td><div style="width:100px;height:20px;background-color:#505050"></div></td>
                <td>Lead body text</td> 
                </tr>
                
                <tr>
                <td>Grey tint 5</td>
                <td>#333</td>
                <td><div style="width:100px;height:20px;background-color:#333"></div></td>
                <td>Article body text</td> 
                </tr>
                
                <tr>
                <td>Black</td>
                <td>#000000</td>
                <td><div style="width:100px;height:20px;background-color:#000000"></div></td>
                <td>FT.com nav bar</td> 
                </tr>
            </table>

###FT Weekend Colours
These colours are only to be used for sections within the FT weekend. They're not to be used anywhere else.

<table class='o-techdocs-table' style="width:100%;">
                <tr>
                <th>Name</th>
                <th>Hex</th>
                <th>Colour swatch</th>
                <th>Use</th>   
                </tr>
                <tr>
                <td>Section Green</td>
                <td>#09a25c</td>
                <td><div style="width:100px;height:20px;background-color:#09a25c"></div></td>
                <td>House and Home</td>   
                </tr>
                
                <tr>
                <td>Section Light Green</td>
                <td>#a1dbb2</td>
                <td><div style="width:100px;height:20px;background-color:#a1dbb2"></div></td>
                <td>House and Home</td> 
                </tr>
                
                <tr>
                <td>Section Red</td>
                <td>#cc0033</td>
                <td><div style="width:100px;height:20px;background-color:#cc0033"></div></td>
                <td>FT Money</td> 
                </tr>
                
                <tr>
                <td>Section Purple</td>
                <td>#92288f</td>
                <td><div style="width:100px;height:20px;background-color:#92288f"></div></td>
                <td>Life and Arts</td> 
                </tr>
                
                <tr>
                <td>Section Light Purple</td>
                <td>#ebcaec</td>
                <td><div style="width:100px;height:20px;background-color:#ebcaec"></div></td>
                <td>Life and Arts</td> 
                </tr>
                
                <tr>
                <td>Section Blue</td>
                <td>#0e6dcc</td>
                <td><div style="width:100px;height:20px;background-color:#0e6dcc"></div></td>
                <td>FT Weekend Magazine</td> 
                </tr>
                
                <tr>
                <td>Section Light Blue</td>
                <td>#c5d4e8</td>
                <td><div style="width:100px;height:20px;background-color:#c5d4e8"></div></td>
                <td>FT Weekend Magazinee</td> 
                </tr>
                
            </table>


##Spacing

A standard FT spacing unit is 20px.

When laying out your product please give enough room to the page elements. Vertical spacing between elements should be consistent. Products presented with varying gaps between elements will look like mistakes. 

Horizontal spacing, gutters and margins should be controlled by the Origami grid. For vertical spacing you should use the FT spacing unit.


##Fonts
__Benton Sans__ 

Benton is the FT's house font online. It is also used for all body text on generic pages such service pages, tool pages and other ancillary pages which are not articles. 

__Miller Display Bold__ and __Miller Display Bolder__

Used for article headlines on the FT webapp.

__Georgia__

Georgia is the standard article body font. If at all possible don’t use Georgia italic.

__Clarion__

Clarion is the standard article body font on the FT webapp.

__Arial / Helvetica__

If Benton Sans is not available these fonts can be used as a fallback.

All fonts can be retrieved from the <a href="http://registry.origami.ft.com/components/o-fonts">Origami o-fonts component.</a>


###Implementation Names

Fonts used by development differ in name to the font names installed for design software. All font names above are accoding to the CSS names for fonts. Below is a table of the CSS names compared to actual font names locally used by design software. Under contractual agreement copies of these fonts cannot be distributed to third parties.

<table class='o-techdocs-table'>
                <tr>
                <th>CSS font name</th>
                <th>Actual Font</th>  
                </tr>
                
                <tr>
                <td>Bentonsans lighter</td>
                <td>Benton Sans Light</td>
                </tr>
                
                <tr>
                <td>Bentonsans bold</td>
                <td>Benton Sans Bold</td>
                </tr>
                
                <tr>
                <td>Millerdisplay normal</td>
                <td>Miller Display Regular</td>
                </tr>
                
                <tr>
                <td>Millerdisplay bold</td>
                <td>Miller Display Semibold</td>
                </tr>
                
                <tr>
                <td>Millerdisplay bolder</td>
                <td>Miller Display Bold</td>
                </tr>
                
                <tr>
                <td>Clarion normal</td>
                <td>Clarion</td>
                </tr>
                
                <tr>
                <td>Clarion bold</td>
                <td>Clarion Bold</td>
                </tr>
                
                <tr>
                <td>Clarion italic</td>
                <td>Clarion Italic</td>
                </tr>
</table>


##Buttons

__Legacy buttons__

Please note there are a set of <a href="http://http://financial-times.github.io/ft-velcro">legacy</a> buttons widely in use. These are primarly for FT.com and have been deprecated in Origami.

All Origami button styles can be retrieved from the <a href="http://registry.origami.ft.com/components/o-buttons">Origami o-buttons component.</a>

###Origami Buttons

Buttons are designed to not be preset with any colour. If your product uses a specific colour palette you can colour your buttons accordingly. Below are the recommended default settings.


####Standard Origami Button

These buttons have hollow colouring and are the default for standard button interactions.

<iframe width="100%" frameborder='0' scrolling='no' src='http://registry.origami.ft.com/components/o-ft-buttons@1.4.1/demos/visual/demos/individual.html?embed=1'></iframe>



####Call-to-action Button

These buttons are only used for pages which require affirmative action. Examples would be on marketing pages, product purchasing pages, sign-up pages and as sign-in buttons.

<iframe width="100%" frameborder='0' scrolling='no' src='http://registry.origami.ft.com/components/o-ft-buttons@1.4.1/demos/visual/demos/individual-standout.html?embed=1'></iframe>

####Pagination

Used for paging through content. e.g. search results. There are two scales depending on whether you're creating something for touch or not.

<iframe width="100%" frameborder='0' scrolling='no' src='http://registry.origami.ft.com/components/o-ft-buttons@1.4.1/demos/visual/demos/pagination.html?embed=1'></iframe>


####Toggle buttons / multi toggle

Simple on / off interactions will use the following design.

<iframe width="100%" frameborder='0' scrolling='no' src='http://registry.origami.ft.com/components/o-ft-buttons@1.4.1/demos/visual/demos/grouped.html?embed=1'></iframe>

##Forms

Forms are designed to be responsive at different screen sizes. It’s very important that ample layout and spacing is given to ensure ease of use on touch devices.

All the form elements can be retrieved from the <a href="http://registry.origami.ft.com/components/o-ft-forms">Origami o-forms component.</a>

###Text input

We suggest always prepopulating the form field with suggestive text to help the user.

<a class="jsbin-embed" href="http://jsbin.com/payela/4/embed?output">o-ft-forms: text-inputs demo</a><script src="http://static.jsbin.com/js/embed.js"></script>

###Multi column layout

When laying out input fields in a form all fields must stack vertically. This is the easiest way to read and complete a form. 

In exceptional cases a two column form can be used. For example, if your form is a simple request for a name and email these two fields can be placed horizontally. When your form has more than four fields it's advised to use a single column layout. Design discretion is advised as you don't want to make your form difficult to read.


###Input error message

These will always appear underneath the input field. The error message should be understandable to the average user and give them a clue how to correct any mistake.

<a class="jsbin-embed" href="http://jsbin.com/soleye/3/embed?output">o-ft-forms: text-inputs demo</a><script src="http://static.jsbin.com/js/embed.js"></script>

##Overlays

FT.com currently uses a series of legacy overlay styles. Do not in any circumstances reproduce any of these legacy overlays. Code can be retrieved from <a href="http://registry.origami.ft.com/components/o-overlay">Origami o-overlay component.</a>

###Content inside overlays

Use the o-typography component to create text inside an overlay. Buttons should always appear aligned in bottom right as per the example below.

<iframe height='500' frameborder='0' width="100%" src='comps/overlay1.html'></iframe>

The width and height will be controlled by the content inside these overlays.

###Modal Overlays

These overlays are needed to deliver interactions and FT tools and services. Examples are things such as FT Clippings (our save-for-later service), social sharing options, email this and gift article. Only use this overlay if you want to specifically interupt the users flow - you must have a valid reason for this. 

<iframe height='500' frameborder='0' width="100%" src='comps/overlay2.html'></iframe>

Users who arrive at the FT and haven't registered their email will get a barrier overlay. these overlays contain marketing information explaining why they cannot see the page content and paywall information with subscription information.

**Closing** - users can click on the close button in the top right __or__ click off the box.

**Width** - recommended width for desktop is **500px**. While the code is allowed to be flexible to any width do not let overlays strecth to be full width of the screen.

**Height** - there is no restriction on height but likewise with width please start with a min-height of 200px

**Heading** - all modal overlays should have a heading. Keep the title short as long titles will not play nice at smaller screen sizes.  


###Compact Overlays

These overlays are used for minor page interactions. Similiar to tooltips these should be small and just pop up over a small area that the user has interacted with. They should never be implemented as hover. 

An arrow should appear pointing to the original point where the user clicked. This arrow can be placed on the top or bottom or left and right of the overlay.

<a class="jsbin-embed" href="http://jsbin.com/pigoca/5/embed?output">o-overlay: overlay-with-arrow demo</a><script src="http://static.jsbin.com/js/embed.js"></script>

**Closing** - users can click on the close button in the top right or click off the box.

**Heading** - a heading with a coloured background is NOT to be used.

**Scale** - as the name says do not make smallscale overlays too big in proportion to your products screensize


##Right-hand Rail
On FT.com there is a column to the right of the page which is known as the "Right-hand Rail". All ancillary content some related to the article and some promotional appears in this column. Modules are stacked on top of each other as in the example below.

The modules can contain lists, article links, promo graphics or links to third party services. it is important to keep the padding, fonts, keading and spacing coherent on on-brand. Please use Origami's <a href="http://registry.origami.ft.com/components/o-typography">typography</a> component to keep all these type styles correct.

The current Right-hand Rail on FT.com is aligned to a legacy grid but you can use the Origami<a href="http://registry.origami.ft.com/components/o-grid">grid</a> to create your own custom width.

<iframe height='500' frameborder='0' width="100%" src='http://jsbin.com/puvew/1/embed?output'></iframe>



