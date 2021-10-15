# Ecstatic Dance Limerick
Welcome! https://amzzy78.github.io/ecstatic_dance-limerick/

Ecstatic Dance Limerick website is to be a digital poster for a weekly event based in Limerick, Ireland. The site will feature the event details, guidelines and contact pages in the nav bar. The footer will have links to the connect, guidelines, safety, and privacy policy pages. The website features two videos that have no sound but are to portray the essence of an Ecstatic Dance event, where silence is also part of the dance. Images throughout the site show the diversity and inclusive nature of the event.
The guideline's page will explain what is required at these events, such as a code of conduct to adhere to, and a connect page with a subscribe form.

It is a fully responsive site. The site will be targeted toward building a community of locals looking to express themselves through the freeform dance movement and will be a space for people wishing to connect with a conscious dancing community that is outside of the regular dance/club scene in Ireland.

![Responsive Mockup](https://user-images.githubusercontent.com/62209464/137389849-2681302e-6a87-482c-9a57-b0acd2b0fa47.jpg) 

# User Experience (UX)

## First Time Visitor Goals: 
(a.) I want to attend a weekly dance practice and find information online as to where the nearest event is.

(b.) I want the site to be easy to navigate and for the content to inform me of the events guidelines.

(c.) I want to see clear instructions on how to get to the event.

(d.) I want to be able to sign up to receive updates on the event.

(e.) I want to be able to view the site in any reasonable browser so that I can use what I’m accustomed to. 

## Returning Visitor Goals: 

(a.) I want to see reqular updates and pictures of the event.

(b.) I want to see new videos of the event.

-------------------------------
# Features
1. Nav bar with links to the sites' main pages: events, guidelines, and connect.
   
2. Footer bar with links to the site's pages: safety, privacy policy, guidelines, and contact us.

3. Image logo in the footer links back to the top of the page.

4. Content relative to the event.

5. Responsive on all device sizes. 

## Existing Features
  -----------------
 ### Navagation Bar
 ![nav](https://user-images.githubusercontent.com/62209464/137390532-26edb4c3-38c0-46e9-b7fe-f5efc5b4d858.jpg)
 The navigation bar links: Event, Guidelines and Connect page.
 Ecstatic Dance Limerick text Logo returns the user to the top of each page currently on.
 

# ![Image of navbar] (../assets/images/navbar-mobile.jpg)

   


This website is:
Easy to navigate.
Steps the client through easy to understand learnable information.

Guiding them to the goal of the website - to fill out the contact form.



Things to add to the site....
As a returning visitor to the website, who has already decided to attend the event, I want to see a function to buy tickets for the event.



......................

 rewrite to fit this app

.........



## Existing Features
  -----------------



Hero section
# ![Image of hero header] (../assets/images/hero-section.jpg)
Contains logo image/ text and tagline.

About section
# ![Image of about section] (../assets/images/about-section-1.jpg)
# ![Image of about section] (../assets/images/about-section-2.jpg)

The about section contains text information about the event, images and a video clip with no audio.

Footer column section
# ![Image of footer column section] (../assets/images/footer-column-section.jpg)
Event details,price,time and day on an image poster. This can be updated regularly with new images. Location with google maps and brief description.

Footer banner section
Subscribe button section.
# ![Image of footer banner section] (../assets/images/footer-banner-section.jpg)


Footer section with links,logo and copyright.
# ![Image of footer section] (../assets/images/footer-copyright-section.jpg)


Images and video throughout the site suitable to the event.

Subscribe button on connect page is linked to a subscribe page when details filled out and sent.
  

## Design
   --------------
   ### Colour palette:
   
   ### Typography:
  
   ### Imagery:
Logo image:
# ![Image of svg logo] (../assets/images/logo1-01.svg)
# ![Image of logo jpg] (../assets/images/geometric_logo.png)


The logo I wanted to use was an SVG and this took alot of trying to write the correct css and finding the correct placement.

SVG Logo image was not loading on desktop running firefox and also I could not set the image exactly where I wanted it.Trouble shooting to fix the problem. Experimented with inline and using svg as an img, as an object, and nothing seemed to fix the problem. Finally settled on using as a background image on the hero section. Then the text-tagline in the hero was out of alignment with the logo and this took some time to get right.

I settled on a jpg of the logo and it works right across all browsers.

The Subscribe button and footer banner and navbar stopped being responsive and troubleshooting to figure out what went gone wrong with my media queries and inputs. This I spent alot of time trying to fix to the point that I cut the whole code out and rebuilt it again. 
   

## Wireframes
   1. Desktop

   ![]()

   2. Mobile

   ![]()

First Mockup
After talking with my tutor on the first draught, there were some issues she spotted that I had not considered when on a mobile phone device.
The initial mockup idea would not translate well on a mobile device as the planned layout for the nav bar I wanted for the Ecstatic Dance Limerick would not translate well when on a mobile. It would be too many words in the header fighting for space. Modified to suit by playing with letter-spacing and margins left/right.

Guidelines:
# ![Image of guidelines page 1] (../assets/images/guidelines-page.jpg)
# ![Image of guidelines page 2] (../assets/images/guidelines-page2.jpg)

Connect:
# ![Image of connect nav,header and hero image] (../assets/images/connect-page.jpg
# ![Image of connect form.subscribe button] (../assets/images/gconnect-form.jpg



## Testing
--------------------------------------
Validating showed up alot of errors in my code and this has taken me alot of time to fix.It was a very good learning tool for my errors.
### HTML tested https://validator.w3.org/
### CSS tested https://jigsaw.w3.org/css-validator/

### Unicorn Revealer:
This dev tool helped in revealing where there was overflow from the image gallery container which was affecting the responsive layout on the iPhone 5/SE. 
### Lighthouse metrics:
Focused on improving the overall performance score by eliminating render-blocking resources which in particular had to do with the external typekit and issues with preloading. Created a second css stylesheet with the Adobe typekit and linked in html. Followed suggestions by Lighthouse to improve score: Added <link rel="preload"> and to css and js file in the header and <script...defer></script> in the body. This enabled the script to be downloaded in parallel to parsing the page, and executed after the page finished parsing. 

### Mobile score:
![]()
### Desktop score:
![]()

## Validator Testing
--------------------------------------
Images Validation:
# ![Image of html] (../assets/images/html-validation.jpg)
# ![Image of css (../assets/images/css-validation.jpg)
# ![Image of guidelines.html (../assets/images/guidelines-validation.jpg)
# ![Image of connect.html (../assets/images/connect-validation.jpg)
# ![Image of subscribe.html (../assets/images/subscribe-validation.jpg)
# ![Image of privacy.html (../assets/images/privacy-validation.jpg)
HTML: 
![]()
CSS:
![]()
JS:
![]()
Color Contrast Accessibility Validator:
![]()
Web Content Accessibility Guidelines (WCAG) 2.1 standards:
![]()

Accessibility:
I did not get to solve all the accessibility issues. Color contrast was an issue and I styled the header and footer darker to fix the color. There is more work to be done to get 100%.
The website evaluator below shows their current analysis.
https://wave.webaim.org/report#/https://amzzy78.github.io/ecstatic_dance-limerick/index.html

# ![Image of color contrast accessibilty (../assets/images/colour-contrast.jpg)

A different site called site improve confirmed it passed at 96% accessibilty.
# ![Image of accessibilty validation (../assets/images/sitemap-accessibility-validation.jpg)
# ![Image of accessibilty validation (../assets/images/site-map-details.jpg)

Plagiarism:
Checking to make sure I credit every source.
https://smallseotools.com/plagiarism-checker/
# ![Image of plagairisim checker (../assets/images/plagairisim-checker.jpg)


### Fixed Bugs
--------------------------------------


### Unfixed Bugs
------------------------------
Hover not active on page currently on. 
Subscribe page needs to be linked to subscribe button as is only linked to the form on Connect page(contact us).

## Features Left to Implement
-------------------------------- 
Animation to the image logo.
Shopping cart for ticket sales.
Hover active on page currently on.
Subscribe page to be linked to button as is only linked to the form on Connect page(contact us).

## Deployment
-------------------------------------
The site was deployed to GitHub pages. 
The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab from the source section drop-down menu, select the Main Branch. Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here -  https://amzzy78.github.io/psychedelic-quotes-generator/

### Credits
-------------------------------------
https://www.ecstaticdancela.com/homepage/
https://ecstaticdance.org/resources/
https://kilmurrycentre.com/about-us/
https://www.facebook.com/events/hayfork-yoga-center/ecstatic-dance/462021097690846/
https://en.wikipedia.org/wiki/Ecstatic_dance/
https://www.facebook.com/ecstaticdancelasvegas/
https://css-tricks.com/snippets/css/a-guide-to-flexbox/
https://en.wikipedia.org/wiki/Gabrielle_Roth/
https://www.w3schools.com/howto/howto_make_a_website.asp


Content
The text for all pages are a mix taken from two sites https://www.ecstaticdancela.com/homepage and https://ecstaticdance.org/media/
Quotes from  Gabrielle Roth https://en.wikipedia.org/wiki/Gabrielle_Roth
Instructions on how to implement form validation on the Connect page was taken from a Code Institute Tutorial.

W3schools for tutorials on all stages and used/modified a mix of code from a template in dreamweaver and an old website I half built.I got a bit confused as was drawing from too many sources and caused alot more work more than I needed to do.
https://www.w3schools.com/howto/howto_make_a_website.asp

The social media icons in the footer banner were taken from Font Awesome.
Tutorials on https://css-tricks.com/snippets/css/a-guide-to-flexbox/ for flexbox build.
FreeCode Academy for flexbox, svg and responsive media queries https://www.freecodecamp.org/news/tag/svg/



Media
The photos and videos used on all pages are from https://www.pexels.com/collections/dance-xlb5itr/

## Technologies 
-------------------





































