# ![Logo](https://launch.sa/assets/images/logos/tuwaiq-academy-logo.svg) 

# Android-Capstone #2:  Make an Android Application!

### Overview

- Congratulations on completing the second phase of the course! To reinforce your learning from the Kotlin Essentials and Android Essentials courses, it’s time for you to build an application of your own design.

- You’ve come a long way, and it's time to show it. This will be your most advanced project to date, and if you put creativity into it, it'll hopefully be the thing you want to show off most prominently in your portfolio. So, pull from everything you've learned so far, and **tackle something that'll push you a little outside of your comfort zone.**

- Make sure your android app is impressive visually as well. Sometimes people do judge a book by its cover – or **an app by its design**.


**You will be working in groups for this project**, but we are here to support you and you are here to support each other and your group mates. Show us what you've got!

---

## What You've Learned

By the time you submit this project, you will have covered new ground in, and reviewed, many of the big themes of the course so far:

- **Command Line**: Practice interacting with the computer and navigating the filesystem from the command line.
- **Source Control**: Manage and interact with a git repository to store changes to code.
- **Programming Fundamentals**: Work with objects, arrays, events, while learning how to strategically solve problems and resolve errors.
- **Kotlin Fundamentals**: Learned how to declare variables, write function, use class and objects to obtain the desired results. 
- **Android Fundamentals**: Learned how to create an android application and how to implements the logic in it with layouts. 
- **Products and Teams**: Document your code and your code repository so others understand what you've built.
- **Implicit Intents**: Implicit intents do not name a specific component, but instead declare a general action to perform, which allows a component from another app to handle it
- **Taking Pictures with Intents**: Leanred about how to take pictures from camera and save it on our device.
- **Dealing with Gallery Pictures**: Leanred how to open gallery and select picture(s) and incorporate that in your app.
- **Coroutines**: A coroutine is a concurrency design pattern that you can use on Android to simplify code that executes asynchronously.
- **Loopers, Handlers, and HandlerThread**: Leanred how to run the process in the background with loopers and handlers.
- **APIs**: Communicating to an API using Retrofit to fetch and post data.
- **JSON APIs**: JSON (or JavaScript Object Notation) is a lightweight, easy and popular way to exchange data. A backend REST service to deliver some data in JSON format to the front-end application.
- **SearchView and SharedPreferences**: Learned how to do searching and sharing of the information.
- **Group GIT**: Learned how the git team works and how you can keep your project upto date with push and pull requests.
- **Unit Testing**: Learned how to perform Unit tests which are the fundamental tests in your app testing strategy.



---

## Big Goals

- **Build an android application from scratch**, without a starter codebase
- Use your programming skills to **work out the logic for an application**
- **Separate activities and/or fragments** in your application
- Build an application **to a specification that someone else gives you**
- **Build a dynamic application that are production ready
- **Create a `README.md` file that explains your app** to the world

---

## Technical Requirements


- In this project your goal is to demonstrate everything that you have learned so far, and to learn something new.
- Your assignment is to write a new app from scratch that will download and present images to the user that were taken near their current location.

- Get the user’s location in the form of a latitude and longitude.
  - This will require you to learn about an API that was not covered in class. Throughout the class, you have been learning to fish. It is time to fish.

