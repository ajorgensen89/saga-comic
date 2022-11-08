# New Saga Comic Launch in 2022!

## Landing page.
![Landing Page](assets/images/LandingPage.png)
[New Saga Comics!]()

	Head purpose of page includes 'New Saga to 2022' and image of main characters. 
	Th
	e focus of the website is about the New Issues released this year after a hiatus, since 2018.

	Includes navigation down the page through anchor links.

***
### Table of Contents
* [Features](#features)
	- [Introduction Page](#introduction-page)
	- [New Issues](#new-issues)
	- [Volume 1-9](#volume-1-9)
	- [About the Author](#about-the-author)
	- [Subscribtion Form](#subscribtion-form)
	- [Footer](#footer)
	- [Future features](#future-features)
* [Testing](#testing)
	- [HTML](#html)
		- [Bugs Fixed](#bugs-fixed)
		- [Bugs Remaining](#bugs-remaining)
	- [CSS](#css)
	- [General](#general)
		- [Browser Testing](#browser-testing)
		- [Unfixed Problems](#unfixed-problems)
* [User Experience](#user-experience)
	- [Wireframe](#wireframe)
	- [Design](#design)
		- [Colour Scheme](#colour-scheme)
		- [Typography](#typography)
* [Clone Website](#clone-website)
* [Deployment](#deployment)
* [Technologies](#technologies)


## Removed and change heading titles.
Changed head title through the building of the website to make the focus on the purpose of the website highlight the new releases after a hiatus from 2018 untill 2022.

[Back to Top](#new-saga-comic-launch-in-2022)
***
## Features
### Introduction Page.

Information surrounds general introduction to the storyline of the Saga Comics. Used Flex box to position them how you would read in a comic. Starting from the top and then reading left to right. 

![Introduction Page](assets/images/Intro.png)
[Back to Top](#new-saga-comic-launch-in-2022)
### New Issues.

Images of the new comic's front page so they can be easy to indentify it needed to find them for purchase.
Issue number and release dates given.

![New Comic Issues](assets/images/NewIssues.png)
[Back to Top](#new-saga-comic-launch-in-2022)
### Volume 1-9.

Table introduced for this section to show information about their previous releases however, this was not the main focus of the website so thought a simple table of 
information was a good display method.

![Volume 1-9](assets/images/Table.png)
[Back to Top](#new-saga-comic-launch-in-2022)
### About the Author.

Fieldsets used to set the information in a separated design from writer and Artist of the website.
Clickable Icons used for Wikipedia links for further information.

![About the Author](assets/images/About.png)
[Back to Top](#new-saga-comic-launch-in-2022)
### Subscribtion Form.

Background image used with Form information over the top. Image used for the background was the final image in volume 9 back in 2018 before the hiatus began.
Purpose of the form is for people to subscribe to get upto date release inforamtion.

![Subscribtion Form](assets/images/Form.png)
[Back to Top](#new-saga-comic-launch-in-2022)
### Footer.

Included link to the publishers homepage for the Saga Comic series.
Links to their Saga Comic social media platforms on Instagram and Facebook.
Link to purchase the New Issues released in 2022 through Kindle on Amazon. 
All have clickable links via clickable icons.
![Footer](assets/images/Footer.png)

[Back to Top](#new-saga-comic-launch-in-2022)
***
### Future Features.
For features to add to this website I would have liked to added a Character gallery to show some more of the illustrations of the Saga Comic Book Series.
***
## Testing.
### HTML - Validated on the Official W3C Validator.
#### **Bugs fixed.**

Use of _span_ in a number of occasions came back as unsuitable so adapted and changed to _div_.
![HTML Error](assets/images/HTMLIssues.png)
Image evidence not captured before fixing the bugs encounter below.
Use of _h5_ and _h6_ in certain sections such as _ul_ and _fieldset_ did not pass. 

Use of an _anchor_ element around the _button_ or _input_ elements did not work. I needed to change my form _method_ to _'method="GET"_ instead of _"POST"_ and remove the _anchor_ element. 
Used Tutor Support for this fix.
![anchor error](assets/images/HTMLanchor.png)


#### **Bugs remaining.**

	Error reads for my _script_ input for the Icons attachment however,	it was positioned where stated in course information of the Love Running Project provided by Code Institute. All Icons are linked and working in the deployed website on Github and Gitpod.

![HTML Error](assets/images/HTMLRemain.png)

[Back to Top](#new-saga-comic-launch-in-2022)
### CSS
I faced one bug in my CSS when setting the borders, margins and padding to the _body_ of the website. I fixed this issues and it passed. 
![Fixed CSS bug to achieve Pass](assets/images/CSSIssue.png)
	
[Back to Top](#new-saga-comic-launch-in-2022)
### General
Some general Issues and bugs I faced when creating thie website
* README.md kept deleting my input and not saving. I had used 'git add README.md'.
  I ensured the method of 'git add', 'git commit' and 'git push' was always used to snsure the error stopped.
* Errors - Files and folders for Images and CSS needed their paths correcting as they did not link to the index.html page. I added links to style.css file and to images used in the website.
* Change font text.
* Issues with setting background image using code from Love Running. Atempted positioning using _'position: relative;'_ and _'position: absolute;'_ in child and parent elements.
* Tried using the method in CSS shown below but had forgotten the _'overflow: hidden;'_ style declaration.
	- #form-set {
    	- background-image: url('../images/red2.jpg');
    	- background-color: rgb(132, 24, 24);
    	- background-repeat: no-repeat;
    	- background-position: center;
    	- background-size: cover;
    	- width:  100%;
    	- height: 700px;
    	- overflow: hidden;}
* To the above CSS I added the this above input: 
	- height 
	- font-size
	- border-radius.	
* Changing the _'placeholder'_ text colour for the button for the form. Below website assistance used: 
https://www.w3schools.com/howto/howto_css_placeholder.asp

### Browser Testing.
All loading and avaliable to view while tested on [Microsoft Edge](url'https://www.microsoft.com/en-us/edge?form=MA13FJ'), [Google Chrome](url'https://www.google.co.uk/chrome/'), [Opera](url'https://www.opera.com/') and [Firefox](url'https://www.mozilla.org/en-GB/firefox/new/').
Loading problems found with [Safari](url'https://www.apple.com/uk/safari/').

[Back to Top](#new-saga-comic-launch-in-2022)

### Unfixed Problems.
		Lots of media enteries made for position of the table in the Volume 1-9 section as I struggled to make it adjust 'naturally' to fit the page. To center the page when viewed I used different pixel widths {different screen widths) in these media enteries.
		Central positioning for text within <Fieldset> looks slightly off when viewed on a webpage even when 'text-align: center;' is set to this section.
[Back to Top](#new-saga-comic-launch-in-2022)
***
## User experience	
	The general experience should allow the audience to briefly understand how Comics are put togther and read. Then, I have impletmented a large portion of the website to the New Comic Issues this year so they easily avaliable to notice. 
	Information can be found about the hiatus both the Writer and Illustrator for the Comic took and a link to find more information is avaiable from the website. Including, the Pulisher of this particular Comic book Series.
	An easy subscribtion form can be found to sign up for future details and the footer contains links to look further in their Social aspects and purchasing the Comics themselves.
### Properties continued throughout website.
Border-radius continued throughout the webpage for a 'round world' effect.

Pixels height of 10px's increments over the webpage.

Padding increased in 2px increments used where necessary (e.g. 2px, 4px, 6px)

[Back to Top](#new-saga-comic-launch-in-2022)

### 'Back' Form


[Back to Top](#new-saga-comic-launch-in-2022)
### Wireframe
Used to design the layour of the website. Final website has been made different to the wireframe provided.
Certain elements such as the, Character gallery, was removed and added to future adapations to the webpage's features.

**Computer View**
![Laptop View of wireframe](assets/images/WireframeL.png)

**Mobile Device view.**
![Mobile Device View](assets/images/WireframeS.png) ![Mobile Device View](assets/images/WireframeS2.png)
### Design
#### Colour Scheme
The beige to orange colour field continued down into the rest of the page, was used as a subtle hint to the colours in the characters clothing on the landing page image, aswell as the main 'Saga' title in the image.

Colours over page:
* rgba(240, 209, 178, 0.9) (Beige)
* rgb(238, 125, 13) (Orange)
* rgb(29, 7, 51) (Dark Purple, almost black)

The last image which is the background to the Form, is an image used from the Final Chapter of the Comic they released in 2018 before the hiatus. I felt this was a subtle ending to the webpage.
[Back to Top](#new-saga-comic-launch-in-2022)
#### Typography
Font used from [Google Fonts](url'https://fonts.google.com/') website.
The two I choose has subtle differences, giving the paragraphs a font of 'Noto Serif' a more 'floaty' look compared to the more basic fuller rounded main font 'Varela Round'.

[Back to Top](#new-saga-comic-launch-in-2022)

***
### Clone Website.
The process of cloning the website can be seen below.


[Back to Top](#new-saga-comic-launch-in-2022)
***
## Deployment.
The process involved signing into GitHub pages and opening the repository. 
- Click on the 'settings' button.
- Scroll down to 'Pages' on the lefthand menu.
![Step 1](assets/images/GithubPages.png)
- Changed Deployent branch to main with /root file and then save.
![Step 2](assets/images/GithubPages2.png)
- Wait for the process to become visable on the main repository page for Saga-Comic. Sometimes the webpage my look like the photo below and therefore you have a clickable deployable link avaliable.
![Step 3](assets/images/GithubPages3.png)

- Click on 'Active' github-pages link underneathe Environments on the Right side of the page. You will notice in the top left corner your Branch is set to Main.
- Click 'View Deployment'
![Step 4](assets/images/GithubPages4.png)

Active link: 

[Back to Top](#new-saga-comic-launch-in-2022)
***
### Technologies.
Technologies used thoughout this wesbite.
1. [Github](url'https://github.com/')

2. [Gitpod](url'https://gitpod.com/')

3. [Code Institute](url'https://codeinstitute.net/') Course Plan
4. W3C [HTML cod Validator](url'https://validator.w3.org/') and [CSS Code Validator](url'https://jigsaw.w3.org/')
5. [w3schools](url'https://www.w3schools.com/') 'How to' information. 
6. [README.md](url'https://www.ionos.com/digitalguide/websites/web-development/readme-file/') writing assistance.
7. [Balsamiq](url'https://balsamiq.com/') used to create wireframes. 
8. Lighthouse Overview. Pictured below.
![Lighthouse](assets/images/Lighthouse.png) 
9. Chrome Devtools is used for a brief look of the website. Included in this view is the General Overview and Colour chart. (Orange colour for the _hover_ attribute not included in chart)
![Chrome Devtools](assets/images/overview.colour.png) 
10. [Am I responsive?](url'https://ui.dev/amiresponsive') webpage used to test the view on various devices.
![Am I Responsive](assets/images/Devices.png)

[Back to Top](#new-saga-comic-launch-in-2022)

***

### Credits
* Fonts from [Google Fonts](url'https://fonts.google.com/')
* Icons from [Font Awesome](url'https://fontawesome.com/')
* Wireframe from [Balsamiq](url'https://balsamiq.com/')
* Images used from [Amazon](url'https://www.amazon.co.uk/Saga-55-Brian-K-Vaughan-ebook/dp/B09KMF7S37/ref=sr_1_4?crid=R379XB6DTXWF&keywords=saga+comic+55+issues&qid=1667848064&s=books&sprefix=saga+comic+55+issues%2Cstripbooks%2C74&sr=1-4') where the New Issues for 2022 can be purchase via Kindle.
* Image from [Image Comics](url'https://imagecomics.com/comics/releases/saga-54') for Landing Page.
* Image from [Image Comics](url'https://imagecomics.com/comics/releases/saga-1') for Form page.
* Help with [README.md](url'https://www.w3schools.io/file/github-readme-image/') layout.

[Back to Top](#new-saga-comic-launch-in-2022)
***
### Acknowledgements.
This project was completed as part of my Project One for My Portfolio for the Full Stack Software Developer Course provided by Code Institute.
My Acknowledgements would like to go out to:
- Code Institute course for acceptance into this world.
- Anna Greaves for Love Running module 'run through' over the [Code Institute](url'https://codeinstitute.net/') Coursework.
- [Slack](url'https://slack.com/intl/en-gb/') Community for help throughout.
- Mentor Precious Ljege for encourgement to produce better and advise along the way.
- [Image Comics](url'https://imagecomics.com/comics/series') for comic books release dates and Issue information.
- Oisin on Tutor Support for Code Institute Course.

[Back to Top](#new-saga-comic-launch-in-2022)







