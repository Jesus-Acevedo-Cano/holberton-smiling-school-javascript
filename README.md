# 0x0F. Build a web app in JavaScript

<h1 align=center>Holberton Smiling School javascript

![Holberton Similing School](images/smile_on.png)

## Description

In this project, you will finalize the previous project 0x0B. Implement a design with bootstrap and make some parts dynamic with Javascript (JQuery exactly).

You will reuse final files of 0x0B. Implement a design with bootstrap and update them.

You will use all HTML/CSS/Accessibility/Responsive design/Bootstrap/Javascript knowledges that you learned previously.

You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have fully functional web pages that look the same as the designer file.

## Requirements

- You have to use Bootstrap
- Your styles.css must be as small as you can - you must use as much as you can Bootstrap classes
- You have to use JQuery
- Your scripts.js must contain all your Javascript part
- Your Javascript must be executed only when the document is loaded

## Tasks

#### 0. Reuse and polish your Bootstrap integration
Copy files from 0x0B. Implement a design with bootstrap:
- homepage.html -> 0-homepage.html
- pricing.html -> 0-pricing.html
- courses.html -> 0-courses.html
- styles.css and any files/folders needed (images, fonts…)

#### 1. Homepage - quotes
From 0-homepage.html, create 1-homepage.html.

Replace static quotes by dynamic loading:

- URL: https://smileschool-api.hbtn.info/quotes
- No static quotes should be present in the quotes section
- During the Ajax request, a loader should be present
- Carousel should work like before

#### 2. Homepage - popular tutorials 
From 1-homepage.html, create 2-homepage.html.

Replace static video cards by dynamic loading:

- URL: https://smileschool-api.hbtn.info/popular-tutorials
- No static video cards should be present in the section
- During the Ajax request, a loader should be present
- Carousel should work by sliding card by card (like GIF below) - this kind of carousel is not unique, make it generic to reuse it easily!
- Don’t forget the responsive part!

#### 3. Homepage - latest videos
From 2-homepage.html, create homepage.html.

Replace static video card by dynamic loading:

- URL: https://smileschool-api.hbtn.info/latest-videos
- No static video cards should be present in the section
- During the Ajax request, a loader should be present
- Carousel should work by sliding card by card (like GIF below) - this kind of carousel is not unique, make it generic to reuse it easily!
- Don’t forget the responsive part!

#### 4. Pricing - quotes
From 0-pricing.html, create pricing.html.

Replace static quotes by dynamic loading:

- URL: https://smileschool-api.hbtn.info/quotes
- No static quotes should be present in the quotes section
- During the Ajax request, a loader should be present
- Carousel should work like before

#### 5. Courses
From 0-courses.html, create courses.html.

Replace static video card by dynamic loading:

- URL: https://smileschool-api.hbtn.info/courses
  - GET parameters:
    - q: search value (in our case, the value of the field KEYWORDS)
    - topic: topic filter value (in our case, the value of the field TOPICS)
    - sort: order of all courses (in our case, the value of the field SORT BY)
- No static video cards should be present in the section
- During the Ajax request, a loader should be present
- Dropdowns are dynamic (coming from the API):
  - Topic: list of topics
  - Sort by: list of sorts
- Search value should be initialized by the value q in the API response
- The list of video cards is coming from courses in the API response
- API request must be done when:
  - Search value is changing
  - A new Topic is selected
  - A new Sort by is selected