- Download a selection of images from the Flickr web service that were taken near the user’s location.
  - The number of images to download and their distance from the user is up to you.
  - If you prefer, you may add interface elements to let the user make these decisions.
  - To do this, you will need to explore the Flickr API documentation (https://www.flickr.com/services/api/) to discover which query parameters you must
provide to Flickr in order to filter the returned photos by location.

- Present the images to the user in a way that ties them to the user’s location.
  - How you do this is up to you. Options include, but are not limited to:
    - Thumbnail images on a map
    - A list or grid of images with location/distance information on them
    - Anything else you can imagine!

- Persist these images in a local disk cache.
- Perform as much non-UI work asynchronously as you can.

- Include unit tests that verify the correctness of your model and transformation code.
- Exemplify git best practices (frequent, descriptive commit messages, and use a pull request workflow).


- Stick with **KISS (Keep It Simple Stupid)** and **DRY (Don't Repeat Yourself)** principles
- Have well-formatted, and well-commented code

- **In addition to the above, your submission may exhibit any other features that you would like to
include. Add visual flair, add fun features, and show off your skills and creativity!**


---

## Potential Extra 

You are encouraged to use your imagination to make this application as nice and complete as you
wish. Below are some ideas to guide you, but you are not restricted to them:

- Let the user upload new photos to Flickr
- Change the way the photos look if they are nearer to, or farther from, the user.
- Let the user select other locations on a map to see photos near that location.
- Let the user “star” or “favorite” certain photos, and see them in a separate list.
- Anything else that you can think of!



## README 

- List technologies used
- Link to wireframes and user stories.
- Document your planning and tell a story about your development process and problem-solving strategy.
- List unsolved problems which would be fixed in future iterations.
- Describe how some of your favorite functions work

## Necessary Deliverables
* Projects are due Thursday, 16 Dec 2021 at 8:30am!

- A **working application, built by you**
- Link to your published app/ Name of the published app on Google Play Store **(We will walk you through this process)**
- A **git repository hosted on Github**, and frequent commits dating back to the _very beginning of the project_

- **A `README.md` file** with explanations of the technologies used, the approach taken, installation instructions, unsolved problems, any other useful information etc.

- **Projects will be submitted by [Google Sheet](https://docs.google.com/spreadsheets/d/1u5SSvcKwTl_Vsb3FV8ZqV2s2vAurv46s/edit#gid=1606216321)**

- A **15-20 minutes presentation** in which you answer the following questions:
  - What is the application about and its features?
  - Is there any information you think might help us understand what you built?
  - What features did you include?
    - Make sure to explain anything "new" (things that we didn't cover in class)
  - What was the most difficult part of the project?
  - What was your favourite part to work on?
  - What would you like to add next?
  - Demo of the application

---

## Team Requirements

- Every team member must have commits contributing to the project.  
- Pair programming is allowed and should be noted in the commit by using `@github_username` of each student pairing
- No single student should do a majority of the commits.

---

## Suggested Ways to Get Started

- **Break the project down into different components** (data, presentation, views, styling, activites, fragments) and brainstorm each component individually. Use whiteboards!
- **Use your Developer Tools** (`console logs`, inspector/ debugger, etc) to debug and solve problems
- Work together with your group mates and work everyday, **ask questions and come to office hours** when you need to. Think about adding relevant code to your application each day, instead of, you know... _procrastinating_.
- **Commit early, commit often.** Don’t be afraid to break something because you can always go back in time to a previous version.
- **Check out Tutorial and Documentation resources** at home to better understand what you’ll be getting into.
- **Don’t be afraid to write code that you know you will have to remove later.** Create temporary elements (View Groups and Views, etc) that trigger events if real data is not available. For example, if you’re trying to figure out how to change some text when the application is over but you haven’t developed the whole application logic, you can create a button to simulate that until then.

1.  Create a repository on github for your project
2.  Clone it to the projects folder on your computer
3.  Add ViewGroups and Views for your application
4.  Connect your layout with activity to check that they all work correctly
5.  Build the most basic version of your application (very little styling, just a first version)
6.  Write the pseudocode for application logic as comments in your Kotlin file
7.  Begin working on the [user stories], 1 at a time
---


# Tips

You **should**:

-   **Don’t get too caught up in too many awesome features** – simple is always
    better. Build something impressive that does one thing well.
-   **Design first.** Planning with user stories and wireframes before writing
    code means you won't get distracted changing your mind – you'll know what to
    build, and you can spend your time wisely by just building it.
-   **Don’t hesitate to write throwaway code** to solve short term problems.
-   **Read the docs for whatever technologies / frameworks / API’s you use**.
-   **Write pseudocode before you write actual code.** Thinking through the
    logic of something helps.
-   **Write your code DRY** and **KISS**.
-   **Commit early, commit often.** Don’t be afraid to break something because
    you can always go back in time to a previous version.
-   **Keep user stories small and well-defined**, and remember – user stories
    focus on what a user needs, not what development tasks need accomplishing.
-   **Write code another developer wouldn't have to ask you about**. Do your
    naming conventions make sense? Would another developer be able to look at
    your app and understand what everything is?
-   **Make it all well-formatted.** Are you indenting, consistently? Can we find
    the start and end of every div, curly brace, etc?
-   **Comment your code.** Will someone understand what is going on in each
    block or function? Even if it's obvious, explaining the what and why means
    someone else can pick it up and get it.

**Good luck and happy hacking!**

## Useful Resources
- **[Android Documentation](https://developer.android.com/docs)**
- **[GitHub Markdown Tutorial](https://guides.github.com/features/mastering-markdown/)** _(for working with Markdown)_
- **[Model–view–viewmodel](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel)**
- **[Kotlin coroutines on Android ]**(https://developer.android.com/kotlin/coroutines?gclid=Cj0KCQiAhMOMBhDhARIsAPVml-EX2YIvJpZqKGPyLHmACAf5FLpnWILlglBxjs13g5ubYpxEcG_-7qcaAkYhEALw_wcB&gclsrc=aw.ds)
- **[Intents and Intent Filters]**(https://developer.android.com/guide/components/intents-filters)
- **[Understanding Android Core: Looper, Handler, and HandlerThread]**(https://blog.mindorks.com/android-core-looper-handler-and-handlerthread-bd54d69fe91a)
- **[Retrofit]**(https://square.github.io/retrofit/)
- **[Git Team Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows)**
- **[Git Team Cheatsheet](https://jameschambers.co/writing/git-team-workflow-cheatsheet/)**
- **[Git Team Cheatsheet - Instructions](https://github.com/Tuwaiq-KotlinAndroid-DMM/GIT-Cheat-Sheet/tree/main)**


