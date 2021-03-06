# 100 Days Of Code - Log

### Day 25 April 11, 2018

**Today's Progress**: Wrote the unit tests for the Todo component. Other than one or two small things I feel like I'm getting the hang out how to write some basic tests. I'm sure there's still a lot to learn, but at least I'm making progress!

**Thoughts:**: I think that I've written some hard to test code, but my lack of knowledge of Angular and the best practices are making figuring out what's right and wrong difficult. I think next steps might include burning through some of the more related Angular docs to try and figure out if I can be improving my code at all. Going to need to be sharp on my best practices if I want to write good code for this new job. 

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 24 April 10, 2018

**Today's Progress**: Spent more time learning how to write Jasmine unit tests. A little frustration just from not reading in to issues well enough, soon enough, but I ended up getting all the basics figured out. All base tests complete, starting to write actual test cases and some future test cases for TDD. 

**Thoughts:**: This is the first time I've willingly participated in writing tests for my own code, so it's interesting to actually dig into that. I would really like to try TDD for the user workflow of the app moving forward. 

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 22-23 April 8-9, 2018

**Today's Progress**: Finally figured out the issue with the `@Output()`'s for the Angular app. After much frustration it turned out that I had just put the `*ngFor` in a `<ul>` instead of a `<div>` which angular didn't like. Also started working on unit tests! Exciting

**Thoughts:**: JS unit testing continues to prove itself a major pain. I understand why it's so complicated, but I often feel that BDD, which is extremely popular right now, adds an extra layer of complexity over what is truly needed. Might just be the frameworks though. Overall I'm very happy with how far I've come with this app and can't wait to continue working on it now that I've resolved that stupid angular issue...

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 20-21 April 6-7, 2018

**Today's Progress**: Spent yesterday working extra late, so all of my coding was work related, which isn't super great. But today I've been banging my head against Angular and trying to figure out why my `@Output()`'s aren't working properly. Really frustrating, but I have reached out to other Angular devs to see if they can help me out

Pt 2: Worked around the issue I was having with the `@Output()`'s not registering, and was able to get all of my current endpoints working. The user can now update/add/delete/complete a Todo and have the change persist to the DB! 

**Thoughts:**: Currently very frustrated with Angular and how un-intuitive it can be sometimes. Obviously the issue that I'm having is purely lack of knowledge, but it's still incredibly difficult to sit down to code for an hour and hardly accomplish anything at all. Definitely my least favorite type of "productivity" time

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 19 April 5, 2018

**Today's Progress**: Not much. Got the Add endpoint working, so the user can add live todos, but have been struggling to get the update endpoint working. It looks like the service method is only being called half of the time, which I'm sure has to do with how I've set up the UI controller for what I'm doing. I would like to do a small refactor when adding new todos so that the user adds a todo locally and it opens for them in an "edit" view, but only saves once they have finished editing it and pressed the save button. 

**Thoughts:**: Rolling back on to not liking Angular 4 that much. Every time I jump back into the UI I just end up wishing I had done the entire thing with React. Finding myself increasingly exhausted with this project. I really want to finish it up over the next few days so I can move on to something else, but if I want to add User/Credential workflows it's going to take me at least another week or 2 with the slow crawl of a pace I've been at for the last few days. 

**Link to work:**: https://github.com/Rodhlann/HyperTodo/tree/development

### Day 17-18 April 3-4, 2018

**Today's Progress**: Spent the 3rd reading some more about recent updates to Javascript. Actually learned some pretty useful stuff, that I was able to use at work. Today I spent my time testing out the endpoints I had created with Postman and making sure the DB updated properly for each request. 

**Thoughts:**: I really need to add a layer of data validation to the back end so the user doesn't send in junk data. In a happy-path scenario everything is working as expected now and I will be ready to wire up the UI to the endpoints finally tomorrow. After I have all of the MVP todo logic working I plan to start working on user creation and authentication, which really is a different project entirely. Should be fun to dig into that. I've also started thinking about projects to do once I'm content with my progress on this current one. I'd like to look into webpack and babel, and also start a functional programming project. Other than that I would like to continue working on bots that I have started in the past, and I would also like to start contributing to some open source projects. Lots of stuff to do! I'm absolutely sure I can fill up 100 days!

