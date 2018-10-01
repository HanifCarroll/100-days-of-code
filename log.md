# 100 Days Of Code - Log

### Day 0 (Technically day 2): September 20, 2018

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
