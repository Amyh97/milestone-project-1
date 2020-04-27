#User Centric Front-End Development Milestone Project - Portfolio#

This comprehensive website is for me as a web developer. The website features a breakdown of my skills and experience, links to other projects that I have done and a contact page. The main goal of this website is to promote myself as a web developer. 
The business goals of this website are:
-	Attract potential recruiters
-	Showcase my work to potential employers
-	Set up a point of contact for other developers, recruiters and employers
-	Use good UX to keep people on the website long enough to reach the contact me page having seen enough to interest them.
The goals of the users are:
-	Looking for someone to work with/ for them to create beautiful websites for their own business needs.
-	See other examples of my work that are conveniently located in one place. 
-	Have an intuitive way of contacting me. 


##UX##
This website will be for me as a developer to use as a platform to showcase my work. I think this project will be the best way of doing this as not only will it be on a site that I have built, but it ill also provide a way of putting all my projects in one place to show to potential recruiters. I believe that mine will stand out from other similar sites which look to be scrolling webpages, whereas mine is easy to navigate with clear sections and different pages for each heading, making navigation of the website easier. 

-	As someone visiting this website, I want to be able to easily navigate the site by using a nav bar.
-	As someone who would potentially want to work with the developer, I would want to be able to see other examples of work completed by clicking on links to see the full projects. 
-	As a potential employer/recruiter I want to see previous experience and skills gained by looking at a well-presented list/timeline.
-	As a person who is interested in seeing the development of the web developer, I would want to be able to connect with them in a professional manner and see them at work by following links to social networks and GitHub.
-	As someone who would want to work with the developer, I would like to see information about the developer, such as where they are based, and what motivates them. I would want to do this by viewing a profile so help get a sense of who I would be working with.
-	As a recruiter or employer, I would want to see the developer’s CV to gain greater understanding of them, I would want to be able to click a link so see a PDF of this. 
-	As someone interesting with the web developer, I would want an easy way to start contact with them by filling out a form within the site. 

To help ensure I created the best UX that I could for my users, I created wireframes for my pages. This way I knew what features and functions I was going to put on my site. Therefore, I did not keep adding things during development and giving the users an information overload. This way I was also able to design a header and footer that would be the same across the pages. This would help keep the website predictable and helps make the site more intuitive for users. I have chosen to keep to the convention of having a navigation bar in the header, this will meet user expectations. By having the navbar in the header it will appear the same on every page and will have links to all the other pages so that users can freely explore the website and get to any page they want. I created the wireframes on Balsamiqu <! --- add wireframe to GitHub---!>. ![wireframe](URL for wireframe)

##Features##
####Profile####
The profile page of my website is the first one that users see. On this page users can see an **image** to draw their attention to the left-hand side of the page where the contact details are. In addition, **divs** have been used on the other section that takes up two thirds of the screen. These divs help break up the text and space it out so that the information is kept in small bite size bits, therefore being easier for users to digest the information. 

####Skills and Experience####
On this page users can see three clear sections, two of writing and a **timeline**. This helps me present more information to the user as it is presented in a more visual way , this not only makes it more appealing to users, but also helps break up the information presented. 

####Portfolio####
This page has been split into tow sections. Although this does not follow the rule of thirds, it was the most logical way to split the data (into front end development and back end development). It also prevented me from adding unnecessary data in the third section and compromise the space I had to display the information for the two main sections of information. In addition, splitting this page into two sections allowed me space to add **images** to my page, therefore making it more visually appealing to users. This page included **external links** that are in “a” tags, this allowed me to customise the writing that is clicked to take you to the links. I have styled these elements separately with CSS to help them stand out and make the site more intuitive to users by letting them know they can click on these links to see my other projects. 

####Contact####
The final page of my website is the contact page, I have put this as the last page in my nav bar so that users visit the other pages first so that they know who they are contacting and what the developer can do. This page includes a **form**. Currently, the form does not send the data to me in an email as this project is created only using HTML and CSS. However, it includes two **input** elements with different data types (text and email), a **text area** and a submit **button**. In the input fields and the text area I have included **placeholder text** to help instruct users as to what information is intended to be put in each field. 


