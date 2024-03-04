![Logo](assets/images/gylogo.webp.webp)

# Gigis Yarn
Gigis Yarn is designed to be a digital gallery for handmade crochet artwork. On the site users will find handmade baby toys and accessories. The site is for inspirational purposes and user can even buy items or patterns. 

![Am I Responsive](assets/img_readme/amiresponsive.png)

## Features
The site features a clear and simpel design that includes a navbar at the top next to the logo. In the navbar there is a menu (burger-menu for mobile-devices and buttons for other larger devices) with three buttons – Home, Photos and Contact. There is also a footer containing working icons of Facebook, Instagram and Contact.  

- Homepage: Contains a description of Gigis Yarn. 
- Gallery: Shows photos of my previous works. 
- Contact: A form for contact, when submitted there will be a thank you page and a button to go back to homepage. 

### Homepage
![Printscreen desktop index](assets/img_readme/print_index.png)

### Gallery 
![Printscreen desktop gallery](assets/img_readme/print_gallery.png)

### Contact
![Printscreen desktop contact](assets/img_readme/print_contact.png)

### Thanks
![Printscreen desktop thanks](assets/img_readme/print_thanks.png)

## User Stories
### First time visitors:
An inspirational page for someone interested in crochet.
Puschase finished products or the pattern. 
Contact me for any requests or questions.

### Returning visitors:
Find inspiration from updated information/images
Purchase finished products and patterns

### Others: 
Potentional customer wanting to know prices and what else is offered


## Site Administrator
The site should be organised, easy to navigate and to easy to update information and new images to the gallery.

## Design
### Colour scheme
- #000000
- #2B1A05
- #714C42
- #FAFAF8

![Color palette](assets/img_readme/gy_palette.png)

Color palette created using Canva.
The colors are very neutral with a lot of brown and beige colors, this is to match all the colors in the photos and let the photos "decorate" the site. 

### Font family
For the logo (made in Canva) I used ITC Avant Garde Gothic and Gothham.
For the rest of the site I used the linked Google Fonts with Poppins and the the fallback font is sans-serif. 
Bold was used mainly on the button texts with a weight of 900. 

## Wireframe
The outcome from the Wireframes I made at the beginning has changed a bit from how the end product looked like. Nothing major, changed text-content placement etc. 
I also added the thanks-page which I didn't plan for when I made the wireframes:

### Mobile Wireframes:
![Wireframe mobile index](assets/img_readme/wfmobile_index.png) 
![Wireframe mobile gallery](assets/img_readme/wfmobile_gallery.png)
![Wirefram mobile contact](assets/img_readme/wfmobile_contact.png)

### Tablet Wireframes:
![Wireframe tablet index](assets/img_readme/wftab_index.png)
![Wireframe tablet gallery](assets/img_readme/wftab_gallery.png)
![Wireframe tablet contact](assets/img_readme/wftab_contact.png)

### Desktop Wireframes:
![Wireframe desktop index](assets/img_readme/wfdesk_index.png)
![Wireframe desktop gallery](assets/img_readme/wfdesk_gallery.png)
![Wireframe desktop contact](assets/img_readme/wfdesk_contact.png)

## Languages and resources:
- HTML5 Markup language, used to make the site 
- CSS Used to style most parts of the site 
- Github Repository 
- Gitpod IDE to make the site 
- FontAwesome Where icons on the site is used from 
- Favicon Where icon in tab is used from 
- Google Fonts Where I have taken the fonts from 
- Balwamiq Wireframes Program to create wireframes 
- Canva Program to make hero-image and logo 
- Converter from png to webp: https://convertio.co/png-webp/
- Used this to check contrast, match background and text: https://dequeuniversity.com/rules/axe/4.8/color-contrast
- Lighthouse DevTool
- W3C Validator HTML: https://validator.w3.org/
- W3C Validator CSS: https://jigsaw.w3.org/css-validator/
- README exampel from my mentor: https://github.com/rhysbobbett/heartenhorticulture
- Color picker (For the background): https://htmlcolorcodes.com/

## Media
- The logo was made by me in Canva. The hero-image was also made by me in Canva with photo included in for Canva Pro. 
- All other photos were photographed and edited by me and was taken from my Instagram account @gigisyarn. 

## Sources
- Love Running Walkthrough Project from Code Institute

- Center image (Page 1):
https://www.w3schools.com/howto/howto_css_image_center.asp

- Button to Gallery: 
https://www.w3schools.com/tags/tag_button.asp

- Style submit button:
https://stackoverflow.com/questions/38149704/why-does-the-text-inside-an-input-tag-get-cut-off-even-if-theres-already-a-pa

- Form on Contact me page:
https://www.w3schools.com/css/tryit.asp?filename=trycss_forms


## W3C Validator
Tested 2023-03-01, result: 
### Index page
- Could not have an a tag as a decendant to button tag. This was solved by putting only an a href-tag ad styling it. 
- Changed my section tag to div tag since I'm not using a header and only h2.
### Gallery page
- Same issue with the button since I used the same code. 
- Changed my section tag to div tag since I'm not using a header and only h2.
- I had a div tag without a closing tag
### Contact page
- Changed my section tag to div tag since I'm not using a header and only h2. 
### Thanks page
- button tag issue and section tag issue, the same as the other pages. 

### CSS Stylesheet
- Forgot to put px after a unit

All issues has been taken care of and there are no more errors or warnings. 

## Lighthouse testing
2023-03-02, result: 

### Mobile version:
![Lighthouse result Mobile](assets/img_readme/lighthouse_result.png)

After the first run I had some errors on the Performance (70) and Accessibility (82). 

My first choice of color was a lighter brown (#AD795B) combined with a back font color. I used a color contrast tool (linked in my resources) and picked a slightly darker brown (#714C42)with a white font color instead. I also changed the logo to the same brown to match the rest of the site, this I did in Canva since I designed the logo myself. 

After those changes my Accessibility came up to 100. 

My Performance was still on 70 and Lighthouse recommended to change my images from png to webp, which I did using a converter (also linked in my resources). This made my Performance board to go up to 75. Main problem is still my header/hero image. 

Lightroom also cautioned about my logo (an image) and wanted it to be 375x225px instead of 250x150px. So I changed it the larger size and used my media query to change the size depending on device. 

![Lighthouse error Mobile](assets/img_readme/lighthouse_error.png)

### Desktop version:
![Lighthouse result Desktop](assets/img_readme/lighthouse_resultdesk.png)

The desktop came back with a better result. The Performance is still not where I want it to be but 85 is better than the mobile versions 75. I ran the mobile version and fixed the errors the best I could. This most likely has effected the results for the desktop results as I ran that after.

![Lighthouse error Desktop](assets/img_readme/lighthouse_errordesk.png)

### W3C Validator 
2023-03-02: Tested the site again after testing it on Lighthouse, no errors were found. 

![W3C Validator HTML no errors](assets/img_readme/w3c_html.png)
![W3C Validator CSS no errors](assets/img_readme/w3c_css.png)

One warning: 
![W3C Validator Warning](assets/img_readme/w3c_warning.png)

## Testing
I decided to add a text in hero last night so I had to redo the testing today. 
This time I deployed my site and tested the deployed version,  results 2023-03-04:

