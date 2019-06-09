# 100 Days Of Code - Log

### Day 0: September 20, 2018

I decided that it would be worthwhile to try and plan out some of my journey over the next 100 days.

I normally have a hard time coming up with applications that I care to write. I've tried doing to-do apps in the past, and I get demotivated rather quickly. Plus, they always say, "Build something that you need." Well, the things I've needed haven't really been all that complex, so, in terms of projects, there hasn't been anything super impressive on my resume so far.

That means I have a few options with these next 100 days.

I could build one massive, complex application.

I could work on a bunch of small applications that use different tools (GraphQL, Apollo, Spring, etc).

Or a combination of the two: some days work on the big app, some days work on the small apps.

In any case, I'll have to take some time to think about what I want to build. I'm currently leaning towards the second approach; I'd love to get a handle on all of these tools that I haven't used yet.

### Template

### Day 0: September 20, 2018

**Today's Progress**:

**Thoughts:**

**Link to Work:**

### Day 1: September 19, 2018

**Today's Progress**: Worked on Discord Logger Bot. Removed some fluff from the bot, and added 'youtu.be' to list of domains to check. Practiced implementing bubble sort algorithm from memory that I learned earlier today.

**Thoughts:** I also attempted to utilize some thumbnail resizing package for the Django back-end, but it ended up 1. Giving me an error with the migrations I was supposed to run, and 2. It didn't work exactly how I thought it would, anyway. If I were going to use it, I would have to use it when the media object is saved, then create a smaller thumbnail image and host the URL somewhere, probably on S3. That just seems like more trouble than it's worth right now, but I might look into it for the future.

