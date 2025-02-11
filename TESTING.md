# Testing

1. [Testing](#Testing)
    * [Code Validation](#Code-Validation)
      * [W3C Validator](#w3c-validator)
      * [Lighthouse](#lighthouse)
    * [Known Bugs](#Known-bugs)
    * [Manual Testing](#manual-testing)
      * [Testing User Stories](#testing-user-stories)
      * [Manually Link Testing](#manually-link-testing)
      * [Responsiveness Testing](#Responsiveness-testing)
    

## Code Validation

### W3C Validator

<a href="https://validator.w3.org/" target="_blank" rel="noopener" >W3C html Validator</a> was used to validate the HTML on all pages of the website. [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) was also used to validate the CSS.
Minor errors were found which I have described in [Known Bugs](#known-bugs) section. After a fix and retest, no errors were returned.

### HTML-

![index html validation](readme-images/testing/w3cTesting/w3c-html-index-validation.png) - Passed

![menu html validation](readme-images/testing/w3cTesting/w3c-html-menu-validation.png) - Passed

![about html validation](readme-images/testing/w3cTesting/w3c-html-about-validation.png) - Passed

![contact html validation](readme-images/testing/w3cTesting/w3c-html-contact-validation.png) - Passed

![success html validation](readme-images/testing/w3cTesting/w3c-html-success-validation.png) - Passed

### CSS - 
CSS Validation

![CSS Validation](readme-images/testing/w3cTesting/w3c-css-validation.png) - Passed, No error found.

[Back to top](#Testing)


### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

### Desktop Results

All pages of the site are achieving a score of above 90 or better across the 4 categories.

Home

![index.html](readme-images/testing/LighthouseTesting/lighthouse-homepage.png)

Menu

![menu.html](readme-images/testing/LighthouseTesting/lighthouse-menupage.png)


About

![about.html](readme-images/testing/LighthouseTesting/lighthouse-aboutpage.png)

Contact

![contact.html](readme-images/testing/LighthouseTesting/lighthouse-contactpage.png)

Success

![success.html](readme-images/testing/LighthouseTesting/lighthouse-successpage.png)

[Back to top](#Testing)

### Mobile Results

All pages of the site on mobile devices are achieving good score across the 4 categories.

Home

![index.html](readme-images/testing/LighthouseTesting/LHMobile-home.png)

Menu

![menu.html](readme-images/testing/LighthouseTesting/LHMobile-menu.png)

About

![about.html](readme-images/testing/LighthouseTesting/LHMobile-about.png)

Contact

![contact.html](readme-images/testing/LighthouseTesting/LHMobile-contact.png)

Success

![success.html](readme-images/testing/LighthouseTesting/LHMobile-success.png)

[Back to top](#Testing)

- - -

# Known Bugs

Menu Page 
![Menu Html Bug Image](readme-images/testing/w3cTesting/menu-html-error.png)
Errors were corrected easily as suggested by validator.


CSS
![CSS Bug Image](readme-images/testing/w3cTesting/CSSError.png)
Error was corrected.

* Another bug was images's size. When validated through lighthouse, Performance was really low.
fixes:- I compressed all the images of the website. That's how performance was improved.

## Manual testing

### Testing User Stories

`As a Customer`

| Goals | Actions |
| :--- | :--- |
| As a customer I want to know about the business. What it is and what does it offer.| I mentioned in cover text it is 100% indian vegetarian food cloud kithen. I added a Call to Order button to show it's call to order approach.| 
| As a customer I want to be able to easily navigate the website. | I added a navigation bar to all pages that gives the user an easy way to navigate the website. |
| As a customer I want to be able to easily find the contact details. | I added a footer with basic contact details for the Business. |
| As a customer I want to find out the menu and speciality of the business. | I added a card section on home page with the six popular dishes of Kaku's Kitchen. I have added a full menu offered by Kaku's Kitchen on menu page and navigation bar is on the top of all pages to go menu page.  |


[Back to top](#Testing)


### Manually Link Testing

#### __Global__

- - -
__Navigation bar__

![The navbar is available on all pages](readme-images/features/navbar-desktop.png)

__Expected__

I expect the nav bar to link all the pages together and give easy navigation of the website. On each respective page the navbar will show what page you are on as shown below.

Home page - Home option is underlined to show current page.
![Navbar with home page being shown as the active page](readme-images/testing/ManualTesting/Navbar/Navbar-home.png)

Menu page - Menu option is underlined to show current page.
![Navbar with menu page being shown as the active page](readme-images/testing/ManualTesting/Navbar/Navbar-menu.png)

Contact page - Contact option is underlined to show current page.
![Navbar with contact page being shown as the active page](readme-images/testing/ManualTesting/Navbar/Navbar-contact.png)

About page - About option is underlined to show current page.
![Navbar with about page being shown as the active page](readme-images/testing/ManualTesting/Navbar/Navbar-about.png)

Success page - For success page contact option is highlighted as it is extension of contact page.
![Navbar with success page is an extention of the contact page](readme-images/testing/ManualTesting/Navbar/Navbar-success.png)

__Results__

The navigation bar on all the pages works as designed and as expected.

- - -
[Back to top](#Testing)


__Footer__

![The footer is carried across all pages](readme-images/testing/ManualTesting/TestFooter.png)

__Expected__

The social media links open up to the respective home page in a new tab. Pinned address will take you to the google map in new tab.

__Results__

Worked as intended.

- - - 
[Back to top](#Testing)


#### __Home Page__

- - -

__Hero call to action button__

![Call to action button on home page](readme-images/testing/ManualTesting/CallToAction.png)
__Expected__

The user will click on the button which will take them to the contact detail in the footer section.

__Results__

The button worked as expected.

- - -
[Back to top](#Testing)

#### __Contact Page__

- - - 

__Form__

![The form on the contact page](readme-images/testing/ManualTesting/FormValidation/FormImage.png)


- - -

__Form validation__
![Name](readme-images/testing/ManualTesting/FormValidation/NameValidation.png)
![alt text](image-1.png)

![Email](readme-images/testing/ManualTesting/FormValidation/EmailValidation.png)

![Phone Number](readme-images/testing/ManualTesting/FormValidation/PhoneValidation.png)

Validation has been checked manually on all the field like above.

Filled form ready to submit. Once you hit the submit button, it will direct you to the Thankyou/Success page. 

![Filled Form](readme-images/testing/ManualTesting/FormValidation/FilledForm.png)

__Results__

Form is working as expected. 

[Back to top](#Testing)


__ThankYou Page__

![Sucess Page](readme-images/testing/SuccessPageValidation.png)

Back to Home button on contact form will take you back to the home page.

![Back to Home button](readme-images/testing/backtohomeValidation.png)

__Result__

Success page is working as expected.

[Back to top](#Testing)

## Testing on different devices

## Responsiveness Testing

* The responsive design tests were carried out manually with [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/) and [Am I Responsive](https://ui.dev/amiresponsive?url=https://deepika-garg.github.io/KakusKitchen/).

|        | Galaxy S5 | iPhone 13| iPad | iPhone 15 pro| Laptop <1200px | Display >1200px |
|--------|-----------|----------|------|--------------|-----------------|----------------|
| Render | pass      | pass     | pass | pass         | pass            | pass           |
| Images | pass      | pass     | pass | pass         | pass            | pass           |
| Links  | pass      | pass     | pass | pass         | pass            | pass           |

Note: On wide display types the contents of the site are restricted in width to 2000px. This helps the UX by not spreading the content too wide on the extra wide screens.

## Browser Compatibility

Kaku's Kitchen site was tested on the following browsers with no visible issues for the user. 
Google Chrome, Safari. Appearance, functionality and responsiveness were consistent throughout for a range of device sizes.

## WebAIM 
All the pages are checked and found no errors.

* [Back to top](#Testing)
* Back to [Readme](./README.md#testing)

