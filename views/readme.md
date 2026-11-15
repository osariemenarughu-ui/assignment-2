Assignment 2 – Express Portfolio Website

About This Project

This is my second assignment for INFR3120 Web and Scripting Programming at Ontario Tech University.

For this assignment, I created a personal portfolio website using Node.js, Express.js, and EJS. The goal was to build on my first portfolio assignment while learning how to create a website using Express and reusable EJS templates.

My website has four main pages:

Home – An introduction to who I am.

About Me – More information about my background, education, and interests.

Projects – Some of the projects I've worked on.

Contact Me – Ways to get in touch with me.

Technologies I Used

I used the following tools and technologies to build my website:

Node.js and Express.js – To set up and run the website.

Express Generator – To create the starting project structure.

EJS – To create the pages and reuse the same header and footer.

Bootstrap – To help with the website's layout and design.

Font Awesome – To add icons for my social links and contact information.

CSS – To customize the appearance of the website.

Git and GitHub – To save my work and track changes.

Render – To host my website online.

Project Structure

I used Express Generator to set up the project with EJS as the view engine.

Here are the main folders and files:

routes/index.js – Handles the routes for each page.

views – Contains the EJS files for my website pages.

views/partials – Contains the shared header and footer.

public/stylesheets – Stores the CSS files.

public/images – Stores the images used on the website.

public/videos – Stores the video files used on the website.

Using EJS partials made it easier to keep the navigation bar and footer consistent across all four pages without having to write the same code multiple times.

Reusing Content From Assignment 1

Since this assignment builds on my first portfolio website, I reused some of the content I had already created.

This includes my personal information, images, video, project descriptions, contact information, and some of my original CSS.

However, I recreated the website pages using EJS instead of copying over the HTML files from Assignment 1, as required by the assignment instructions.

Course Material

Most of the Node.js and Express code I used was based on what we learned in INFR3120, especially the MEAN Stack Development lecture.

Some of the main concepts I used include Express routing, require(), module.exports, res.render(), static files, and EJS templates.

Other Resources Used

I also used a few outside resources to help build and deploy my website.

Bootstrap


I used Bootstrap to create the navigation bar, organize the page layouts, and style buttons, forms, and other parts of the website.

Font Awesome

Website: https://fontawesome.com/

I used Font Awesome to add icons for links such as GitHub, LinkedIn, and email.

EJS

Website: https://ejs.co/

I referenced EJS documentation to help with the shared header and footer using includes.

Render

Website: https://render.com/docs/deploy-node-express-app

I used Render to deploy my Express application so the website can be accessed online.

Version Control

I used Git and GitHub to manage my project and keep track of the changes I made while working on the website.

I made commits at different stages of development as I added pages, updated the design, and worked on the website's functionality.

