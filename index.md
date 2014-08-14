---
layout: default
title: Home
section: Section 1
---

<div class="o-techdocs-leadbody">
            The following pages show all the component parts and elements that go to create an Financial Times web page. The sister site, the <a href="http://registry.origami.ft.com/components">Origami Registry</a>, only contains the physical code elements needed to make the parts of an app, website or digital product this page describes the rules on layout and structure.
            
</div>

##Origami Grid

The Origami grid is designed to be responsive and works on a 12 column system. Margins and gutter widths between each column is controlled by the grid. Resizing and formatting is accounted for as you reduce the page width down through the FT’s various breakpoints.

For technical implementation, setup and general paramters please see <a href="http://registry.origami.ft.com/components/o-grid@2.0.8">Origami o-grid module.</a>

Below is a demo link of the grid with columns displayed. There are a few key design characteristics. The gutters are 20 pixels and page margins on left and right alter depending on the screen size. The grid has three different scales; XL, L, M, S. There are breakpoints between each.

<a href="http://build.origami.ft.com/files/o-grid@2.1.0/demos/silent.html">Click here</a> to see a page showing the FT's responsive grid. 

<iframe frameborder='0' width="100%" src='http://registry.origami.ft.com/components/o-grid@2.1.0/demos/visual/demos/silent.html?embed=1'></iframe>


##links
__Standard Links__ 
FT standard links are always blue and turn black on hover. This applies to all links in content on a page or in any apps.

__Article Links__ 
Article links are an inversion of standard links so appear black and turn blue on hover. When a user clicks on an article link they'll be taken to an FT article links can appear on the home page, section pages and for any other situation where articles appear.

These colours can be retrieved from <a href="http://registry.origami.ft.com/components/o-colors@2.3.6">Origami o-color module.</a>


##Colour pallette

The FT's signature colour is pink. It's been the colour of the paper for over 125 years. Physically the colour is actually shade of beige but this is used to best reproduce of the flagship colour of the paper. This colour has come to be a key brand signal marking the FT out from other products. As such, it is strongly suggested that you use FT pink when creating your design, product or app. 

There are also a host of other colours in the FT's digital colour pallette. They are broken down into three principal groupings. All these colours can be retrieved from the <a href="http://registry.origami.ft.com/components/o-colors@2.3.6">Origami o-color module.</a>

###Common colours

**FT Pink** - the background colour for FT.com, webapp and all FT products. FT pink is crucial and should be the first requirement when designing FT digital products.

**FT Blue** - used for links only

**Tint 1** - used to make the background colour of the Right-hand Rail 

**Tint 3** - used to make the header modules in the Right-hand Rail 

###Ancillary colours
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



###Other colours

__Claret__ is used for Special Report titles. This colour can be used as an accent colour for elements and designs that specifically need to stand-out strongly. FT Tints are used to seperate page elements and designs. Be warned that the Claret is used sparingly so don’t over-do it. 

__Green__ is typically used for arrows, positive actions on marketing pages

__Red__ is used for warnings and emergency messaging

These colours can be retrieved from <a href="http://registry.origami.ft.com/components/o-colors@2.3.6">Origami o-color module.</a>

##spacing

A standard FT spacing unit is 20px.

When laying out your product please give enough room to the page elements. Vertical spacing between elements should be consistent. Products presented with varying gaps between elements often look like mistakes with users sublimilally picking it up. The FT is premium brnad so you should strive to uphold accurate, consistent and neat presentation. Using our Ft spacing unit will help you achieve this.

Horizontal spacing, gutters and margins should be controlled by the Origami grid if possible. For vertical spacing you should use the FT spacing unit.






##Fonts
__Benton Sans__ 

Benton is the FT's house font used in the newspaper and online. It is also used for all body text on general pages. General pages encompass all pages that are not article pages. 

__Miller Display Bold__

This font is used for article headlines. It's not used by FT.com but can be seen on the FT webapp.

__Miller Display Bolder__

This is used for article headlines. It's not used by FT.com but can be seen on the FT webapp.

__Georgia__

If Miller is not possible then the fall back font should be Georgia. If at all possible don’t use Georgia Italic

__Arial / Helvetica__

This is the fallback standard font if Benton Sans is not available.

All these fonts can be retrieved from the <a href="http://registry.origami.ft.com/components/o-fonts">Origami o-fonts module.</a>


###Implementation names

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


####Standard Origami button

These buttons have hollow colouring and are the default for standard button interactions.

<iframe width="100%" frameborder='0' scrolling='no' src='http://registry.origami.ft.com/components/o-ft-buttons@1.4.1/demos/visual/demos/individual.html?embed=1'></iframe>

####Call-to-action button

These buttons are only used for pages which require affirmative action. Examples would be on marketing pages, product purchasing pages, sign-up pages and as sign-in buttons.
![Demo code here]({{site.baseurl}}/img/democode.fw.png)

####Pagination

Used for paging through content. e.g. search results
![Demo code here]({{site.baseurl}}/img/democode.fw.png)

####Toggle buttons / multi toggle

Simple on / off interactions will use the following design.
![Demo code here]({{site.baseurl}}/img/democode.fw.png)






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


###Input fields

When laying out input fields in a form all fields must stack vertically. This is the easiest way to read and complete a form.


###Multi column layout

In exceptional cases a two column form can be used. For example, if your form is for a simple request for a name and email these two fields can be placed horizontally. When your form has more than four fields it's advised to use a single column layout. UX and design descretion is advised as you don't want to make your form difficult to read.

Example 2 column layout for a competition.



###Input level errors

These will always appear underneath the input field. Any information you need to present to explain an error should be written into the redbox displayed below the input field.

###Page level information

Below is the style for when you want to display important information related to a form. There is clear distinction 

![Demo code here]({{site.baseurl}}/img/democode.fw.png)









##Overlays

FT.com currently uses a series of legacy overlays. 

The FT uses many different overlays to deliver different messages. Some are barrier overlays explaining why a user cannot see content others are needed to deliver tools or services such as FT Clippings, share tools, email, gift article etc

![Demo code here]({{site.baseurl}}/img/democode.fw.png)

###Origami overlays

There is one universal overlay container that all overlays must use. The content inside overlays can vary depending on your products need. The current FT.com overlay types are listed above.

![Demo code here]({{site.baseurl}}/img/democode.fw.png)



