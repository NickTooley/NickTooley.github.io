---
layout: page
title: Timeline
---
<style>table td, table td * {
    vertical-align: top;
}</style>
<h3>The following is a session by session run down of my work on the project including dates and quick overview of what I had achieved in that session.</h3>
<br />
<table>
<tr><td>Week 0: </td><td>	Submitted my CV and cover letter as application for 2 of the projects listed. I picked Leave Management as my first option and Semester Planning as the second.
	Was lucky enough to be assigned to my first option, the Leave Management group, where I joined Fletcher Barratt, Albert Tireck, and Coen. I quickly created a Slack channel and added all the members to the group. </td></tr>

<tr><td>Week 1:	       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td><td>We spent the first session together as a group creating user stories based on both our client’s specifications and our best estimates of what an end user may require. We added these user stories onto a newly created Trello board.<br /><br />
	The second session of the week we assigned some tasks to members to do over the weekend, examples of tasks were wireframes for potential site layouts and technology researching. I assigned myself the role of creating a database model and making a UML diagram of it. I spent parts of the weekend completing these at home.</td></tr>

<tr><td>Week 2:</td>	<td>I showed the team my database model and they seemed to be happy with it, so I began coding up a PHP file which created the database and filled it with a small amount of dummy data. I also spent my time looking into potential frameworks to use for the project.<br /><br />
	I wanted to follow the Agile principles for this project and one of those I need to get onto quickly was to ‘satisfy the customer through early and continuous delivery of valuable software’ so I began coding up an early prototype of the system that I will be able to show the client by early next week. I spent all of the latter part of the week and the weekend coding up a working system and deployed it on my personal kate server. This early system was very barebones (no styling, only the completely necessary features) but it was functional.</td></tr>

<tr><td>Week 3:</td>	<td>I signed up for a free 14 day trial of Calamari, another premium leave management system on the market, in order to research necessary features and the overall UX. I took screenshots and added them to the Trello board for the rest of the team to view. We managed to get a few extra user stories and more potential wireframes out of it, so it came in handy quite a bit.<br /><br />
	Also managed to add an emailing functionality to the site which sent an email to the student confirmed requests, and notified of approval or denials.<br /><br />
	We assigned ourselves the task over the holiday to research some PHP frameworks which could potentially make our system a bit more sophisticated</td></tr>

<tr style="background-color: #f2f2f2;"><td>Week 4:</td>	<td>(Holiday Period) I was working a full-time job over the holiday period so I didn’t have the chance to work on the project all that often, however through research, found a few PHP frameworks which may work for our system. Laravel, CodeIgniter and the tutor recommended Yii. Laravel seemed to be the new ‘hot’ framework which a lot of companies in the industry were turning to, however was quite a bit out of scope from what I thought necessary. Yii didn’t have the easiest to comprehend documentation and found the built-in UI elements quite ugly. CodeIgniter was a very nice lightweight option with good documentation.</td></tr>

<tr style="background-color: #f2f2f2;"><td>Week 5:</td>	<td>(Holiday Period) Still working full-time, I worked my way through CodeIgniter’s tutorial, figuring things out and seeing how it would translate to our project. I spoke with Albert (the other PHP proficient programmer in the group) through Slack talking about the frameworks benefits vs it’s learning curve and we both came to the conclusion that it would be more beneficial to continue to code in plain PHP as it’s a language we know, we already had an initial codebase and it would be easier to delegate HTML and CSS tasks to the other members.</td></tr>

<tr><td>Week 6:</td>	<td>Returning to class, we were able to have a group meeting again. Straight off the bat, we had been given a new member, Henry. We began assigning overall roles to all the members. This was important as 3 of the members weren’t proficient in PHP. Coen was assigned GUI and UX, Fletcher provided with git and security and Henry given testing. Albert and I were given the roles of general PHP coding with the added task of database management. Our first sprint tasks were assigned.<br /><br />
	I started a complete overhaul of the database model that our initial version was based off of after realizing the current model would stop us from adding necessary features down the road. I uploaded a UML diagram to the Trello board, which Albert then used to code up a new database creation PHP file.<br /> <br />
	I also spoke to Rob and got a Kate server with a MariaDB account created for the group and moved over our initial codebase to there, editing the necessary files to include the new domain name.</td></tr>

<tr><td>Week 7:</td>	<td>We met on the Monday in the common room and we discussed together our website flowchart. We also assigned specific pages that each member had to code up (PHP light pages were given to members with less PHP nous) and this became our next sprint tasks. My task was the admin landing page.<br /><br />
	I sat with Fletcher in another one of our classes and started our git repo and cloned it into a directory on the groups Kate server and added our existing code to it. I also added the Trello plugin into our Slack channel which allowed us to display cards and assign tasks directly from our Slack channel.<br /> <br />
	I also provided some additional database modelling, which I provided to Albert to code up, and completed my coding up of the admin landing page. Our sprint tasks for the week was to make sure days of leave remaining was calculated and shown to the user and that our site was fully functional with styling.</td></tr>

