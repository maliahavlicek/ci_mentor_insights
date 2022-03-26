
# OVERVIEW

This template was made as a guide to ensure you cover assessment criteria in your fourth portfolio write up. It is specific to the **PORTFOLIO 4: Full-Stack Toolkit** project. 

## Helpful tools

Markdown's not all that easy so sometimes you may want to use some tools to make tables. 

- [Markdown Cheatsheet](https://guides.github.com/features/mastering-markdown/)
- [markdown table generator](https://www.tablesgenerator.com/markdown_tables) - used to help with documentation table formatting
- [mardown table of contents generator](https://ecotrust-canada.github.io/markdown-toc/) - used to create table of contents (be weary it does have some bugs if you have dashes or trailing spaces in your headers)
- [readme.so](https://readme.so/) - if you don't want to learn markdown, this tool might help you

# Table of Contents
Copy your readme to http://ecotrust-canada.github.io/markdown-toc/ to make a table of contents.  This will help assessors to see the structure of your readme. Just test it out ast this tool isn't perfect. It tends to mess up with special characters like dashes.

====================================== The Sections you Fill in are below ==============================


# PROJECT_NAME

*replace the **PROJECT NAME** header with your project's name*
- Screenshot of logo/navigation of mobile deployed site
- Include a link to deployed project with one line explanation of project


## Author
DEVELOPER_NAME


## Project Overview
- Include a picture of site that shows it in responsive states and links to deployed code: http://ami.responsivedesign.is/
- One or two paragraphs providing an overview of your project.
- Write this as a sales pitch or commercial making users want to purchase your website.
- Include a link to your deployed website


# UX
Your site is most likely geared to a certain audience and goals for the business owner and users of the site, and your design choices should tie into them. Let the assessors know your thought process.

If you don't feel like the overview gave enough detail about the site, you can write up what you are expecting users to actually do on your site, book things, find thing then lead into the goals and target audience.


## Target Audience
Can be a paragraph or a list

> **Paragaph Example**
> The target audience for What2do2day comes in two flavors. The revenue driving forces is children ages 12-18 who have a bit of freedom to move around unsupervised but very little means to addend costly mass entertainment complexes more than 5 miles from home. Their parents are expected to be a customer group too as they will want to ensure the site is safe and not a preditory place where their kids could be scammed into unsafe adventures. Other groups of users are the businesses that want to promote themselves as community friendly who will be hosting events for the primary customer group. The business owners will want a friendly interface to upload details of their place and events.

> **List example**
> 1. Patients who have been referred for radiology examinations by registered physicians
> 2. External healthcare companies who have equipment to sell
> 3. Radiology staff who want to have a more managable and predictable workload

## Design Choices
Now that you have let the assessors know about the target audience and users, you can go into the design choices

### Colors

- Discuss your color pallet choices and how it ties into users' emotions or target audience.
- include a screenshot of your pallet using a tool like coolors.co

### Typography

- discuss font size, font types for headers vs buttons vs general text and how it ties into users' emotions or target audience.
- include screenshots of fonts used and links to the appropriate website ex) https://fonts.google.com/specimen/Raleway

### Images

Explain why you used certain icons and images on your site

### Design Elements

- list out the type of elements you want to use on your site, this will help you  when choosing a framework and goes hand in hand when doing the wireframes. If you did something out of the ordinary, or think something was particularly clever, add a sentence and a screenshot or reference the file the code or css is in.

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

- discuss any special animations or transitions you've programmed 
- special hover state effects

### Frameworks
- If you use bootstrap, tailwind, bulma, materialize or some other JS/CSS framework, call it out here and why you made that choice. (Typically I look at the design elements I want and make sure the framework supports them)

### Custom Styles
- call out any overrides you did for bootstrap styles or the framework you used,  even if they are fonts and colors, perhaps lead assessors to the file of interest in your repo 

### Custom Javascript
- call attention to any custom javascript you created to help your User Experience you can organize this by functions or files

## Wireframes

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in a separate directory), or  hosted elsewhere online and can be in any format that is viewable inside the browser.

- You should minimally have wireframes for desktop and mobile. Adding a Tablet view will help you get into merit and distinction.

## Goals
Bullet point out things from web users to web site owners and other groups of people

**Booking Site Example**
> - To allow the opportunity for patients to book and manage their own radiology appointments
> - To give patients the opportunity to educate themselves on radiation safety prior to their visit
> - To provide a simple to use contact form for site visitors to use in order to contact the radiology department
> - To provide useful information to patients about radiology and the department to reduce 'white-coat-syndrome' and anxiety during their visit
> - To give external companies the opportunity to partner with the radiology department and share their equipment prior to potential purchases
> - To give radiology staff the opportunity to manage their workload and see in advance the patients they will encounter during the day

**Granular Goals Example**
> **Customers**
> Customers of What2do2day are children ages 12-18 who have a bit of freedom to move around unsupervised but a short range of mobility, approximagely 5 miles from home.
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
> Owners of Places would ideally have a different set of user permissions and the Update and Contribute sections of navigation would be under a strict workflow, but in the initial phase, I wanted to show off the ability to add, update and delete items from the website's view so it's not hidden behind permissions or workflow at this point. Place owners are those that have a business or an organization that hosts free events within a community. Examples are a group that wants to play pickup soccer or a bicycle shop that leads group rides once a month.
> 
> **Place Owner Goals:**
> 
> - I want my place to be easily found on the site so I can get more customers
> - I want users to share community reviews so I build trust with future customers
> - I want to add events to my place to build a repertoire with my clients
> - I want users to join my events so I can track how successful community events are to my bottom line
> - I want the ability to update my place's details
> - I want to update events associated with my organization
> - I want to protect against bloated ratings
> - I want to protect against accidental deletion of my information
> 
> **WebSite Goals**
> The primary goal of what2do2day is to create a user-friendly app that allows customers to quickly find an event they want to attend. It's a meeting point between business/organizations and kids/parents to improve the likelihood of kids getting off their devices and interacting with others face to face at a low cost with minimal adult supervision.
> In order to support the maintenance and development of cool features on the site, what2do2day hopes to produce monetary gains through the following means:
> - Workflow Management Plans for Businesses around:
>   - oversee approval/disapproval of reviews to ensure spamming and bad-mouthing in reviews does not occur
>   - batch event creation to help save time
>   - user account management to help with password recovery and assigning or removing roles as employees change
>   - sharing of user emails that attend events
> - Affiliate linking - link to at-cost services provided by businesses and receive a kickback
> - Ads - target online sales related to equipment based on activities a place or event is associated with


## User Stories
User stories evovle over a project's lifetime. Start with a wish list, do a feasabilty analysis then move the ones you will work on into gitHub so you can track their progress.

## Initial Stories
To start the agile process this section kicks off with a bullet list/brainstorming dump about features you'd like to have. EVERYTHING write them out in bullet form:
- As a 'user type' I 'to perform an action' so that I can 'achieve a goal'

**Examples**
- [radiology booking](https://github.com/DeannaCarina/ELHTRadiology#user-stories)
- [places/events searching site](https://github.com/maliahavlicek/what2do2day#user-stories)


## Feasiblity vs Importance
To scope the project for a MVP (mimimally viable product) a feasbilty analysis was done. 

The features in the table below have been taken from the user stories above. Generic features found in most websites will also be implemented such as nav-bar, footer, obvious website purpose etc.

| Opportunity/Feature | Feasibility/Viability (score out of 5) | PurposeLevel of Importance (score out of 5) | In Or Out |
|---------------------|----------------------------------------|---------------------------------------------|-----------|
|                     |                                        |                                             |           |
|                     |                                        |                                             |           |
|                     |                                        |                                             |           |
|                     |                                        |                                             |           |

> You should dicuss the outcome of what you will be dropping based on the outcome.

## Scope
Now you have to talk about the scope to recude things more, you don't necessarily need all the bells and whisltes, they could be beyond your skill set.  Think basic stuff.

## GitHub Stories

Now you are ready to start using Git Hub Issues to write your user stories.  To get to merit levels you need to show you have refined stories from Epics to Generic User stories.

### User Story Templates
[Here's the lesson](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+AG101+2021_T1/courseware/a4e548ca70) on how to create a User Story Templates. 

If you want a chance at **DISTINCTION**, I'd suggest the following:
- Create an Epic Story template, this would have a title, the story and children stories
- Create a User Story template, this would initially have the title, the story, and a link to the Epic. Then you'd come back when you are prioritizing it to include the acceptance criteria, and story points, then again when you are working on it and fill in the tasks and adjust the story points if needed.
- Name your stories in a way that it's easy to tie the children to the EPICS by name.

Example: 
EPIC: Navigation
As a user, I want to have easy to see navigation on the page, so I can intuitively interact with the site without getting frustrated.

USER STORY: Navigation: Create Template
As a developer, I don't want to have copy and paste my navigation on every page. I want to use a template to house this information, so my code is easier to maintain.

USER STORY: Navigation: Desktop
As a user I want clear navigation that is up to industry standards for my desktop experience, so I can easily find what I need on a website.

USER STORY: Navigation: Mobile
As a user I want clear navigation that is up to industry standards for my mobile experience, so I can easily find what I need on a website without the 

**What to keep in this section**
- include links and/or screenshots of your story template(s)

### Product Backlog
https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+AG101+2021_T1/courseware/a4e548ca70a3473aa890ba2ab9bf612c/085f3a8e344a4cf28b5b5355399abcc1/?child=last
This is the MILESTONE where you grab stories from the issues or USER stories you created and prioritize them  and order them, leave the epics out.

**What to keep in this section**
Include a link to your Product Catalog Milestone, 

an initila  screen shot might help to of intial, mid point and end

## Iterations
https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+AG101+2021_T1/courseware/a4e548ca70a3473aa890ba2ab9bf612c/71fe6c52cccf477688e924c9889f5fec/?child=first

Add links to iteration milestones (most people have ONE iteration since they are the solo worker, just state that here), it could be that you won't have all your product backlog worked in the end, and that is ok, hte MVP might morph, you might find other stories you want instead, it's OK.



## Progress Boards
https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+AG101+2021_T1/courseware/a4e548ca70a3473aa890ba2ab9bf612c/7ad7f487cc6148ecb182d77feaeda269/?child=first
Add links to Progress boards


# Information Architecture
As part of the requirements for this project you need to have at least **1 original data model**.  It's this section that discusses your data and how each piece relates to another and draws out the CRUD functionality you built. 

## Entity Relationship Diagram
Wade Williams wrote a great blog about how to add a django extension to auto create an ERD. https://wadewilliams.com/technology-software/generating-erd-for-django-applications/ You can always draw one out by hand or google sheets. You can also draw this up by hand if you want or use a spreadsheet to show your data model. 

## Database Choice
Just state you used postgres as the database because the data is relational and heroku serves this up realitvely easily with no cost.

## Data Models
Show the accessors you know your data. If you end up using some data models from an example project, call that out and don't be as detailed about writing those up unless you added to them.  

Each data model that you created yourself should have its Fields, Field Type and any validation documented.  You should also cross-reference any code in your repository that relate to CREATE, READ, UPDATE, DELETE operations for these models. 

Below is an example of a write up for an Activies Data Model
>  **Activities Model**
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
> 
> The reading/writing of the activities table is housed in the [what2do2day/activities/views.py](what2do2day/activities/views.py) file.

### CRUD Diagrams
This is if you want to go for distinction.  You can also have CRUD diagrams to show them visually how the model is used in your site. 

I used [draw.io](https://app.diagrams.net/) and hooked it up to my google drive to create the screenshot below

> ![image](https://user-images.githubusercontent.com/23039742/154406188-c9beb57a-2fd1-4f26-a8ed-bee320e46e3d.png)


# Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so and how they tie into  your user stories. Have screenshots with any callouts to differences for responsive display.

## Implemented Features

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

It's easiest to break this section down into the header, footer, and each page/layer of your website. Call out any differences for mobile vs desktop presentations, **include a screenshot of the implemented feature** and **at least 2 bullet points of their importance**.

Don't forget your 404 error page.

## Future Features

Use this section to discuss plans for additional features to be implemented in the future:

If you end up not developing some features you hoped to implement, you can include those in this section.

# Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

**At this point, you should use gitHub Issues Templates** to track test cases and defects. Here's a [document](https://docs.google.com/document/d/1nDS5tZeMO77Dfq85IZGMSV6C41XaPm9FwcpR3k-UTVc/edit#heading=h.3kdbr3tqbzi) I put together for this process.


## Cross Browser and Cross Device Testing
To save time, you can create this type of table in [markdown table generator](https://www.tablesgenerator.com/markdown_tables) 

As of Feb 14, 2022 CI students can take advantage of the Student Developer Pack where you have access to great things like [browserstack](https://education.github.com/pack/offers/#browserstack) You should have received an email about how to activate your student Developer Pack, here's a [slack](https://code-institute-room.slack.com/archives/C0L316Z96/p1644946870567999) with details if you can't find it in the associated thread.

Start with a brief explanation of why you chose the mixture you did. The point is to prove that you looked at the site across various browsers, operating systems, and viewport breakpoints. You can add a column about the spot checking path you took or write it out here:

> **Example:**
> To ensure the code was functional and looked good on varoius devices I tested a couple of generic flows though my site on using the following Tool/Device combinations:
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


## Accessiblity Testing

You should have test cases for accessiblity and links to them here. Start with a brief paragraph and then link to the test cases. If you are ambitious you can record the screen of you using the keyboard, convert it to a gif and upload it to the test case too. 


**example**
> To ensure that the site was accessible to people with visual impairments, I used chrome's dev tools, lighthouse audits to ensure I had a scrore in the green for accessiblity and that I could keyboard navigate through the page.  
> 
> Here are links to the test cases for each which contains the screenshot for the lighthouse audit. 
> - [home page accessibility test](https://github.com/maliahavlicek/ci_mentor_insights/issues/12)
> - [experience page accessiblity test](https://github.com/maliahavlicek/ci_mentor_insights/issues/13)
> - [skills page accessibilty test](https://github.com/maliahavlicek/ci_mentor_insights/issues/14)
> - [recommendations page accessiblity test](https://github.com/maliahavlicek/ci_mentor_insights/issues/15)
>
> To ensure the site was accessiblity to people with physical imparitments, I tried to navigate the site using tabbed navigation:
> - [site tabbed navigation test](https://github.com/maliahavlicek/ci_mentor_insights/issues/10)

You can totally combine the tabbed navigation in the accessiblity test and have 2 expected criteria, it's all up to you!


## Validation Testing
You should try to ensure you code is valid and follows proper indentation.  In this section you should write up any websites you used to validate your code so there is credit given to those sites.  Then add links to the test cases you put into GitHub for the validation. You can copy your validation success to those tests. 

The following site were used to aid in validation testing:
- **[CSS Validator](https://jigsaw.w3.org/css-validator/)** 
> If you only have one CSS file, you can just run the validator through one deployed page URL, if you have custom CSS for diffent pages, make sure you hit those different URLS

- **[HTML Validator](https://validator.w3.org/)**  
> For each view you wrote, you should validate the HTML and have a test case for it linked to from here
> NOTE: You may need to right click to view the source of each page and paste that into the validator if you need to go through authentication to get to the page.

- **[JS validation](https://jshint.com)** 
> for each .js file, copy the code and paste it into this site, and have a test case for it linked to from here. You can have warnings, but no errors.
> if using ES6, add this before pasting in your file: `/*jshint esversion: 6 */ `, similarily you can update it to 7 if you see warnings about ES7 syntax `/*jshint esversion: 7 */ `

- **[PEP8 Validator](http://pep8online.com/)**
> for each .py file you created, copy the source code and paste it into this site, and have a test case for it linked to from here. 
> include a screenshot of results in the test case. (you should do this for all .py files in your repo, or note that there are no red errors in the gitpod Problems list after the file is saved)

- **[JSON validation](https://jsonlint.com/)**
>  for each .json file, you should copy the code and paste it into this site, and have a test case for it linked to from here. 


## Automated Testing
If you managed to write jasmine tests or some django tests, note those files out here and how to run them.  I only did this in my last project as I didn't have the time or energy to learn how to write tests. https://github.com/maliahavlicek/ms4_challenger/blob/master/documentation/TESTING.md is my write up about those and how I ran them, but a simple test I'd recommend is authentication and any views you limit to superusers or logged in users: 

https://github.com/maliahavlicek/ms4_challenger/blob/master/challenges/tests/test_views.py 

## Defects

At this point you really should be using GITHUB's Issues to track these as it helps you with the AGILE process requirement as it's really easy to copy/paste screenshots in and then write up how you closed them. 

[Here's a brief overview](https://docs.google.com/document/d/1nDS5tZeMO77Dfq85IZGMSV6C41XaPm9FwcpR3k-UTVc/edit#heading=h.542xzc8ufx4x) I put together on how to do this.

## Defects of Note
Some defects are more pesky than others. Highlight 3-5 of the bugs that drove you the most nuts and how you finally ended up resolving them.
Just create a link to the issues/defect of note.


### Outstanding Defects
It's ok to not resolve all the defects you found. If you know of something that isn't quite right, list it out and explain why you chose not to resolve it. Again, do this in gitHub and provide a link to the defects you are not closing and ensure they have a comment in them. 


# Deployment

## Requirements
If the user is required to have certain keys and credentials you should include this section with diretions on how to get the necessary information.
ex)
1. **Google Account:** In order to have verification and forgot password emails sent to registered users you need a google account. If you don't have one  [Create a google account](https://accounts.google.com/Signup)
2. **Google APIs**
    1. in a new incognito tab, log into your new google account.
    1. then update the url to be: https://console.cloud.google.com/getting-started?pli=1 
        
        **GOOGLE DRIVE API Access**
        1.  create a new project for this, call it XXXXXX (You might want to refer to what you see in this video: https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LS101+2021_T1/courseware/293ee9d8ff3542d3b877137ed81b9a5b/071036790a5642f9a6f004f9888b6a45/ at the bottom of the screen to write out steps.)
        2. Then click on Add APIs and Services and select Libraries
        3. Search for Google Drive
        4. Click Enable
        5. Click Create Credentials
        6. Select Google Drive API from the drop down, Application Data, then no and click the Next Button
        7.  (https://developers.google.com/drive/api/v3/enable-drive-api) 
        8. for service account details fill in a service account name ex) xxx_API, then click Create and Continue
        9. For the Accoun acces, select Role: Basic/Editor then continue
        10. Then Click Done
        11. Now select the newly created service account
        12. Click on the KEYS Tab
        13. Click Add Key
        14. Select JSON type (right click to show in folder so you know where the file was saved.
        
        **GOOGLE SHEETS API Access**
        You may need to us the back button get to the APIS & SErvices section from where you were.
        1. click the Libray  Tab and serarch for Google Sheets
        2. click enable

3. The downloaded credentialsJSON file is basically your creds.json file that you need to put into your heroku settings or gitpod environment to access your google drive.

4. Google Sheet Template
  - If you had to create specific sheets for your project, instruct users to make their own copy of it from yours and rename it back to what the python project expects
  - And don't forget to share the spreadsheet in question with the client_email from the creds.json 
## Gitpod
This section should describe the process someone would have to go through to get the local working in gitpod.  Such as install requirements.txt  and setting up a creds.json file that is in the gitignore and keeping their workspace and what goes in the env.py file without REAL KEYS.

If you have project settings required such as a creds.json file from the GOOGLE DRIVE API acess, please provide an example of that file in the writeup with the project key values:
```$python
{
    "type": "service_account",
    "project_id": "<YOUR_VALUE>",
    "private_key_id": "<YOUR_VALUE>",
    "private_key": "<YOUR_VALUE>",
    "client_email": "<YOUR_VALUE>",
    "client_id": "<YOUR_VALUE>",
    "auth_uri": "https://accoutns.google.com/0/oauth2/auth",
    "token_uri": "https://oauth2.googleapis.com/token",
    "auth_provider_x509_cer_url": "https://www.googleapis.com/oauth2/v1/certs",
    "clien_x509_cert_url": "<YOUR_VALUE>"
}
```

If you have any dependencies, you should instruct users to install them
```$python
pip3 install -r requirements.txt
```


## Heroku
This section should describe the process you went through to deploy the project to Heroku. Include screenshots if you think they would make the process easier.

You may want to re-watch the lessons when writing up this section.

If you have project settings required for Heroku, provide a table of the keys and values.
Do not share your personal keys but either cut them out of the screen shot or say <YOUR_VALUE> and include links on how the user would obtain such values.

## Fork the repository
Instruct users to make a fork so they have a copy of the repository in THEIR own git hub account: https://github.com/maliahavlicek/portfolio_project_03

![image](https://user-images.githubusercontent.com/23039742/132136504-eb79a6f3-0205-4c82-80c2-eef136ec7e4c.png)


#### New Project
Log into Heroku and create a new project. Name it something like XXX_coders_bistro.


#### Settings
On the settings tab you have to address two things:
1. **Config Vars**

  ![image](https://user-images.githubusercontent.com/23039742/132135869-215d2e0f-805d-40a8-a8c2-fb1098e2645d.png)

  At a bar minimum you should show the user that they need to add the PORT. 8000 key value pair.


2. **Build Packs**

  ![image](https://user-images.githubusercontent.com/23039742/132135918-28cac112-7766-4277-905c-4a4963d8442d.png)

  add Python Then Node.js


#### Deploy
1. Set up to github and select the correct repository:

  ![image](https://user-images.githubusercontent.com/23039742/132136113-c257c921-d10c-4ccc-af09-6a1d25136395.png)

2. Deploy either manual or automatic

![image](https://user-images.githubusercontent.com/23039742/132136241-9d76fabb-39f0-4696-bc5f-047398fdaf41.png) 


# Credits

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


