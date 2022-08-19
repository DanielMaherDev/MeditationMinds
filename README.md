# MeditationMinds
# Daniel Maher's Porfolio 1 Website

![](assets/readmeimages/amiresponsive.png)


Website designed to provide end users with information on Meditation

## **Site Overview**
Meditation minds in a website designed to provide information to end users to help them in bringing meditation into their life.It is designed to be intuitive, and to evoke a sense of calmness in the end user.
<!-- screenshot of Homepage responsiveness to go here-->
## Table of contents:
1. [**Site Overview**](#site-overview)

# Readme:
## 1. Purpose of the project
This project aims to create a front-end site to present useful information to users regarding out meditation community. This has been done using the web design I have learned within Code Institute to date. 

This site aims to provide information regarding our community, including some self-guided meditation resources & information regarding our communal meditations.

Homepage: https://danielmaherdev.github.io/MeditationMinds/

## 2. User goals

The goal of both new and returning users is to find information and resources regarding meditation. 

Resources are provided on this site to fulfill this need, and a contact us page has also been provided if any questions are left unanswered.

### Navigation Bar
The navigation bar, like the rest of this site, was designed mobile-first. 
It appears at the top of all pages within this site, and as a burger menu on mobile devices.
This section will allow the visiting user to easily navigate from page to page across all devices without reverting to the previous page via the 'back' button.
The navigation has been implemented with a hover effect on desktop when hovering over a link.

#### Desktop
![](assets/readmeimages/nav-desktop.png)

#### Mobile
![](assets/readmeimages/nav-mobile.png)


### The hero image
The homepage (index.html) contains a large hero image at the top of the page, along with the title of the website and a short description.
The text overlay on desktop has a white semi-opaque background on desktop to allow for sufficient contrast and moves on smaller screen sizes for compatibility.

#### Desktop
![](assets/readmeimages/hero-desktop.png)

#### Mobile
![](assets/readmeimages/hero-mobile.png)

### About Us Section
Further down from the hero image we have the about us section. This is to provide the user with basic information about the community.


#### Desktop
![](assets/readmeimages/about-us-desktop.png)

#### Mobile
![](assets/readmeimages/about-us-mobile.png)

### Self Guided Section
Below the about us section, you will find the self-guided section. This section provides 3 blocks of information regarding our self guided meditations. Each section contains a button which redirects to a specific anchor link on the self-guided meditation page.
Each block also includes a hover effect on desktop screens, which should produce an animation revelant to the exercise mentioned. These animations were made purely with HTML & CSS.

#### Desktop
![](assets/readmeimages/self-guided-section-desktop.png)

#### Mobile
![](assets/readmeimages/self-guided-section-mobile.png)


### Communal Meditation Section

Below the self-guided meditation section is a section regarding our communal meditation. This is also referenced in the navigation bar.

This section provides information on our group meditations, occuring twice monthly. Similar to the Self-Guided section, this section is set to show each block side by side on desktop and on top of one another on mobile.
![](assets/readmeimages/communal-desktop.png)

### The Footer
The footer section includes links to the relevant social media sites for our meditation group. As there is no actual social media accounts setup, these links will simply navigate to the homepage of the social media site in question.
These links will open in a new tab.
The footer appears on all pages of the website.

![](assets/readmeimages/footer.png)

### Self Guided Page

This page provides information on the 3 different self-guided blocks on the homepage. This page is also referenced in the navigation on each page.
The top of this page features a sub navigation below the title, linking to each of the sections on this page, breath, body scan, and reset.
The content witin each of the 3 sections is styled using grid within the css stylesheet.

Similar tp previous sections, this grid layout will collapse on smaller screen sizes.

![](assets/readmeimages/self-guided-page-desktop.png)

### Contact Us Page
The contact us page contains the familiar basic header and footer structure, along with a form. 
This form collects the full name and email address of the user submitting the form. Along with this, it collects the users query.
The form will then redirect the user to a thank you page, with navigation links to the other sections of our site.

![](assets/readmeimages/contact-us.png)


## 3. Future Changes & Features
* I plan to include a LinkedIn option within my social links on the footer of this pahe
* Future releases will see improvement of the layout within the self-guided page. This site was designed mobile first, but this page could be restructured to make it more compatible with larger screens
* Currently the form redirects to a thank you page but does not send the form imformation anywhere. This is something I am looking to introduce in a future release.

## 4. Typography and colour scheme
The Typography used on the site was Oxygen Light 300 and was taken from [Google Fonts](https://fonts.google.com/specimen/Oxygen).
I wanted the site to feel light, and spacious, and I feel this font allowed for this.

The scheme of the colours used for the site is this:
![](assets/readmeimages/color-palette.png)

## 5. Technology
After studying the HTML and CSS essentials course with Code Institute, this project was created in Git pod using HTML and CSS languages.
I have not imported any libraries , or used bootstrap for this site.
There is also minimal JS used for the mobile navigation menu.

## 6. Testing
**Code validation**
**_HTML_**
No errors were returned when passing through the official W3C validator on any pages
[Homepage](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdanielmaherdev.github.io%2FMeditationMinds%2F)

[Self-guided page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdanielmaherdev.github.io%2FMeditationMinds%2Fselfguided.html)

[Contact Us page](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdanielmaherdev.github.io%2FMeditationMinds%2Fcontact-us.html)


![](assets/readmeimages/html-validated.png)

**_CSS_**
No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdanielmaherdev.github.io%2FMeditationMinds%2Fcontact-us.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

![](assets/readmeimages/css-validated.png)

## 8. Fixed Bugs
The Unfixed bugs are Error 1 and Error 2 mentioned in teh code validation.
   
## 9. Supported screens and browsers 
- The Chrome simulator was used from my mobile and desktop devices.
- It was tested in Chrome simulator for both Mobile and Desktop
- It was tested in Microsoft Edge simulator for Desktop
- It was tested in Safari simulator for mobile 
- The screen size on mobile was on iPhone 11 Pro, namely 5.8 inches, 84.4 cm2 (~82.1% screen-to-body ratio)
- The screen size on the Desktop was 2560x1440.

## 10. Deployment
The site was opened via Gitpod to check its process. The step to open that site is as follows:
* Go to terminal 
* Git command: python3 -m http.server
* A pop-up message will appear on the right-hand side where Open Browser should be clicked.
* A new page opens where the site is available.

The site was deployed to GitHub pages. The steps to deploy are as follows:
* In the GitHub repository, navigate to the Settings tab
* From the source section drop-down menu, select the Master Branch
* Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
* The live link can be found here: https://van-essa.github.io/Project1_Metaverse/

## 11. Credits

**Content**
* The text for the Home page was taken from [Virtual Speach Article](https://virtualspeech.com/blog/vr-applications)
* The scroll left feature on Follow Us on Social Media was taken from this [Open Code Source](https://www.html.am/html-codes/marquees/html-scrolling-text.cfm)
* The Metaverse list was inspired and used the code from this other [Open Code Source](https://codepen.io/vikassingh1111/pen/xBPmbL)
* The icons in the footer were taken from Font Awesome
* Instructions on how to implement the HTML and CSS code using GitHub was taken from the HTML and CSS course from Code Institute

**Media**
* The same photo used on the Home, About Us and Sign Up page are from This [Open Code Source Site](https://pixabay.com/photos/woman-headset-virtual-reality-vr-6882918/)
* The image used on the About Us page was taken from this other open [Content Creation Source Site](https://www.canva.com/)
* The video used on the Thank You page was taken from this other open [Content Creation Source Site](https://www.canva.com/)

