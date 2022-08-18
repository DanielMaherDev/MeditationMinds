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
Each block also includes a hover effect on desktop screens, which should produce an animation revelant to the exercise mentioned.

#### Desktop
![](assets/readmeimages/self-guided-section-desktop.png)

#### Mobile
![](assets/readmeimages/self-guided-section-mobile.png)


### Communal Meditation Section

Below the self-guided meditation section is a section regarding our communal meditation. This is also referenced in the navigation bar.

This section provides information on our group meditations, occuring twice monthly. Similar to the Self-Guided section, this section is set to show each block side by side on desktop and on top of one another on mobile.
![](assets/readmeimages/communal_desktop.png)

### The Footer
The footer section includes links to the relevant social media sites for Metaverse Lovers. In this case, the links will land to Code Institute social accounts since the Metaverse Lovers page does not exist in reality. The links will open to a new tab to allow easy navigation for the user.
The footer section is featured on all four pages.
The footer is valuable to the visiting user as it encourages them to keep connected via social media.
The footer page will be visible at the end of each page and look the same on a desktop, iPad and mobile display.

![](assets/ReadMeImages/Footersocialmedia.png)

## 3. Future features what would like to add in the future
* Future features shall include a blog page, where a comments section will be available to the visiting user and can express any questions, concerns or thoughts on the topic. 
* The future feature shall include more immersive animation to engage th visiting user and communicate the world of Metaverse with immersive videos.

## 4. Typography and colour scheme
The Typography used on the site was Bellota Text Light 300 and was taken from [Google Fonts](https://fonts.google.com/specimen/Bellota+Text?category=Display,Monospace)
The scheme of the colours used for the site is this:
![](assets/ReadMeImages/colourpallete.png)

## 5. Technology
After studying the HTML and CSS essentials course with Code Institute, this project was created in Git pod using HTML and CSS languages.

## 6. Testing
**Code validation**
**_HTML_**
Two errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fvan-essa.github.io%2FProject1_Metaverse%2F)

![](assets/ReadMeImages/HTMLChecker.png)

_Error 1_
When coding the subject list on the Home Page, being featured in the same line was not the aim, rather than having points 1-3 to the first row and 4-5 to the second row. The only way it could be achieved was by adding the <br> element between them. Hence this bug was not fixed due to difficulties finding another way.

_Error 2_
This Error looked so strange due to misunderstanding the bug. The code was rewritten, checking online any similar issues, checking spelling mistakes, but no answer seemed to be valuable for this bug. The code was not removed since the fontawesome script had to be mentioned in the code.

**_CSS_**
No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvan-essa.github.io%2FProject1_Metaverse%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

![](assets/ReadMeImages/CSSWarnings.png)

After checking online what the problem is and what this warning wants to communicate, the outcome was that the style sheet code did not respect the syntax of CSS and that there is nothing to do about this since those errors will help support browser compatibility efforts. Hence, the code is still there since the eye-catching list on Home Page would not be visible otherwise.

## 7. Test cases
It is tested by filling the Newsletter form, ensuring that the required information is filled and the message pops up if it is not filled in.
The Newsletter form requires the Full Name of the Visiting User and the email address. If the visiting users do not share this information, then the visiting user can not subscribe.
Testing filling the form in both Desktop and Mobile this is what happens:
   - When the visiting user does not fill in their name
   
   Desktop

   ![](assets/ReadMeImages/Notfillingname_Desktop.png)

   Mobile

   ![](assets/ReadMeImages/MobileName.PNG)

   - When the visiting user does not fill in their surname
   
   Desktop

   ![](assets/ReadMeImages/notfillingSurname_Desktop.png)
   
   Mobile

   ![](assets/ReadMeImages/MobileSurname.PNG)

   - When the visiting user does not fill in their email address
   
   Desktop

   ![](assets/ReadMeImages/fillinEmail_Desktop.png)
   
   Mobile

   ![](assets/ReadMeImages/MobileEmail.PNG)

   - When the visiting user fills in all required information
   
   Desktop

   ![](assets/ReadMeImages/thankyou_Desktop.png)
   
   Mobile

   ![](assets/ReadMeImages/MobileThankYou.PNG)

## 8. Unfixed Bugs
The Unfixed bugs are Error 1 and Error 2 mentioned in teh code validation.
   
## 9. Supported screens and browsers 
- The Chrome simulator was used from my mobile and desktop devices.
- It was tested in Chrome simulator for both Mobile and Desktop
- It was tested in Microsoft Edge simulator for Desktop
- It was tested in Safari simulator for mobile 
- The screen size on mobile was on iPhone 11 Pro, namely 5.8 inches, 84.4 cm2 (~82.1% screen-to-body ratio)
- The screen size on the Desktop was 2560x1440.

## 10. Deployment
The site was opened via Gitpud to check its process. The step to open that site is as follows:
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

