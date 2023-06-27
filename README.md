
---

# *Bootx*

"Bootx. Buy. Sell. Donate." Bootx is a re-seller of old childrens football boots. Parents can buy, sell or donate their childs pre-loved boots, in order to save money, act sustainably and to rasie a little money for their football club. This website is about showcasing this service, giving a flavour of the inventory and collecting data for marketing.

The site can be accessed by this [link](https://t0bes1.github.io/bootx/)

---
## User Stories

As a user I want to be able to undertsand Bootx, why it exists and its benefits, so that I can determine whether I would like to use the service

As a user I want to be able to browse some of the best boots available for purchase, so that I can see the types of boots available for sale and determine whether I would like to use the service

As a user I want to be able to sign up to receive notifications about boots that are becoming available for sale, so that I can see boots relevant to me and determine whether I would like to make a purchase

## Features

+ ### Navbar

+ ##### Navigation
    - Positioned at the top of the page.
    - Contains logo of the company on the left side.
    - Contains navigation links on the right side:
        * HOME - leads to the home page where users can learn about the company Bootx.
        * TOP BOOTS - leads to the tops boots page where users can see available boots.
        * SIGN UP - leads to a sign up form page where users can fill out the form in order to get updates from the company.
    - The links have animated hover effect.
    - The navigation is clear and easy to understand for the user.

    - The navigation bar is responsive
---

+ ### Home Page

    - Represent: 

        * the main idea of the company.
        * Emphasize the strong points of the company.
        * Shows top boots available for sale.
        * Invites to fill out the sign up form.

---

+ #### Hero Section

    - Hero section has a zooming background image.

    - Hero section have the block section below the image that consist of a Short description of the company's philosophy.

--- 

+ #### About Section

    - Gives 3 compelling key reasons why a consumer would want to use the company.

    ---
+ #### Top Boots Section

    - Testimonials Section has three feedbacks from people who were satisfied with the company's service.

    - Each top boots has a picture of the boots.

    - Each top boots shows a Size and Desctipiion of the pair for sale.

    - Each top boots shows an indicative price, should the customer wish to contact us for purchase.

---
+ #### Sign Up Section

    - The Sign Up Section shows reasons for the usert to want to sign up to the company mailing list.

    - Is also has a button that directs to the Sign Up page.

---
+ #### Footer

    - Footer contains social media links that open in a new tab.
​
---
+ ### Top Boots Page

    - The Top Boots page shows 5 pairs of boots available for sale.

    - Each top boots has a picutre of the boots.

    - Each top boots shows a Size and Desctipiion of the pair for sale.

    - Each top boots shows an indicative price, should the customer wish to contact us for purchase.

    - Each top boots has an orange bar for a "value" price and silver bar for a "premium" price.


---
+ ### Sign Up page

    - Sign Up page has a form for signing up to the Bootx mailing list:

        - All input fields are customised.
        - All inputs are set to be required to fill out.
        - The submit button is animated on hover.

    - The page is responsive on all common screen sizes.

    - The submit button leads to the response page.

---
+ ### Response page

    - Response page appears after submitting the contact form.
    - It contains a confrimation message.
    - It will automatically direct the user to the main page in 5 seconds.

---
## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) was used as the foundation of the site.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/css) - was used to add the styles and layout of the site.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - was used to arrange items simmetrically on the pages.
- [CSS roots](https://developer.mozilla.org/en-US/docs/Web/CSS/:root) was used to declaring global CSS variables and apply them throughout the project. 
- [Balsamiq](https://balsamiq.com/) was used to make wireframes for the website.
- [VSCode](https://code.visualstudio.com/) was used as the main tool to write and edit code.
- [Git](https://git-scm.com/) was used for the version control of the website.
- [GitHub](https://github.com/) was used to host the code of the website.

---
## Design

### Brand Guide

The website is created using a brand guide, designed by Nick Walters [Link](documentation/bootx-nu-html-checker.png)

### Wireframes

#### Mobile devices

#### Tablets

#### Desktop

---

## Testing

In order to confirm the correct functionality, responsiveness, and appearance:

+ The website was tested on the following browsers: Chrome, Firefox, Brave.

    - Chrome:

    - FireFox:

    - Brave:

+ The website was checked by devtools implemented in Firefox and Chrome browsers.

    - Main Page:

    - Top Boots Page:

    - Sign Up Page:

    - Response Page:

+ The website was checked with [Responsive Website Design Tester](https://responsivedesignchecker.com/).

    - Desktop Screens:

    - Tablet Screens:

    - Mobile Screens:

+ The functionality of the links in the website was checked as well by different users.

### Manual testing

| feature | action | expected result | tested | passed | comments |
| --- | --- | --- | --- | --- | --- |
| Navbar | | | | | |
| Home | Click on the "Home" link | The user is redirected to the main page | Yes | Yes | - |
| Top Boots | Click on the "Top Boots" link | The user is redirected to the top boots page | Yes | Yes | - |
| Sign Up | Click on the "Sign Up" link | The user is redirected to the sign up page | Yes | Yes | - |
| Footer | | | | | |
| Instagram icon in the footer | Click on the Instagram icon | The user is redirected to the Instagram page | Yes | Yes | - |
| Facebook icon in the footer | Click on the Facebook icon | The user is redirected to the Facebook page | Yes | Yes | - |
| Twitter icon in the footer | Click on the Twitter icon | The user is redirected to the Twitter page | Yes | Yes | - |
| YouTube icon in the footer | Click on the YouTube icon | The user is redirected to the YouTube page | Yes | Yes | - |
| Home page | | | | | |
| "Sign Up" button in Sign Up section | Click on the "Sign Up" button | The user is redirected to the sign upp page | Yes | Yes | - |
| Top Boots page | | | | | |
| "Sign Up" button in Sign Up section | Click on the "Sign Up" button | The user is redirected to the sign up page | Yes | Yes | - |
| Sign Up page | | | | | |
| Full Name input | Enter the full name | The full name is entered | Yes | Yes | If user doesn't enter the full name, the error message appears |
| Email input | Enter the email | The email is entered | Yes | Yes | If user doesn't enter the email, the error message appears. If user enters not valid email, the error message appears |
| Age input | Enter the age | The age is entered | Yes | Yes | If user doesn't enter age, the error message appears |
| "Submit" button | Click on the "Submit" button | The user is redirected to the response page | Yes | Yes | - |
| Response page | | | | | |
| Response message | The user will be automatically redirected to the home page after 5 seconds | The user is redirected to the home page | Yes | Yes | - |

---
​
### Bugs
+ ##### Solved bugs
    1. The navigation bar text would move when a user highlighted each link.
    
        *Solutions:* The nav bar was moved to a horizontal layout, this avoided the text moving issues.
    
    2. The top boots section would warp when viewed on certain devices, with images and text not always centered.
        
        *Solution:* flexbox was used across all relevant child elements in order to ensure the response designs 

    3. The sign up section would become unreadable with certain screen sizes.
        
        *Solution:* The section was re-designed to remove a background image and instead use a flexible design that would be more satisfying for users on all screen sizes.
    ---
+ ##### Unsolved bugs
    - None.
+ ##### Mistakes
    - The orginal sign design was not responsive, being over reliant on media queries to work on varying devices. This was resolved as part of a re-write.
    - While progressing in my code I learned to use flex more deeply on my web site design

---
## Validator testing
+ ### HTML
  #### Home Page
    - No errors or warnings were found when passing through the official W3C validator.
    
  #### Top Boots Page
    - No errors or warnings were found when passing through the official W3C validator.

  #### Sign Up Page
    - No errors or warnings were found when passing through the official W3C validator.

  #### Response Page
    - No errors or warnings were found when passing through the official W3C validator.
    
+ ### CSS
  No errors or warnings were found when passing through the official W3C (Jigsaw) validator except:


+ ### Accessibility and performance 
    - Using lighthouse in devtools I confirmed that the website is performing well, accessible and colors and fonts chosen are readable.
    
  #### Home page

  #### Top Boots page

  #### Sign Up page

  #### Response page

---
## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the [GitHub repository](https://github.com/t0bes1/bootx), navigate to the Settings tab 
  - From the source section drop-down menu, select the **Main** Branch, then click "Save".
  - The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

---
## Credits

+ #### Content

    - Inspiration for the gallery hover effect came from the article "How to add a gradient to overlay to a background image using just CSS and HTML" published the website [Web Dev etc](https://webdevetc.com).
    - Inspiration for the responsive hamburger navbar came from [Kevin Powell](https://www.youtube.com/user/KepowOb) on his YouTube channel.
---

## Acknowledgments

- [Code Institute](https://codeinstitute.net/) tutors and Slack community members for their support and help.
- [Kevin Powell](https://www.youtube.com/user/KepowOb) for his amazing CSS tutorials.

---