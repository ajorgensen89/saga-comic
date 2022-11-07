Landing page.
![Landing Page](/assets/images/LandingPage.png)
	Head title purpose of page includes 'New Saga to 2022' and image of main characters. Subtitles shows focus about the New Issues released this year.

Heading position - position along top of page better using line-height. 
Improve position of h1 and h1 ~ p to each other.
Removed and change heading titles - Changed head title through the building of the website to make the focus on the purpose of the website highlight the new releases after a 
hiatus from 2018 untill 2022.



Introduction Page.

	Includes navigation down the page through anchor links. Information surrounds general introduction to the storyline of the Saga Comics. Used Flex box to position them 
how you would read in a comic.
Starting from the top and then reading left to right.
Beige colour to continue down into the rest of the page.


New Issues.

	Images of the new comic's front page so they can be easy to indentify it needed to find them for purchase.
Issue number and release dates given


Volume 1-9.

	Table introduced for this section to show information about their previous releases however, this was not the main focus of the website so thought a simple table of 
information was a good display method.


About the Author.

	Fieldsets used to set the information in a separated design from writer and Artist of the website.
Clickable Icons used for Wikipedia links for further information.


Subscribtion Form.

	Background image used with Form information over the top. Image used for the background was the final image in volume 9 back in 2018 before the hiatus began.
Purpose of the form is for people to subscribe to get upto date release inforamtion.


Footer.

	Included link to the publishers homepage for the Saga Comic series.
Links to their social media platforms.
Link to being able to purchase the issue through Kindle and Amazon. 
Clickable icons.

TESTING.
HTML - Validated on the Official W3C Validator.

	Bugs fixed.

	Use of <span> in a number of occasions can back as unsuitable so adapted and changed to <div>.
	Use of <h5> and <h6> in certain sections such as <ul> and <fieldset> did not pass. Removed and change to have the status accepted.

	Bug/error remaining.

	Error reads for my script into for the Icon attachment however it works of the website and was positioned where stated in course information of the Love Running Project.

CSS - Validated on Jigsaw Validator.

No errors in css. Pass.

General Bugs and problems.

	USE OF README.md - keeps deleting my input. I have used 'git add README.md' but I seem to be getting it wrong.

	Errors - files and folders correction as they did not link to the index.html page. 

	Added links to style.css file and link to images used in the website.

	Issue centering Background image to text - used display: flex instead.
	Change font text.
	Issues with setting background image using code from Love Running.
	Atempted positioning using 'position relative and position absolute' in child and parent elements.
	Tried using the method shown below but had forgotten the 'overflow: hidden;' style declaration.
	It hadnt set the height to the size i wanted so i put that it myself.
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

Properties continued throughout website.
	Pixels height - in 10px's mostly. 
	Padding increased in 2px increments (e.g. 2px, 4px, 6px)

Unfixed Problems.
	Lots of media enteries made for position of the table in the Volume 1-9 section as I could not make it adjust 'naturally' 
to the center of the page when viewed at different pixel widths {different screen widths).

	Central positioning for text within <Fieldset> looks slightly off when viewed on a webpage even when 'text-align: center;' is set to this section.

Deployment to Github Pages.
	The process involved signing into GitHub pages and opening the repository. 
		Clicked on the 'settings' button.
		Scrolled down to 'Pages' on the lefthand menu.
		Changed Deployent branch to main with /root file and saved.
		Waited for the process to become visable on the main repository page for Saga-Comic.
		Clicked on 'Active' github-pages link underneathe Environments on the Right side of the page.
		Clicked 'View Deployment'
		Active link: 




Acknowledgements.
Code Institute course for acceptance into this world.
Anna Greaves for Love Running module run through.
Slack Community
Mentor Precious Ljege.
Attempted 2 tone background to Intro paragraphs.
Used padding and letter spacing and line height to space out some of the content on the page.


IMAGE COMICS - release dates.
Tweak letter spacing in fieldset. Add h5 to ul lists.
Remove span and h2-h5 titles are did not work together. - chnage to divs. all good.
read just introduction to adjust padding for mobile width 320px.