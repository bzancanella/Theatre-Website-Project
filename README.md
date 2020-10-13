# Theatre-Website-Project
Internship with Prosper IT Consulting
Introduction
During the end of my Front End Web Developer bootcamp at the Tech Academy I was involved in a two week internship where a team of students worked on a large scale MVC web application. The scale of it was larger than anything I had previously worked on, but it provided a great experience for the type of work I will be doing in the future. We were given lists of specific projects, and I worked on several tasks related to fixing design issues, altering layouts for specific results, and programming additional features. I really enjoyed the entire process, from learning the ins and outs of the IDE, to the constant fine-tuning and troubleshooting of my code. Working as a small team was a good opportunity to get the feel of team software development, and it is something I am looking forward to with a lot of enthusiasm. I am excited for the chance to work on projects of any scale in the future,I felt the process worked well for my strengths while challenging a few of my weaknesses, which lead to an experience that left me hungry for more. 

Front-End User Stories

Button Styling
I was tasked with standardizing all of the buttons on the main site. The previous buttons were based on a Bootstrap class and I was tasked with creating a new custom class for the website so that changes in the styling could be made from within the site’s css file. I based the new class off of one of the existing buttons that fit the profile of what the team was looking for. I updated the hover effects and transitions, as well as the overall styling. 

The original code (referencing the Bootstrap class btn-primary) on the left, updated code on the right:








Original:				   	  Updated:
  



The button class needed to be changed on every page so I updated it on 51 different files. Several of the pages needed additional styling and adjustments, which I used Bootstrap classes to achieve. 


Archive Page Styling
In this story I was tasked with several changes to the Archive Page. First I needed to move the search bar and resize it. In order to achieve that I moved the entire code block into the correct position on the website. I edited the css file to change the size of the search bar. The design team also gave us a color palette for the site and I needed to update the page to match, so I updated the colors of the search bar and search results table to match the rest of the site.

Original:						   Updated:
  

I also needed to fix the buttons on the page, aligning them with the rest of the website. I used the custom button class that I had updated in a previous story, and edited the css to fix an issue with disabled buttons reacting to mouse events. I created some space along the edges of the content by adding Bootstrap classes to each of the content sections. 

Original:						    Updated:
  

In order to make the Past Productions section more visible I updated the accordion buttons to the site’s custom button class, which changed the look of them completely while fitting the theme of the site. 

Original:						    Updated:
  

Clickable Area Fix
I was assigned the task of fixing it so the clickable area of a photo link was contained only within the Production Photo. There was a Bootstrap spacing class in the <img> tag that was making the clickable area larger than the photo, so I removed it. In order to maintain the distance between the header and content that had previously existed I placed the spacing class back into the <div> tag above it.

The original clickable area of the production photo is outlined in blue on the left picture. The right picture shows the updated clickable area of the production photo. 
  

Skills & Lessons Learned

Understanding what tools you have, and utilizing them in the best way. This goes for the tools inside your IDE, to the tools available to you on the internet, to the tools available to you through your work and personal networks.
Balancing troubleshooting on my own with being able to ask for help. While it is important to solve things on your own, there is a point where you begin to bog down and it is simply more efficient to look for an outside opinion. 
Debugging, debugging, debugging. From learning the best tools for debugging, to the mental fortitude of being patient, persistent, and detailed when going line by line. 
