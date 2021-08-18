# The Book Review

## Milestone 3 Project

The Book Review - my third milestone project - a site for book lovers and people who want to keep a lost of books that they have read/reviewed .
<!-- ## [Link to finished site](https://craigmantona.github.io/EPL-Memory-Game-1/) -->

A site for book readers to join and see and review books.

It is an easy to use site that has been made using CSS, HTML, Python3, MongoDB and Javascript.


<!-- <img src="/assets/images/mockup.png" alt="Images of site on different media screens."/> -->

#### A view of how the site looks over different media.
---
# Table of contents

- [UX](#ux)
    - [Website owner business goals](#website-owner-business-goals)
    - [User goals](#user-goals)
        - [As a site owner](#as-a-site-owner)
        - [As a visitor to the site](#as-a-visitor-to-the-site)
    - [User stories](#user-stories)
    - [Structure of the website](#structure-of-the-website)
    - [Wireframes](#wireframes)
    - [Surface](#surface)
- [Features](#features)
- [Technology](#technology)
- [Testing](#testing)
    - [Code Validation](#code-validation)
    - [Functionality testing](#functionality-testing)
    - [Compatibility testing](#compatibility-testing)
    - [User stories testing](#user-stories-testing)
    - [Issues found during site development](#issues-found-during-site-development)
    - [Performance testing](#performance-testing)
    - [Known bugs](#known-bugs)
- [Deployment](#deployment)
- [Credits](#credits)
- [Screenshots](#screenshots)

---
## UX


## User goals

## Website owner business goals

To create an easy to use visually appealing site where book lovers can see and leave reviews.


## User stories

### As a site owner
* I would like the site to be easy to navigate.
* I would like to clearly see what books users are recommending.
* I would like the ability to add/delete/edit reviews with admin abilities.
* I would like to be able to generate revenue from Amazon book links.

### As a visitor to the site
* I would like the site to be easy to navigate.
* I would like to clearly see what books are recommended.
* I would like to register and log in to keep a list of books that they have reviewed.
* I would like to be able to edit my reviews.
* I would like to be able to delete my reviews.
* I would like to know where to purchase a book from if I like it.


## Structure of the website

I have tried to make a website that is easy to access, and that has similar visuals/colour themes throughout. 
It should be fully accessible on a range of devices and simple to navigate for all.
I have asked some friends and family for their input and to test interaction

## Wireframes

I used the site https://www.balsamiq.com/wireframes/ to create the wireframes for the site.

-	[Mobile](static/images/mobile-view-wireframe.pdf)
-	[Desktop](static/images/web-view-wireframe.pdf)

## Surface

### Colors
Main colours used in a project:
* background: #fff3e0 an off orange selected from the Materialize colour pallette.
* navbar: brown darken-2 also taken from the Materialize colour pallette.
* cards: a contrast of orange lighten-4 and orange lighten-5 also taken from the Materialize colour pallette.



### Fonts 

* The Cinzel font is the main font used throughout the whole website with Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Cinzel is a clean and clear and stylish font, so it is both attractive and appropriate. 

___

<!-- # Features

The website consists of four pages. All are accessible from the main page. (Game page, team location page and contact page)

* Responsive on all device sizes
* Interactive elements

The website has below features: -->

<!-- ## Home

* ### Title 

    * There is a h3 title to let people know what site they are on.

* ### Rules of the game

    * This is a modal showing the simple instructions of how to play the game.

* ### Play Game

    * This button takes you to the game page.

* ### Team location

    * This take you to the team location page where you can see the location of all 20 Premier League clubs.

## Game page

* ### Home button

    * This allows the user to navigate back to the home page.

* ### Play again button

    * This allows the user to play the game again.


## Team location page

* ### Home button

    * This allows the user to navigate back to the home page.

* ### Google map

    * This shows the user where the location of all 20 Premier League clubs.

## Contact us page

* ### Home button

    * This allows the user to navigate back to the home page.

* ### Enquiry form

    * This is where you can send a message directly to us.


[Back to Table of contents](#table-of-contents)
___ -->
# Technology

### Languages Used
* HTML5
* CSS
* Javascript
* Python3

### Database Used
* MongoDB

### Frameworks, Libraries & Programs Used
1. Google Fonts:
    * Google fonts were used to import the 'Cinzel' font into the style.css file which is used on all pages throughout the project.
2. jQuery:
    * jQuery to make the navbar responsive.
3. Git
    * Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
4. GitHub:
    * GitHub is used to store the projects code after being pushed from Git.
5. Heroku:
    * Heroku was used to deploy the project.
6. Materialize:
    * Materialize was used for the layout, styling, visual appearance and responsiveness on the website.
7. PyMongo:
    * PyMongo was used as the Python driver for MongoDB.
8. Jinja:
    * Jinja was used as a templating engine for Python.
9. Flask:
    * Flask was used as a web framework for Python.
10. Balsamiq:
    * Balsamiq was used to create the wireframes for the project.
11. Font-Awesome:
    * Font-Awesome was used ifor the icons throughout the website.
12. Werkzeug:
    * Werkzeug was used is a comprehensive WSGI web application library.


[Back to Table of contents](#table-of-contents)
___
# Testing

## Code validation
The Webformatter.com Markup Validator were used to validate every page of the project to ensure there were no syntax errors in the project for both HTML and CSS.

* [HTML, CSS and JavaScript code checked through HTML/CSS/Javascript Formatter](https://webformatter.com/html) No issues found

## Functionality testing 

 I used Chrome developer tools throughout the project for testing and solving problems with responsiveness and style issues.
 

## Compatibility testing
 Site was tested across several virtual mobile devices and browsers.
 
 I tested on hardware devices such as: iPad pro, Macbook, Windows Desktop and iPhone11.


## User stories testing

### As a site owner:

- I would like the site to be easy to navigate.
    * The site is simple to navigate.
- I would like to clearly see what books users are recommending.
    * The yellow 'tick' next to recommended books is visualy easy to see.
- I would like the ability to add/delete/edit reviews with admin abilities.
    * There is a delete and edit facility to remove or ammend any reviews that the user has submitted.
- I would like to be able to generate revenue from Amazon book links.
    * There is a link to purchase the book from Amazon if the book is available (currently not working!)



### As a visitor:

- I would like the site to be easy to navigate.
    * The site is simple to navigate.
- I would like to clearly see what books are recommended.
    * The yellow 'tick' next to recommended books is visualy easy to see.
- I would like to register and log in to keep a list of books that they have reviewed.
    * There is a register and log in/out function.
- I would like to be able to edit my reviews.
    * There is an edit facility to ammend any reviews that the user has submitted.
- I would like to be able to delete my reviews.
    * There is a delete facility to remove any reviews that the user has submitted.
- I would like to know where to purchase a book from if I like it.
    * There is a link to purchase the book from Amazon if the book is available (currently not working!)


---
## Issues found during site development

* The API site that I signed up to use on the site proved to be unreliable and I had to abandon it in favour of the google map api.

* The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.

* The website was viewed on a variety of devices such as Desktop, Laptop, iPhone8, iPad Pro & iPhone11.

* Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

* Issue with getting the cards to flip caused a lot of headaches. I got a friend (Palmjit Kunnar) to cast his eyes over my js code and he found my problem. I had accidentaly left some code out of the curly brackets that meant the js always stopped after the first click.
<img src="/assets/images/flip-issue.png" alt="Images of cards staying turned after click in error."/>


## Performance testing

I ran [Lighthouse](https://developers.google.com/web/tools/lighthouse/) tool to check performance of the website.
Screenshots are presented below:

<img src="/assets/images/lighthouse.png" alt="Images of performance from Lighthouse."/>


### Known bugs
The bottom of the cards on the game screen are slightly off the bottom of the screen.

---

# Deployment

This project was made using GitHub and GitPod.

How to deploy this page to GitHub pages from the repository:

1. Log in to GitHub
2. Select the repository craigmantona/EPL-Memory-Game-1
3. Under the repository name, click Settings.
4. Under "GitHub Pages", use the None or Branch drop-down menu and select a publishing source.
5. Optionally, use the drop-down menu to select a folder for your publishing source.
6. Click Save.

Alternatively tou can pull the code from the GitHub repository:

1. On GitHub, navigate to the main page of the repository.
2. Above the list of files, click Code.
3. To clone the repository using HTTPS, under "Clone with HTTPS", click the folder looking icon. To clone the repository using an SSH key, including a certificate issued by your organization's SSH certificate authority, click Use SSH, then click the folder looking icon. To clone a repository using GitHub CLI, click Use GitHub CLI, then click the folder looking icon.
4. Open Terminal.
5. Change the current working directory to the location where you want the cloned directory.
6. Type git clone, and then paste the URL you copied earlier.
7. Press Enter to create your local clone.

[Back to Table of contents](#table-of-contents)
___

# Credits

### Code
* Code learned through the Code Institute Full Stack Development course was used throughout the site.

* Bootstrap4: Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

* Deployment instructions used from GitHub help pages

* README file template from Code Institute used as a guide. <a href="https://github.com/Code-Institute-Solutions/SampleREADME"></a>

* code learnt through freeCodeCamp.org video on YouTube for Memory Game <a href="https://www.youtube.com/watch?v=ZniVgo8U7ek&t=1733s"></a>

### Content
* All content was written by the developer.

### Links and images

1. Photo by Dom Le Roy from Pexels stadium photo - https://www.pexels.com/photo/people-sitting-on-stadium-seats-3991976/
2. Arsenal flag - Image by <a href="https://pixabay.com/users/jorono-1966666/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3568936">jorono</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3568936">Pixabay</a>
3. Chelsea - Image by <a href="https://pixabay.com/users/jorono-1966666/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2699594">jorono</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2699594">Pixabay</a>
4. Leicester - Image by <a href="https://pixabay.com/users/jorono-1966666/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3566688">jorono</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3566688">Pixabay</a>
5. Liverpool - Image by <a href="https://pixabay.com/users/jorono-1966666/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2698969">jorono</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2698969">Pixabay</a>
6. Man City - Image by <a href="https://pixabay.com/users/jorono-1966666/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2697766">jorono</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2697766">Pixabay</a>
7. Wolverhampton Wanderers - Image by <a href="https://pixabay.com/users/jorono-1966666/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3568910">jorono</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=3568910">Pixabay</a>
8. Badge - Image by <a href="https://pixabay.com/users/clker-free-vector-images-3736/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=308943">Clker-Free-Vector-Images</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=308943">Pixabay</a>


### Acknowledgements
* My Mentor Adegbenga Adeye for assistance and feedback - he's great!

* Tutor support at Code Institute for their support.

* My friend Palmjit Kunnar for his help on finding my error in my js game code!

[Back to Table of contents](#table-of-contents)
___

# Screenshots

## Project screenshots

Home page on website <img src="/assets/images/home-page.png" alt="Home page on website."/>

Rules modal on website <img src="/assets/images/rules.png" alt="Rules of game pop-up."/>

Team location page on website <img src="/assets/images/team-location.png" alt="Team location page on website."/>

Contact page on website <img src="/assets/images/contact.png" alt="Contact page on website."/>

Game page on website <img src="/assets/images/game-page.png" alt="Game page on website."/>