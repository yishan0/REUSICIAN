# REUSICIAN
Made by James Liu, Yishan Lin, Tengyi Huang, and William Chen Lv for Hack Cupertino 2025.

## Overview
What is Reusician?
Reusician, (Reuse+Musician!) is a website where people can list instruments and instrumental supplies they do not need, in search for a new owner.

The website is made using HTML, CSS, SQL (sqlite3), and python (flask).

## Inspiration
As a team of both musicians and coders, we noticed that many of our peers have eventually gave up their musical journey, no matter if it is because of other time commitments or just simply a lack of interest. In our community, where many students have learned to play musical instruments but inevitably some will quit. So the question comes, where do their musical instruments and supplies go? Not only that, but instruments are extremely expensive. If I wanted to try out a Viola, how can I get a chance to? These observations led us to our idea to stay sustainable by helping those wanting to begin their musical journey with cost effective, used, alternatives to expensive, unsustainable new instruments and materials.

## What it does
Our program allows users to make posts about instruments or musical supplies they do not use anymore, or do not need. These posts go into a large online forum, where the seller can either exchange it for other instruments, sell it for cheaper used item prices, or simply donate it away. Users can comment on any post, to be able to get more information about the seller and purchase the instrument safely in person. Other than the fact that students often give up on their instruments, music instruments are also often build unsustainably, requiring rare exotic woods, and some beginner disposable instruments are even mass produced. This causes unnecessary unused instruments as students become better, buy new instruments, and throw their old instruments away. Instead, these unused instruments can be provided to a new musician that is willing to try but may not have that much budget.

## How we built it
We used flask as the back-end framework and SQLite for the database. The front-end was created with HTML and CSS. Using Jinja2 templating for the web pages to dynamically render content in response to database queries done with SQLite in python.

## Challenges we ran into
A major challenge was logistically figuring out how we would manage our own comments system using a database. We eventually decided to hold all the comments in their own table with their parent post ID and a timestamp, then rendering comments which had the corresponding post ID. While we had experience in flask and SQL, another big challenge was learning to create pages dynamically in response to a database ID so that we would have unlimited unique pages for new forum posts.

## Accomplishments that we're proud of
We are proud to have created a function forum-like web-app from scratch. We managed to create a modular and cleanly organized project using more complicated implementations of code and database queries, implementing a dynamic commenting system and having unique pages for each post all stored in a database. Ultimately, we are proud to have created a project that effectively tackles sustainability in a way relevant to our community.

## What we learned
We more deeply reinforced our skills with SQLite and flask, especially with dynamically creating pages and managing table relationships. We also learned how to effectively handle user data and make a clean front-end and back-end interaction to create a smooth user experience.

## What's next for Reusician
We noticed that many students in our own community have given up instruments. It is a great next step to distribute our website to our local community so these instruments will not go to waste, and help maintain a more sustainable community. Some code improvements would include adding more secure features like user authentication, post searching, and a more precise user experience for this project to be scaled up. Ultimately, we aim to grow Reusician to help anyone around the world begin their musical journey while staying sustainable.

## More information
Read our slideshow for more information.
https://docs.google.com/presentation/d/12GbslulLvFcXJTfWrNomheHun4FMsW5Ch_lmVHCMiNE/edit#slide=id.g34b813f8cae_1_24233

