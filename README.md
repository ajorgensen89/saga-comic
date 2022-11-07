# New Saga Comic Launch in 2022!

### Landing page.
![Landing Page](assets/images/LandingPage.png)
[Deploy Website]()

	Head purpose of page includes 'New Saga to 2022' and image of main characters. 
	the focus of the website is about the New Issues released this year after a hiatus, since 2018.

	Includes navigation down the page through anchor links.

#### Table of Contents
* [Features](#Features)
	- [Introduction Page](#Introduction-Page)
	- [New Issues](#new-issues)
	- [Volume 1-9](#volume-1-9)
	- [About the Author](#about-the-author)
	- [Subscribtion Form](#subscribtion-form)
	- [Footer](#footer)
* [Testing](#Testing)
	- ![CSS](#css)
	- ![HTML](#html)
* [User Experience](#User-Experience)
	- [Wireframe](#Wireframe)
	- [Design](#design)
		- [Typography](#typography)
		- [Colour Scheme](#colour-scheme)
* [Deployment](#Deployment)
* [Technologies](#Technologies)


#### Removed and change heading titles
Changed head title through the building of the website to make the focus on the purpose of the website highlight the new releases after a hiatus from 2018 untill 2022.

[Back to Top](#New-Saga-Comic-Launch-in-2022)

## Features
### Introduction Page.

Information surrounds general introduction to the storyline of the Saga Comics. Used Flex box to position them how you would read in a comic. Starting from the top and then reading left to right. 

[Step 2](assets/images/GithubPages2.png)
### New Issues.

Images of the new comic's front page so they can be easy to indentify it needed to find them for purchase.
Issue number and release dates given.

[Step 2](assets/images/GithubPages2.png)
### Volume 1-9.

Table introduced for this section to show information about their previous releases however, this was not the main focus of the website so thought a simple table of 
information was a good display method.

[Step 2](assets/images/GithubPages2.png)
### About the Author.

Fieldsets used to set the information in a separated design from writer and Artist of the website.
Clickable Icons used for Wikipedia links for further information.

[Step 2](assets/images/GithubPages2.png)
### Subscribtion Form.

Background image used with Form information over the top. Image used for the background was the final image in volume 9 back in 2018 before the hiatus began.
Purpose of the form is for people to subscribe to get upto date release inforamtion.
### Footer.

Included link to the publishers homepage for the Saga Comic series.
Links to their Saga Comic social media platforms on Instagram and Facebook.
Link to purchase the New Issues released in 2022 through Kindle on Amazon. 
All have clickable links via clickable icons.
[Step 2](assets/images/GithubPages2.png)
[Back to Top](#New-Saga-Comic-Launch-in-2022)
## Testing.
### HTML - Validated on the Official W3C Validator.
#### Bugs fixed.
	Image evidence not captured before fixing the bugs encounter below.
	 1.Use of <span> in a number of occasions came back as unsuitable so adapted and changed to <div>.
	 2.Use of <h5> and <h6> in certain sections such as <ul> and <fieldset> did not pass. 

#### Bug/error remaining.

	Error reads for my <script> input for the Icons attachment however,	it was positioned where stated in course information of the Love Running Project provided by Code Institute. All Icons are linked and working in the deployed website.
[Back to Top](#New-Saga-Comic-Launch-in-2022)
### CSS 

	Validated on CSS Validator.
	No errors in css. Pass.
[Back to Top](#New-Saga-Comic-Launch-in-2022)
## General
	Some general Issues I faced when creating thie website .
* README.md kept deleting my input and not saving. I had used 'git add README.md'.
  I ensured the method of 'git add', 'git commit' and 'git push' was always used to snsure the error stopped.
* Errors - Files and folders for Images and CSS needed their paths correcting as they did not link to the index.html page. I added links to style.css file and to images used in the website.
* Change font text.
* Issues with setting background image using code from Love Running. Atempted positioning using 'position: relative;' and 'position: absolute;' in child and parent elements.
* Tried using the method in CSS shown below but had forgotten the 'overflow: hidden;' style declaration.
	#form-set {
    	background-image: url('../images/red2.jpg');
    	background-color: rgb(132, 24, 24);
    	background-repeat: no-repeat;
    	background-position: center;
    	background-size: cover;
    	width:  100%;
    	height: 700px;
    	overflow: hidden;
	}
* The above CSS I added the this above input was the height, font-size and border-radius.	
* Changing the 'placeholder' text colour for the button for thr form. https://www.w3schools.com/howto/howto_css_placeholder.asp
[Back to Top](#New-Saga-Comic-Launch-in-2022)
### Properties continued throughout website.
	Pixels height of 10px's increments over most of page.

	Padding increased in 2px increments (e.g. 2px, 4px, 6px)

### Unfixed Problems.
		Lots of media enteries made for position of the table in the Volume 1-9 section as I struggled to make it adjust 'naturally' to fit the page. To center the page when viewed I used different pixel widths {different screen widths) in these media enteries.
		Central positioning for text within <Fieldset> looks slightly off when viewed on a webpage even when 'text-align: center;' is set to this section.
[Back to Top](#New-Saga-Comic-Launch-in-2022)
### User experience		
Beige colour to continue down into the rest of the page.

[Back to Top](#New-Saga-Comic-Launch-in-2022)
### Deployment.
The process involved signing into GitHub pages and opening the repository. 
- Clicked on the 'settings' button.
- Scrolled down to 'Pages' on the lefthand menu.
[Step 1](assets/images/GithunPages.png)
- Changed Deployent branch to main with /root file and then save.
[Step 2](assets/images/GithubPages2.png)
- Waited for the process to become visable on the main repository page for Saga-Comic. Sometimes the webpage my look like the photo below and therefore you have a clickable deployable link avaliable.
[Step 3](assets/images/GithubPages3.png)

- Clicked on 'Active' github-pages link underneathe Environments on the Right side of the page. You will notic in the top left corner your Branch is set to Main.
- Clicked 'View Deployment'
[Step 4](assets/images/GithubPages4.png)

Active link: 
[Back to Top](#New-Saga-Comic-Launch-in-2022)
### Technologies.
	1. ![Github](url'https://github.com/')
	2. ![Gitpod](url'https://gitpod.com/')
	3. ![Code Institute](url'https://codeinstitute.net/') Course Plan
	4. W3C ![HTML cod Validator](url'https://validator.w3.org/') and ![CSS Code Validator](url'https://jigsaw.w3.org/')
	5. ![w3schools](url'https://www.w3schools.com/') 'How to' information. 
	6. ![README.md](url'https://www.ionos.com/digitalguide/websites/web-development/readme-file/') writing assistance.

[Back to Top](#New-Saga-Comic-Launch-in-2022)
### Acknowledgements.
Code Institute course for acceptance into this world.
Anna Greaves for Love Running module run through.
Slack Community.
Mentor Precious Ljege.
IMAGE COMICS for comic books release dates and Issue information.

[Back to Top](#New-Saga-Comic-Launch-in-2022)







