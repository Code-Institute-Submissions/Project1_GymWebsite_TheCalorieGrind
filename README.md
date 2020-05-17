# Code Institute

# User Centric Frontend Development Project - "The Calorie Grind" Gym Website

The Calorie Grind is a gym set up with the aims of having an environment that is open to everyone while at the same time professional. The main aim is to reassure new customers that the gym puts their mental health first through positive statements such as the ones outlined in the Mission section on the first page. 

The website itself offers all of the key information needed to to see what the gym is about, what classes are being taken, availability, where to find the gym and how to get started via a submission form. On top of this all contact details and social medias are provided at the footer section of every page.  

# UX

For the user experience I wanted to ensure that it was simple for the potential customer to access all information as fast as possible. 

Through the drop down menu all information is available within 3 clicks of opening the website. It is layed out in order so as one goes through the website step by step they get to the final page with all the information they need. 

The index page greets the user with a burn animation upon loading which is then a reoccuring theme in each page following. My idea around this was to subliminally incentise the idea of when you come to the page you are there to burn calories reflecting the gym logo itself The Calorie Grind. This is followed by inspirational messages with the intent of making the user feel comfortable as the gym experience for most new users often is wrapped in some form of anxiety/nervousness. 

# Features 

1. Photo Gallery - Users can see other customers through images provided. 
2. Dropdown Menu - Allows you to navigate through the website in 3 clicks.
3. Google Maps Iframe - Users can see the exact location of the gym on an interactive map.
4. Burn Animation - Every page loads with a transition of colours to mimic fire. 
5. Timetable Scroll - Overcomes scaling issue on table by allowing user to scroll across table independent of page. 
6. Submission Form - Customers can submit a form to sign up for a free session.

# Technologies Used

1. Bootstrap - Used when setting up rows and columns for rescaling for different sized screens.
2. Font Awesome - links all of the icons to the screen seen throughout project and footer section

# Testing 

## Browser Testing and Screen Sizing 

Comparing the user experience between Internet Explorer and Google Chrome showed no difference between the two. All aspects and features of the website ran the exact same. In both browsers the dropdown menu worked the same and all keyframes ran as they should.

The screen sizing was tested rigorously from the screen size of a laptop all the way down to a phone. All features stacked well as screen size dropped. 

## Bugs

Main issue that persisted the entire project was that of overscrolling on the X-axis. The bug was fixed by removing min-width:100% to width:100% when setting out the design of the websites. 
Min-width:100% adds extra space to the right which was causing the overscroll issue. Inital fix was to have overscroll-x:0 in the body. 

Inital header displayed all of the pages. Stacking and spacing issue occured where they would overlap as the screen size got smaller. Issue resolved by recreating the header to have a dropdown menu. 

Similar overlapping issue in the Timetable which was overcome by adding a scroll feature to the timetable making it independent of the rescaling process. 

# Deployment
The Deployment of the project is being completed through GitHub Pages. 


# Credits 

## Content 

Content for mission statements came from http://www.fit100hq.com/'s previous website. 

## Media 

All media came from https://www.pexels.com/ to ensure copyright free images. 

## Acknowledgement

Mentor Aaron who gave the idea for a dropdown menu in the header and to add a scroll feature to the timetable.

Set up for the gym website w/ black and white theme came from http://www.fit100hq.com/, https://www.goldsgym.com/ and https://www.elegantthemes.com/blog/divi-resources/examples-of-fitness-websites-built-with-divi for various examples of how other gym websites look. 

Submission form, Timetable and dropdown design came from research on StackOverFlow. 

All other aspects of the website came from the lessons taught on the course and my own intuition e.g. photo gallery. 

