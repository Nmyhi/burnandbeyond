# Burn and Beyond Website

This site has been created to showcase the company's services, projects, webshop and to introduce Burn and Beyond.

![Burn and Beyond Website](assets/images/readme/responsiveness-screenshot.png)

Are you looking for a professional laser technology company?
Do not search any further you have found it. Browse from our services, projects, webshop or contact us to disguss your idea!

Head to the deployed site at [Burn and Beyond](https://nmyhi.github.io/burnandbeyond/).

## Table of Contents
* [User Experience](#User-Experience)
  * [Initial Discussion](#Initial-Discussion)
  * [Demographic](#Demographic)
  * [User Stories](#User-Stories) 
  * [Strategic Trade offs](#Strategic-Trade-offs)
* [Design](#Design)
  * [Colour Scheme](#Colour-Scheme)
  * [Typography](#typography)
  * [Imagery](#Imagery)
  * [Wireframes/Sitemap](#Wireframes/Sitemap)
  * [Features](#Features)
  * [Future Implementations](#Future-Implementations)
  * [Accessibility](#Accessibility)
* [Technologies Used](#Technologies-Used)
  * [Languages Used](#Languages-Used)
  * [Software, Frameworks & Libraries Used](#Software,-Frameworks-&-Libraries-Used)
* [Testing](#Testing)
  * [Validation](#Validation)
  * [Fixed Bugs](#Fixed-Bugs)
  * [Known Issues](#Known-Issues)
  * [Testing User Stories](#Testing-User-Stories)
  * [Lighthouse](#Lighthouse)
    * [Index Page](#Index-Page)
    * [Products Page](#Products-Page)
    * [Reviews Page](#Reviews-Page)
    * [Gallery Page](#Gallery-Page)
    * [Contact Page](#Contact-Page)
  * [Manual Testing](#Manual-Testing)
* [Deployment & Local Development](#Deployment-&-Local-Development)
  * [Deploying to Github Pages](#Deploying-to-Github-Pages)
  * [Local Development](#Local-Development)
    * [How to Fork](#How-to-Fork)
    * [How to Clone](#How-to-Clone)
  * [Credits](#Credits)
    * [Images](#Images)
    * [Acknowledgement](#Acknowledgement)


## User Experience
### Initial Discussion

Burn and Beyond is a small laser cutting and engraving company located in Hatfield (UK). We provide a wide range of services and various artistic items for companies and people. Burn and Beyond want to provide a platform where customers can get faimiar with the company and their products.

### Demographic

With the site being in the edge of London there is a wide range of people who may be interested in their services and products.

* Young professionals
* Business owners
* Light Designers
* Interior designers
* Exterior designers
* All age group of Etsy users

### User Stories

* Client goals
    - To have an online presence.
    - Display a wide range of information on the site like: products, projects, services.
    - Increase traffic to a physical site.
    - Increase interactions with customers via social media and contact form.

* First time Visitor goals
    - Being able to navigate the site easily.
    - Being able to access the menu and pages including contact details.
    - Find out about products and services.

* Returning visitor goals.
    - Find out about new services, products and projects.
    - To be able to access the company's social media sites and the quotation form in case they want to send new requests.

* Frequent visitor goals
    - Using the webshop to click and order products they liked before.

### Strategic Trade offs

| Opportunity/Problem | Importance | Viability/Feasability |
| ----------- | ----------- | ----------- |
| Create an online presence | 5 | 5 |
| Display the range of services and products on the site | 5 | 3 |
| Increase social media interaction | 3 | 4 |
| Provide opportunity to get in touch | 5 | 3 |
| Showcase gallery images | 3 | 5 |
| Total | 21 | Avg 20 |

Above I have listed documented some trade-offs and I will explain the reasoning behind them.

- Online presence
  - This is mandatory and should be achievable given that I am a Front-End Web Developer(the course upto now has given everything I need to achieve this).

- Display the range of services and products on the site
  - Not as important as an online presence, but most definitely still up there. I feel it is also feasible given my skillset, however this company is still quite small in size
   therefore there is not too many things to showcase.

- Social media interaction
  - Again, this is well within my skillset as this could be something as simple as a CTA or footer icons with links to social media.

- Provide opportunity to get in touch
  - In order to get in touch I can provide a company email and a contact form with all the details of the company, however being a front-end developer I feel like this problem is not fully solved yet, because of the lack of back-end knowledge. (the contact form is not fully functioning.)

- Showcase gallery images
  - This is a fully achiveable goal through different photoes I have collected throughtout the company's lifetime.
  
## Design

### Colour Scheme

I wanted to use a colour scheme that wasn't going to distract too much from the text but also make the website pop, and look fun. I felt like the approach is to use various shades of grey with few vibrant colours like a shade of blue, white and silver.

<img src="assets/images/readme/colorpalette.png" width="400" height="300" /> 

### Typography

I decided that I didn't want to overcomplicate the typography, and settled on Roboto and Oxygen with a fallback font of Sans-serif. 

Font weights for Roboto are regular(300) and medium(500) and bold. Regular is used for the text on the pages and medium, bold are used for headings.

I have used [ChatGpt](https://openai.com/blog/chatgpt) for generating content for the about us page.

### Imagery

Being a local lasercutting company I decided to use as many own images as possible, however I used few stock and AI generated photos as well.

- External sources:

- Free stock photo site:

[Unsplash](https://unplash.com "Stock photo site")

- Free Photo generator AI:

[Dall-e-2](https://openai.com/product/dall-e-2 "Photo generator site")

- Free photo editor for formatting my own pictures.

[Gimp](https://www.gimp.org "free photo manipulator software")

- Free open source video editor to transform the index page hero video.

[Shotcut](https://shotcut.org/download/ "free, open source video editor software")

[Shotcut-github-repository](https://github.com/mltframework/shotcut "Github repository")

### Wireframe/sitemap

Burn and Beyond Sitemap

The sitemap allows me to get a higher-level view of how the users will navigate the site. Portfolio and services, webshop are being the priority for returning customers, then gallery, about us, webshop are for the first-time users and contact for frewuent users.

[Sitemap](assets/images/readme/sitemap.png)

[Mobile Wireframe](assets/images/readme/mobile-wireframe.png)

[Tablet wireframe](assets/images/readme/tablet-wireframe.png)

[Desktop wireframe](assets/images/readme/desktop-wireframe.png)

Wireframes were initially created using [Balsamiq](https://balsamiq.com/wireframes/ "Balsamiq Wireframes Software") windows version.

### Features

Burn and Beyond consist 4 pages and a link to a 3rd party webshop page (etsy). (Home About Gallery Webshop Contact).

Features in common accross the site include: 

* A responsive navigation bar across the top of the site. This allows users on different screen sizes to view the same site on any device. On the left hand side of the navbar we have the Burn and Beyond logo and on the right hand side there are navigation links:

  * Burn and Beyond logo: navigates back to the index.html page.

  * Home: navigates back to the index.html page

  * About: navigates to the about.html page which contains more information about the company.

  * Gallery: navigates to the gallery.html page which contains various pictures of different orders and products furthermore pictures of the machine and other accessories.

  * Webshop: navigates to the company's Etsy page.

  * Contact: navigates ot the company's contact form made for questions, quotations and general questions.

There is also a hamburger menu icon included in the navbar which allows for a better user experience on smaller devices.

A footer and a contact section is inluded across all pages of the site with social media icons which open in a new window and the company email, phone and address.

* Home page:
  * A hero video of a laser-cutter machine in work.
  * A welcome text, "Unleash Laser Precision: Welcome to Burn and Beyond!.
  * Our lasercutting services consists the most popular services of the company.
  * The portfolio section consists the most recent projects of the company.
  * The materials section provides information about the different materials we utilize.

* About page:
  * A hero image of a laser-cutter cnc machine downloaded from [Uplash](https://unsplash.com/ "Free stock photo page").
  * A welcome text.
  * Additional information about the company.

* Gallery page:
  * A hero image of a fictional gallery downloaded from [Uplash](https://unsplash.com/ "Free stock photo page").
  * Different images of various products and projects.

* Webshop:
  * A link to the company's Etsy page.

* Contact:
  * A hero image of a business man with a pan and a piece of paper downloaded from [Uplash](https://unsplash.com/ "Free stock photo page").
  * Contact form for questions, quotations and general questions.

### Future Implementations

* Add a fully functional webshop instead of using a 3rd party company for this purpose.
* Develop a more engaging project and portfolio section using Java script.

### Accessibility

Whilst coding the site I have ensured that the site is accesible for all. This is achieve by using:

* Google Dev tools to check contrast of items. 
* Alt tags to describe the images on site.
* Using semantic HTML

## Technologies Used

### Languages Used 

* HTML and CSS
* JavaScript - however this was the Hamburger Dropdown from a youtube video.

### Software, Frameworks & Libraries Used

* [Balsamiq](https://www.balsamiq.com/wireframes "Balsamiq Wireframing Tool") was used to create the wireframes/sitemap for the site.
* [Font Awesome](https://fontawesome.com/icons "Font Awesome 6.2.1 Free Icons") was used for the social media icons in the footer.
* [Chrome Developer Edition](https://developer.chrome.com/docs/devtools "Chrome Developer Tools") this was used to find out specific styling of elements and to identify and resolve problems related to responsiveness and appearance.
* [Google Fonts](https://fonts.google.com/ "Google Fonts") we used the Roboto font and also the Oxygen font.
* [Github](https://github.com/ "Github") was used to store my project in a repository. 
* [Git](https://git-scm.com/ "Git Version Control") was used for Version Control.
* [Google](https://www.google.co.uk "Google Search Engine") was used to research HTML & CSS.
* [Gitpod](https://www.gitpod.io "Gitpod Cloud IDE") the vast majority of my time was spent inside GitPod's VSCode Cloud IDE.
* [Gimp](https://www.gimp.org/ "free photo editor") was used to reduce file size of an image.
* [Shotcut](https://shotcut.org/download/ "free, open source video editor software") was used for formatting the index page's hero video.
* [TinyJPG](https://tinyjpg.com/ "TinyJPG online image compressor software") was used to compress the gallery images to improve performance.

## Testing

I have created the full testing documentation which collects all the information into a test sheet. [Testing documentation](testing.md)

### Validation

I used the W3C Markup Validation Service on all pages of Burn and Beyond. I also validated the my own style.css with the CSS Validator.

* [Index Page HTML](assets/images/readme/burnandbeyond-index-validation.png)
* [About Page HTML](assets/images/readme/burnandbeyon-about-validation.png)
* [Gallery Page HTML](assets/images/readme/burnandbeyond-gallery-validation.png)
* [Contact Page HTML](assets/images/readme/burnandbeyond-contact-validation.png)
* [Stylesheet style.css](assets/images/readme/burnandbeyond-stylesheet-validation.png) 

### Fixed Bugs

* Issue 1:
  * The hero image on the gallery page has got a way too high resolution which caused a long page load time. This issue has been solved by resizing the image.

* Issue 2:
  * The hero video on the index page was loading too slow due to hi resolution video format. This issue has been solved by resizing the video .

### Known Issues

* Issue 1:
  * The hero video on the index page is not playing on iphone devices.
  
  <img src="assets/images/readme/iphone-bug1.jpg" height="640" width="312" alt="iphone hero video issue">

* Issue 2:
  * The materials fixed background picture appears incorrectly on iphone devices.

  <img src="assets/images/readme/iphone-bug2.jpg" height="640" width="312" alt="materials background issue">

These known issues will remain unsolved for know due to the lack of knowledge but in the future I want the site to be fully functioning on every devices.

### Testing User Stories

* First time Visitor goals
  * Being able to navigate the site easily.

  ![Burn and Beyond desktop navbar](assets/images/readme/burnandbeyonddesktopnavbar.png)

  ![Burn and Beyond mobile navbar](assets/images/readme/burnandbeyondmobilenavbar.png)

  * Being able to access the menu and pages including contact details.

    * The menu is accessible from every page to any location on the site.

    * The contact details are visible on every page above the footer.

    ![Burn and Beyond contact us section](assets/images/readme/contactus.png)

  * Find out about products and services.

    - The products are accesible from the menu->Webshop and the main products and services have been showcased on the index page as well.

    ![Services and portfolio screenshot](assets/images/readme/services-and-portfolio-screenshot.png)

* Returning visitor goals.
    * Find out about new services, products and projects.

    I have achieved this goal by updating the new services whenever there is going to be one and the new products are always visible on the webshop which is accessible from the menu.

    ![Burn and Beyond Etsy webshop](assets/images/readme/www.etsy.com_uk_shop_BurnBeyond.png)

    * To be able to access the company's social media sites and the quotation form in case they want to send new requests.

    I achieved this goal by including the social media site addresses in the footer and by having a contact form where customers can send their messages, questions and quotations as well.

    ![Contact form screenshot](assets/images/readme/contactform.png)

    ![Social media screenshot](assets/images/readme/socialmedia.png)

* Frequent visitor goals.

    * Using the webshop to click and order products they liked before.

    ![Ordering from the Etsy Webshop](assets/images/readme/orderingfrometsy.png)

### Lighthouse
 #### Index Page
 The Index page Lighthouse results can be found here [Index Page Lighthouse](assets/images/readme/indexpage-lighthouse.png)
 #### About Page
 The About page Lighthouse results can be found here [About Page Lighthouse](assets/images/readme/aboutpage-lighthouse.png)
 #### Gallery Page
 The Gallery page Lighthouse results can be found here [Gallery Page Lighthouse](assets/images/readme/gallerypage-lighthouse.png)
 #### Contact Page
 The Contact page Lighthouse results can be found here [Contact Page Lighthouse](assets/images/readme/contactpage-lighthouse.png)

### Manual Testing

As I proceeded through the development phase I consistently checked each page to make sure that they were responsive. I achieved this by utilizing Chrome Dev Tools, my own Samsung Galaxy S10 and my friend's Iphone 14 Pro.

* Each link on each page was clicked to verify that it goes to the correct page.
* Social media links were clicked on each page to verify that they opened in new windows and the correct page.
* The Burn adn Beyond logo was clicked to verify that it went back to index.html.

#### Mobile

The navbar for mobile is replicated through the entire site so I have only provided the single screenshot for the mobile navbar and footer.


<img src="assets/images/readme/mobile-menu.png" height="640" width="312" alt="mobile navbar view">

The results for the mobile navbar are as expected.

<img src="assets/images/readme/mobile-footer.png" height="640" width="312" alt="mobile footerview">

The results for the mobile footer are as expected.

<img src="assets/images/readme/index-page-images-mobile.png" height="640" width="312" alt="mobile index page images view">

Screenshot of the index page images on mobile are as expected.

<img src="assets/images/readme/about-page-mobile.png" height="640" width="312" alt="mobile about page view">

Screenshot of the about page on mobile are as expected.

<img src="assets/images/readme/gallery-page-mobile.png" height="640" width="312" alt="mobile gallery page view">

Screenshot of the gallery page on mobile are as expected.

<img src="assets/images/readme/contact-page-mobile.png" height="640" width="312" alt="mobile contact page view">

Screenshot of the contact page on mobile are as expected.

#### Tablet 

Each page was tested on tablet Ipad emulation via Chrome Dev Tools. I have attached a full page screenshot shown here Full Page Index Screenshot Tablet. Each page works as expected.

[Full Page Index Screenshot Tablet](assets/images/readme/index-page-tablet.png).

[Full Page About Screenshot Tablet](assets/images/readme/about-page-tablet.png).

[Full Page Gallery Screenshot Tablet](assets/images/readme/gallery-page-tablet.png).

[Full Page Contact Screenshot Tablet](assets/images/readme/contact-page-tablet.png).

#### Desktop

Using Chrome Developer tools each page was verified to be working correctly.

* [Index Page Screenshot](assets/images/readme/index-page-desktop.png)
* [About Page Screenshot](assets/images/readme/about-page-desktop.png)
* [Gallery Page Screenshot](assets/images/readme/gallery-page-desktop.png)
* [Contact Page Screenshot](assets/images/readme/contact-page-desktop.png)

## Deployment & Local Development

### Deploying to Github Pages

* Choose the repository you want to deploy from the main overview.
* Go to settings by clicking on the icon on the menu.
* In the left navigation, select the "Pages" option.
* Under "Source", choose "Master" branch and click "Save".
* After it's done, you will see a message saying "Your site is ready to be published at (insert url here)".

### Local Development
#### How To Fork

Forking a repository is the process of creating a copy of the original repository. This enables you to make changes without affecting the main repository. 

To do so:-
* go to the GitHub repository you want to copy.
* select the 'Fork' button located in the top right corner, under your profile icon. 
* Once complete, you will now have your own version of the repository to make changes to.

#### How To Clone

To copy a GitHub repository:-
* first navigate to the repository you wish to copy. 
* click on the 'Code' button (which has a download icon) and copy the link provided.
* in the Gitpod Terminal, navigate to the directory where you wish to place the clone. Then, type 'git clone' and paste the link you copied earlier and press enter. This process can also be completed using VSCode.

## Credits

* [Bob's Bakery deployed github repository](https://github.com/boblogdev/bobsbakery/tree/main "Bobs Bakery 1st Milestone project") was used as a template to have a clear idea about the structure of the readme.md file.
* [ChatGpt](https://openai.com/blog/chatgpt "free text generator AI") was used for generating text content for the about us page.
* [Dall-E-2](https://openai.com/dall-e-2 "Dall-E-2 open AI") was used for generating the material section's fixed background picture.
* [Youtube tutorial](https://www.youtube.com/watch?v=OjQP7rPwJyE "Tutorial of creating a 'hamburger' mobile menu") was used to create the mobile menu.
* [Shotcut-github-repository](https://github.com/mltframework/shotcut "Github repository") was used to format the hero video.

### Images

* My own images
* Dall-E-2
* Unsplash

### Acknowledgement

* Chris Quinn - came up with some things I'd never even thought of and was a really good guide.
* Callum Jones - for turning up consistently and offering helpful advice and tips.

