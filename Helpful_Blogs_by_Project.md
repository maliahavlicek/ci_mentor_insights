# PURPOSE
This is an attempt to put helpful links and sites for basic tutorials together which students might use to supplement their learnings for features in their projects.

# General


## Color Contrast
- [color contrast](https://webaim.org/resourceshttps://webaim.org/resources/contrastchecker//contrastchecker/) Tool used to adjust colors on fonts flagged as needing a higher contrast ratio from google's lighthouse audit tool.


## Color Pallet

- [colors.co](https://coolors.co/) - helps you select complementary colors


## Color Variables
- If you are terrible at picking colors, use color variables to make refactoring them easier [Daniel's post](https://codeburst.io/css-variables-explained-with-5-examples-84adaffaa5bd). 


## Core Web Vitals
- [lighthouse audit](https://developers.google.com/web/tools/lighthouse) Google's open source tool to help improve the quality of your website. Specifically pay attention to Accessibility and SEO aiming for scores above 80 in your local deployment.

- [web.dev](https://web.dev/measure/) runs the lighthouse audit on independent servers to give more realistic Performance scores.  Most web developers will start looking at the First Contentful Paint, Largest Contentful Paint, Time to Interactive, and Cumulative Layout Shift.  Ideally you want a shift of 0. Google search engines take these scores into account when aggregating results for keywords. If you have higher scores and faster paint times, you get a better ranking.


## CSS Tricks
- [CSS tricks](https://css-tricks.com) has an assortment of helpful ways to use CSS to accomplish tasks. 
  - [image centering](https://css-tricks.com/perfect-full-page-background-image/) - how to center the home page background image across device sizes
  - [styling scrollbars](https://css-tricks.com/the-current-state-of-styling-scrollbars/) - to conserve vertical space
  - [star inputs](https://css-tricks.com/five-methods-for-five-star-ratings/) - ideas on how to display ratings


## Favicon Generation

- [favicon generator](https://favicon.io/favicon-generator/) - free site to help in website icon generation


## Icons
- https://www.flaticon.com, just be sure you add their required footer
- [Font Awesome](https://fontawesome.com/icons?d=gallery)
- [iconfinder](https://www.iconfinder.com/social-media-icons?price=free)

## Markdown Table of Contents Generator

- [mardown table of contents generator](https://ecotrust-canada.github.io/markdown-toc/) - used to create table of contents (be weary it does have some bugs if you have dashes or trailing spaces in your headers)


## Markdown Table Generator

- [markdown table generator](https://www.tablesgenerator.com/markdown_tables) - used to help with documentation table formatting. 


# User Centric Front End

## Grid
Grid based CSS example: [Tania Rascia's pen](https://codepen.io/taniarascia/pen/rOLEGe/)


# Interactive Front End

[PortEx](https://www.youtube.com/watch?v=28VfzEiJgy4) - youtube instructional video of a simple matching card game


# Data Centric 

## Advanced Flask Features
- [uniwebsidad.com](https://uniwebsidad.com/libros/explore-flask/chapter-8) - Provides documentation on more advanced features of flask
  - how to build macros and include them from an external file 
  - how to make custom filters
- [Todd Birchard](https://hackersandslackers.com/flask-blueprints/) - blueprints concept which makes larger flask application's directory structure manageable


## Upload File to Mongo DB
- https://www.youtube.com/watch?v=DsgAuceHha4 - shows you how to add a file to mongo db and use it in your templates to display it

## User Login System for Flask
https://www.youtube.com/watch?v=w1STSSumoVk

# Django Python Ecommerce

## Blog

- How to create a blog in django: https://www.youtube.com/watch?v=B40bteAMM_M&list=PLCC34OHNcOtr025c1kHSPrnP18YPB-NFi&index=2
- how to add a blog comment: https://www.youtube.com/watch?v=hZrlh4qU4eQ&list=PLCC34OHNcOtr025c1kHSPrnP18YPB-NFi&index=34
- how to post blog comments: https://www.youtube.com/watch?v=OuOB9ADT_bo&list=PLCC34OHNcOtr025c1kHSPrnP18YPB-NFi&index=35
- Like Unlike a blog: https://www.youtube.com/watch?v=PXqRPqDjDgc


## Django Email Templates

- Documentation: https://docs.djangoproject.com/en/3.1/topics/email/#the-emailmessage-class
- Video tutorial:  https://www.youtube.com/watch?v=1BaLWYUO1k4


## Customizing Error Views

- Documentation: https://docs.djangoproject.com/en/3.1/topics/http/views/#customizing-error-views
- Video: https://www.youtube.com/watch?v=gsW5gYTNi34


## Loading and Dumping Data

- [coderwall](https://coderwall.com/p/mvsoyg/django-dumpdata-and-loaddata) for examples on how to dump data and load it which saves a bunch of time when deploying the application from a local database to a hosted database
- https://docs.djangoproject.com/en/3.1/ref/django-admin/#dumpdata
- https://docs.djangoproject.com/en/3.1/ref/django-admin/#loaddata

## Video File Uploader
- [Learning about Electronics](http://www.learningaboutelectronics.com/Articles/How-to-create-a-video-uploader-with-Python-in-Django.php) - how to get a video file uploaded and displaying