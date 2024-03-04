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

