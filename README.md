# GJMR Quartet

![Am I Responsive Image](docs/images/am-i-responsive-image.png)

GJMR Quartet is a fictional classical string quartet that plays around the world in a variety of styles. They have expertise in performaing for weddings, high-profile public performances, intimate private evetns, and delivering top-class masterclasses to up-and-coming quartets

The main purpose of this site is to increase bookings for weddings, private evetns and masterclassess for both people who have heard of the quartet before and new listeners to the quartet. An important function of the website therefore is to showcase why someone should be booking us, which has been achieved through both audio performances of the quartet playing and a quick overview of the recent big public performances given, which shows the high level they are able to produce.

Visit the deployed website [here](https://greggy1234.github.io/GJMR-Quartet/)

## Table of Contents

1. [UX & Design](#ux--design)
    1. [Website Objectives](#website-objectives)
    2. [User Stories](#user-stories)
    3. [Typography](#typography)
    4. [Colour Scheme](#colour-scheme)
    5. [Wireframes](#wireframes)
2. [Features](#features)
    1. [General](#general)
    2. [Home Page](#home-page)
    3. [Discover Our Sound Page](#discover-our-sound-page)
    4. [Calendar Page](#calendar-page)
    5. [Book Now Page](#book-now-page)
    6. [Success Page](#success-page)
    7. [Future Features & Pages](#future-features--pages)
3. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Libraries](#frameworks--libraries)
    3. [Other Programs](#other-programs)
4. [Testing](#testing)
    1. [Code Validation](#code-validation)
    2. [User Story Testing](#user-story-testing)
    3. [Common Element Testing](#common-elements-testing)
    4. [Lighthouse Testing](#lighthouse-testing)
    5. [Browser & Device Testing](#browser--device-testing)
5. [Final Website](#final-website)
6. [Deployment](#deployment)
7. [Development Lifecycle](#development-lifecycle)
8. [Credits](#credits)
    1. [Content](#content)
    2. [Media](#media)
    3. [Code](#code)

***

## UX & Design

### Website Objectives

* Portray the feeling of a classical music site in both colour scheme and typography. The style is traditional and relaxing

* Clearly present the services offered - playing for weddings and private events and devliering masterclasses

* Clearly show the public concerts that will be played in the future

* Easily allow users to book the quartet's services

* Allow users to listen to the quartet's performances

### User Stories
The aim of this site is to target 4 individual types of users all looking to interact with the GJMR Quartet. Below are the 4 types of users and their user stories.
1. Users looking to hire a string quartet for their wedding
- I want to see this quartet performs at weddings so I can book them
- I want to hear their sound so I can see if they would be relevant for my wedding
- I want to see reviews of people who have hired this quartet for their wedding
- I want an easy way to book my interest in them performing at my wedding

2. Users looking to hire a string quartet for my private function
- I want to see this quartet is available to hire for my private function
- I want to hear a selection of their repetoire to see if they would be relevant for my private function
- I want to see any recent highlight concerts to understand if they are professional enough for my private function
- I want to see reviews of people who hired them for their private function to show their professionalism
- I want an easy way to book my interest

3. Users looking for more information on the public concerts this quartet perform
- I want to hear their repetoire to see if I want to spend money on seeing them in a concert hall
- I want to know their upcoming concerts so I can review if I have availability to see them in my country
- I want to see reviews to see if the concerts are worth seeing live

4. Users looking for a masterclass
- I want to see their most recent and upcoming concerts to see if they are at a level where a masterclass would be worth spending money for
- I want to hear their sound to know if I agree with their musical stylings
- I want an easy way to book my interest

Combining these user stories together, this is the definite list of user stories this website aims to cater for, also including user stories applying to all types of users:
- I want to see this quartet is available to hire for my event (wedding/private function/masterclass)
- I want to hear their sound so I can see if they would be relevant for my event
- I want to hear their sound so I can see if I want to spend money on seeing them live
- I want to see reviews of people who have hired this quartet for their event
- I want to see reviews of the quartet playing live
- I want an easy way to see the quartet's upcoming public performances
- I want an easy way to book my interest in using the quartet's services
- I want to view the website on all devices and browsers easily
- I want the website to be responsive and look good on any device
- I want to navigate around the site easily
- I want to find the quartet's social media pages

### Typography
The header font used for this website is Playfair Display with font style of Italics being added to it thoughout the site. This helps contribute to the elegance and traditional feel of the website.

The paragraph font used is Quattrocento, again adding to the traditional feel of the website while still being an easily readable font. 

The fallback generic-family font for both of these is Serif to continue the traditional feel even if the preferred fonts don't load correctly.

### Colour Scheme
![Colour palette image](docs/images/colour-palette.png)

The main background colour used is the light pink (#EEDADA). A gradient was added on each page to white at the top adn from white to light pink at the bottom. This added to the elegant feel of the website.

The primary font colour used is the dark green (#585A47) which contrasts wel with the light pink and the white background while keeping wiht the traditional feel.

The three highlight colours are the dark purple/grey (#83757E) acting as a dark highlight, the lilac (#BDAFC3) and the light green (#939883) acting as the light highlits. The dark highlight was used as the background to the Nav bar to ensure it clearly stands out throughout the website and also the border and divider colours, and all 3 highlights are used for throughout for hover effects.

### Wireframes
[Balsamiq](https://balsamiq.com/) was the app used to create the wireframes. These were create before production of the website began so there are some changes between the wireframes and the final product, including a newsletter sign up form in the footer, more audio files on the Discover Our Sound page, and a constnatly scrolling review section.

Page | Desktop Version | Tablet Version | Mobile Version
--- | --- | --- | ---
Index | ![Desktop index wireframe image](docs/wireframes/index-desktop.png) | ![Tablet index wireframe image](docs/wireframes/index-tablet.png) | ![Mobile index wireframe image](docs/wireframes/index-mobile.png)
Discover Our Sound | ![Desktop discover sound wireframe image](docs/wireframes/ds-desktop.png) | ![Tablet discover sound wireframe image](docs/wireframes/ds-tablet.png) | ![Mobile discover sound wireframe image](docs/wireframes/ds-phone.png)
Calendar | ![Desktop calendar wireframe image](docs/wireframes/calendar-desktop.png) | ![Tablet calendar wireframe image](docs/wireframes/calendar-tablet.png) | ![Mobile calendar wireframe image](docs/wireframes/calendar-mobile.png)
Booking | ![Desktop booking wireframe image](docs/wireframes/booking-desktop.png) | ![Tablet booking wireframe image](docs/wireframes/booking-tablet.png) | ![Mobile booking wireframe image](docs/wireframes/booking-mobile.png)
Success | ![Desktop success wireframe image](docs/wireframes/success-desktop.png) | ![Tablet success wireframe image](docs/wireframes/success-tablet.png) | ![Mobile success wireframe image](docs/wireframes/success-phone.png)


[Back to top ⇧](#gjmr-quartet)

## Features

### General

* Responsive design is applied throughout the website so all the information is displayed correctly no matter the screen size or device type

* The colour scheme and typography remains consistent across all pages so the webste feels unified

**Buttons**

![Button Image](docs/images/button-style.png)

* This button style is the only button style used so users know easily that it is a clickable button

* The buttons have a hover effect to ensure users know when something can be clicked on

**Nav Bar**
![Nav Bar Image](docs/images/nav-bar-style.png)

* The Nav Bar is sticky throughout all pages so the user can easily navigate the website

* The page the user is on is highlighted on the Nav Bar, unless they are on the Booking or Success page, so the user can easily see exactly where they are in the site

**Header**
![Header Image with Carousel](docs/images/header-style.png)
    
* Two headers are used in this site. The header with a carousel of images are on pages where people will be spending more time so a more complex header makes the pages more involved. 
    
* The simple header with just the logo and title of the page represent simpler pages at the end of a user's journey

* The logo in the header acts as alink back to the Home Page

* The Nav Bar is consistent and sticky across all pages, and the links light up on hover to allow users to know where they are clicking, including on the dropdown for the Discover Our Sound Page.

**Footer**
![Footer Image](docs/images/footer-style.png)

* The footer is kept simple with only some get in touch links and the quartet#s social pages, encompassed in an elegant border. This ensures the bottom of the page is not too busy while still providing some extra information.

### Home Page

**Services Section**
![Services Section Image](docs/images/services-style.png)

* This portrays the four services offered in a clear manner and when the Lern More button is clicked on, a modal appears with more info. The modal allows for an easy change of information in the future as well.

**Reviews Section**
![Reviews Section Image](docs/images/reviews-style.png)

* Shows glowing reviews of people who recommend the quartet to influence people's decision to choose them

**Recent Landmark Concerts Section**
![Recent Concerts Section Image](docs/images/recent-concerts-style.png)

* A quick review of large scale concerts recently given, giving the quartet a professional feel 

### Discover Our Sound Page
![Excerpts Image](docs/images/discover-our-sound-style.png)

* This allows users to listen to varying pieces within the quartets main styles to influence their decision to choose the quaret

### Calendar Page
![Calendar Page Image](docs/images/calendar-style.png)

* A clear way for users who follow the quartet to see where they are playing next and what genre of music will be played. This centralises information and keeps users coming back to the site as they know the information they need will be there

### Book Now Page
![Booking Form Image](docs/images/booking-style.png)

* This form allows users to book the services they want straight from the website in a clear and easy way

![Pricing Table Image](docs/images/pricing-style.png)

* A table to inform users on what the prices for the requested service could be, keeping their expectations in check

### Success Page
![Success Image](docs/images/success-style.png)

* A clear message to inform the user that their details have been submitted

### Future Features & Pages
There are number of features in the future that can add to this website to improve the utility. These include:

1. A link to sign up to the newsletter containing news about the quartet and more behind the scenes commentary, which helps build relationships

2. Links to book tickets on the venue website on the calendar page to improve the user journey

3. A media/news/PR page where mentions of the quartet can be displayed. External links is also good for SEO so that would be an added benefit

4. More media (both audio and images) to promote the quartet

5. A gallery page to utilise the increased amount of images

[Back to top ⇧](#gjmr-quartet)

## Technologies Used

### Languages

* HTML
* CSS

### Frameworks & Libraries

* [Google Fonts](https://fonts.google.com/)
    - Google Fonts was used to import the fonts Quattrocento & Playfair Display which were used as for the site's typography.

* [Font Awesome](https://fontawesome.com/)
     - Font Awesome loaded on all pages for icon use, which can be seen in the footer on every page and the review section on the Home Page

* [Bootstrap](https://getbootstrap.com/)
     - The Bootstrap toolkip was used throughout to ensure consistent responsive design and allow for ease styling on different devices

### Other Programs

* [Visual Studio Code](https://code.visualstudio.com/)
    - This was used to write the code of the website.

* [TinyPNG](https://tinypng.com/)
    - Files were compressed sing this site to ensure the lowest possible file size while still ensuring quality which helps keep the website running faster.

* [Cloud Convert](https://cloudconvert.com/)
    - This was used to turn files to the WEBP format.

* [GitHub](https://github.com/)
     - GitHub was used to house the code and deploy the website.

* [Balsamiq](https://balsamiq.com/)
     - Wireframes created at the beginning of the project were designed on Balsamiq.

* [favicon.io](https://favicon.io/)
     - This was used to create the colour palette for the website.

* [Coolors](https://coolors.co/)
     - This was used to create the colour palette for the website.

* [Am I Responsive](https://ui.dev/amiresponsive?url=https://greggy1234.github.io/GJMR-Quartet/)
     - Used to check mockup of website and for the image at the top fo this Read Me.

* [Chrome DevTools](https://developer.chrome.com/docs/devtools/)
    - Throughout the building of the website, Chrome DevTools was used to solve any problems I had with my HTML or CSS

* [W3C Markup Validator](https://validator.w3.org/)
    - To test the HTML code, this was used.

* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
    - To test the CSS code, this was used.
   
[Back to top ⇧](#gjmr-quartet)

## Testing

### Code Validation

* **CSS**
![CSS validated image](docs/images/css-validated.png)

   - CSS has been checked and no errors were found
   - Warnings were brought up, but these are not errors in the code

![CSS warnings image](docs/images/css-warning-image.png)

* **HTML**

Page | Validator Confirmation
--- | ---
Index | ![Index page validation](docs/images/index-html-validation.png)
Discover Our Sound | ![Discover Our Sound page validation](docs/images/discover-our-sound-html-validation.png)
Calendar | ![Calendar page validation](docs/images/calendar-html-validation.png)
Booking | ![Booking page validation](docs/images/booking-html-validation.png)
Success | ![Success page validation](docs/images/success-html-validation.png)

### User Story Testing

User Story | Feature to Address User Story | Evidence
--- | --- | ---
I want to see this quartet is available to hire for my event (wedding/private function/masterclass) | The services section on the Home Page clearly shows the services offered so there is no confusion as to which services the quartet offers | ![Services Section Image](docs/images/services-style.png)
I want to hear their sound so I can see if they would be relevant for my event | There is a whole page dedicated to showing off the quartet's sound so people can easily listen and decide if the quartet is for them | ![Excerpts Image](docs/images/discover-our-sound-style.png)
I want to hear their sound so I can see if I want to spend money on seeing them live | There is a whole page dedicated to showing off the quartet's sound so people can easily listen and decide if the quartet is for them | ![Excerpts Image](docs/images/discover-our-sound-style.png)
I want to see reviews of people who have hired this quartet for their event | The review section on the Home Page has a review of someone who used the quartet for their wedding | ![Reviews Section Image](docs/images/reviews-style.png)
I want to see reviews of the quartet playing live | Three of the reviews on the Home Page contain reviews from preofessional publications | ![Reviews Section Image](docs/images/reviews-style.png)
I want an easy way to see the quartet's upcoming public performances | There is a whole page dedicated to upcoming public performances of the quartet | ![Calendar Page Image](docs/images/calendar-style.png)
I want an easy way to book my interest in using the quartet's services | The booking form on the booking page is simple and effective, allowing for user's to easily book their interest | ![Booking Form Image](docs/images/booking-style.png)
I want to view the website on all devices and browsers easily | The Browser and Device testing section show that the website can be viewed on a variety of devices and browsers without problem | [Browser & Device Testing](#browser--device-testing)
I want the website to be responsive and look good on any device | The Final Website section shows the website on each page across different screens, showing the responsiveness of the website | [Final Website](#final-website)
I want to navigate around the site easily | The Nav Bar, which is sticky across every page, allows the user to access every page easily. The only page that cannot be accessed is the Success page, and that can be accessed when the form is filled in correctly | ![Nav Bar Image](docs/images/nav-bar-style.png)
I want to find the quartet's social media pages | The Footer contains all the link sto the quartet's social media pages | ![Footer Image](docs/images/footer-style.png)

### Common Elements Testing

**General**

* General

Feature | Outcome | Pass/Fail
--- | --- | ---
Buttons | Hover effect is working correctly and links are directed to the correct page for all buttons throughout the website | Pass
Navigation Bar | Hover effect is working correctly, links are directed to the correct page and it is sticky throughout the website | Pass
Footer | Contact links open the correct application and social links open in a new tab | Pass
Carousel | Scroll works as expected and the images resize correctly | Pass

* Home Page

Feature | Outcome | Pass/Fail
--- | --- | ---
Services Boxes | The four boxes keep equal sizing no matter the screen size and all buttons link to the correct modal which opens up on top of the content | Pass
Review Section | All reviews line up correctly no matter the screen size | Pass
Recent Landmark Concert Section | All cards line up correctly no matter the screen size | Pass

* Discover Our Sound Page

Feature | Outcome | Pass/Fail
--- | --- | ---
Links to different sections | The three links go to the correct part of the page and the nav bar does not cover the section heading | Pass
Audio Files | All audio files play correctly and the user can pause, navigate, doedownloadnaload and adjust the playback speed of the audio file | Pass

* Calendar Page

Feature | Outcome | Pass/Fail
--- | --- | ---
Concert Cards | All cards line up correctly no matter the screen size | Pass

* Booking Page

Feature | Outcome | Pass/Fail
--- | --- | ---
Booking Form | All fields need to be filled correctly before submission is accepted, and the fields resize correctly based on screen size | Pass
Booking Form | The informataion is presented correctly no matter the screen size | Pass

### Lighthouse Testing

* Lighthouse testing was used to review performance and accessibility of the pages

Page | Lighthouse Result
--- | ---
Index | ![Index page lighthouse report](docs/images/lighthouse-index.png)
Discover Our Sound | ![Discover Our Sound page lighthouse report](docs/images/lighthouse-discover-sound.png)
Calendar | ![Calendar page lighthouse report](docs/images/lighthouse-calendar.png)
Booking | ![Booking page lighthouse report](docs/images/lighthouse-booking.png)
Success | ![Success page lighthouse report](docs/images/lighthouse-success.png)

### Browser & Device Testing

 **Browser Testing**

Browser | Outcome | Pass/Fail  
--- | --- | ---
Google Chrome | No appearance, responsiveness or functionality issues | Pass
Safari | No appearance, responsiveness or functionality issues | Pass
Mozilla Firefox |  The horizontal lines on the Discover Our Sound page were not appearing center. I contained them within a div with flex properties and justified the content center to fix this.<br><br>Now there are no appearance, responsiveness or functionality issues | Pass
Microsoft Edge | No appearance, responsiveness or functionality issues | Pass

 **Device Testing**

Device | Outcome | Pass/Fail
--- | --- | ---
iPhone SE | No appearance, responsiveness or functionality issues | Pass
iPhone XR | No appearance, responsiveness or functionality issues | Pass
iPhone 12 Pro | No appearance, responsiveness or functionality issues | Pass
iPhone 14 Pro Max | No appearance, responsiveness or functionality issues | Pass
Samsung Galaxy S20 Ultra | No appearance, responsiveness or functionality issues | Pass
iPad Pro| No appearance, responsiveness or functionality issues | Pass
Surface Pro 7 | No appearance, responsiveness or functionality issues | Pass
HP Laptop | No appearance, responsiveness or functionality issues | Pass


[Back to top ⇧](#gjmr-quartet)

## Final Website

Page | Desktop Layout |Tablet Layout | Mobile Layout
--- | --- | --- | ---
Index | ![Index page Desktop](docs/full-pages/desktop-full-index.png) | ![Index Page Tablet](docs/full-pages/tablet-full-index.png) | ![Index page Mobile](docs/full-pages/mobile-full-index.png)
Discover Our Sound | ![Discover our Sound page Desktop](docs/full-pages/desktop-full-discover-our-sound.png) | ![Discover our Sound Page Tablet](docs/full-pages/tablet-full-discover-our-sound.png) | ![Discover our Sound page Mobile](docs/full-pages/mobile-full-discover-our-sound.png)
Calendar | ![Calendar page Desktop](docs/full-pages/desktop-full-calendar.png) | ![Calendar Page Tablet](docs/full-pages/tablet-full-calendar.png) | ![Calendar page Mobile](docs/full-pages/mobile-full-calendar.png)
Booking | ![Booking page Desktop](docs/full-pages/desktop-full-booking.png) | ![Booking Page Tablet](docs/full-pages/tablet-full-booking.png) | ![Booking page Mobile](docs/full-pages/mobile-full-booking.png)
Success | ![Success page Desktop](docs/full-pages/desktop-full-success.png) | ![Success Page Tablet](docs/full-pages/tablet-full-success.png) | ![Success page Mobile](docs/full-pages/mobile-full-success.png)


[Back to top ⇧](#gjmr-quartet)


## Deployment
This project was developed using the VisualStudio Code IDE, commited to git and pushed to GitHub using the in-built function within the IDE

To deploy this page to GitHub Pages from it's [GitHub Repository](https://github.com/Greggy1234/GJMR-Quartet), the following steps were taken:
1. Log into GitHub
2. From the list of repositories, select **GJMR-Quartet**
3. Open settings from the menu options available
4. Select **Page** under the **Code and automation** option on the right side menu
5. Select **Master Branch**, after which the site is automatically deployed
6. Find the link either within the pages section of settings, or on the **Code** section of the repository on the right side options.

### How to run this project locally
To clone this project from GitHub to make further changes:
1. Go to the the [GitHub Repository](https://github.com/Greggy1234/GJMR-Quartet)
2. Click the green **Code** button
3. Copy the HTTPS url on the dropdown
4. Open your local IDE and select Git Bash
5. Navigate to the directory you want the project to be clones in (**must be an empty folder**)
6. Type `git clone` followed by the url copied in step 3 and press enter

[Back to top ⇧](#gjmr-quartet)

## Development Lifecycle

**Sprint 1: Planning & Design (approx. 12 - 27 May 2025)**

* The start of the project was spent deciding exactly what the website would represent. I knew I wanted to focus on classical music as I was a professionakl pianist int he past so I knew the requirements for a music website, but i felt going the direction of a quartet opened up more avenues for services, specifically weddings.

* Once that was decided, I spent a week putting together the wireframes for the website across all 3 device types on Balsamiq. While I originally intended for a larger Discover Our Sound page with all genres of Classical music displayed, I opted against that so the page was more streamlined and less overwhelming in the final product. Further elements that I decided against while building include a horizontal scrolling review section on the Home Page and a newsletter sign up form in the footer as those were outside my skillset at the current time. I also added in a pricing table to the Booking page as users testing my site thought it would be good to get an understanding of price for the services.

* After some testing, I decided that four fonts were suitable for this website. They were Quattrocento, Quattrocento Sans, Courgette and PLayfair Display. I opted against Quattrocento Sans as this was less elevated than Quattrocento, and Courgette as I found through feedback that this was too hard to read.

**Sprint 2: Development Part 1 (approx. 28 May - 18 June 2025)**

* This sprint was dedicated to create the structure of the pages throughout the website. No major bugs were encountered during this phase which is to be expected as I was focused on mainly putting together the base HTML structure for all the pages and not the minutiae of element placement.

* No road blocks were found during this sprint as all the structural elements came togther as I have originally planned them 

**Sprint 3: Development Part 2 (approx. 19 June - 9 July 2025)**

* This sprint was dedicated to filling in the main structural elements of the website, and while there were no major bugs encountered, many smaller ones kept appearing as the coding continued.

* The Nav Bar was easy to create as a base design and make sticky, but the highlights on the Discover Our Sound drop-down were not rounded like the edges of the drop-down box so that had to be corrected, and the BOOK NOW button took a few attempts to look right.

* The footer was a simple design, although on larger screen sizes, when the contact us and socail links appear side by side, it took longer than expected to get the desired layout using Bootstrap columns. On the Services page as well, as the page was so small, I had to force the footer to the bottom of the page and offset the extra 56px added by the Nav Bar so that the display was correct.

* The header with carousel, appearing on the Home Page and the Discover Our Sound page, kepy changing in height as the images that were used were all different heights so a max-height property had to be set at every screen class to ensure there were not increases in height when a user clicks through the carousel.

* Home Page:
    - The services section was simpler than I thought it would be, and came together after only slight corrections to the gap between the header and the button to the modal.
    - The reviews section presented more challenge. After I wrote in the copy, the bottom of each of the four seperate reviews were not lined up, so restructuing of the CSS was required to make sure the star reviews and name appeared in a line, increasing the readability of the site.
    - The cards in the recent landmark concert section were completely unaligned when I added the images and copy into them. To fix this, I set a max height for each of the screen sizes based on Bootstrap breakpoints, and forced the image to be only 50%.

* Discover Our Sound Page:
    - The links to the various sections at the top of the page took experimentation to find the best way to add them while still appearing in line with the style of the website, but the rest of the page was built with minimal problems, although a max height was needed on larger screens to ensure the layout was correct.

* Calendar Page:
    - There were no problems during this sprint with this page, just the same issue as with the recent landmark concert section, so it was a quick fix.

* Booking Page:
    - The booking form and pricing table were built without issues, but the double border around the form, which was also used in the reviews section, required me to overide Bootstrap code to position the form lavel correctly.

* Success Page:
    - There were no major or minor bugs when building this page.

**Sprint 4: Testing & Deployment (approx. 10 July - 31 July 2025)**

* Again, there were no majot bus found throughout this sprint. The focus here was on testing the website across all types of devices and browsers, and validating the code. The following minor bugs and further fixes were found:
    - The purple divider on the Discover Our Sound and Calendar page was not centred on the Firefox browser. To fix this, I wrapped a div element round the hr element, added flex and justified the hr element.
    - The services section on the Home Page when viewed on an iPhone SE looked cramped with minimal space between the H3 and button elements. THis was fixed by decreasing the gap between the two aforementioned elements.

* Much of the code was validated without further changes, but three minor changes were needed:
    - The butons were originally written as an anchor element wrapping round a button element. I added the button stylings to the anchor tag to replicate the correct look and feel, which then removed the error.
    - The telephone number int he footer was linked with spaces, so I removed the spaces to prevent the error.
    - The modal popups in the services section on the Home Page originlly had the H1 element for the title, and when changed to H3, there was no more error.

* As I deployed this website as soon as the project was created, there no problems with the deployment of this project.

## Credits

### Content

- All content was written by the developer

### Media

 **Images**

Page | File Name | Credit Link
--- | --- | ---
Home Page/Discover Our Sound (Header) | header-image-1 | [Pixabay](https://pixabay.com/illustrations/quartet-string-fiddle-viola-cello-255071/)
Home Page/Discover Our Sound (Header) | header-image-2 | [Pixabay](https://pixabay.com/photos/violin-violinist-music-classic-374096/)
Home Page/Discover Our Sound (Header) | header-image-3-version-2 | [Pixabay](https://pixabay.com/photos/sheet-music-manuscript-old-time-944796/)
Home Page/Discover Our Sound (Header) | header-image-4 | [Pixabay](https://pixabay.com/photos/cello-musical-instruments-4480885/)
Home Page | index-services-box-1-wedding | [Unsplash](https://unsplash.com/photos/man-and-woman-holding-hands-focus-photo-464ps_nOflw)
Home Page | index-services-box-2-private | [Unsplash](https://unsplash.com/photos/a-table-set-up-for-a-wedding-reception-Voqts1b2S1Y)
Home Page | index-services-box-3-public | [Unsplash](https://unsplash.com/photos/a-large-auditorium-filled-with-lots-of-people-ZeNciLLPQas)
Home Page | index-services-box-4-masterclass | [Pexels](https://www.pexels.com/photo/pile-of-music-sheets-4861059/)
Home Page | index-recent-concerts-box-1-wigmore | [Tripadvisor](https://www.tripadvisor.co.uk/Attraction_Review-g186338-d522999-Reviews-Wigmore_Hall-London_England.html)
Home Page | index-recent-concerts-box-2-philarmonie | [Philharmonie de Paris](https://philharmoniedeparis.fr/en/discover/philharmonie)
Home Page | index-recent-concerts-box-3-laeiszhalle | [Elbphilharmonie ](https://www.elbphilharmonie.de/en/laeiszhalle-hire#grand-hall)
Home Page | index-recent-concerts-box-4-sinpoli | [Auditorium](https://www.auditorium.com/en/auditorium-rooms-and-spaces/)
Discover Our Sound | discover-wedding-excerpts-pic | [Unsplash](https://unsplash.com/photos/a-courtyard-with-white-flowers-aRQrz0fclB8)
Discover Our Sound | discover-romantic-excerpts-pic | [Unsplash](https://unsplash.com/photos/white-music-sheet-2zHGVCrdxHw)
Discover Our Sound | discover-modern-excerpts-pic | [Pexels](https://www.pexels.com/photo/music-notes-934067/)
Calendar | calendar-box-1-violin | [Unsplash](https://unsplash.com/photos/brown-violin-with-bow-in-black-background-uqKyeMaaAOQ)
Calendar | calendar-box-2-violin | [Unsplash](https://unsplash.com/photos/brown-violin-on-white-paper-TeqVvTX8qKA)
Calendar | calendar-box-3-viola | [Freepik](https://www.freepik.com/free-photo/violin-bow-white-background_4291673.htm#fromView=keyword&page=1&position=2&uuid=a37f71af-5a40-43af-b1aa-923a8dde6a87&query=Viola)
Calendar | calendar-box-4-cello | [Unsplash](https://unsplash.com/photos/brown-violin-lDKmtwvrZZs)

 **Audio**

Page | File Name | Credit Link
--- | --- | ---
Discover Our Sound | discover-wedding-1-pachelbel | [IMSLP](https://imslp.org/wiki/Canon_and_Gigue_in_D_major,_P.37_(Pachelbel,_Johann))
Discover Our Sound | discover-wedding-2-tchaikovsky | [IMSLP](https://imslp.org/wiki/String_Quartet_No.1%2C_Op.11_(Tchaikovsky%2C_Pyotr))
Discover Our Sound | discover-wedding-3-kreisler | [Musescore](https://musescore.com/user/35644221/scores/7011303?srsltid=AfmBOoqJWkHqxsOQiKtb8pvJAz4irC9a82eQYFg2oKPyZBrKM5WHgPlC)
Discover Our Sound | discover-wedding-4-beethoven | [MUSOPEN](https://musopen.org/music/2620-string-quartet-no-13-in-b-flat-major-op-130/#google_vignette)
Discover Our Sound | discover-romantic-1-schubert | [IMSLP](https://imslp.org/wiki/String_Quartet_in_D_minor,_D.810_(Schubert,_Franz))
Discover Our Sound | discover-romantic-2-borodin | [IMSLP](https://imslp.org/wiki/String_Quartet_No.2_(Borodin%2C_Aleksandr))
Discover Our Sound | discover-romantic-3-mendelssohn | [IMSLP](https://imslp.org/wiki/String_Quartet_No.6%2C_Op.80_(Mendelssohn%2C_Felix))
Discover Our Sound | discover-romantic-4-dvorak | [IMSLP](https://imslp.org/wiki/String_Quartet_No.12%2C_Op.96_(Dvo%C5%99%C3%A1k%2C_Anton%C3%ADn))
Discover Our Sound | discover-modern-1-shostakovich | [Soundcloud](https://soundcloud.com/outhere-music/string-quartet-no-8-in-c-minor)
Discover Our Sound | discover-modern-2-glass | [YouTube](https://www.youtube.com/watch?v=HiXoFhq5qiU)
Discover Our Sound | discover-modern-3-bartok | [IMSLP](https://imslp.org/wiki/String_Quartet_No.2%2C_Sz.67_(Bart%C3%B3k%2C_B%C3%A9la))
Discover Our Sound | discover-modern-4-paart | [YouTube](https://www.youtube.com/watch?v=rNDr3F-YaBM)

### Code

- On the Index page, for the Services section boxes, the code for the slightly transparent overlay on a picture was taken from [dev.co](https://dev.to/selbekk/how-to-overlay-your-background-images-59le)

- [Stack Overflow](https://stackoverflow.com/) and [W3Schools](https://www.w3schools.com/) were consulted throughout the project to check the code was correctly implemented


[Back to top ⇧](#gjmr-quartet)