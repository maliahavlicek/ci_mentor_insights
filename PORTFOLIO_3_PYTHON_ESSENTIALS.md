# OVERVIEW

This template was made as a guide to ensure you cover assessment criteria in your third milestone write up. It is specific to the **PORTFOLIO 3: Python Essentials** project. It was based off the [battleship readme](https://codeinstitute.s3.amazonaws.com/CSSEssentials/p3-readme.png) with a few additions to help elevate you to possible distinction status.

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
- Include a recording of site that shows the terminal interaction.
  https://chrome.google.com/webstore/detail/loom-for-chrome/liecbddmkiiihnedobmlmillhodjkdmb is a very intuitive and free tool to do a web recording.
- Then you can use https://cloudconvert.com/mp4-to-gif to convert the mp4 to a gif and just paste it into the readme via git hub and it'll resovle itself.
- One or two sentences providing an overview of your project.
- Include a link to your deployed website

## Table of Contents
Generate after readme is complete for UX and below

## How To Play/Use
Paragraph or bullet points of how the user initiates the program and interfaces with it. You could have videos of each bit if you want and ditact what the user should do.

## Features
Use this section to itemize the features of your project. 

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

It's easiest to break this section down into piece parts or core functionality blocks such as data upload, user input, analysis and data output; focusing on the atomic functions and data model(s) you created to make the program work. 


### Implemented Features
In each subsection, write out what the feature is for and what value it adds. If there is terminal interaction or output associated with the function, include a screenshot.


### Future Features

Use this section to discuss plans for additional features to be implemented in the future:

If you end up not developing some features you hoped to implement, you can include those in this section.


## Design Documents

This section is where you would share logic diagrams and spreadsheets that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in a separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser. 

The flowchart can be as simple as a picture of a drawing of how you envisioned laying out the logic for you project, or done with a professional tool such as powerpoint, googlesheets, or [https://app.diagrams.net/](https://app.diagrams.net/) They are a roadmap and do not have to be 100% accurate of the final product.

## Data Model
In this section write our your data model(s).

You might want to include subsections that include how the data in the model is . initialized and then the methods that you created to update it through the program.

![image](https://user-images.githubusercontent.com/23039742/130148204-b56406bf-0fff-48f3-9dee-2f3cdbe67cc5.png)



## Libraries used
List out the python libraries you purposefully used in your project and why. You can look at your requirements.txt file and go back to https://pypi.org/ to rediscover the purpose of a library if needed.

A bulleted list is a good presentation for this information.

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your features and ensure that they all work as intended in an easy and straightforward way for the users to achieve their goals.

### Validation Testing
You should try to ensure you code is valid and follows proper indentation.  In this section you should write up any websites you used to validate your code. As your projects becomes more complex these tools may change.

- [PEP8 Validator](http://pep8online.com/) include a screenshot of results

If the line is too long just add 
```$python 
# noqa
```
There is a space before the # and after it to skip the quality assurance for that line.



### Manual Testing

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Startup:
    1. User enters name
    2. try to submit no entry, blank name not allowed
    3. Try to submit the name with spaces
    4. Try to submit the name as special characters
    5. Try to submit the name as calling a function in the code
   
    
Here is a [Manual Testing Template](https://docs.google.com/spreadsheets/d/189VpSeEG9oevSRhvb2WZl8zCk9L3s2iWQyrJ_1jjAGQ/edit?usp=sharing) that you can use as a starting point to keep track of your testing efforts. Make a copy of it in your own account and update as needed to reflect the browsers you are testing and features.  

Or you could open a Project in github and write your tests there in a basic khanban board. 
1. Click on the projects menu:

![image](https://user-images.githubusercontent.com/23039742/132130197-465d3db9-04e0-4843-9509-041cd0639551.png)

2. Click on the create project button:

![image](https://user-images.githubusercontent.com/23039742/132130216-1623af38-827f-4fd6-9729-c9bc5a1e5485.png)

3. Select the Basic Kanban template

![image](https://user-images.githubusercontent.com/23039742/132130414-4e60b081-555f-49e3-a446-da6fc88951f2.png)

4. Fill in the information and click Create

![image](https://user-images.githubusercontent.com/23039742/132130417-f6051c42-4a1d-4faf-8ed7-780215d1805d.png)

4. Click the + sign on the project board to craete a new Test

![image](https://user-images.githubusercontent.com/23039742/132130433-dcb741ac-9deb-401a-8801-6e3d1861c7f7.png)

5. You can use the templates provided to steal the checkbox mardown to write out your test by clicking the ... button and selecting edit note option:

![image](https://user-images.githubusercontent.com/23039742/132130460-2314a026-ed12-493c-a4e9-16726e812b94.png)

6. Just copy the example text you want:

![image](https://user-images.githubusercontent.com/23039742/132130503-d4611154-d62b-4eff-9ec5-004fd89f440e.png)

7. Then you can past that into your new note and update as needed then save:

![image](https://user-images.githubusercontent.com/23039742/132130729-161ff2e6-65c0-4344-a4d4-e3baf4670a24.png)

8. Then when you start to test, just move it into progress and update as you finish the tasks in your test.  If you've used checkboxes to track the testing tasks, you should mark them off and then once all are done, you can move the item to the done list.

There are ways to create issues with these project cards so you don't have to write up everything. You can create an issue from a test item. 

For more information you can visit: https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/about-project-boards 


### Defect Tracking

You can use git hub issues to track any bugs rather than a spread sheet and just link to that page for your repository.

![image](https://user-images.githubusercontent.com/23039742/130149053-bf506388-a791-426e-8ffc-a56c1212e01c.png)

You should created issues in real time and close them out as you fix the bugs. Include steps to recreate and screenshots.

Create a link to the issues dashboard  of your repository
[ci_insights isssues](https://github.com/maliahavlicek/ci_mentor_insights/issues)

### Defects of Note
Some defects are more pesky than others. Highlight 3-5 of the bugs that drove you the most nuts and how you finally ended up resolving them.


### Outstanding Defects
It's ok to not resolve all the defects you found. If you know of something that isn't quite right, list it out and explain why you chose not to resolve it.

### Commenting Code

Make sure you  use triple double quotes to document fuctions and classes.
 Here'a  documentation worthy example:
```$python
def yes_no(question):
    """
    Function to ask a simple yes no question of the user.
    :param question: String displayed as the question
    :return: answer: String equal to "1" or "2" representing yes or no respectfully
    """
    print(question)
    print("yes = 1")
    print("no = 2")
    answer = input("enter your answer here \n").strip()
    while answer not in ("1", "2"):
        print("please choose 1 for yes and 2 for no")
        answer = input("enter your answer here \n").strip()
    return answer

```

## Deployment

### Requirements
If the user is required to have certain keys and credentials you should include this section with diretions on how to get the necessary information.
ex)
1. **Google Account:** In order to have this program work, you need a google account. If you don't have one  [Create a google account](https://accounts.google.com/Signup)
2. **Google APIs**
    a. in a new incognito tab, log into your new google account.
    b. then update the url to be: https://console.cloud.google.com/getting-started?pli=1 
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

### Gitpod
This section should describe the process someone would have to go through to get the local working in gitpod.  Such as install requirements.txt  and setting up a creds.json file that is in the gitignore and keeping their workspace.

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



### Heroku
This section should describe the process you went through to deploy the project to Heroku. Include screenshots if you think they would make the process easier.

You may want to re-watch the [python essentials deployment video](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LS101+2021_T1/courseware/293ee9d8ff3542d3b877137ed81b9a5b/e3b664e16366444c8d722c5d8340b340/?child=first) when writing up this section.


If you have project settings required for Heroku, provide a table of the keys and values.
Do not share your personal keys but either cut them out of the screen shot or say <YOUR_VALUE> and include links on how the user would obtain such values.

At a bar minimum you should show the user that they need to add the PORT. 8000 key value pair.


## Credits

To avoid plagiarism amd copyright infringement, you should mention any other projects, stackoverflow, videos, blogs, etc that you used to gather imagery or ideas for your code even if you used it as a starting point and modified things. Giving credit to other people's efforts and ideas that saved you time acknowledges the hard work others did. 

-[Code Institute Template](https://github.com/Code-Institute-Org/python-essentials-template)
    - The Template for the GUI for this project was provided by Code Institute. This allows for the Command line to be shown and used within the browser.

### Content

Use bullet points to list out sites you copied text from and cross-reference where those show up on your site

### Media

Make a list of sites you used images from. If you used several sites try to match up each image to the correct site. This includes attribution for icons if they came from font awesome or other sites, give them credit.

### Acknowledgments

This is the section where you refer to code examples, mentors, blogs, stack overflow answers and videos that helped you accomplish your end project. Even if it's an idea that you updated you should note the site and why it was important to your completed project.

If you used a CodeInstitute Instructional project as a starting point. Make note of that here too.


