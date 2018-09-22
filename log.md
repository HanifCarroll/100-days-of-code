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