**Link to work:**: https://github.com/Rodhlann/HyperTodo/tree/development

### Day 16 April 2, 2018

**Today's Progress**: Create remaining database calls on server side. Will test them out tomorrow. 

**Thoughts:**: Getting to a low point with my motivation to finish this project. I think tomorrow I'll be able to see the fruit of my labor and that should reinvigorate me a bit! 

**Link to work:**: https://github.com/Rodhlann/HyperTodo/tree/development

### Day 14-15 March 31-April 1, 2018

**Today's Progress**: Spent the last two days troubleshooting the Sql Server connection to my application. After quite a bit of poking and research I finally got data all the way from the DB to the front end! Very exciting. Next I will be creating methods to add/update/delete todos. After that I will be adding the User functionality, which will pretty much close up all the MVP work I need to do for the project!

**Thoughts:**: I think the most frustrating thing so far about using C#/.NET is the sheer amount of information there is for the platform. There is just way to much. And it seems that things change/update so frequently that there's a million outdated/deprecated ways to do something wrong, but only a few ways to do it right in the current version of .NET. This creates an extremely frustrating development experience. When it works, it works, though, and at the end of the day that's really all I can hope for. Really happy with how far I've come on this project, and I'm sure that the things I have learned so far will help me a lot at my new job!

**Link to work:**: https://github.com/Rodhlann/HyperTodo/tree/development

### Day 13 March 30, 2018

**Today's Progress**: Finally got the backend and frontend talking! After some CORS issues figured out everything is working as expected. Very excited! 

**Thoughts:**: Just happy to get everything talking now :) Can't wait to move forward with the rest of the functionality

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 12 March 29, 2018

**Today's Progress**: Talked more about CSS and learned a few things about UX. Trying to make the app usable, but trying to also strike a balance for what I think looks good, since I'm really gonna be the only user. Also picked up my functional programming book for a bit. 

**Thoughts:**: Eventually I need to work on the backend. Sort of getting burnt out on the front end work. I really want to finish this project up soon so I can start digging back into my functional programming learning. I think that's the direction I really want to go in my learning for a bit. 

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 11 March 28, 2018

**Today's Progress**: Completely built out the category workflow in the UI. The user can now add/select categories and see the filtered values on the main page. Also added my first CSS animation! 

**Thoughts:**: I'm getting more in the flow of the Angular process now, which is nice. The interesting thing about that, though, is that I feel that my experience with React has actually made me a better Angular developer. I did quite a bit with Angularjs for a previous project at work, and I can just cringe at all the terrible code I wrote, but now I feel that my workflow and understanding of how front end applications should behave is much better. I give that credit to react/redux. I'm also feeling much more comfortable with CSS now. I'm still sort of frustrated by it, but I think that I have the fundamentals of how it SHOULD work down, which will hopefully help me as I move forward.

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 10 March 27, 2018

**Today's Progress**: Spent the entire time just looking up CSS animation information

**Thoughts:**: I'd really like to add more CSS animations to the application. I feel like they make an application feel more modern, but I want to be able to add them without disturbing the user workflow! I guess I'll just have to tinker. 

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 9 March 26, 2018

**Today's Progress**: Sat down with a friend today to talk about CSS and how to fix the crap I'd been writing. I think I learned a lot and was able to use my new knowledge to create a UI I'm much more comfortable with. Today was 100% UI/CSS refactoring. 

**Thoughts:**: CSS is annoying, but knowing that I can do a CSS reset is super useful. Having to work around someone else's styles just makes everything way more frustrating. I'm really excited about the new direction the UI is taking and I can't wait to implement the rest of it in the same style. 

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 8 March 25, 2018

**Today's Progress**: Mostly just ended up drawing up my mockups for how I would like the final UI to work. Sort of got stuck in a loop of not knowing how to implement some functionality that boiled down to me not really having a vision for the UI, but I think that's been resolved. Did a little work to start gearing the backend for communication with the front. 

