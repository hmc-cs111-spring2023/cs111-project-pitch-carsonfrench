# Project proposal

## The user and a language

This section describes who the project would serve and why a language might be a
good way to meet their needs.

My idea is a language that can be used to track calories over time and quickly generate custom graphs using the data. This project would serve people who are hoping to lose, gain, or maintain weight or people who are just interested in their calorie intake. A language would be helpful for tracking calories because it could quickly genrate custom graphs for a variety of calorie statistics. 

### What's the need?

_What need is met by your idea? Who are you helping? What is that person's
experience like now? What would their experience be like if you could help
them?_

There are already counless calorie tracking apps available that people can use to track various health statistics such as calorie intake from meals, calories burnt from workouts, and weight. These apps are helpful, but they are not ideal mainly because the graphs are usually locked behind a paywall and/or not very customizable. Furthermore, these apps can track the personal data of their users which can possibly be hacked or sold. My language will hopefully make the calorie and weight graphs simpler to generate and more customizable so users can view the trends that are important to them rather than just some generic graphs they might not care about. The language would also hopefully make users feel more comfortable since their personal data is less vulnerable. 

### Why a language?

_Why is a DSL appropriate for your user(s)? How does it address the need?_

There are many types of data that can be helpful for tracking weight such as time, date, body weight, calories burnt, calorie intake, and foods eaten. There are many different graphs that can be made from this data, so it would be helpful to have a language to quickly generate a graph you are looking for in an understabdable way. There are many languages available that can already be used to generate these graphs, such as Python and R, but it would be convenient to has a language specifically for fitness tracking to speed up the process. A plan for weight loss or weight gain takes commitment over time and constant tracking. Even the smallest amount of time saved generating a graph would be significatly more efficient since the language would be used so often. 

### Why you?

_What excites you about this idea? How did you come up with it?_

I am someone who has used these types of apps for both weight gain and weight loss. Through my experience with the apps I definitely saw a need for something more personal since the graphs that I generated were helpful, but not exactly what I was looking for. The app already had all the data to generate the graphs I was looking for but there was no way to do it in the app. I am excited about this idea because it is something I could actually see myself using and I hope others will find it helpful too. 

### Domain

_Describe the project's domain in five words._

Tracking and displaying calorie data

### Interface (syntax)

_How might the user interact with the language? What does programming look
like? Why is this the right way to interact with the problem domain?_

The user would first enter their data using simple phrases like "log broccoli 100 calories" or "log weight 150". Ideally the user can create custom meals as variables and just enter the name for that if it is a meal they have often and don't want to log every specific item each time. Another feature would be creating custom graphs. If there are certain parameters for a graph that the user is specifically interested in, they can save that as a variable as well, so they don't have to type out thise specific settings every time. Generating a graph that looks at weight over the last 5 days would look something like this: "Graph(last 5 days, weight)". The user could then save this as a variable, so they just have to type in the name of the graph next time they want to look at it. Also, the user can create a dashboard which contains a collection of graphs that can be printed together. 

### Operation (semantics)

_What might happen when a program runs? How does a program interact with the
user? What kinds of errors might occur, and how might they be communicated to
the user?_

When entering the data, there shouldn't be any response unless there is an error. An error may occur when someone enters the wrong data type, and the language should respond to them letting them know. Creating a graph should automatically return an image of the graph. There will need to be some srt of file system to save all the data as well. 

### Expressiveness

_What should be easy to do in this language? What should be possible, but
difficult? What should be impossible or very difficult?_

I think it should be pretty simple setting up the classes within the language such as Food, Meal, Graph, and Dashboard. I thing making the sematics look nice will probably be the most difficult part but definitely possible. One thing that may be very challenging is data entry. Many of the fitness tracking apps can just scan barcodes of items and automatically enter the data. It will be very difficult to create something as efficient as that. 

### Related work

_Are there any other DSLs in this domain? If not, describe how you know there
aren't and conjecture why not. If so, describe them and provide links. How well
do they address the need? Are there any particularly admirable qualities of the
language? Are there parts of the language you think could be improved?_

## The Project

This section examines whether the idea makes for a good CS 111 project.

### Suitability

_If someone were to work on this project, what percentage of their time would be
spent directly engaging in the **language** aspects of this project (e.g.,
making language design decisions), as opposed to "systems" aspects of the
project (e.g., implementing a complicated semantics that doesn't require a lot
of language design)?_

### Scope

_How big an idea is this? How ambitious is this project?_

### Benefits and drawbacks

_Why might this be a good idea for a project? Why might this not be a good idea
project?_
