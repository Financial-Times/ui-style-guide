---
layout: default
title: Home
section: Section 1
---

![UI Style guide banner]({{site.baseurl}}/img/banner.png)

<div class="o-techdocs-leadbody">
            The following pages show all the component parts and elements that go to create a Financial Times web page. The sister site, the <a href="http://registry.origami.ft.com/components">Origami Registry</a>, contains the physical code needed to make the parts of an FT app, website or digital product. This site describes the rules on layout, structure and how to present the various components.
            
</div>


##FT Square

Many services and digital require a square icon to represent brands digitally. There is only one version of the FT square please do not use a copied imitation or the print version.

![UI Style guide banner]({{site.baseurl}}/img/FT-square.png)

##Origami Grid

The Origami grid is designed to be responsive and works on a 12 column system. Margins and gutter widths between each column is controlled by the grid. Resizing and formatting is accounted for as you reduce the page width down through the FT’s various breakpoints.

For technical implementation, setup and general paramters please see <a href="http://registry.origami.ft.com/components/o-grid@2.0.8">Origami o-grid module.</a>

Below is a demo link of the grid with columns displayed. There are a few key design characteristics. The gutters are 20 pixels and page margins on left and right alter depending on the screen size. The grid has three different scales; XL, L, M, S. There are breakpoints between each.

<a href="http://build.origami.ft.com/files/o-grid@2.1.0/demos/silent.html">Click here</a> to see a page showing the FT's responsive grid. 

<iframe frameborder='0' width="100%" src='http://registry.origami.ft.com/components/o-grid@2.1.0/demos/visual/demos/silent.html?embed=1'></iframe>


##Link Styles
__Standard Links__ 
FT standard links are always FT blue and turn Grey tint 5 on hover. This applies to all links in content or in any apps.

<div class="o-ft-typography-body-wrapper" style="padding:20px;margin:20px 0;background-color:#fff1e0;">
The valuation of the company was not <a style="color:#2e6e9e">disclosed</a> but it is likely to be more than $1bn, based on other fundraisings at this scale. The start-up’s last fundraising was in October 2013, when a large telecoms company led a <a style="color:#2e6e9e">$55m round</a> that also included money from international investors.
</div>

__Article Links__ 
Article links are an inversion of standard links so appear black and turn blue on hover. When a user clicks on an article link they'll be taken to an FT article links can appear on the home page, section pages and for any other situation where articles appear.

These colours can be retrieved from <a href="http://registry.origami.ft.com/components/o-colors@2.3.6">Origami o-color module.</a>


##Colour Pallete

The FT's signature colour is pink. It's been the colour of the paper for over 125 years. Physically the colour is actually shade of beige but this is used to best reproduce of the flagship colour of the paper. This colour has come to be a key brand signal marking the FT out from other products. As such, it is strongly suggested that you use FT pink when creating your design, product or app. 

There are also a host of other colours in the FT's digital colour pallette. They are broken down into three principal groupings. All these colours can be retrieved from the <a href="http://registry.origami.ft.com/components/o-colors@2.3.6">Origami o-color module.</a>

###Common Colours

**FT Pink** - the background colour for FT.com, webapp and all FT products. FT pink is crucial and should be the first requirement when designing FT digital products.

**FT Blue** - used for links only

**Tint 1** - used to make the background colour of the Right-hand Rail 

**Tint 3** - used to make the header modules in the Right-hand Rail 

###Ancillary Colours
These colours are generally used to create interactive graphics or for ancillary widgets, components and page elements outside of standard editorial content. THese colours should never be used on article text, headings or section pages.

<table class='o-techdocs-table' style="width:100%;">
                <tr>
                <th>Name</th>
                <th>Hex</th>
                <th>Colour swatch</th>
                <th>Example use</th>   
                </tr>
                
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
                
                <tr>
                <td>Red</td>
                <td>#c00</td>
                <td><div style="width:100px;height:20px;background-color:#c00"></div></td>
                <td>Errors and ngative alerting messages.</td> 
                </tr>
                
                <tr>
                <td>Green</td>
                <td>#458b00</td>
                <td><div style="width:100px;height:20px;background-color:#458b00"></div></td>
                <td>Affirmative input and feedback e.g. forms</td> 
                </tr>

            </table>



