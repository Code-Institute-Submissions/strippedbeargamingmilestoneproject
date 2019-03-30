# Milestone Project:
# **STRIPPED BEAR GAMING**

## Project overview
My milestone project is a front-end only mobile-first responsive website designed to give everyday/casual gamers the latest gaming news, reviews and upcoming releases. The website will aim to give enough information and convey the passion of the writer, without being too technical that it could alienate or confuse the average user that likes to just pick up and play.

The website will allow for people to learn about the reviewers, read reviews, keep up to date on current game news/updates, watch videos of other content creators reviews/gameplay, and also to contact us should they want a particular game reviewed/submit their own game review to be featured.

## The UX
When designing the website, I had to cover the factors of the ux (strategy, scope, structure, skeleton, surface) and I will provide a brief overview here, but the files for each part of the process are actually available to read on github.

So, the website itself is a reviews site that has been designed to allow the two individuals to post their content online where it is readily available for anyone to read, with the aim of connecting them to others through social media and concurently expanding their online presence. This project is a guaranteed way to help achieve those goals, as the website has easy to access content that has been designed for mobile first (66% of adults use a smartphone to go online - https://www.ofcom.org.uk/__data/assets/pdf_file/0020/102755/adults-media-use-attitudes-2017.pdf - section 5.5, page 32 ), therefore ALL content is able to be viewed in an aesthetically pleasing way that isn’t restricted based on the limitations of the device being used to view the site. The site also emphasises the ability to connect through social media by including social icons in the footer of every page, as well as a ‘contact us page’ and subscription form to further allow for the user to feel they have the chance to interact with the two members of the group.

If the user wishes to connect to the group through social media, they can click on the social icons in the footer and voila, further access and ability to connect.

If the user wishes to communicate their wish for a certain game to be reviewed/to send their own review, or has a general issue, they can contact the group through the ‘contact us’ page which will be linked to the official group email account.

If the user wishes to communicate directly to the group and/or other users about reviews/current games/with the wish to team up and play together, then there will be a link in the footer for discord, which will have a group set up for all users to join.

Further user stories have been completed and are available to view in the ‘Scope’ document for this project on github.

I have also included the files for the other factors of the ux, including the wireframes and mock-ups for the website (both hand drawn, and through www.marvelapp.com ), which are included individually as jpeg/png files, as well as in document form through word document/pdf.

## Features
There are many features that the website includes/makes use of, these can be found on the ‘Strategy’ file I have included on the github page for this project.

However I will provide an overview of some of the features of the website, and how they enable users to complete the various needs they may have through certain specific actions on the webpage:

#### *Current features*
* Social icons/links – allows users to connect to the group through social media, they can click on the social icons in the footer, this will direct them to the various forms of social media that the group has.
* Contact us page/form – allows users to fill out a form on the ‘contact us’ page to communicate their wish for a certain game to be reviewed/to send their own review/report a general issue.
* Discord icon/link – allows the user to communicate directly to the group and/or other users about reviews/current games/to team up and play together, the link will take them to the discord app where there is a group set up for all users to join.
* Reviews page – allows users to read up on reviews of games, this will enable them to get a better understanding and view of a game, therefore enabling them to make an educated decision on whether to purchase said game.
* Media page – allows users to watch footage/other reviews of the games covered in the ‘Reviews’ page, this will allow the user to actually see the gameplay and aims to reinforce/aid their opinion of the game further (having read the review on the website already).

Other features can be found in the ‘Strategy’ document/pdf.

##### *Future features (to be implemented…)*
There are also a few features that I wish to be implemented in future, but due to limitations in my current skillset, they have not yet been applied. These include:
* The ‘Contact us’ form is not currently linked to the company’s actual email address, therefore it will not actually send the form to the official email address, which will be rectified once I cover/learn this on the course.
* The ‘Subscribe’ form is also currently not functional as it isn’t linked to a database, this will also be rectified once I cover/learn this on the course.
* Will also include a section in reviews to put archived reviews, and a search bar to allow for easier navigation/location of reviews – rather than forcing the user to scroll down the page and hunt for the review they want (if it has been covered). This will also allow for the reviews on the main section of the website to be the newest/freshest reviews possible.

## Functionality of project

The website is fully responsive, designed for mobile first. When viewing the website on large tablets, desktops and larger screen sizes (md+) there is various content that can be seen that isn’t visible on mobile/small tablets, this is to allow for the layout on smaller screens to be more aesthetically pleasing and put emphasis solely on certain features, for example: the social icons are the only information visible in the footer on mobile/tablets (where  there is two further pieces of information about discord/contact in the footer on md+ screen sizes).

The navigation is functional and changes depending on the screen size the content is being viewed on. On phones and small tablets, the menu is collapsed into a collapsible menu which is navigated using a ‘hamburger’ button, whereas on md+ screen sizes, the menu takes a more traditional format wherein the menu items can be seen at the top of the screen in the navigation bar.

The two forms work on all screen sizes/ device types, but are not fully functional yet as they don’t currently contact/send the information to the group email, nor is there a database set up that the form fills.

When viewing the website on the simulated mobile and tablet devices on google chrome tools, the fixed background worked fine and would allow the content to be scrolled, whilst the image remained fixed. Yet upon further testing, the functionality wasn’t working properly on iPhone 6s, iPhone 7, iPhone X, iPad (generation 2) and Sony Xperia, the background was stretched across the entire length of the content that was inside the main container div. So I opted instead to create a separate dedicated div for the background on mobile and tablet, which alters the picture slightly, but it allows for the picture to stay fixed and to cover the background of the webpage, (as opposed to covering the entire background of the content and therefore making it impossible to make out what the image is) and also allows for the content to be scrolled over the image, rather than the image to be stretched and scrolled with the content.

## Technologies used
##### *These technologies were used to make/form the website:*
* Cloud 9 IDE
* HTML5
* CSS3
* Javascript and JQuery – used in conjunction with the collapse menu and the subscribe form modal.
* Bootstrap

##### *These technologies were used for command line interface, repositories and version control:*
* Bash
* Git
* GitHub

##### *These technologies were used to carry out testing of the website on simulated devices, as well as to check code and issues with code, prior to changing it on the actual Cloud9 workspace:*
* Google Chrome developer tools

##### *These technologies were used to design the wireframes/mock-ups of the website:*
* Marvel App (www.marvelapp.com)

## Testing
When testing the website, I carried out testing locally (on Cloud9), and on GITHUB pages using Chrome developer tools. On chrome developer tools I tested its functionality on simulated devices, in both portrait and the landscape views. The simulated devices that the website was tested on were:
* Galaxy S5
* Pixel 2
* Pixel 2 XL
* iPhone 5/SE
* iPhone 6/7/8
* iPhone 6/7/8 Plus
* iphone X
* iPad
* iPad Pro
* Responsive

All parts of the website were tested, including the links to social media and other parts of the website, the embedded videos, the ‘contact us’ form and ‘subscribe’ form were also tested locally (on Cloud9) and remotely too. They currently work, but aren’t functional due to my skillset limitation at this point.
I have also tested the website both locally and remotely on actual devices (rather than just simulated ones on Google Chrome tools), these devices consisted of:
* iPhone 6s
* iPhone 7
* iPhone X
* iPad (generation 2)
* Sony Xperia
* Multiple desktops (various sizes)

Some examples of the physical testing carried out by myself on certain parts of the site include:
* Contact us form:
    1. Go to the ‘Contact Us’ page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with all inputs valid and verify that the form submits and sends (but does not currently have a success message appear to inform the user)

* Subscribe form:
    1. Click on the ‘Subscribe’ button
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that the form submits and sends (but does not currently have a success message appear to inform the user)

When testing the website on various devices I encountered a bug with the fixed background image that was applied to the main content container. When viewing the website on the simulated mobile and tablet devices on google chrome tools, the fixed background worked fine and would allow the content to be scrolled, whilst the image remained fixed. Yet as mentioned, the functionality wasn’t working properly on the various mobile/tablet devices that I tested the website on (iPhone 6s, iPhone 7, iPhone X, iPad and Sony Xperia), as the background was stretched across the entire length of the content that was inside the main content container. So I opted instead to create a separate dedicated div for the background on mobile and tablet, which alters the picture slightly, but it allows for the picture to stay fixed and to cover the background of the webpage, (as opposed to covering the entire background of the content and therefore making it impossible to make out what the image is) and also allows for the content to be scrolled over the image, rather than the image to be stretched and scrolled with the content.

## Deployment
My website was coded in Cloud9. Once I had created the workspace in Cloud9 for my project to be built in, I then turned to GitHub (which is a web-based interface that links with Git and allows you to store and view the different versions of code at the stages it was pushed to the GitHub server) and created a repository for my milestone project, I then went back to Cloud9, and into the terminal I pasted in the Command Line Interface commands that GitHub had provided me with to create a local Git repository and form a link between Git and the GitHub server.

- *echo "# practice" >> README.md*
- *git init*
- *git add README.md*
- *git commit -m "first commit"*
- *git remote add origin https://github.com/Mcrowley93/strippedbeargamingmilestoneproject.git*
- *git push -u origin master*

Once I had done this, I was then able to use Bash script in the CLI at various stages to add changes I had made within the workspace, to the staging area (storing files is a 2 step process). This was done using the command: ‘*git add*‘ which could be followed with the specific file name/s that needed to be added to the staging area (prior to being committed to the repository). Alternatively, when there was a few changes that could be added all at once, the command was followed by a full stop (‘*git add .*’)

Once changes had been added to the staging area, they then needed to be commited (the 2nd stage of storing files) to the repository using ‘*git commit*’. However with each commit, I also included a message that explained the reason for each commit to the repository. This was done by using the command: ‘*git commit –m “text explaining commit goes here“* ‘

At this stage, the local Git repository could then be synced with the repository on the GitHub server, which was achieved by using the command: ‘git push’

Once the project/website was in the dedicated GitHub repository, it was then able to be made live in the settings by using GitHub Pages.

The website can be found here: https://mcrowley93.github.io/strippedbeargamingmilestoneproject/ 

## Credits
#### *Code used from previous work*

Code for the collapsed menu and the modal (for the subscription form) re-used from the whiskey-drop project (the bootstrap and grid system) section of this course. Have adapted the code I re-used to make it relevant to this project.

Code for the News page timeline, was reused from the Resume Webpage mini-project section of this course. As above, I have adapted the code that I re-used to make it relevant to this project.

#### *Code used from others*

Help with code for the responsive iframe boxes on the Media page taken from: *Author – Gregory Gan (https://blog.theodo.fr/2018/01/responsive-iframes-css-trick/)*

Help with code for attachment button in the ‘Contact Us’ form was reused from: *Author – Adam Bene (https://blog.benestudio.co/custom-file-upload-button-with-pure-css-5aacf39aa0a)*

#### *Media*

The media used in this project is as follows:

**Background images**

Playstation-wood:
https://pixabay.com/photos/playstation-controller-video-games-2617305/ 

Ps4-controller-green-light: 
Photo by Nikoloz Ergemlidze on Unsplash (https://unsplash.com/photos/v5STLzdFEPs?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText )

Ninendo-switch-green:
Photo by Jippe Joosten on Unsplash (https://unsplash.com/photos/0gNzcMqd0sw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText )

Ps4-controller-home:
Photo by Fabian Albert on Unsplash (https://unsplash.com/photos/-yePUylDPJQ?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText )

Ps4-controller-white:
Photo by Caspar Camille Rubin on Unsplash (https://unsplash.com/photos/HUBNTCzE-R8?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText )

Ps4-controller-blue:
Photo by Harpal Singh on Unsplash (https://unsplash.com/photos/eY9nCR7G0xw?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText )

**Logo images**

Bear-icon:
https://svgsilh.com/image/2660867.html

Ps4-controller-icon:
Author: needforbleed
https://opengameart.org/content/ps4-controller-icon  

**Reviews photos**

The-last-of-us-photo:
https://www.flickr.com/photos/ncarvajal/14887762785/sizes/m/

Anthem-photo:
https://www.flickr.com/photos/158561476@N06/46570491961/sizes/z/

Bloodborne-photo:
https://www.flickr.com/photos/65092514@N08/16516028163/sizes/z/

Breath-of-the-wild-photo:
https://www.flickr.com/photos/bagogames/32603960053 

**Youtube video content**

Anthem review by ACG:
https://www.youtube.com/watch?v=P65K_gNnCto

The Last of Us: Remastered review by Gamespot: 
https://www.youtube.com/watch?v=8-G3atTc9CE

Bloodborne review by Fungo:
https://www.youtube.com/watch?v=1hME5NaA46Y

The Legend of Zelda: Breath of the Wild review by IAmPeterCole:
https://www.youtube.com/watch?v=DzB86nNNohM 

**News info**

https://www.gamesradar.com/uk/destiny-2-season-of-the-drifter/

https://db.destinytracker.com/d2/en 

#### Acknowledgement

Inspiration for this project was taken from my own experience with using review sites like IG, as well as from my personal love of video games and gaming that is also shared with my best friend Daniel Kew, whom also donated a section to the “About Us” page and a review on The Legend of Zelda: Breath of the Wild to the “Reviews” page.
