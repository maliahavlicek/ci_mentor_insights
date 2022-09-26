# OVERVIEW

This template was made as a guide to ensure you cover assessment criteria in your second milestone write up. It is specific to the **PORTFOLIO 2: Javascript Essentials** project. It was based off the [loves maths_readmd.md](https://github.com/Code-Institute-Solutions/readme-love-maths) with a few additions to help elevate you to possible distinction status.

## Helpful tools

Markdown's not all that easy so sometimes you may want to use some tools to make tables. 

- [Markdown Cheatsheet](https://guides.github.com/features/mastering-markdown/)
- [markdown table generator](https://www.tablesgenerator.com/markdown_tables) - used to help with documentation table formatting
- [mardown table of contents generator](https://ecotrust-canada.github.io/markdown-toc/) - used to create table of contents (be weary it does have some bugs if you have dashes or trailing spaces in your headers)
- [readme.so](https://readme.so/) - if you don't want to learn markdown, this tool might help you

# Table of Contents
Copy your readme to http://ecotrust-canada.github.io/markdown-toc/ to make a table of contents.  This will help assessors to see the structure of your readme. Just test it out ast this tool isn't perfect. It tends to mess up with special characters like dashes.

====================================== The Sections you Fill in are below ==============================

# PROJECT NAME
*replace the **PROJECT NAME** header with your project's name*
- Screenshot of logo/navigation of mobile deployed site
- Include a link to deployed project with one line explanation of project

## Author
DEVELOPER_NAME

## Project Overview
- Include a picture of site that shows it in responsive states and links to deployed code: https://ui.dev/amiresponsive
- One or two paragraphs providing an overview of your project.
- Write this as a sales pitch or commercial to entice users to interact with your site or how you want investors to purchase your website.
- Include a link to your deployed website

## Table of Contents
Generate after readme is complete for UX and below

## UX

### Project Goals
Use this section to provide insight into your UX process, focusing on who this website is for, calling out demographics, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Design Choices
Your site is most likely geared to a certain audience, and your design choices should tie into them. Let the assessors know your thought process.

You may want to re-watch the videos about the [5 planes of UX development ](https://learn.codeinstitute.net/courses/course-v1:codeinstitute+FE+2017_T3/courseware/22905698f3be425d918ebc64c87801b7/9c295bdc5a4048308460e262b14ab7df/) when writing up this section

#### Colors

- Discuss your color pallet choices and how it ties into users' emotions or target audience.
- include a screenshot of your pallet using a tool like coolors.co

#### Typography

- discuss font size, font types for headers vs buttons vs general text and how it ties into users' emotions or target audience.
- include screenshots of fonts used and links to the appropriate website ex) https://fonts.google.com/specimen/Raleway

#### Images

Explain why you used certain icons and images on your site

#### Animations and Transitions

- discuss any special animations or transitions you've included 
- special hover state effects

### Wireframes

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in a separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser. 

Wireframes can be as simple as a picture of a drawing of how you envisioned laying out the information for you pages in desktop, tablet and mobile views. They are a roadmap and do not have to be 100% accurate of the final product.

### Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so and how they tie into  your user stories.

#### Implemented Features

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

It's easiest to break this section down into the header, footer, and each page/layer of your website. Call out any differences for mobile vs desktop presentations, include a screenshot of the implemented feature.

Don't forget your 404 error page.

#### Future Features

Use this section to discuss plans for additional features to be implemented in the future:

If you end up not developing some features you hoped to implement, you can include those in this section.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Validation Testing
You should try to ensure you code is valid and follows proper indentation.  In this section you should write up any websites you used to validate your code. As your projects becomes more complex these tools may change.

- [CSS Validator](https://jigsaw.w3.org/css-validator/) Note, any error associated with root: color variables were ignored.
- [HTML Validator](https://validator.w3.org/)
- [JS validation](https://jshint.com) for each .js file/ , if using ES6, add this before pasting in your file: `/*jshint esversion: 6 */ `
- [JSON validation](https://jsonlint.com/) for each .json file 

### Cross Browser and Cross Device Testing
1. Visit https://gs.statcounter.com/browser-market-share to figure out the most popular browsers & operating system combos seen across the we for the geographic region, and platoform(s) and screen sizes you expect your users to belong to. 

1. Include a sentence about why you chose the combinations you did.

1. Create a table that lists out what devices, browsers, and operating system you tested your application on and a brief description of why you chose the mixture you did. The point is to prove that you looked at the site across various browsers, operating systems, and viewport breakpoints.

1. if you can't find the brower/device/OS combinations you want on Browserstack with your github student webpack (or you didn't activate that in time), note what you'd ideally test on then what you ended up testing on as a compromise. 

| TOOL / Device                 | BROWSER     | OS         | SCREEN WIDTH  |
|-------------------------------|-------------|------------|---------------|
| real phone: motog6            | chrome      | android    | XS 360 x 640  |
| browser stack: iPhone5s       | safari      | iOs        | XS 320 x 568  |
| dev tools emulator: pixel 2   | firefox     | android    | SM 411 x 731  |
| browserstack: iPhone 10x      | Chrome      | iOs        | SM 375 x 812  |
| browserstack: nexus 7 - vert  | Chrome      | android    | M 600 x 960   |
| real tablet: ipad mini - vert | safari      | iOs        | M 768 x 1024  |
| browserstack: nexus 7 - horiz | firefox     | android    | LG 960 x 600  |
| chrome emulator: ipad - horiz | safari      | iOs        | LG 1024 x 768 |
| browserstack                  | Chrome      | windows    | XL 1920 x 946 |
| real computer: mac book pro   | safari 12.1 | Mohave     | XL 1400 x 766 |
| browserstack                  | IE Edge 88  | windows 10 | XL 1920 x 964 |

### Manual Testing

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. 

There are 3 ways you can document your testing:

**1. Markdown**

Describing your testing process is via scenarios, right here such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

**2. Use Spreadsheets**    

Here is a [Manual Testing Template](https://docs.google.com/spreadsheets/d/1vc1IVL-ydQwWeWMqnk_GRox6HE6qxDLpchGse8Crayo/edit#gid=296578096) that you can use as a starting point to keep track of your testing efforts. Make a copy of it in your own account and update as needed to reflect the browsers you are testing and features.  

**3.Use Github Agile Tools**

Create Custom Issue Template and A Pojrect Board in git hub.[Here's a brief overview](https://docs.google.com/document/d/1nDS5tZeMO77Dfq85IZGMSV6C41XaPm9FwcpR3k-UTVc/edit?usp=sharing) I put together on how to do this

It's ok to spot check specific functionality across devices and browsers but each page should be viewed as a whole for each device/browser combo at least once too.

A quick way to check if items are exceeding the screen width of a project is to run this javascript in the console for various screen emulations:

```
var docWidth = document.documentElement.offsetWidth;
[].forEach.call(document.querySelectorAll('*'),function(el){if(el.offsetWidth > docWidth){console.log(el);}});
```


### Defect Tracking

Try to create issues in real time as it better reflects the daily life of a developer.

The easiest way to track defects is by using GITHUB's Issues to track these as it's really easy to copy/paste screenshots in and then write up how you closed them. At this stage you don't need a custom template or labels, that comes in P4.

**Creating Defects**
1. Click the Issues menu item 
![image](https://user-images.githubusercontent.com/23039742/169566835-240ce89c-6ab1-45b6-8ee8-5f693de70e5d.png)

2. click the Green New Issue button
![image](https://user-images.githubusercontent.com/23039742/169567026-07ff2fb7-ebc0-4ce0-b8a8-38ab7da8844b.png)

3. Fill in the default form
![image](https://user-images.githubusercontent.com/23039742/169567286-c85218d1-1118-4472-93be-04eda040ecc5.png)
 - Fill in a descriptive title
 - add steps to reproduce if it's not straight forward
 - include a screenshot
<img width="967" alt="image" src="https://user-images.githubusercontent.com/23039742/169567840-255b514c-0a1e-4514-8593-9c2aab295b6e.png">
4. click the submit New issue button

**Closing Defects**
1. Go to the issue list in GitHub and click on the issue you have fixed 
<img width="1476" alt="image" src="https://user-images.githubusercontent.com/23039742/169568053-6e34b94c-ff31-4d7f-9faf-1d04286f0397.png">

2. Add a brief write up of what you fixed and include a screenshot if necessary then Click the Close with Comment Button
![image](https://user-images.githubusercontent.com/23039742/169570025-6d559641-d573-4749-bc0f-33a151358481.png)

**Reopening Defects**
1. If you find you didn't fix the issue, you can toggle to the closed items:
![image](https://user-images.githubusercontent.com/23039742/169570117-274898ec-ee02-487a-ac14-4755095d5e8a.png)

2. Click on the issue you want to re-open
3. Scroll down and click the re-open button
![image](https://user-images.githubusercontent.com/23039742/169570383-9fc53595-1761-4117-a369-d798877c7fe2.png)


### Defects of Note
Some defects are more pesky than others. Highlight 3-5 of the bugs that drove you the most nuts and link to them directly here.


### Outstanding Defects
It's ok to not resolve all the defects you found as long as:
- it does not impacting a user from completing a vital function on the website
- it only affects a very small subset of users
- is an extreme edge case that very few users would try

If you know of something that isn't quite right, create an issue and  link to it here and explain why you chose not to resolve it. 

Sometimes it's as simple, word wrapping issue that makes the site look odd at a certain screensize that you just didn't have time to fix due to the impending deadline and lack of skills. It's best to mention it but note why you allowed it to go live than let asccessors think you didn't notice it. 

## Accessibility

Accessibility testing is aimed to make sure that those with visual or physical disabilities can still browse your website. Some users have had strokes or accidents that make it difficult to use a mouse so they use keyboard keys to tab through sites. Others use screen readers that rely on HTML tags to help the user navigate quickly through the site to find information they want, others have color blindness or contrast issues. It's the law to provide services 
Here's a [site](https://www.w3.org/WAI/fundamentals/accessibility-intro/#:~:text=Accessibility%20is%20Important%20for%20Individuals%2C%20Businesses%2C%20Society,-The%20Web%20is&text=That%20is%2C%20the%20accessibility%20barriers,older%20people) where you can learn more about accessibility and the internet.

### Lighthouse Audits
You should run your deployed website pages through lighthouse's audit to check performance, accessibility, best practices and SEO scores. You should aim to get 85 or higher score. 
https://web.dev/measure/  If you have lower scores, read the report and follow the links to address the flagged issues. You can run this tool from Chrome Dev Tools too against your local machine, but the performance will the worst (I personally ignore my performance results unless it's deployed code. I hope for > 60 on that mark, but > 85 on the other 3)

### Keyboard Navigation
Another way to accessibility test you site is to try to click on the browser and see what happens if you use the tab, arrow and enter keys. Does it work well or does the user get stuck?

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages).

In particular, you should provide all details of the differences between the deployed version and the development version, if any.

Remember to use proper markdown for commands and enumerated steps.


You may want to re-watch the [initial deployment in gitpod video](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/9b06129195c64fada6783de9cfe82d60/) when writing up this section.


Write out steps you would take and test them to deploy your code to GitHub Pages, include screenshots if you think they would make the process easier.

## Credits

To avoid plagiarism amd copyright infringement, you should mention any other projects, stackoverflow, videos, blogs, etc that you used to gather imagery or ideas for your code even if you used it as a starting point and modified things. Giving credit to other people's efforts and ideas that saved you time acknowledges the hard work others did. 

### Content

Use bullet points to list out sites you copied text from and cross-reference where those show up on your site

### Media

Make a list of sites you used images from. If you used several sites try to match up each image to the correct site. This includes attribution for icons if they came from font awesome or other sites, give them credit.

### Acknowledgments

This is the section where you refer to code examples, mentors, blogs, stack overflow answers and videos that helped you accomplish your end project. Even if it's an idea that you updated you should note the site and why it was important to your completed project.

If you used a CodeInstitute Example project as a starting point. Make note of that here.