###Tints
Use a combination of these tints to create your page elements and differentiate different page elements of your design. These tints are carefully slected to compliment the FT pink backgruond colour. If you are looking to encapsulate certain page elements with borders, boxes or background colours you must use these tints. THese tints are preferred to the FT grey pallette.

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

These tints are preferred to the exceptional colours in the Ancillary category below.  


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
                <th>Example use</th>   
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
                <td>Life and Arts</td> 
                </tr>
                
                <tr>
                <td>Section Purple</td>
                <td>#92288f</td>
                <td><div style="width:100px;height:20px;background-color:#92288f"></div></td>
                <td>Culture</td> 
                </tr>
                
                <tr>
                <td>Section Light Purple</td>
                <td>#ebcaec</td>
                <td><div style="width:100px;height:20px;background-color:#ebcaec"></div></td>
                <td>enter section name</td> 
                </tr>
                
                <tr>
                <td>Section Blue</td>
                <td>#0e6dcc</td>
                <td><div style="width:100px;height:20px;background-color:#0e6dcc"></div></td>
                <td>enter section name</td> 
                </tr>
                
                <tr>
                <td>Section Light Blue</td>
                <td>#c5d4e8</td>
                <td><div style="width:100px;height:20px;background-color:#c5d4e8"></div></td>
                <td>enter section name</td> 
                </tr>
                
            </table>


###Other Colours

__Claret__ is used for Special Report titles. This colour can be used as an accent colour for elements and designs that specifically need to stand-out strongly. FT Tints are used to seperate page elements and designs. Be warned that the Claret is used sparingly so don’t over-do it. 

__Green__ is typically used for arrows, positive actions on marketing pages

__Red__ is used for warnings and emergency messaging

These colours can be retrieved from <a href="http://registry.origami.ft.com/components/o-colors@2.3.6">Origami o-color module.</a>

##Spacing

A standard FT spacing unit is 20px.

When laying out your product please give enough room to the page elements. Vertical spacing between elements should be consistent. Products presented with varying gaps between elements often look like mistakes with users sublimilally picking it up. The FT is premium brnad so you should strive to uphold accurate, consistent and neat presentation. Using our Ft spacing unit will help you achieve this.

Horizontal spacing, gutters and margins should be controlled by the Origami grid if possible. For vertical spacing you should use the FT spacing unit.






##Fonts
__Benton Sans__ 

Benton is the FT's house font used in the newspaper and online. It is also used for all body text on general pages. General pages encompass all pages that are not article pages. 

__Miller Display Bold__

Used for article headlines. It's not used by FT.com but can be seen on the FT webapp.

__Miller Display Bolder__

Used for article headlines. It's not used by FT.com but can be seen on the FT webapp.

__Georgia__

If Miller is not possible then the fall back font should be Georgia. If at all possible don’t use Georgia Italic

__Arial / Helvetica__

This is the fallback standard font if Benton Sans is not available.

All these fonts can be retrieved from the <a href="http://registry.origami.ft.com/components/o-fonts">Origami o-fonts module.</a>


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

All Origami button styles can be retrieved from the <a href="http://registry.origami.ft.com/components/o-colors@2.3.6">Origami o-buttons module.</a>

###Origami Buttons

Origami buttons are designed to not be preset with any colour. If your product uses a specific colour pallete you can colour your buttons accordingly. Below are the recommended default settings.


####Standard Origami Button

These buttons have hollow colouring and are the default for standard button interactions.

<iframe width="100%" frameborder='0' scrolling='no' src='http://registry.origami.ft.com/components/o-ft-buttons@1.4.1/demos/visual/demos/individual.html?embed=1'></iframe>



####Call-to-action Button

These buttons are only used for pages which require affirmative action. Examples would be on marketing pages, product purchasing pages, sign-up pages and as sign-in buttons.

<iframe width="100%" frameborder='0' scrolling='no' src='http://registry.origami.ft.com/components/o-ft-buttons@1.4.1/demos/visual/demos/individual-standout.html?embed=1'></iframe>

####Pagination

Used for paging through content. e.g. search results

<iframe width="100%" frameborder='0' scrolling='no' src='http://registry.origami.ft.com/components/o-ft-buttons@1.4.1/demos/visual/demos/pagination.html?embed=1'></iframe>


####Toggle buttons / multi toggle

Simple on / off interactions will use the following design.

