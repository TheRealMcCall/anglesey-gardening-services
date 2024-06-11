# Testing

## Browser Compatibility


I've tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](documentation/chrome-screen.png) | Works as expected |
| Firefox | ![screenshot](documentation/firefox-screen.png) | works as expected |
| Edge | ![screenshot](documentation/edge-screen.png) | Works as expected

## Responsiveness

The website was tested on Chrome, Firefox and Edge with no problems found.

The website was tested on numerous sized screens including Google Pixel 8 Pro, Samsung Galaxy S22 PLUS, 15" laptop, 24" screen, 27" screen and responded as expected to all sizes.
Chrome development tools was used throughout the design process to check responsiveness and breakpoints. Adjustments were made accordingly.

## Validator Testing
+ ### HTML
  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Home Page HTML Validator](documentation/home-page-validator.png)
    
  #### About Us Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Gallery Page HTML Validator](documentation/about-us-validator.png)

  #### Contact Us Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Contact Page HTML Validator](documentation/contact-page-validator.png)

  #### Form Completed Page
    - No errors or warnings were found when passing through the official W3C validator.

    ![Form Completed Page](documentation/form-complete-validator.png)

---

+ ## LightHouse report

    - Using lighthouse in devtools I confirmed that the website is performing well, accessible and colors and fonts chosen are readable.
    
  ### Home page

  ![Home Page Lighthouse](documentation/lighthouse-home.png)

  ### About Us page

  ![About Us Page Lighthouse](documentation/lighthouse-about-us.png)

  ### Contact Us page

  ![Contact Us Page Lighthouse](documentation/lighthouse-contact-us.png)

  ### Form Completed page

  ![Response Page Lighthouse](documentation/lighthouse-form-complete.png)

---
## Bugs
+ ### Solved Bugs

    * Hero Image causing overflow on some smaller screen sizes.
    
      *Solution:* Added max width 100% to style.css
    
    * Footer not at end of webpage in some screen sizes.

      *Solution:* Added height 100% to style.css

    * Submit button too close to footer on Contact Us page.

      *Solution:* Added margin-bottom to .contact form.

    * Customer reviews aligned left and not center on mobile screens.

      *Solution:* Bootstrap class Justify-content-center added.

+ ### Unsolved bugs.
  - None Found.
