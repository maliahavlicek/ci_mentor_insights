# OVERVIEW

This template was made as a guide to ensure you cover assessment criteria in your fourth portfolio write up. It is specific to the **PORTFOLIO 5: Full-Stack Toolkit** project.

## Helpful tools

### Screenshots and Videos
**Here’s a great video on how to add videos to your readme! no need to convert to gifs!!**

https://www.youtube.com/watch?v=G3Cytlicv8Y

> 1. record a video via slack
> 2. download it
> 3. in github, edit your readme via the pencil icon
> 4. type a place holder word and highlight it
> 5. drag and drop mp4 file over that text
> 6. scroll down to the commit area
> 7. update the default commit message
> 8. click the green button
> 9. ```git pull``` changes to your gitpod workspace

**You can do the steps 3-9 for the image/screenshot uploads too!**

### Cheatsheets and Auto Generation Tools

Markdown's not all that easy so sometimes you may want to use some tools to make tables.

- [Markdown Cheatsheet](https://guides.github.com/features/mastering-markdown/)
- [markdown table generator](https://www.tablesgenerator.com/markdown_tables) - used to help with documentation table formatting
- [markdown table of contents generator](https://ecotrust-canada.github.io/markdown-toc/) - used to create table of contents (be weary it does have some bugs if you have dashes or trailing spaces in your headers)
- [readme.so](https://readme.so/) - if you don't want to learn markdown, this tool might help you

# Table of Contents
Copy your readme to http://ecotrust-canada.github.io/markdown-toc/ to make a table of contents.  This will help assessors to see the structure of your readme. Just test it out ast this tool isn't perfect. It tends to mess up with special characters like dashes.

- [PROJECT_NAME](#project_name)
  - [Author](#author)
  - [Project Overview](#project-overview)
- [UX](#ux)
  - [Target Audience](#target-audience)
  - [Goals](#goals)
  - [User Stories](#user-stories)
  - [Initial Stories](#initial-stories)
  - [Feasibility vs Importance](#feasibility-vs-importance)
  - [Scope](#scope)
  - [Design Choices](#design-choices)
  - [Wireframes](#wireframes)
- [Information Architecture](#information-architecture)
  - [Entity Relationship Diagram](#entity-relationship-diagram)
  - [Database Choice](#database-choice)
  - [Data Models](#data-models)
- [Agile Process](#agile-process)
  - [GitHub User Stories](#github-user-stories)
  - [Iterations](#iterations)
  - [Progress Boards](#progress-boards)
- [Features](#features)
  - [Implemented Features](#implemented-features)
  - [Future Features](#future-features)
- [Testing](#testing)
  - [Cross Browser and Cross Device Testing](#cross-browser-and-cross-device-testing)
  - [Accessibility Testing](#accessibility-testing)
  - [Validation Testing](#validation-testing)
  - [Automated Testing](#automated-testing)
  - [Defects](#defects)
  - [Defects of Note](#defects-of-note)
- [E-commerce Business Model](#e-commerce-business-model)
  - [Facebook Business Page](#facebook-business-page)
  - [Newsletter Signup](#newsletter-signup)
  - [Links](#links)
  - [SEO Strategy](#seo-strategy)
- [Deployment](#deployment)
  - [Prerequisits](#prerequisits)
  - [Fork and Clone the Repository](#fork-and-clone-the-repository)
  - [Development Deployment](#development-deployment)
  - [Production Deployment](#production-deployment)
- [Credits](#credits)
  - [Content](#content)
  - [Media](#media)
  - [Acknowledgments](#acknowledgments)

====================================== The Sections you Fill in are below ==============================


# PROJECT_NAME

*replace the **PROJECT NAME** header with your project's name*
- Screenshot of logo/navigation of mobile deployed site
- Include a link to deployed project with one line explanation of project


## Author
DEVELOPER_NAME


## Project Overview
🚨**Required**

- Include a picture of site that shows it in responsive states and links to deployed
  code: https://ui.dev/amiresponsive
- One or two paragraphs providing an overview of your project.
- Write this as a sales pitch or commercial making users want to purchase your website.
- Include a link to your deployed website

# UX

Your site is most likely geared to a certain audience and goals for the business owner and users of the site, and your
design choices should tie into them. Let the assessors know your thought process.

If you don't feel like the overview gave enough detail about the site, you can write up what you are expecting users to
actually do on your site, book things, find thing then lead into the goals and target audience.

## Target Audience
🚀 **merit & beyhond**

Can be a paragraph or a list

> **Paragraph Example**
> The target audience for What2do2day comes in two flavors. The revenue driving forces is children ages 12-18 who have a bit of freedom to move around unsupervised but very little means to addend costly mass entertainment complexes more than 5 miles from home. Their parents are expected to be a customer group too as they will want to ensure the site is safe and not a predatory place where their kids could be scammed into unsafe adventures. Other groups of users are the businesses that want to promote themselves as community friendly who will be hosting events for the primary customer group. The business owners will want a friendly interface to upload details of their place and events.

> **List example**
> 1. Patients who have been referred for radiology examinations by registered physicians
> 2. External healthcare companies who have equipment to sell
> 3. Radiology staff who want to have a more manageable and predictable workload

## Goals
🚀 **merit & beyhond**

Bullet point out things from web users to website owners and other groups of people

**Booking Site Example**
> - To allow the opportunity for patients to book and manage their own radiology appointments
> - To give patients the opportunity to educate themselves on radiation safety prior to their visit
> - To provide a simple-to-use contact form for site visitors to use in order to contact the radiology department
> - To provide useful information to patients about radiology and the department to reduce 'white-coat-syndrome' and anxiety during their visit
> - To give external companies the opportunity to partner with the radiology department and share their equipment prior to potential purchases
> - To give radiology staff the opportunity to manage their workload and see in advance the patients they will encounter during the day

**Granular Goals Example**
> **Customers**
> Customers of What2do2day are children ages 12-18 who have a bit of freedom to move around unsupervised but a short range of mobility, approximately 5 miles from home.
>
**Customer Goals:**
> - Bring up the site and look for an inexpensive event to attend close to home
> - Look at places to see how they rank without having to read much
> - Quickly find activities that interest them without having to type much
> - Read reviews about places that interest them
> - See events related to places that interest them
> - Easily know where an event they are interested in is located
> - Join an event of interest
> - See how many others are interested in an event
> - Receive notification about an event they've joined
> - Receive updates about events they've joined
>
> **Place Owners**
> Owners of Places would ideally have a different set of user permissions and the Update and Contribute sections of navigation would be under a strict workflow, but in the initial phase, I wanted to show off the ability to add, update and delete items from the website's view,so it's not hidden behind permissions or workflow at this point. Place owners are those that have a business or an organization that hosts free events within a community. Examples are a group that wants to play pickup soccer or a bicycle shop that leads group rides once a month.
>
> **Place Owner Goals:**
>
> - I want my place to be easily found on the site, so I can get more customers
> - I want users to share community reviews, so I build trust with future customers
> - I want to add events to my place, to build a repertoire with my clients
> - I want users to join my events, so I can track how successful community events are to my bottom line
> - I want the ability to update my place's details
> - I want to update events associated with my organization
> - I want to protect against bloated ratings
> - I want to protect against accidental deletion of my information
>
> **WebSite Goals**
> The primary goal of what2do2day is to create a user-friendly app that allows customers to quickly find an event they want to attend. It's a meeting point between business/organizations and kids/parents to improve the likelihood of kids getting off their devices and interacting with others face to face at a low cost with minimal adult supervision.
> In order to support the maintenance and development of cool features on the site, what2do2day hopes to produce monetary gains through the following means:
> - Workflow Management Plans for Businesses around:
    >
- oversee approval/disapproval of reviews to ensure spamming and bad-mouthing in reviews does not occur
>   - batch event creation to help save time
>   - user account management to help with password recovery and assigning or removing roles as employees change
>   - sharing of user emails that attend events
> - Affiliate linking - link to at-cost services provided by businesses and receive a kickback
> - Ads - target online sales related to equipment based on activities a place or event is associated with

## User Stories
🚨**Required**

User stories evolve over a project's lifetime. Start with a wish list, do a feasibility analysis then move the ones you
will work on into gitHub, so you can track their progress.

## Initial Stories
🚨**Required**

To start the agile process this section kicks off with a bullet list/brainstorming dump about features you'd like to
have. EVERYTHING write them out in bullet form:

- As a 'user type' I 'to perform an action' so that I can 'achieve a goal'

**Examples**

- [radiology booking](https://github.com/DeannaCarina/ELHTRadiology#user-stories)
- [places/events searching site](https://github.com/maliahavlicek/what2do2day#user-stories)

## Feasibility vs Importance
🚀 **merit & beyhond**

To scope the project for a MVP (minimally viable product) a feasibility analysis was done.

The features in the table below have been taken from the user stories above. Generic features found in most websites
will also be implemented such as nav-bar, footer, obvious website purpose etc.

| Opportunity/Feature | Feasibility/Viability (score out of 5) | PurposeLevel of Importance (score out of 5) | In Or Out |
|---------------------|----------------------------------------|---------------------------------------------|-----------|
|                     |                                        |                                             |           |
|                     |                                        |                                             |           |
|                     |                                        |                                             |           |
|                     |                                        |                                             |           |

> You should discuss the outcome of what you will be dropping based on the outcome. Making a scatter plot of the scores and coloring the dot

## Scope
🚀 **merit & beyhond**

Now you have to talk about the scope to reduce things more, you don't necessarily need all the bells and whistles, they
could be beyond your skill set. Think basic stuff.

## Design Choices
🚀 **merit & beyhond**

Now that you have let the assessors know about the target audience and users, you can go into the design choices

### Colors
🚀 **merit & beyhond**

- Discuss your color pallet choices and how it ties into users' emotions or target audience.
- include a screenshot of your pallet using a tool like coolors.co

### Typography
🚀 **merit & beyhond**

- discuss font size, font types for headers vs buttons vs general text and how it ties into users' emotions or target
  audience.
- include screenshots of fonts used and links to the appropriate website ex) https://fonts.google.com/specimen/Raleway

### Images
🚀 **merit & beyhond**

Explain why you used certain icons and images on your site

### Design Elements
🚀 **merit & beyhond**

- list out the type of elements you want to use on your site, this will help you when choosing a framework and goes hand
  in hand when doing the wireframes. If you did something out of the ordinary, or think something was particularly
  clever, add a sentence and a screenshot or reference the file the code or css is in.

> - desktop navigation
> - mobile navigation
> - footer
> - containers/cards
> - buttons
> - text input
> - textarea inputs
> - dropdowns
> - modals/layers
> - check boxes
> - switches
> - accordions/drawers
> - pagination
> - date pickers
> - maps
> - images
> - tooltips
> - icons
> - tabbed content
> - file pickers
> - video players
> - audio players

### Animations and Transitions
🚀 **merit & beyhond**

- discuss any special animations or transitions you've programmed
- special hover state effects

### Frameworks
🚨**Required**

- If you use bootstrap, tailwind, bulma, materialize or some other JS/CSS framework, call it out here and why you made
  that choice. (Typically I look at the design elements I want and make sure the framework supports them)

### Custom Styles
🚨**Required**

- call out any overrides you did for bootstrap styles or the framework you used, even if they are fonts and colors,
  perhaps lead assessors to the file of interest in your repo

### Custom Javascript
🚨**Required**

- call attention to any custom javascript you created to help your User Experience you can organize this by functions or
  files

## Wireframes
🚨**Required**

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of
the design process. These files should themselves either be included as a pdf file in the project itself (in a separate
directory), or hosted elsewhere online and can be in any format that is viewable inside the browser.

- You should minimally have wireframes for desktop and mobile for the pages you are making for you register, login,
  read(list/detail), add, update, delete functionality. Adding a Tablet view will help you get into merit and
  distinction.

You can hand draw these, but CI posts a yearly license in the general channel for Balsamiq which is pretty easy to use.
Here is the [2022 announcement](https://code-institute-room.slack.com/archives/C0L316Z96/p1640099614368000)


# Information Architecture
As part of the requirements for this project you need to have at **least 3 custom data models**.  It's still under discussion what that means, but I'd make 1 original and then update the products to be custom to what you are selling and create another new one. It's this section that discusses your data and how each piece relates to another and draws out the CRUD functionality you built. You must have CREATE, READ, UPDATE & DELETE for at least one model.

## Entity Relationship Diagram
🚨**Required**

Wade Williams wrote a great blog about how to add a django extension to auto create an ERD. https://wadewilliams.com/technology-software/generating-erd-for-django-applications/ You can always draw one out by hand or google sheets. You can also draw this up by hand if you want or use a spreadsheet to show your data model.

## Database Choice
🚀 **merit & beyhond**

Just state you used postgres as the database because the data is relational and heroku serves this up realitvely easily with no cost.

## Data Models
🚨**Required**

Show the accessors you know your data. If you end up using some data models from an example project, call that out and don't be as detailed about writing those up unless you added to them.

Each data model that you created yourself should have its Fields, Field Type and any validation documented.  You should also cross-reference any code in your repository that relate to CREATE, READ, UPDATE, DELETE operations for these models.

*Below is an example of a write up for an Activities Data Model*

> ### Activities Model
> Activities is a table to hold a unique icon image and name values that users have associated with events and places. It helps with sorting events and prevents the need from carrying around two data objects in the larger Events and Places data structures. The purpose of an Activities object is to provide an imagery association to a category.
> 
> | DB Key 	| Data Type 	|          Purpose          	| Form Validation                        	| DB processing    	|
> |--------	|:---------:	|:-------------------------:	|----------------------------------------	|------------------	|
> | _id    	| ObjectId  	| unique identifier         	| None                                   	| n/a              	|
> | name   	| String    	| Name of Activity          	| Required<br>Min 1 char<br>Max 50 chars 	| trim<br>to lower 	|
> | icon   	| String    	| system path to image file 	| Required                               	|                  	|
> 
> Activity entries are used by events, places and filtering.
> 
> - [x] Create - An activity is potentially created when a user successfully creates a place, creates an event, updates an event, or updates a place.
> - [x] Read - The Activities table is read when a user is adding an event, updating an event, adding a place or updating a place, to determine if a new value should be created or not. The activities table is queried for using the name and icon pair, if it is found, the ObjectId is passed to the event and places. If no match is found, a new Activity is created and that ObjectID is passed to the the place or event.
> - [ ] Update
> - [ ] Delete
> 
>  This table has no deletion or updates associated with it. It's strictly create and read. Eventually, maintenance scripts should be written to delete unused/deprecated entries.

> The reading/writing of the activities table is housed in the [what2do2day/activities/views.py](what2do2day/activities/views.py) file.

### CRUD Diagrams
🚀 **merit & beyhond**

This is if you want to go for distinction.  You can also have CRUD diagrams to show them visually how the model is used in your site.

I used [draw.io](https://app.diagrams.net/) and hooked it up to my google drive to create the screenshot below

![image](https://user-images.githubusercontent.com/23039742/154406188-c9beb57a-2fd1-4f26-a8ed-bee320e46e3d.png)


# Agile Process

## GitHub User Stories
🚨**Required**

Now you are ready to start using Git Hub Issues to write your user stories. To get to merit levels you need to show you
have refined stories from Epics to Generic User stories.

### User Story Templates
🚨**Required**

[Here's the lesson](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+AG101+2021_T1/courseware/a4e548ca70)
on how to create a User Story Templates.

If you want a chance at **DISTINCTION**, I'd suggest the following:

- Create an Epic Story template, this would have a title, the story and children stories
- Create a User Story template, this would initially have the title, the story, and a link to the Epic. Then you'd come
  back when you are prioritizing it to include the acceptance criteria, and story points, then again when you are
  working on it and fill in the tasks and adjust the story points if needed.
- Name your stories in a way that it's easy to tie the children to the EPICS by name.

Example:
EPIC: Navigation As a user, I want to have easy to see navigation on the page, so I can intuitively interact with the
site without getting frustrated.

USER STORY: Navigation: Create Template As a developer, I don't want to have copy and paste my navigation on every page.
I want to use a template to house this information, so my code is easier to maintain.

USER STORY: Navigation: Desktop As a user I want clear navigation that is up to industry standards for my desktop
experience, so I can easily find what I need on a website.

USER STORY: Navigation: Mobile As a user I want clear navigation that is up to industry standards for my mobile
experience, so I can easily find what I need on a website without the

[Here is a quick link](https://github.com/maliahavlicek/go-hrvatska/tree/master/.github/ISSUE_TEMPLATE) to some templates I set up for these
[Here is the UX for those templates where you choose a new type of issue](https://github.com/maliahavlicek/go-hrvatska/issues/new/choose)

screenshot of EPIC new issue using template
![image](https://user-images.githubusercontent.com/23039742/165651624-7ff6c839-1824-48df-81a3-fda444f2d7f5.png)


screenshot of USER_STORY new issue using template
![image](https://user-images.githubusercontent.com/23039742/165651758-beac7bc6-f62f-42e5-b8a0-feeefafcd5b4.png)


Note: You can play around with the labels to add an EPIC one and a USER_STORY one or even ones for each MAJOR epic you have or page
https://github.com/maliahavlicek/go-hrvatska/issues/labels 
![image](https://user-images.githubusercontent.com/23039742/165651335-46ab8ff3-4014-4e55-a29d-35e1d998fb42.png)


**What to keep in this section**

- include links and/or screenshots of your story template(s)

### Product Backlog
🚨**Required**

https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+AG101+2021_T1/courseware/a4e548ca70a3473aa890ba2ab9bf612c/085f3a8e344a4cf28b5b5355399abcc1/?child=last
This is the MILESTONE where you grab stories from the issues or USER stories you created and prioritize them and order
them, leave the epics out.

**What to keep in this section**
Include a link to your Product Catalog Milestone,

an initial screenshot, mid-point and final will help document the agile process.

## Iterations
🚀 **merit & beyhond**

https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+AG101+2021_T1/courseware/a4e548ca70a3473aa890ba2ab9bf612c/71fe6c52cccf477688e924c9889f5fec/?child=first

Add links to iteration milestones (most people have ONE iteration since they are the solo worker, just state that here),
it could be that you won't have all your product backlog worked in the end, and that is ok, hte MVP might morph, you
might find other stories you want instead, it's OK.

## Progress Boards
🚀 **merit & beyhond**

https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+AG101+2021_T1/courseware/a4e548ca70a3473aa890ba2ab9bf612c/7ad7f487cc6148ecb182d77feaeda269/?child=first
Add links to Progress boards

# Features
🚨**Required**

In this section, you should go over the different parts of your project, and describe each in a sentence or so and how they tie into  your user stories.

## Implemented Features

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

It's easiest to break this section down into the header, footer, and each page/layer of your website. Call out any differences for mobile vs desktop presentations, **include a screenshot of the implemented feature** and **at least 2 bullet points of their importance**.

**Required for passing**
- Authentication Process
- Custom 404 
- Facebook Business page
- Newsletter signup Form

## Future Features
🚀 **merit & beyhond**

Use this section to discuss plans for additional features to be implemented in the future:

If you end up not developing some features you hoped to implement, you can include those in this section.

# Testing
🚨**Required**

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that
the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and
ensure that they all work as intended, with the project providing an easy and straightforward way for the users to
achieve their goals.


**At this point, you should use gitHub Issues Templates and Test Case** to track test cases and defects. Here's
a [document](https://docs.google.com/document/d/1nDS5tZeMO77Dfq85IZGMSV6C41XaPm9FwcpR3k-UTVc/edit#heading=h.3kdbr3tqbzi)
I put together for this process.

You should make sure your test cases cover the following: 
## Cross Browser and Cross Device Testing
🚨**Required**

To save time, you can create this type of table
in [markdown table generator](https://www.tablesgenerator.com/markdown_tables)

As of Feb 14, 2022 CI students can take advantage of the Student Developer Pack where you have access to great things
like [browserstack](https://education.github.com/pack/offers/#browserstack) You should have received an email about how
to activate your student Developer Pack, here's
a [slack](https://code-institute-room.slack.com/archives/C0L316Z96/p1644946870567999) with details if you can't find it
in the associated thread.

Start with a brief explanation of why you chose the mixture you did. The point is to prove that you looked at the site
across various browsers, operating systems, and viewport breakpoints. You can add a column about the spot checking path
you took or write it out here:

1. Visit https://gs.statcounter.com/browser-market-share to figure out the most popular browsers & operating system combos seen across the we for the geographic region, and platoform(s) and screen sizes you expect your users to belong to. 

1. Include a sentence about why you chose the combinations you did.

1. Create a table that lists out what devices, browsers, and operating system you tested your application on and a brief description of why you chose the mixture you did. The point is to prove that you looked at the site across various browsers, operating systems, and viewport breakpoints.

1. if you can't find the brower/device/OS combinations you want on Browserstack with your github student webpack (or you didn't activate that in time), note what you'd ideally test on then what you ended up testing on as a compromise. 

> **Example:**
> To ensure the code was functional and looked good on varoius devices I tested a couple of generic flows though my site on using the following Tool/Device combinations. The device/browser/and OS combinations were used based on reports found at [browser market share](https://gs.statcounter.com/browser-market-share) taken on MM/DD/YYYY:
>
> | TOOL / Device                 | BROWSER     | OS         | SCREEN WIDTH  |
> |-------------------------------|-------------|------------|---------------|
> | real phone: motog6            | chrome      | android    | XS 360 x 640  |
> | browser stack: iPhone5s       | safari      | iOs        | XS 320 x 568  |
> | dev tools emulator: pixel 2   | firefox     | android    | SM 411 x 731  |
> | browserstack: iPhone 10x      | Chrome      | iOs        | SM 375 x 812  |
> | browserstack: nexus 7 - vert  | Chrome      | android    | M 600 x 960   |
> | real tablet: ipad mini - vert | safari      | iOs        | M 768 x 1024  |
> | browserstack: nexus 7 - horiz | firefox     | android    | LG 960 x 600  |
> | chrome emulator: ipad - horiz | safari      | iOs        | LG 1024 x 768 |
> | browserstack                  | Chrome      | windows    | XL 1920 x 946 |
> | real computer: mac book pro   | safari 12.1 | Mohave     | XL 1400 x 766 |
> | browserstack                  | IE Edge 88  | windows 10 | XL 1920 x 964 |
>
> Here is a link to the [test case](https://github.com/maliahavlicek/ci_mentor_insights/issues/9).

Note, you might find it easier to create a test case for each tool/device and link to the test case in the table here.

## Accessibility Testing
🚨**Required**

You should have test cases for accessibility and links to them here. Start with a brief paragraph and then link to the
test cases. If you are ambitious you can record the screen of you using the keyboard, convert it to a gif and upload it
to the test case too.

**example**
> To ensure that the site was accessible to people with visual impairments, I used chrome's dev tools, lighthouse audits to ensure I had a score in the green for accessibility and that I could keyboard navigate through the page.
>
> Here are links to the test cases for each which contains the screenshot for the lighthouse audit.
> - [home page accessibility test](https://github.com/maliahavlicek/ci_mentor_insights/issues/12)
> - [experience page accessibility test](https://github.com/maliahavlicek/ci_mentor_insights/issues/13)
> - [skills page accessibility test](https://github.com/maliahavlicek/ci_mentor_insights/issues/14)
> - [recommendations page accessibility test](https://github.com/maliahavlicek/ci_mentor_insights/issues/15)
>
> To ensure the site was accessibility to people with physical impairments, I tried to navigate the site using tabbed navigation:
> - [site tabbed navigation test](https://github.com/maliahavlicek/ci_mentor_insights/issues/10)

You can totally combine the tabbed navigation in the accessibility test and have 2 expected criteria, it's all up to
you!

## Validation Testing
🚨**Required**

You should try to ensure you code is valid and follows proper indentation. In this section you should write up any
websites you used to validate your code so there is credit given to those sites. Then add links to the test cases you
put into GitHub for the validation. You can copy your validation success to those tests.

The following site were used to aid in validation testing:

- **[CSS Validator](https://jigsaw.w3.org/css-validator/)**

> If you only have one CSS file, you can just run the validator through one deployed page URL, if you have custom CSS for diffent pages, make sure you hit those different URLS

- **[HTML Validator](https://validator.w3.org/)**

> For each view you wrote, you should validate the HTML and have a test case for it linked to from here
> NOTE: You may need to right-click to view the source of each page and paste that into the validator if you need to go through authentication to get to the page.

- **[JS validation](https://jshint.com)**

> for each .js file, copy the code and paste it into this site, and have a test case for it linked to from here. You can have warnings, but no errors.
> if using ES6, add this before pasting in your file: `/*jshint esversion: 6 */ `, similarily you can update it to 7 if you see warnings about ES7 syntax `/*jshint esversion: 7 */ `

- **[CI's pep8 tool](https://pep8ci.herokuapp.com/)** 

> for each .py file you created, copy the source code and paste it into this site, and have a test case for it linked to from here.
> include a screenshot of results in the test case showing NO ERRORS. (you should do this for all .py files in your repo)
> 
> **run.py**
> 
> ![image](https://user-images.githubusercontent.com/23039742/212106175-36b2f18a-7c75-458d-94dd-9886e81c71f3.png)

> Ideally you would have no errors remaining outside of line too long which you can fix by 
> 
> adding
> ```$python 
> # noqa
> ```
> There is a space before the # and after it to skip the quality assurance for that line.
> 
> Note any errors or warnings you are ignoring and why.

- **[JSON validation](https://jsonlint.com/)**

> for each .json file, you should copy the code and paste it into this site, and have a test case for it linked to from here.

## Automated Testing
🚀 **merit & beyhond**

**NOTE: If you want MERIT or Higher, you MUST have some automated testing**
If you managed to write jasmine tests or some django tests, note those files out here and how to run them.

https://github.com/maliahavlicek/ms4_challenger/blob/master/documentation/TESTING.md is my write up about my automated testing and how I ran them, but a simple test I'd recommend is a views test that tests authentication and any views you limit to superusers or logged in users.

https://github.com/maliahavlicek/ms4_challenger/blob/master/challenges/tests/test_views.py

## Defects
🚨**Required**

At this point you really should be using GITHUB's Issues to track these as it helps you with the AGILE process
requirement as it's really easy to copy/paste screenshots in and then write up how you closed them.

[Here's a brief overview](https://docs.google.com/document/d/1nDS5tZeMO77Dfq85IZGMSV6C41XaPm9FwcpR3k-UTVc/edit#heading=h.542xzc8ufx4x)
I put together on how to do this.

is what my custom tempalte looks like in the UX
![image](https://user-images.githubusercontent.com/23039742/165650359-a352d64e-b128-473d-ab60-7df0568a44df.png)




## Defects of Note
🚀 **merit & beyhond**

Some defects are more pesky than others. Highlight 3-5 of the bugs that drove you the most nuts and how you finally
ended up resolving them. Just create a link to the issues/defect of note.

### Outstanding Defects

It's ok to not resolve all the defects you found. If you know of something that isn't quite right, list it out and
explain why you chose not to resolve it. Again, do this in gitHub and provide a link to the defects you are not closing
and ensure they have a comment in them.

# E-commerce Business Model
🚨**Required**

In this section discuss your business model, how you use  SEO to get users to your site and how you hope to generate more traffic and get sponsors to back link to your site. 

## Facebook Business Page
🚨**Required**

- copy a screenshot of the FB page
- add a couple of bulletpoints about the goals of what this fills for building out followers & special content

## Newsletter Signup
🚨**Required**

- copy a screenshot of the signup 
- add a couple of bullet oints outlining the goals of what this functionality provides for building out followers

## Links
- sponsored links are flagged with rel="sponsored"
- social links and other links that go outside domain have `rel="nofollower"` to signal to search engines that those links are not associated with our specific domain

## SEO Strategy
🚨**Required**

In this section write out the process you used to come up with short tailed and long tailed results to help refine the keywords you came up with. You should call out attention to the following:

### Keywords
Describe the process you went through identifiying keywords that you want Google and other search engines to relate to your site.

### Description
Note that you have a the meat description tag and if any of the content changes based on the page.

### Title
Call out that you have this set in your base.html so it can be changed per page

### Relevant Content
Call out how you purposefully incorporated keywords into your content, H1, meta data etc. 

### Sitemap
🚨**Required**

- [sitemap.xml file]() call out files that exist so browsers can easily crawl site

### Robots.txt
🚨**Required**

- [robots.txt file]() to restrict pages that are should be searched by google, authentication and others are blocked to only allow relevant pages to be searched by google

# Deployment
🚨**Required** 

## Prerequisits
🚀 **merit & beyond**

If the user is required to have certain keys and credentials you should include this section with directions on how to get the necessary information. ex)

1. **Gmail Account:** In order to have verification and forgot password emails sent to registered users you need a
   google account. 
  - [create a gmail accoount](https://accounts.google.com/signup) 
  - [downgrade to less secure](https://myaccount.google.com/lesssecureapps?pli=1) after you are signed into the gmail account, downgrade to less secure
2. **Couldinary URL**
  - [create an account](https://cloudinary.com/)
  - go to the dashboard and copy your API environmental variable
   
    <img width="1230" alt="image" src="https://user-images.githubusercontent.com/23039742/213839829-b4f349b3-419d-4ea2-bbca-90cf3c663bba.png">     
 
## Fork and Clone the Repository
🚀 **merit & beyond**
To keep the main reposotory for this project clean, please fork the repostiory into your own account. GitHub has [forking directions](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository) but here's what you might do:
1. login to your own gitHub account
2. navigate to [my repository](URL OF YOUR LIVE REPOSITORY)
3. In the top right corner of the page, click fork 

![image](https://user-images.githubusercontent.com/23039742/213840378-e785eaa0-712b-468c-bcda-64fde56eae44.png)

4. set yourself as the owner
5. change the name of the repo if you want
6. add a description if you want
7. choose what to copy, typicall the main branch only
8. click the snazy green button

![image](https://user-images.githubusercontent.com/23039742/213840549-5bef12ae-198e-412b-84b6-0cc718b6fa1d.png)

9. To get files to your local environment, you need to clone it: click the code button
10. Copy the url as needed (here's gitHub instructions)[https://docs.github.com/en/get-started/quickstart/fork-a-repo#cloning-your-forked-repository}



## Development Deployment 
🚨**Required** 

This section should describe the process someone would have to go through to get the local working in GitPod, or your preferred IDE. Start from installing the chrome extension then clicking the green gitpod button in THEIR FORKED repository, the enumerate the steps to walk them through the process as if they were brand new to this proccess. **Include screenshots** where applicable.

**Key points to cover** 
- Install required python packages: `pip3 install -r requirements.txt`
- Create env.py
- What to put in the env.py, don’t disclose real values
>  - EMAIL_HOST_PASSWORD=<YOUR_VALUE>
>  - DEFAULT_FROM_EMAIL=<YOUR_VALUE>
>  - EMAIL_USERNAME=<YOUR_VALUE>
>  - SECRET_KEY=<YOUR_VALUE>
>  - CLOUDINARY_URL=<YOUR_VALUE>
>  - DEV=True
- Apply Database Migrations so the database starts up `python3 manage.py migrate`
- Create a super user so you can add and inspect things via django admin  `python3 manage.py createsuperuser`
- Preload data: Sometimes you might want to include steps to create data in the admin or preload a data dump [coderwall blog](https://coderwall.com/p/mvsoyg/django-dumpdata-and-loaddata) has examples on how to dump data and load it which saves a bunch of time when deploying the application from a local database to a hosted database but you don’t  have to do this step
- Start the server `python3 manage.py runserver`


## Production Deployment
🚨**Required** 

This section should describe the process you went through to deploy the project to a server where anyone can access the url without your machine running. This is typically Heroku. **Include screenshots** if you think they would make the process easier. Start with getting an heroku account and then setting up databases and other packages.

If you have project settings required for Heroku, provide a table of the keys and values. Do not share your personal
keys but either cut them out of the screenshot or say <YOUR_VALUE> and include links on how the user would obtain such
values.

**Key points to cover** 
- cerating new app
- setting app name
- setting region
- entering dreaded billing info
- subscribing to a plan
- setting up db
- adding environmental values- have a list or table so user has less chance of typos
>  - EMAIL_HOST_PASSWORD
>  - DEFAULT_FROM_EMAIL
>  - EMAIL_USERNAME
>  - SECRET_KEY
>  - CLOUDINARY_URL
>  - COLLECT_STATIC
- adding build packages
- deploy
- gitHub connection
- auto vs manul deploy
- monotior logs


# Credits
🚨**Required**

To avoid plagiarism amd copyright infringement, you should mention any other projects, stackoverflow, videos, blogs, etc that you used to gather imagery or ideas for your code even if you used it as a starting point and modified things. Giving credit to other people's efforts and ideas that saved you time acknowledges the hard work others did.

-[Code Institute Template](https://github.com/Code-Institute-Org/python-essentials-template)
    - The Template for the GUI for this project was provided by Code Institute. This allows for the Command line to be shown and used within the browser.

## Content

Use bullet points to list out sites you copied text from and cross-reference where those show up on your site

## Media

Make a list of sites you used images from. If you used several sites try to match up each image to the correct site. This includes attribution for icons if they came from font awesome or other sites, give them credit.

## Acknowledgments

This is the section where you refer to code examples, mentors, blogs, stack overflow answers and videos that helped you accomplish your end project. Even if it's an idea that you updated you should note the site and why it was important to your completed project.

If you used a CodeInstitute Instructional project as a starting point. Make note of that here too.


