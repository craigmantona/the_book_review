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
* home page info box #4e342e a tonal brown color to fit the theme of the site



### Fonts 

* The Cinzel font is the main font used throughout the whole website with Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Cinzel is a clean and clear and stylish font, so it is both attractive and appropriate. 

___

# Features

The website consists of six pages. The Login, Register, Book Reviews, Add Book, Edit Book and Info page accessed through the logo from the navbar.

* Responsive on all device sizes
* Interactive elements

The website has below features: 

## Home

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
* [Python code checked through PEP8 Online Formatter](http://pep8online.com/checkresult) No issues found

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

* The Amazon link is not diverting to Amazon but instead opens up a duplicate of the current page.

* The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.

* The website was viewed on a variety of devices such as Desktop, Laptop, iPhone8, iPad Pro & iPhone11.

* Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

* When My Profile page was loaded no books were being shown. I have removed the page for now as I didn't feel it was essential as all functions could be used from the Home page. I will look to add this functionality at a later date.



## Performance testing

I ran [Lighthouse](https://developers.google.com/web/tools/lighthouse/) tool to check performance of the website.
Screenshots are presented below:

<img src="/static/images/lighthouse-report.png" alt="Images of performance from Lighthouse."/>


### Known bugs

No Amazon link for The Hunger Games book entry.

<img src="/static/images/lotr.png" alt="Lord of the Rings card with Amazon link"/>
<img src="/static/images/hunger-games.png" alt="The Hunger Games card without Amazon link"/>

I will look into rectifying this in a later edition.

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

Configuring GitHub integration

To connect a Heroku app with a GitHub repo, go to the app’s “Deploy” tab on Heroku Dashboard and select the GitHub pane. If you haven’t connected your Heroku and GitHub accounts, you will be prompted to complete the GitHub OAuth flow. Heroku needs access to help you select repos and to be able to register webhooks triggered when you push to GitHub. Once connected, you can select which repo associated with your GitHub account to link to the Heroku app.

<img src="/static/images/heroku-deploy.png" alt="Deployment image from Heroku."/>

With app and repo connected, you can either manually deploy a specific branch, or select a Git branch that will be auto-deployed whenever it’s pushed to on GitHub.

For auto-deploys, you can optionally configure Heroku to wait for continuous integration (like Travis CI) to pass on GitHub. With that option enabled, Heroku will only auto-deploy after all GitHub statuses for that commit have succeeded.

Any builds created by the GitHub integration can be tracked in the app’s “Activity” tab and build output for running builds is streamed in Dashboard.

[Back to Table of contents](#table-of-contents)
___

# Credits

### Code
* Code learned through the Code Institute Full Stack Development course was used throughout the site.

* I used the base code learnt through the walkthrough project, Task Manager, and used this as a template for my project. This was a huge help in getting the basics of the site. I they added my own custom code to the project.

* Deployment instructions used from GitHub help pages

* Deployment instructions for Heroku used from the Heroku integration page 

* README file template from Code Institute used as a guide. <a href="https://github.com/Code-Institute-Solutions/SampleREADME"></a>


### Content
* All content was written by the developer.

### Links and images

On info page the library image came from:
Image by <a href="https://pixabay.com/users/pexels-2286921/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1281581">Pexels</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1281581">Pixabay</a>


### Acknowledgements
* My Mentor Adegbenga Adeye for assistance and feedback - he's great!

* Tutor support at Code Institute for their support.


[Back to Table of contents](#table-of-contents)
___

# Screenshots

## Project screenshots

Info page on website <img src="/static/images/info-page.png" alt="Info page on website."/>

Book Review page on website <img src="/static/images/book-review-page.png" alt="Book Review page on website."/>

Add book page on website <img src="/static/images/add-book-page.png" alt="Add Book page on website."/>

Login page on website <img src="/static/images/login-page.png" alt="Login page on website."/>

BRegister page on website <img src="/static/images/register-page.png" alt="Register page on website."/>