**Thoughts:**: Really came to a strong conclusion today that I have no idea how to build UI apps that are enjoyable to use and look at. That sort of sparked a need to go and draw out the application as I want it to be. I think that this will at least put me on track to make something I'm happy with. A friend of mine suggested a few libraries for helping with building UIs, which I might look in to. I feel like those are sort of cheating, when it comes down to it, because they take care of the layer of CSS skills that I've been avoiding. One of them, *Material.js*, seems pretty cool though, because it has a gallery functionality that allows you to track your iterations on the UI and easily get feedback from people about that. The feedback concept is something that I really like. I think I definitely have the ability to be a great designer for web apps, I just don't have the knowledge or context to get there at the moment. 

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 7: March 24, 2018

**Today's Progress**: Split the growing UI application up into several components and gave the user the ability to add new todos.

**Thoughts:**: I still really hate CSS, but I'm hoping I can get some input from friends on how to design the app better. It's in a good working state, but I'd like it to be attractive to the eye and easy to use. Angular is kind of growing on me. I still feel like it's a little heavy, in that I could have done all of this in half the time with React, but it's not terrible. I'm sure I will come to find it's nice nuances as I continue to dig into the functionality. 

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 6: March 23, 2018

**Today's Progress**: Continued work on the UI app. Added a User model and service and began shaping the application styles up a little differently. 

**Thoughts:**: Decided I sort of want this to be a mobile app. Or at least mobile ready. Ended up messing with CSS FOREVER which was pretty frustrating. Really hoping there's a way to get a grasp on that language to a point where I feel like I know what I'm doing. Otherwise I'm happy with where the UI app is for now. I think it's time to start working on the back end again. At the very least I think I should do that just to avoid burning out on the Angular, or more specifically CSS. 

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 5: March 22, 2018

**Today's Progress**: Went ahead and put together the base REST calls for the server. Still need to set up the server side endpoints, but I'm having a lot more fun doing the UI right now, so I'm going to continue with that until I feel I can't get any further without live data. Haven't tested the endpoints yet, but I'm fairly certain they won't work in their current state. 

**Thoughts:**: Not really sure how I feel about the rxJs/Http service setup that Angular uses. I really just wish it was as simple as axios or fetch from React. I have heard great things about rxJs in the past, but I'm not really seeing the benefit of it so far. On a more high level note, I really need to be better about restricting the time I'm taking to code per day. I'm really feeling myself potentially beginning to burn out, and want to make sure I can continue coding for the entirety of my 100 day stretch. Definitely need to stop staying up so late to code!!!

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 4: March 21, 2018

**Today's Progress**: Really began digging into the Angular functionality that I will need for this project. Got a good active/complete workflow and the todo editing experience is pretty solid.

**Thoughts:**: I'm still not sure I'm sold on Angular yet. It's way better than AngularJs so far, but I just really wish it was as straighforward as React. I'll have to see how I feel once I've integrated live data. As for the app itself, the general workflow is nice and I'm happy with it, but I really want to make something visually appealing, and I just don't know how to go about doing that right now. Really going to have to start researching other TODO apps to see what styles/workflows are interesting and attractive.

**Link to work:**: https://github.com/Rodhlann/HyperTodo-UI/tree/development

### Day 2: March 19, 2018

**Today's Progress**: Began setting up the database for my project. Created matching models and did quite a bit of research in to connecting the two. 

**Thoughts:**: I've never done very much database work, especially in C#. And the majority of that has been set up by other people. Digging in to this has been a pretty big hurdle, especially since there seems to be so many different ways to set up a DB with C#. I think using the standard MS SQL Server/SSMS combo is pretty much the way to go because of this. I'm hoping that creating the entity layer is simple enough so I can quickly start building out my controllers. I probably won't create a service layer for such a small project, though I know that from a best practices perspective that's probably the way to go. Tomorrow I would really like to get at least one postman call through to add a new user. That's gonna be the goal.  

**Link to work:**: https://github.com/Rodhlann/HyperTodo/tree/development

### Day 1: March 18, 2018

**Today's Progress**: Created a new C# project and began following a tutorial to figure out how to put together an API in .NET Core. 

**Thoughts:**: .NET has a lot of magic going on that isn't super well documented. Might just be me overthinking it, but it's just weird. Now that I've got the API figured out I will probably set up the standard workflow for adding new users/todos with postman before going through the steps of building out the actual UI app. 

**Link to work:**: TODO... 