<iframe width="100%" frameborder='0' scrolling='no' src='http://registry.origami.ft.com/components/o-ft-buttons@1.4.1/demos/visual/demos/grouped.html?embed=1'></iframe>

##Forms

Forms are designed to be responsive at different screen sizes. It’s very important that ample layout and spacing is given to ensure ease of use on touch devices.

All the form elements can be retrieved from the <a href="http://registry.origami.ft.com/components/o-colors@2.3.6">Origami o-forms module.</a>

###Text input

We suggest always prepopulating the form field with suggestive text to help the user.

###Two scales

There are two scales of input available in Origami the “default” size should suffice for most platforms while the “Big”* scale is used for devices and scenarios where touch-based UI is required.

*may change to better name

INSERT DEMO CODE HERE of the 2 scales types.

![Demo code here]({{site.baseurl}}/img/democode.fw.png)


###Input Fields

When laying out input fields in a form all fields must stack vertically. This is the easiest way to read and complete a form.


###Multi Column Layout

In exceptional cases a two column form can be used. For example, if your form is for a simple request for a name and email these two fields can be placed horizontally. When your form has more than four fields it's advised to use a single column layout. UX and design descretion is advised as you don't want to make your form difficult to read.

Example 2 column layout for a competition.


###Input Level Errors

These will always appear underneath the input field. Any information you need to present to explain an error should be written into the redbox displayed below the input field.

###Page level information

Below is the style for when you want to display important information related to a form. There is clear distinction 

![Demo code here]({{site.baseurl}}/img/democode.fw.png)


##Overlays

Ft.com currently uses a series of legacy overlay styles. Do not in any circumstances reproduce any of these legacy overlays.

###Barrier Overlay
Users who arrive at the FT and haven't registered their email will get a barrier overlay. these overlays contain marketing information explaining why they cannot see the page content and paywall information with subscription information.

![Demo code here]({{site.baseurl}}/img/democode.fw.png)

The width and height will be controlled by the content inside these overlays.

###Modal Overlays

These overlays are needed to deliver interactions and FT tools and services. Examples are things such as FT Clippings (our save-for-later service), social sharing options, email this and gift article. Only use this overlay if you want to specifically interupt the users flow - you must have a valid reason for this. 


![Demo code here]({{site.baseurl}}/img/democode.fw.png)

**Closing** - users can click on the close button in the top right or click off the box.

**Width** - recommended width for desktop is 500px. While the code is allowed to be flexible to any width do not let overlays strecth to be full width of the screen.

**Height** - there is no restriction on height but likewise with width please start with a min-height of 200px

**Heading** - all modal overlays should have a heading. Keep it short, long titles will not look nice at smaller screen sizes.  


###Compact Overlays

These overlays are used for minor page interactions. Similiar to tooltips these should be small and just pop up over a small area that the user has interacted with. They should never be implemented as hover. 

An arrow should appear pointing to the original point where the user clicked. This arrow can be placed on the top or bottom or left and right of the overlay.

![Demo code here]({{site.baseurl}}/img/democode.fw.png)

**Closing** - users can click on the close button in the top right or click off the box.

**Heading** - headings are optional on smallscale, if needed keep the text short. The heading with a coloured background is NOT to be used.

**Scale** - as the name says do not make smallscale overlays too big in proportion to your products screensize

<table class='o-techdocs-table'>
                <tr>
                <td>Overlay type</td>
                <td>No Header</td>
                <td>Shaded header</td>
                <td>Non-shaded header</td>
                <td>Side Arrow</td>
                </tr>
                
                <tr>
                <td>Standard</td>
                <td>No Header</td>
                <td>Shaded header</td>
                <td>Non-shaded header</td>
                <td>Side Arrow</td>
                </tr>
                
                <tr>
                <td>Modal</td>
                <td>No Header</td>
                <td>Shaded header</td>
                <td>Non-shaded header</td>
                <td>Side Arrow</td>
                </tr>
                
                <tr>
                <td>Compact</td>
                <td>No Header</td>
                <td>Shaded header</td>
                <td>Non-shaded header</td>
                <td>Side Arrow</td>
                </tr>
                
</table>

##Aside - Right-hand Rail
Beside an article you can insert ancillary content beside an article. These will often be stacked on top of each other to form what's commonly called the ""right-hand rail". 

<iframe height='400' frameborder='0' width="100%" src='http://jsbin.com/sebohekuluge/1/'></iframe>