**Link to Work:** [Discord Bot Github](https://github.com/HanifCarroll/Media-Logger-Discord-Bot)

### Day 2: September 20, 2018

**Today's Progress**: Nearly implemented thumbnail resizing with Pillow.

**Thoughts:** Pretty productive session. I was able to resize the "thumbnail" images from Spotify/YouTube and save them in an s3 bucket. All that I have left to do is to figure out how to get the URL for the uploaded image, so that I can save it in the database.

**Link to Work:** [Discord Bot Django Server](https://github.com/HanifCarroll/Media-Logger-Django)

### Day 3: September 21, 2018

**Today's Progress**: Finished implementing thumbnail resizing on Media Logger service, and fixed a bug with the Discord bot.

**Thoughts:** s3 storage is pretty handy. Reviewed some sorting algorithms for a bit, starting to get the hang of them. I also went through a couple Spring Boot videos, and I feel ready to make another application with it.

**Link to Work:** [Discord Bot Django Server](https://github.com/HanifCarroll/Media-Logger-Django)

### Day 4: September 22, 2018

**Today's Progress**: Spent all evening implementing a pie chart view for the Media Logger. I also started a new blog application using Spring Boot.

**Thoughts:** The charts took a bit longer than I expected due to not-so-great documentation, but I eventually figured it out.

**Link to Work:** [Discord Media Logger Client](http://discord-media-log.s3-website.us-east-2.amazonaws.com)

### Day 5: September 23, 2018

**Today's Progress**: Practiced searching algorithms. Read a lot about job hunting. Worked on the Spring Boot blog project.

**Thoughts:** I feel like I'm in a funny spot. I'm thinking I should scrap the Spring project and just make it in Node instead. I should be using this time to make things that potential employers will like, not necessarily struggling with new technologies. I can do that after I secure a job.

**Link to Work:**

### Day 6: September 24, 2018

**Today's Progress**: Learned about system design, scaling, and algorithms.

**Thoughts:** Gonna have to repeat this one. On Sunday I signed up for TripleByte and I made the questionable decision of scheduling my interview Tuesday morning. Checked what the interview would consist of, and there were a couple things I had practically 0 knowledge of. Namely system design and algorithms. Spent 8 hours learning about the former, where I feel like I made a big improvement. Then about 6 hours on the latter, which I don't think helped much. Regardless of outcome, looking forward to the feedback I get from the interview!

**Link to Work:**

### Day 6: September 25, 2018

**Today's Progress**: TripleByte interview, worked on customer table view React app for job application.

**Thoughts:** TripleByte interview went decently. Attempted to make a Trello-like board. Got stuck on some functionality, but I think I did fairly well on the technical questions. Later on, I started working on this small project for a job application. It's essentially a table view where you can search through the results. Got stuck trying to implement some things on my own, but luckily there were libraries to help me out.

**Link to Work:**

### Day 7: September 26, 2018

**Today's Progress**: Finished application assignment from the recruiter.

**Thoughts:** Finished things up this morning over a couple hours. I'm pretty happy with how it turned out. Also, started working on [this](https://github.com/jwasham/coding-interview-university) CS study guide. My goal is to eventually know enough to be a software engineer at a big N company, despite not having a CS degree.

**Link to Work:** [Customer Table App](https://github.com/HanifCarroll/Customer-Table)

### Day 8: September 27, 2018

**Today's Progress**: Spoke with a successful SWE and received a ton of good advice. Read through some of The C Programming Language. Spent about an hour on Leetcode.

**Thoughts:** Received a lot of direction and good advice today. Afterwards, I sat down and formulated a plan for myself that I'm really happy with.

**Link to Work:**

### Day 9: September 28, 2018

**Today's Progress**: Started the Hartl Rails tutorial, read the first chapter of The Algorithm Design Manual, practiced some algorithm problems on Firecode.io, and started a small CRUD project using Node, Express, and Knex/Objection.

**Thoughts:** I remember when I first got into web development a year and a half ago, I had so much trouble going through the Rails tutorial, and I eventually stopped to start learning Node. Things should be more smooth this time, though. Really enjoying working with Node again on this CRUD app. It's just so fast, and easy to do things...once I remember how exactly to do them. I'm also excited to learn more about algorithms. The 1st chapter does a great job of explaining that there are different types of abstract problems that relate to the real-world problem you're facing; you just have to know the classification of that problem, then it's much easier to find a solution.

**Link to Work:** [Cat App - Node](https://github.com/HanifCarroll/cat-app-node)

### Day 10: September 29, 2018

**Today's Progress**: Spent hours trying to switch a couple sites from Google Cloud Platform to AWS. Read a lot about CSS, including SMACSS. Watched (yet another) video series on system design. Then finished the night with some coding problem practice and working on my node app.

**Thoughts:** Running into some issues with the node app. Trying to figure out how to model relationships with Knex/Objection. I might have to take a different approach/use a different ORM.

**Link to Work:** [Cat App - Node](https://github.com/HanifCarroll/cat-app-node)

### Day 11: September 30, 2018

**Today's Progress**: Got my portfolio site switched from Google Cloud Platform to AWS EC2. Read chapter 2 of Algorithm Design Manual. Finished chapter 2 of Hartl's Rails tutorial. Worked on Node app.

**Thoughts:** Decided that I don't need to be focusing on algorithms and data structures so heavily right now. All I need is that first job, then after I get some experience, I can start worrying about learning those things to interview at better places. For now, I just need to make things, network, and send applications.

Switching from Knex to Sequelize has been great so far. The Node app is coming along. I'll probably work on user login and authorization next.

**Link to Work:** [Cat App - Node](https://github.com/HanifCarroll/cat-app-node)

### Day 12: October 1, 2018

**Today's Progress**: Started user register/login flow on the Node app, and finished chapter 3 of Rails tutorial.

**Thoughts:** Really struggling with implementing user authentication.

**Link to Work:** [Cat App - Node](https://github.com/HanifCarroll/cat-app-node)

### Day 13: October 2, 2018

**Today's Progress**: Finished chapter 4 of Rails tutorial, bookmarked a bunch of React best practices articles, and worked on my Node app.

**Thoughts:** Almost went with Firebase Auth, but decided that I may as well use AWS's solution since AWS is everywhere these days.

**Link to Work:** [Cat App - Node](https://github.com/HanifCarroll/cat-app-node)

### Day 14: October 3, 2018

**Today's Progress**: Worked on a branch of my node app (spent a bunch of time doing the wrong thing and ultimately getting nowhere), finished Rails tutorial chapter 5, and looked up/saved a bunch of React/Redux best practices/tips.

**Thoughts:** Implementing user auth is hard. I don't remember it being like this, so I'm not sure what I'm doing wrong now. The Rails chapter wasn't very interesitng, so hopefully the next one picks up the pace. I'm finding some really good tips for React, though, so that's nice.

**Link to Work:** [Cat App - Node](https://github.com/HanifCarroll/cat-app-node)

### Day 15: October 4, 2018

**Today's Progress**: (Kind of) implemented ratings in my Node app, finished another chapter of the Rails tutorial, and more reading on React topics.

**Thoughts:** Probably gonna be done with this Node app soon. I want to get started practicing my React/RoR skills ASAP.

**Link to Work:** [Cat App - Node](https://github.com/HanifCarroll/cat-app-node)

### Day 16: October 5, 2018

**Today's Progress**: Finished 3 chapters of the Rails tutorial.

**Thoughts:** Didn't work on anything of my own, but I think I made up for it by going through those 3 chapters.

**Link to Work:**

### Day 17: October 6, 2018

**Today's Progress**: Finished 3 more chapters of the Rails tutorial.

**Thoughts:** Ok, this should be the last day that I only do tutorials. I have only 1 chapter left of the Rails tutorial, and then I'll be starting my work with React.

**Link to Work:**

### Day 18: October 7, 2018

**Today's Progress**: Finished the Rails tutorial and started on my React project.

**Thoughts:** Finally done with the Rails tutorial. Started a new project today, a notes app with React. Something that shouldn't be too challenging, but I have an opportunity to do it well, and make it look nice.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 19: October 8, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** Started the notes app and added basic add and delete functionality.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 20: October 9, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** Essentially restarted the notes app to make it look more like Google Keep. Finished adding, editing, and deleting note functionality.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 21: October 10, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** Added a few more features. Nothing crazy.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 22: October 11, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** Added more features. It's really starting to come together! Also,discovered that my github commit history is a bit misleading since I've used a few different email addresses. Gonna have to fix that.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 23: October 12, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** More features. Writing this a day late, so I can't exactly recall what I did.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 24: October 13, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** First draft of the notes app is completed, and it's up on Netlify. There are still a few things I want to add like drag and drop reordering and clicking inside of a note title or content and placing the edit cursor there.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 25: October 14, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** Spent about 2/3rds of the day trying to add drag and drop reordering, and failed. Scrapped it, and added an edit overlay instead.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 25: October 14, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** Spent about 2/3rds of the day trying to add drag and drop reordering, and failed. Scrapped it, and added an edit overlay instead.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 26: October 15, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** Refactored the notes app to be organized by feature/component building blocks rather than just components. Not necessary for this small of an app, but a good exercise to practice.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 27: October 16, 2018

**Today's Progress**: Worked on Notes app.

**Thoughts:** Spent the day reviewing a refactor that another developer did of my app using the render props pattern. Took a lot of time to go through each component and see exactly what was happening, and learned a ton in the process!

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 28: October 17, 2018

**Today's Progress**: Finished refactoring notes app.

**Thoughts:** Finished refactoring my notes app to make use of the "render props" pattern. The concept is still a bit shaky to me, but I'm starting to get it, and I'm seeing how nice declarative style programming is.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 29: October 18, 2018

**Today's Progress**: Add feature to notes app.

**Thoughts:** Finally figured out how to add a feature of the notes app where I can focus an input after I click on text and change it to an input. This required me to learn about how refs work. I also started adding TypeScript into the app.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 30: October 19, 2018

**Today's Progress**: Attempt to convert notes app to TypeScript

**Thoughts:** Had to wade through a ton of errors, and ultimately ended up failing. On the plus side, I learned a lot about how to use TS.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 31: October 20, 2018

**Today's Progress**: Watch TypeScript course and read articles.

**Thoughts:** A day of learning.

**Link to Work:**

### Day 32: October 21, 2018

**Today's Progress**: Tried to get ReactCSSTransitionGroup to work with notes.

**Thoughts:** Didn't work. Also, started the new version of my portfolio with React. Trying to migrate away from Wordpress.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 33: October 22, 2018

**Today's Progress**: Started on portfolio.

**Thoughts:** Started the portfolio migration today

**Link to Work:** https://github.com/HanifCarroll/portfolio-v4

### Day 34: October 23, 2018

**Today's Progress**: Worked on portfolio.

**Thoughts:** Added reactstrap to the project. Things are starting to look pretty good, I've got it nearly looking like the old site.

**Link to Work:** https://github.com/HanifCarroll/portfolio-v4

### Day 35: October 24, 2018

**Today's Progress**: Finished transferring portfolio.

**Thoughts:** Finished recreating my WordPress portfolio in React. Got it up on Netlify and the custom domain all set-up.

**Link to Work:** https://github.com/HanifCarroll/portfolio-v4

### Day 36: October 25, 2018

**Today's Progress**: Fixed bug in notes app. Started reading Clean Code. Starting using/learning Tmux and Vim(again).

**Thoughts:** Lots of new beginnings.

**Link to Work:** https://github.com/HanifCarroll/notes

### Day 37: October 26, 2018

**Today's Progress**: Switched from bash to zsh and started a new project, a blog site. 

**Thoughts:** The blog will use Java/Spring Boot on the backend and React/Next.js for the frontend.

**Link to Work:** https://github.com/HanifCarroll/blog-java

### Day 38: October 27, 2018

**Today's Progress**: Two more chapters of Clean Code, and worked on Java blog.

**Thoughts:** Finished the REST endpoints for posts.

**Link to Work:** https://github.com/HanifCarroll/blog-java

### Day 39: October 28, 2018

**Today's Progress**: Two more chapters of Clean Code, worked on workout log script, and 1 section of spring course.

**Thoughts:** Cleaning the log is proving to be harder than I expected, but it's getting there.  Also, this Spring course is pretty good.  I can tell that I'll be learning a lot.

**Link to Work:**

### Day 40: October 29, 2018

**Today's Progress**: 2 more chapters of Clean Code, 1 section of Spring course, and made a basic CRUD app with Spring Boot and Thymeleaf. 

**Thoughts:** Nearly done with the book, so that's cool.  Getting more familiar with Thymeleaf thanks to the course and my little side project for tonight.  It's not the worst thing in the world, but I'd much rather just create an API and use React.

**Link to Work:** https://github.com/HanifCarroll/spring-boot-thymeleaf-demo

### Day 41: October 30, 2018

**Today's Progress**: 3 more chapters of Clean Code, 1 section of Spring course, and added functionality to java blog app.

**Thoughts:** The blog app is starting to come together.  Created users and associated them with posts, and finally figured out how I can break out of the Jackson JSON infinite loop when displaying them.

**Link to Work:** https://github.com/HanifCarroll/blog-java

### Day 42: October 31, 2018

**Today's Progress**: Finished Clean Code, 1 section of Spring course, and added more features to blog.

**Thoughts:** Nearly done with the backend.  Running into a snag with another Jackson infinite loop, but hopefully I'll get to the bottom of it soon.

**Link to Work:** https://github.com/HanifCarroll/blog-java

### Day 43: November 1, 2018

**Today's Progress**: Finished Comments entity, and extracted createdAt, updatedAt, and id fields to a BaseEntity.

**Thoughts:** Starting to get the hang of the JPA/hibernate annotations.  Spring Boot is actually pretty neat.  Can't wait to start using Project Lombok; that'll clean things up a lot.

**Link to Work:** https://github.com/HanifCarroll/blog-java

### Day 44: November 2, 2018

**Today's Progress**: Finish section of Spring course and start NextJS project.

**Thoughts:** Ran into some problems trying to create a Next.js project from scratch, but luckily there's a create-next-app that worked perfectly.

**Link to Work:** https://github.com/HanifCarroll/blog-client 

### Day 45: November 3, 2018

**Today's Progress**: Learned about JUnit, tweaked Blog server, and added functionality to Blog client.

**Thoughts:** Starting to get the hang of NextJS.

**Link to Work:** https://github.com/HanifCarroll/blog-client 

### Day 46: November 4, 2018

**Today's Progress**: Went through a big runaround with securing the spring api, to no avail.  Started practicing algorithm and SQL questions on Hackerrank.

**Thoughts:** I really don't like algorithms.  SQL is pretty nifty, though.

**Link to Work:** https://github.com/HanifCarroll/blog-java

### Day 47: November 5, 2018

**Today's Progress**: Did a little bit on Hackerrank, started Cracking the Coding Interview, and played with Three.js a little bit.

**Thoughts:** Nothing to add.

**Link to Work:** 

### Day 48: November 6, 2018

**Today's Progress**: Some Hackerrank, did my first coding interview, watched a video of the Spring course.

**Thoughts:** Interview went really well!  Now I just have to think of my next project.

**Link to Work:** 

### Day 49: November 7, 2018

**Today's Progress**: Started working with HTML5 canvas and had a phone interview.

**Thoughts:** Interview went great, and I've really been having a good time with Canvas. 

**Link to Work:** https://github.com/HanifCarroll/canvas-tutorial 

### Day 50: November 8, 2018

**Today's Progress**: More work with canvas.

**Thoughts:** Added a bit to my first canvas project, and started my second one with gravity.

**Link to Work:** https://github.com/HanifCarroll/canvas-tutorial 

### Day 51: November 9, 2018

**Today's Progress**: More work with canvas.

**Thoughts:** Finished another canvas tutorial/project, and started a couple more.

**Link to Work:** https://github.com/HanifCarroll/canvas-gravity 

### Day 52: November 10, 2018

**Today's Progress**: Collision detection with canvas and readings on algorithms.

**Thoughts:** Learned about complete search, greedy algorithms, and dynamic programming.

**Link to Work:** https://github.com/HanifCarroll/canvas-collision 

### Day 53: November 11, 2018

**Today's Progress**: Circular motion with canvas and started reworking my portfolio.

**Thoughts:** Finished the canvas tutorials for now.  Gonna start working on my portolio and try to practice some canvas stuff on my own on the side.

**Link to Work:** https://github.com/HanifCarroll/canvas-circular-motion 

### Day 54: November 12, 2018

**Today's Progress**: Modifed my portfolio.

**Thoughts:** Portfolio is starting to look decent.

**Link to Work:** https://github.com/HanifCarroll/portfolio-v4

### Day 55: November 13, 2018

**Today's Progress**: Modifed my portfolio.

**Thoughts:** Changed a few things and got a ton of feedback for things to implement tomorrow.

**Link to Work:** https://github.com/HanifCarroll/portfolio-v4

### Day 56: November 14, 2018

**Today's Progress**: Finished Portfolio modifications.

**Thoughts:** Implemented the changes that were recommended to me.  Portfolio is looking so much better, and I'm really happy with it!

**Link to Work:** https://github.com/HanifCarroll/portfolio-v4

### Day 57: November 15, 2018

**Today's Progress**: Learned about and practiced sorting algorithms.

**Thoughts:** bubble sort, selection sort, and insertion sort.

**Link to Work:** 

### Day 58: November 16, 2018

**Today's Progress**: Learned about shell sort.

**Thoughts:** Just like insertion sort, sort of confusing, so I"ll hae to work on it."

**Link to Work:** 

### Day 59: November 18, 2018

**Today's Progress**: Took quizzes on Upwork for HTML, CSS, JavaScript, and WordPress. Finished sorting algorithms in Java.

**Thoughts:** The quizzes allowed me to test and exand my knowledge of the subjects, so that was nice. 

**Link to Work:** 

### Day 60: November 19, 2018

**Today's Progress**: Small updates on portfolio site, and spent way too much time coming up with my next project.

**Thoughts:** 

**Link to Work:** https://github.com/HanifCarroll/portfolio-v4

### Day 61: November 20, 2018

**Today's Progress**: Started a new project, a react app that tells the sunset/sunrise time in a given area.

**Thoughts:** 

**Link to Work:** https://github.com/hanifcarroll/sun-times 

### Day 62: November 21, 2018

**Today's Progress**: More on sun-times project.

**Thoughts:** Dealing with the geocoding, reverse geocoding, and timezone translations were much harder than expected.

**Link to Work:** https://github.com/HanifCarroll/guiding-hands

### Day 63: November 22, 2018

**Today's Progress**: Started working on a family friend's website that I offered to make.

**Thoughts:** As usual, designing things is hard. 

**Link to Work:** https://github.com/HanifCarroll/guiding-hands

### Day 64: November 23, 2018

**Today's Progress**: More work on the site.

**Thoughts:** It looks OK, but it's still missing something to make it look special.

**Link to Work:** https://github.com/HanifCarroll/guiding-hands

### Day 65: November 24, 2018

**Today's Progress**: More work on the site.

**Thoughts:** Launched it, then continued to work on it.

**Link to Work:** https://github.com/HanifCarroll/guiding-hands

### Day 66: November 25, 2018

**Today's Progress**: More work on the site, and continued work on sun-times.

**Thoughts:** Added a nice darkened image overlayon the site and made a lot of improvement on sun-times.

**Link to Work:** https://github.com/HanifCarroll/guiding-hands

### Day 67: November 26, 2018

**Today's Progress**: Minor fixes on guiding-hands site and learned some SQL basics.

**Thoughts:** 

**Link to Work:** https://github.com/HanifCarroll/guiding-hands

### Day 68: November 27, 2018

**Today's Progress**: Started new interview assignment.

**Thoughts:** Making a stopwatch that can have multiple instances with HTML, CSS, and JavaScript.

**Link to Work:** https://github.com/HanifCarroll/stopwatch

### Day 69: November 28, 2018

**Today's Progress**: Created/organized a bunch of flash cards for a few different categories and had a pair programming Java interview.

**Thoughts:** Interview went well, much easier than expected.

**Link to Work:** 

### Day 70: November 29, 2018

**Today's Progress**: Continued the interview assignment.

**Thoughts:** Finished the functionality and did a lot of work on the styling.

**Link to Work:** https://github.com/HanifCarroll/stopwatch

### Day 71: November 30, 2018

**Today's Progress**: Continued the interview assignment.

**Thoughts:** Got a LOT done with styling.  I'm satisfied with how it looks, and I'm going to go on to the write-up for the assignment.

**Link to Work:** https://github.com/HanifCarroll/stopwatch

### Day 72: December 1, 2018

**Today's Progress**: Finished the interview assignment.

**Thoughts:** 

**Link to Work:** https://github.com/HanifCarroll/stopwatch

### Day 73: December 2, 2018

**Today's Progress**: Updated portfolio to include stopwatch.

**Thoughts:** 

**Link to Work:** https://github.com/HanifCarroll/portfolio-v4

### Day 74: December 3, 2018

**Today's Progress**: Modified sun-times and added it to my portfolio.

**Thoughts:** 

**Link to Work:** https://github.com/HanifCarroll/sun-times

### Day 75: December 6, 2018

**Today's Progress**: Messed around trying to make some python scripts/a flask app.  

**Thoughts:** Really at a loss as to what I should do for my next project.

**Link to Work:** 

### Day 76: December 7, 2018

**Today's Progress**: Messed around with Okta, Firebase Auth, and Auth0 for my spring boot app. Didn't work.

**Thoughts:** 

**Link to Work:** 

### Day 77: December 8, 2018

**Today's Progress**: Started a new Java application.  

**Thoughts:** Instead of using React, I'm using Thymeleaf, just to get some practice with fullstack Java.  Going decently well so far.

**Link to Work:** https://github.com/HanifCarroll/java-topics

### Day 78: December 9, 2018

**Today's Progress**: Added a lot to my full-stack Java app.

**Thoughts:** Getting more comfortable with templating languages in general.

**Link to Work:** https://github.com/HanifCarroll/java-topics

### Day 79: December 10, 2018

**Today's Progress**: More work on Java app.

**Thoughts:** Spent a lot of time fixing a bug with the comments.  

**Link to Work:** https://github.com/HanifCarroll/java-topics

### Day 80: December 11, 2018

**Today's Progress**: More work on Java app.

**Thoughts:** Worked on the portfolio a little bit.

**Link to Work:** https://github.com/HanifCarroll/hc-portfolio

### Day 81: December 14, 2018

**Today's Progress**: Technical interview.

**Thoughts:** Had a technical interview for a position.  I was asked how I would debug a number of things on a couple of JSFiddles.

**Link to Work:** 

### Day 82: December 15, 2018

**Today's Progress**: Orientation with and starting on new contract project.

**Thoughts:** My first real-world codebase.  It still seems relatively new, so there's probably not as much code as usual, but it's still more than I've ever dealt with.

**Link to Work:** 

### Day 83: December 16, 2018

**Today's Progress**: Worked on 3 small tickets for the contract project.

**Thoughts:** Went pretty smoothly.  The first one took some time, because I had to understand all the moving parts, but it was fun.

**Link to Work:** 

### Day 84: December 17, 2018

**Today's Progress**: Worked on a small ticket and then on the geospatial search.

**Thoughts:** Geospatial work is pretty tough, but I think we're getting there.

**Link to Work:** 

### Day 85: December 18, 2018

**Today's Progress**: More work on polygon search feature, but we're making progress.

**Thoughts:** Also added a couple more things to a few other fixes I had made.

**Link to Work:** 

### Day 86: December 19, 2018

**Today's Progress**: More work on polygon search.

**Thoughts:** Things aren't looking good.

**Link to Work:** 

### Day 87: December 20, 2018

**Today's Progress**: More work on polygon search.

**Thoughts:** After today, we're going to have to come up with a new way to solve this problem.

**Link to Work:** 

### Day 88: December 21, 2018

**Today's Progress**: Tried approaching the problem another way, and found out that it's not supported, so back to the drawing board.

**Thoughts:** 

**Link to Work:** 

### Day 89: December 23, 2018

**Today's Progress**: Finally solved the problem with the project.  

**Thoughts:** I can't believe I did it.

**Link to Work:** 

### Day 90: December 26, 2018

**Today's Progress**: Looked through the codebase to learn about how authentication and account management works. 

**Thoughts:** Might be doing a big change in the future, so this research was to prepare for that.

**Link to Work:** 

### Day 91: December 27, 2018

**Today's Progress**: I was asked to make some changes/fixes to a WordPress site.

**Thoughts:** It was easy enough, but some things I couldn't get done.  I think the site might be corrupted.

**Link to Work:** 

### Day 92: December 28, 2018

**Today's Progress**: Made a script with Python that took all of my Tumblr journal posts in XML form and made them into their own markdown files. 

**Thoughts:** Took 2-3 hours, wasn't too painful.

**Link to Work:** 

### Day 93: December 29, 2018

**Today's Progress**: Made another Python script to organize all the blog posts into the correct folders in my journal folder.

**Thoughts:** 

**Link to Work:** 

### Day 94: December 30, 2018

**Today's Progress**: More work on that WordPress site from a few days ago. 

**Thoughts:** Fixed the problem with the editor.  It was because of the Gutenburg update.

**Link to Work:** 

### Day 95: January 3, 2019

**Today's Progress**: Made a bunch of new flash cards for Java and made a small change on a site for a family friend.

**Thoughts:** Running out of things to do before the new job starts.

**Link to Work:** 

