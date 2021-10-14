# Ecstatic Dance Limerick
Welcome! deployed link here: https://amzzy78.github.io/ecstatic_dance-limerick/


Welcome to Ecstatic Dance Limerick!

This website is to be a digital poster for a weekly event based in Limerick, Ireland. The site will feature the event details, guidelines and contact pages in the nav bar and in the footer there will be links to the connect,guidelines,safety and privacy policy. The website features two videos that have no sound but are to portray the essence of an Ecstatic Dance event, where silence is also part of the dance. Images throughout the site to show the diversity and inclusive nature of the event. 
The guideline's page will explain what is required at these events, such as a code of conduct to adhere to, and a connect page with a subscribe form.
A clear nav bar with 3 pages and footer with important links(safety, guidelines, contact us, privacy policy). 

It is a fully responsive site. The primary goal of the website is to promote an Ecstatic Dance event in Limerick city at the Killmurry Arts and Community centre, and be an online presence like a virtual poster with regular updating of information about the weekly event. The site will be targeted toward building a community of locals looking to express themselves through a free-form dance movement. It will be a space for people wishing to connect with a conscious dancing community that is outside the regular dance/club scene in Ireland.

![Responsive Mockup](https://user-images.githubusercontent.com/62209464/137389849-2681302e-6a87-482c-9a57-b0acd2b0fa47.jpg) 
<<<<<<< HEAD



=======
# ![alt text] (../assets/images/logo.png)
>>>>>>> 2f8d199cd15d8d7a5efed059f8a3e02992928c21




# User Experience (UX)
UX
Ideal client
The ideal customer for this event is:
Looking for a weekly dance practice.
Conscious Dancers already in the movement.
Lives in Limerick or passing through. Open for 18-80++ age, all walks of life.
Visitors to this website are searching for:
An Ecstatic Dance Event to attend.

This website is:
Easy to navigate.
Steps the client through easy to understand learnable information.
Gives the client the information they need without overloading them.
Guiding them to the goal of the website - to fill out the contact form.

Client stories
As a new visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.
As a new visitor to the website, I want to view the event details.

As an interested client, I want an easy to fill in contact form, so I can make contact with the event organisers for updated information.
As an interested observer and/or potential client, I want to follow the event on social media, so I can keep up with the latest news.

As a returning visitor to the website, who has already decided to attend the event, I want to see a function to buy tickets for the event.



## First Time Visitor Goals: rewrite to fit this app

(a.) I want to easily access quotes and be inspired.

(b.) I want the site to be easy to navigate and for the content to match the sites subject title.

(c.) I want to seek out professors in the field of psychedelic research that I may not have heard of before so I can do my own research into their studies.

(d.) I want the site to be visually over the top with colours and images to match the subject matter.

(e.) I want to be able to view the site in any reasonable browser so that I can use what I’m accustomed to. 

## Returning Visitor Goals: 

(a.) I want to see new quotes when I return to the site, so I can come back more often and explore new authors and professionals in the field, so that I can educate myself and research further on this exciting and meaningful topic. 

(b.) I want to see new images when I return to the site, so that I may be stimulated visually by my response to them.

-------------------------------
# Features ... example follows

1. Interactive elements.

      (a.) A container that changes the quote and author on the click of a button.

      (b.) A container that changes images on the click of a previous and next button.

2. Responsive on all device sizes. 

3. Links to external websites for further reference. All open in a new tab.

   (a.) Heading/introduction text under the logo is linked to Michael Pollan's book where the excerpt was borrowed.

## Existing Features
  -----------------

  Navigation Bar
# ![Image of navbar] (../assets/images/nav-bar.jpg)

Featured on all three pages, the fully responsive website has a navigation bar which includes links to the text Logo, Event page(home), Guidelines and Connect page(contact us) and is identical in each page to allow for easy of navigation.

# ![Image of navbar] (../assets/images/navbar-mobile.jpg)

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





