###Existing features###
-	**External Hyperlinks**, this allows users to be taken to my other projects (in new tabs, as not to lose this site) by clicking on key words and icons. In addition, the logos in the footer will take you to the relevant social network site. 
-	**Internal Hyperlinks**, this is how my navbar will work. The user will be able to navigate their way round the website by clicking either on the word or anywhere in the box on the nav bar. In addition, there will be a photo/logo in the top left-hand corner (following convention)  that will always take users back to my profile page (index.html). 
-	In the navbar one of the options is slightly different to the others. Most of the links will open another webpage (from the same repository) in the same tab. However, the download option is still an internal link as the document is in the same repository, but it is only a PDF, so it opens another tab as there would be no way of users getting back to my website form here without using the backwards arrow on the browser. 
-	My website will be **responsive**, therefore resize at different breakpoints for different screen sizes. The biggest change caused will be to the header. On larger screens the menu will appear as five different items, whereas on a mobile view this will turn into a hamburger button, again conforming to what users expect of mobile sites. 
-	Both in my he\der and footer I have used **pseudo classes**. In the header I just used the “:hover” pseudo class to put a white line under the option on the menu that you are over. Whereas in the footer I have used it with some **animation**. I used “transition: ease-in-out” to create pale circles that appear and disappear from around the social links when you hover over them.
###features left to implement###
-	Back end development. In time I would like to set up the form on my contact page in such a way that users can enter their text and details and it automatically send me an email with their message, so that they can contact me through my website instead of having to leave the site to do this. 
##Technologies Used##
 To create this project I used HTML, CSS as my coding languages in a couple of different types of software. In addition to these I used some additional libraries to embellish my work and make it more unique as well as some other design and coding tools. 
-	[https://gitpod.io/]
o	I have created this project in Gitpod
-	[https://github.com}
o	This project has been deployed through and hosted by GitHub. 
-	[https://getbootstrap.com/]
o	I used bootstrap to help me achieve my layout using the grid. In addition, I used it to help me style the button on my form and to help style the navbar. 
-	[https://fontawesome.com/]
o	All the icons in this project come from Fontawsome, they were used to add interest and interactivity to the pages. They are used next to headings as well as the hyperlinks in the footer.
-	[https://fonts.google.com/]
o	I used Lato and Dancing Script from Google fonts to style my project. I used one for the headings and one for the text. By only using two fonts I have added continuity to my pages. 
-	[https://repl.it/]
o	I have used repl.it to create the webpage for my external links for the backend projects that I have not yet completed. 
-	[https://material.io/]
o	I used Material Design to help pick my colour scheme and find the hex codes for the colours that I used. 
-	[https://tinypng.com/]
o	In order to create the best UX possible I did not want users to have to wait a long time for the browser to load large image files, so I used Tiny PNG to compress my images so browsers only had to deal with smaller file sizes, therefore load faster. 
-	[https://htmlformatter.com/]
o	Once I had finished coding I used this HTML formatter to ensure that my code was properly laid out and easier to read. 
-	[https://validator.w3.org/] and [https://jigsaw.w3.org/css-validator/]
o	I used the W3C validators to help test my code. 


##Testing##
The first step that I took in testing my code was to use the W3C Validators for both HTML and CSS. Once I was sure the code was valid and correct, I moved on to testing it from a user perspective. 
<!------ use user storied from UX section once site it built----------->
##Deployment##
 This project was created on **GitPod**, an online IDE. From here I was able to use the git commands (git add, git commit and git push) to put them into the repository on GitHub, where the website is hosted and deployed. In order to deploy a website using GitHub pages, the following steps were taken 
<ol>
	<li>Log into GitHub and select the project you wish to deploy. For this project I logged into Amyh97 and selected the project called “milestone-project-1”</li>
	<li>Go to the settings tab across the top, and scroll down to “GitGub Pages”</li>
	<li>select the source that you would like to use, for this project I used **Master    Branch**.</li>
	<li>Doing this will refresh your page and deploy your site and provide a link to your website. This project was deployed to [https://amyh97.github.io/milestone-project-1/].</li>
</ol>

##Credits##
###Content###
-	As this project only uses HMTL and CSS, there is no back end functionality to it, so the page you are taken to was created by Code Institute [https://formdump.codeinstitute.net/], I chose this webpage as it shops you what names I gave each input field and the values the user has given each field. 
-	To help create my navbar I have used Bootstrap code that I found through the W3Schools website [https://www.w3schools.com/bootstrap/tryit.asp?filename=trybs_navbar_collapse]
###Media###
-	The profile image and the screenshots of my other projects are my own photos that I have put in the GitHub repository for use on this website. 
-	The letter A that I used as a logo came from [https://www.needpix.com/photo/1636497/letter-a-the-letter-a-ornament-capital-letter-vintage-font-symbol-alphabet]. When searching for this image I ensured that the image used I could modify and use on my website. 
###Acknowledgements###
-	I drew inspiration for this project from the walkthrough projects I have done with Code Institute. 
