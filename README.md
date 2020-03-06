# Tunbridge Wells Royals Volleyball Club 

> ## <q>Knowledge is of no value unless you put it into practice.</q><br><i> - Anton Chekhov</i>

[View the website here](https://akrasiel1.github.io/TW-Royals-VC/)


## 1. _General Introduction_

TW Royals is a static, responsive website that has been built by using the folloging technologies:

+ HTML 
+ CSS
+ Google Fonts
+ Font Awesome 

It depicts the fictional homepage of a Volleyball Club based in my hometown, Royal Tunbridge Wells, Kent, England.
<p>It is the end result of my dedication to the study of two of the foundation blocks of Front-End, respectively HTML and CSS.</p>
<p>For this particular project, assigned to me by <a href="https://codeinstitute.net">Code Institute</a>, I decided not to use Bootstrap. Whilst I feel it is a great tool to have in your arsenal, Bootstrap may sometimes provide way too many shortcuts, or copy/paste code snippets scenarios. With that said, I am in no way discrediting this amazing framework and I don't exclude the possibility of using it for future projects.</p> 
<p>Instead, I preferred relying exclusively on CSS for my project's layout, just to give myself a little extra challenge by experimenting, researching and figuring out how things work and what makes them work.</p>

## 2. _Why TW Royals?_

<p>From a very young age and up until my early 20s, I had the fortune of playing competitive Volleyball in Italy, my home country. This life-long passion has been the catalyst for the creation of such project, which I am extremely proud to present as part of my portfolio.</p>
<p>A significant amount of hours had been put into it, along with research, experimentation, trial and error. I didn't simply worry about making the website as realistic and aesthetically pleasing as possible. Among other factors, I kept in mind user-friendliness, simplicity in design and ease of access to all the different section that make the whole ensemble.</p>
<p>I may have missed something or made mistakes during the process, but surely I did my best to minimize that.</p>

## 3. _Project Analysis_

<p>The website consists of 5 pages and has been built using different CSS approaches. The styling has been done using a combination of flexbox, floats and CSS grid. Not necessarily a consistent approach, but it helped me understand how each of the methods work.</p>
<p>When coding my CSS layout, I relied on relative units and percentages rather than using pixel values (only exception being border values and box-shadow values). I felt that this approach simplified and reduced the amount of time I had to spend on responsive design.</p>

All 5 pages feature 2 common elements:

+ A navigation menu set to <em><b>position: fixed</b></em>, with links to all 5 sections of the website. In desktop version, the currently visited page is underlined with the class <em><b>active</b></em>. On hovering the other links, the same underline takes place.

+ A footer section, which has essential information about the Club, links to social networks and a newsletter subscription form. The footer is the only section of the project that uses Font Awesome.

<p>Also,  each of the 5 pages have a different hero image that spans across 100% of the viewport height and text that has been animated by using keyframes and transitions.</p>

<p>Primary text colors are blue and white (#1d2e7c and #fafafa), whilst the footer's background is colored in grey (#424242). Some backcground colors may differ and use RGBA values (primarily black in different opacities). On hover state, some links' background change to a darker tone to provide visual clue.</p>
<p>I also used utility classes to help me stick to the <b>DRY</b> principle as much as possible and to facilitate the styling of some elements. Classes like <em><b>padded</b></em>, <em><b>flex-row</b></em>, <em><b>flex-column</b></em> etc. helped me do just that.</p>

## 4. _UX_

 Typical visitors to the website would be:

+ A user being part of the Club's existing fanbase
+ A new visitor, perhaps a Volleyball aficionado, wanting to know more about the Club
+ A resident of the Tunbridge Wells/Kent area
+ Parents who want to enroll their child/ren to the Club's Youth Academy

### User Stories

+ As a new or recurring visitor to the website, I want to be able to navigate the various sections of the website intuitively and easily
+ As a recurring visitor, I want to be able to keep up to date with what goes on within the Club and the League
+ As a new or recurring visitor, I want to be able to get in touch with the Club's Administration to know what the latest news and events are, be able to access other means like their social networks, purchase official Club's merchandise and match tickets




## 5. _The Homepage_

<p>The homepage's hero image features a detail showing a player holding a blue and yellow volleyball. The title represents the Club's motto, followed by the hashtag <em><b>#GoRoyals.</b></em></p>
<p>Right below it, there is a section dedicated to the latest Club's news, showing images and text and styled using CSS grid.</p>
<p>The following two section are Next Match and League Table. They are adjacent on screen resolution higher than 1024px.</p>
<p>Next Match section is styled using flexbox. Here, visitors have the opportunity to purchase matchday tickets.
<p>League Table section is based on <a href="https://divtable.com/table-styler/">this template</a>.</p>
<p>The Shop section shows a hero image of a Volleyball shirt's detail and a link to a dedicated shop section (not implemented). On resolution higher than 992px, there are 3 more images with additional official merchandise, displaying home kit, away kit and libero kit. This section has also been styled using flexbox.</p>
<p>Lastly, we have the sponsors section (Official Partners), some of which will appear on official match kits. Unlike other components that use flexbox, this one also uses the <em><b>flex-wrap</b></em> property.</p>

## 6. _The Club & Youth Academy_

<p>Unlike the Homepage, the Club History and Youth Academy pages are styled in a more simple fashion. Both feature a descriptive article with two images, one floated on the left and one on the right. I used the "clearfix hack", which I found <a href="https://www.w3schools.com/howto/howto_css_clearfix.asp">here</a>, to help me style the pages the way I wanted.</p>
<p>Additionally, the Club page has a section dedicated to the trophies won by the team. It has been styled using a combination of flexbox and CSS grid.</p>

## 7. _The Team_

<p>The team page is probably the part of the project that required the longest amount of time to develop. It features images of the team players and technical staff arranged in rows, once again styled with CSS grid. When clicking on player or staff images, a popup is activated, showing player's or staff's additional information.</p>
<p>Inspiration for the creation of the popup taken from <a href="https://www.youtube.com/watch?v=8AUtM5lqUZM">here</a>. Also, on resolution higher than 1024px, there's a slight scaling when hovering over the images, giving a zoom-in effect.</p>

## 8. _Contacts_

The Contacts page features a simple form consisting of:
+ Full Name (required)
+ Email Address (required)
+ The type of enquiry, all as dropdown options
+ A text area in which users can type in their messages
+ A checkbox with a message relative to privacy policy
  -*Additional note: when clicking on Privacy Policy link, both in Contact Form and Footer, user is redirected to a new page
+ A submit button
The form's background is an image of players celebrating with a slightly transparent white overlay. On resolution higer than 992px the form is shifted on the left side, keeping the slightly transparent overlay, whilst leaving the right side uncovered.

## 9. _Navigation Menu - Mobile & Tablet_

<p>The hamburger menu, as well as the desktop nav menu, stands at a fixed position. I got inspiration and adapted my idea from the "checkbox hack", an article that I found in <a href="https://css-tricks.com/the-checkbox-hack/">here</a>, and a video that I found <a href="https://www.youtube.com/watch?v=bs3HNguzkT8">here</a>. When clicking on the icon in the top right corner (created using a span and ::before and ::after pseudo-classes), an animation is triggered, allowing for a radial gradient background to scale and cover the entirety of the screen and showing the menu options. The hamburger icon also turns into an X, thanks to transform effects (rotation). The cubic-bezier values for the styling of the background showing up have been experimented with <a href="https://cubic-bezier.com/#.17,.67,.83,.67">here</a></p>.

## 10. _Deployment_

This project was developed using [Visual Studio Code](https://code.visualstudio.com/), commited and pushed to Github using its built-in function. It was deployed and published with Github Pages, using the following steps:

1. Log into [GitHub](https://github.com/)
2. Select akrasiel1/TW-Royals-VC from the list of repositories 
3. Select 'Settings' from the top right corner options.
4. Scroll down to the 'Github Pages' section.
5. Under 'Source', click the drop down menu and select 'Master Branch'
6. The page is automatically refreshed and the website is now deployed
7. A message is dispayed with a prefixed green tick, saying 'Your page is now published at https://github.com/akrasiel1/TW-Royals-VC'


Alternatively, the project can be run locally by following the instructions below:

1. Go to the project repository [here](https://github.com/akrasiel1/TW-Royals-VC)
2. Look for the green button on the right hand side of the page that says 'Clone or Download' (you may need to scroll down slightly to see it), then click
3. Copy and paste the link in the box
4. Open Terminal
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type 'git clone', and then paste the URL you copied in Step 3.
7. Press Enter. Your local clone will be created.

## _Testing_

### Manual Testing

The website has been tested on different browsers, including:

+ Google Chrome
+ Mozilla Firefox
+ Microsoft Edge
+ Opera
+ Internet Explorer

Although website renders as supposed to in the first 4 browsers, compatibility issues are present when rendering the website on IE 11 and earlier versions. This is especially true for pages styled using CSS Grid and flexbox


### Automated testing

Automated testing run on the following:

+ [W3C Validator](https://validator.w3.org/)
    - No errors or warnings to show when running test

+ [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
    - Validator show message "Congratulations! No Error Found". However, 21 warnings are shown, all related to Font Awesome


### Other Known Issues

+ When submitting form, user is redirected on a new page showing a 404 error
+ On mobile and small tablet devices, whilst changing page with hamburger nav menu then hitting the back button, the menu will not disappear
+ When clicking to links within the website that are not part of the nav menu, they may present a "skipping effect", redirecting either to top of section or to top of homepage


## _Final Notes, Credits & Acknowledgements_


<p> This project may not be necessarily optimized for commercial purposes.</p>
<p>As already mentioned, the content of this repository is fictional and the final output is purely for educational and personal development purposes.</p>
<p>This repository may contain some copyrighted images/material and none of its content shall be published anywhere other than my Github Pages.</p>
<p>Players and staff's names, addresses, phone numbers and some of the locations are fictional.</p>
<p>Sponsors logos are borrowed from the web and represent local businesses in the Tunbridge Wells area. They belong to their respective owners and they've been simply used to make the whole project more realistic.</p>
<p>Club logos are either custom made using Photoshop or partly adapted from original ideas. I do not claim ownership of any of the image 
content of the project.</p>
<p>Players and staff photos are borrowed from <a href="https://gospartans.ca/">here</a>.</p>
<p>Team names are either fictional or adapted from real sports clubs.</p>
<p>Kits in the Shop section are custom made using a PSD mockup which I purchased on <a href="https://yellowimages.com/stock/mens-soccer-kit-mockup-front-view-38538/">YellowImages</a>.
<p>General design and layout concept inspired by <a href="https://www.lubevolley.it/">Lube Volley</a>.
<p>Finally, this project is the result of the hard work and dedication I have poured in in the first part of my course at Code Institute. It has stimulated my curiosity, given me constant food for thoughts and some sleepless nights, but definitely helped me push forward every time I found a challenge along the way. It hasn't been an easy task, but all things considered, I'm extremely proud of the outcome.</p>