<tr><td>Week 8:</td>	<td>Met up with Albert on Monday following one of our shared classes to assist in the ‘gluing’ of all the member's pages together, which all went very smoothly. Once that was completed we went to commit it to the git repo when we decided to switch things up and the project had been under a massive overhaul. We deleted all files from the git repo and committed all the new files onto there.<br /> <br />
We showed our new project to the client who was very happy with our progress. Albert and I also came up with a new development cycle which consisted of a development server and a live server both containing our git repo. However, I wrote a script for the development server which calls the git pull command every 10 seconds. We couldn’t get the script to run when not signed in, so we left our git manager, Fletcher, to research a way to get the script to run at all times.<br /><br />
We also assigned tasks for our next sprint, my task for the sprint was to transfer the insert query from the student landing page to the leave request page as there was a bug which caused additional requests to be made upon refreshing. I was also assigned the task of coding up a page which shows the lecturer all students and their remaining leave days for each leave type.</td></tr>

<tr><td>Week 9:</td>	<td>Friday we had an exam for software engineering which meant we had one less meeting this week. I had completed both my sprint task of the past week and added it to the site. Upon our Tuesday meeting, I had discovered Albert had found a much more elegant solution to the bug, so we implemented his version onto the live site.<br /><br />
	Our next assigned sprint tasks were assigned, and I was assigned the task of implementing a feature which allowed a lecturer to upload a csv file of students in a stream and loads it into the database. I spent the week looking for solutions to this but found it difficult as the kate server’s PHP.ini file wouldn’t allow file uploads. Decided to focus on reading in a csv which is just hard coded into the directory. I also provided Coen, our lead UI designer, with the necessary dimensions to resize the OP logo on all pages.
</td></tr>

<tr><td>Week 10:</td> 	<td>This week saw me having 2 assignments due at the end of the week in other classes, which required most of my attention. I only got a minimal amount of work done on the project, but was able to complete a few small tasks and fixed up small things here and there like including a functional return to dashboard button on the allstudents page and adding asterisks to the required fields on the leave request form.  <br /><br />
    As I was unable to complete my sprint task for this week (reading in a csv), so I carried that onto my next sprint as long as a couple additional tasks (adding proper authentication to access control and ensuring good functional password hashing).
</td></tr>

<tr><td>Week 11:</td> 	<td> With last weeks assignments out of the way, and no other ones immediately on the horizon, I was able to put a lot of work into the project this week and I got a lot done! I managed to get the previous week's sprint task that I failed to do completed (CSV reading into the database, which also required some tinkering with our database tables) as well as the other task assigned to me (Proper authentication with password hashing). Not only was I able to finish 2 weeks worth of sprint tasks, I also went above and beyond and entered the backlog of our Trello board and completed numerous tasks from there.<br /><br />
I was able to calculate and display days of leave remaining on the student landing page and in the drop-down box in the Leave Request form. I added require tags on the fields in the leave request form also, stopping the user from creating a bad request, whether on accident or on purpose. Adding onto that I also made sure the number of days was calculated when a request is made and checks if the student has enough remaining.<br /><br />
I formatted the date shown in lecturer and student landings to display in a more user-friendly and less cluttered manner. I also added onto one of my previous sprint tasks which was displaying all the students to the lecturer and their remaining leave days per type. I modified this to only display students in streams the lecturer teaches and also the ability to display students in a stream selected from a drop-down menu.<br /><br />
We had a meeting on the Friday about what to do from here until the end of the semester. We all agreed, because the last week of semester is going to be pretty hectic with exams and portfolios due, to start our proper testing with the members from the Software Testing class early next week, so we can make adjustments late next week. This means we had no active sprint until the software testers provide us with a testing report.

</td>
</tr>
<tr><td>Week 12:</td> 	<td> Closing in on the final week of the semester, our project was starting to look really polished with a lot of functionality. We got our testers to begin their testing of our software and instantly spotted one major bug, we hadn't pulled to our live server in almost 2 weeks and the login could no longer authenticate on our new database, oops !<br /><br />
This week I got to work on another feature I was trying to figure out a couple weeks ago but was struggling with, the csv upload and reading. Back then I was able to get it working from a hard-coded csv file, but that obviously wouldn't be the best solution long term, so I set out to learn a new skill and figure this out<br /><br >
After a good amount of searching and trial and errors, I was able to get it up and running on our admin landing page, along with a form that asks for the new stream name (and sanitizes it), has a drop down box of all the lecturers and a file upload button where the user will upload their csv file. While working on this page, I also added the proper functionality to the rebuild default database button and logout button."
</td></tr>

<tr><td>Week 13:</td> 	<td>Going into the final week of the project, the application was all but completed, and we decided as a team to add no more functionality and to just focus on fixing any bugs that pop up from the user testing report we're receiving from the testing students.<br /><br />I messaged the team on Slack on the Tuesday to ensure they were all at the upcoming class as I wanted to begin a draft of the technical report as a team. Everyone but Henry showed up, and in order to stop everyone awkwardly crouching around one computer making small changes here and there, I created a Google Doc with editing permissions and put it into the Slack channel so everyone in the team was able to edit and add to it simulataneously.<br /><br />
</td>

	 

 

