---
title: "Iteration 3 - Concept Development"
date: 2021-01-02T21:48:17+01:00
draft: false

menu:
    main:
        parent: "Process"
        weight: 3
---

Start: 24/10/2020

## Ideation on both the platform and build system
After having chosen the initial concept we had to focus on what aspects the platform would have: how we could motivate people to use the app and make it engaging for over a longer time period.
We performed an ideation session (figures hieronder) in which we looked at similar games and wrote down what could make our game engaging, such as avatars, leveling up by gaining XP, achievements and titles. These could make the user more interested in the app for over a longer period of time. 

{{< figcontainer class="small" >}}
{{< fig src="images/board1.jpg" caption="Famification" name="whiteboard2" >}}
{{< fig src="images/board2.jpg" caption="Reward and accomplishment" name="whiteboard1" >}}
{{< fig src="images/board3.jpg" caption="Build system functioning" name="whiteboard1" >}}
{{< fig src="images/board4.jpg" caption="Usability goals build system" name="whiteboard1" >}}
{{< fig src="images/avatars.jpg" caption="Ideation on types of avatars" name="avatars" >}}
{{< /figcontainer >}}

Based on this ideation session, the next most important design decisions were made.
One could progress in levels by gaining XP (figure x), which can be received by receiving likes and winning championships, receiving achievements or placing a build. By leveling up, players would collect more assets that can be used in the AR build system to be creatively make changes to your environment.
As we ought collectables to be an interesting feature for people to be encouraged to use the app, we decided to further dive into the possibilities of different types of avatars. The pickaxe was chosen at first, as we believed this best resembled the metaphor of building (figure x).
If too many ideas are submitted in a close spot it can become quite unorganized. A function to cluster all ideas is more appropriate.
A clearer overview of submissions was done by placing all submissions within a championship or clustering in a grid pattern (figure x). One could also use the search bar or the sort button in order to organize the submissions differently (figure x).

{{< figcontainer class="small">}}
{{< fig src="images/mockup1.jpg" caption="The main platform screen" name="main_screen" >}}
{{< fig src="images/mockup2.jpg" caption="The championship page" name="championship" >}}
{{< fig src="images/mockup3.jpg" caption="The page of a championship submission" name="championship_submission" >}}
{{< fig src="images/mockup4.jpg" caption="The grid of clustered ideas" name="cluster" >}}
{{< fig src="images/mockup5.jpg" caption="The page of an individual submission" name="individual_submission" >}}
{{< /figcontainer >}}

However, not everyone will be interested in the more serious, communicative character of this app. Our gameful components as leveling up to collect assets seemed like a fun way of keeping people engaged to use the app for a longer time period were more appropriate for the achiever player type (Stewart, 2011), who are probably less interested in participating in urban design and planning. The goal for our target user is to express his/her creativity and interact with the ideas of others. Therefore, the game is mostly made for the player types explorers and socializers. As their temperaments can best be categorized as the idealist and rational (David Keirsey, 1984), the players will more likely benefit more from full access to all assets to express their creativity. For the same reason, the option of submitting a comment was added.

The current voting system was sensitive for people willing to troll their neighborhood and municipality. We got rid of the dislike button, as ideas could be disliked by groups on purpose. A personal profile needed to be made in which a user can find his/her achievements, as well as options to customize their interface. Solely screenshots of the AR build submission could cause confusion and a button to view the build in a real-world context was added. Furthermore, a description section was added so ideas could be sustained with some background knowledge.

## Expert interview with Gwen Klerks
To gain more knowledge in the field of citizen participation, a discussion was held with Gwen Klerks: https://www.linkedin.com/in/gwenklerks/?originalSubdomain=nl

During the meeting there were some main learning points. We need to focus on what will happen after an idea had been chosen. We could look into possibilities for community building, so citizens themselves can build or realize a chosen idea. This could also apply to places that the citizens want to renovate or the moment an idea needs to be changed.\
Furthermore, we could dive deeper into what will happen if an idea has been chosen. Showing the status of the actual realization would give users more trust in the value of spending time on creating designs with this app.\
Furthermore, rewarding the builder of a realized idea could be done via a nameplate for example.
Game-like wise. We need to focus on rewards for players in-game such as votes or achievements, as well making sure the app stays fun even for over a longer period of time.
Subsequently, we contacted local municipalities to discuss the possibilities of actually realizing submitted builds if they are really popular or won a championship or the nameplate rewards. However, as we got no response, there was little we could do to find out more about these implementations.


## The final midterm concept
The way that people explore other people’s ideas - or rather, builds - will be through the use of a platform. This platform is centered around the idea of a map showing all contributions. 
The second part of the platform is the method of communication between municipalities and urban designers and planners - and most importantly citizens.

As part of sharing ideas and submitting them to challenges, people should be able to voice their opinions. This way, a meaningful discussion can submerge with the aid of visuals and people get a clearer image of what they want. Voting also contributes to this goal. Users are can submit their ideas and express their creativity in three different ways:

*An AR build*\
The AR building tool which is the main part of our app people can design their own neighborhood with the assets collected by playing the game. Once a user is satisfied with the build they made, the idea will be submitted to the app and visualized with a pointer. 

*A comment*\
If users did not feel like a build was appropriate in order to voice their opinion about a certain spot, they could also leave a specific comment.

*A submission to a championship*\
Championships are pre-defined, time-bounded tournaments set up by the municipality. Users can submit ideas for this tournament by clicking the build button within this championship pointer. Once an idea has been submitted, it will can be viewed in a grid of all builds submitted to this specific championship.

{{< figcontainer >}}
{{< fig src="images/mt1.png" caption="The main platform screen" name="main_screen" >}}
{{< fig src="images/mt2.png" caption="The championship page" name="championship" >}}
{{< fig src="images/mt3.png" caption="The page of the championship submissions" name="championship_submission" >}}
{{< fig src="images/mt4.png" caption="The page of an individual submission" name="cluster" >}}
{{< fig src="images/mt5.png" caption="Your profile page" name="individual_submission" >}}
{{< /figcontainer >}}

{{< fig src="images/platformmidtermeverything.png" caption="An overview of the whole platform" name="individual_submission" >}}

## Midterm presentation

For the midterm we used two mediums to communicate our concept: a project description, a video and some images if desired:

*"We aim to empower citizens to change the urban environment for the better, to increase their quality of living and connection to their environment.*\
*We will do this through the use of a platform on which people can create, share, and discuss ideas. These ideas take on the form of contextual - location-based - augmented reality scenes, built up from an endless variety of objects.*\
*Because you might not have the time to create a bench from scratch, the idea of remixing is introduced: you can choose to recycle objects, such as benches or greenery from the library.*\
*You can also create new objects: Every object in our app is made up of primitive shapes, such as a plane, cylinder or sphere These shapes can be positioned in space and painted using the paint tool.*\
*Ideas can be created as part of a challenge, created by a municipality or design firm, but you can also choose to create ideas at any location. To allow people to have meaningful discussions about the designs, the ability for upvoting and commenting is included. You can explore designs from all over the world by looking around on the world map."*

The goal of our video was to be engaging and get make people interested in the potential this project has to offer.\
We would set the scene by showing shots of boring parts of Eindhoven and a person that was clearly not content with the current appearance of many parts in the city.

{{< figcontainer class="large" >}}
{{< fig src="images/video brainstorming.jpg" caption="Initial brainstorming about video content" name="individual_submission" >}}
{{< fig src="images/storyboard v1.jpg" caption="First version of the storyboard" name="individual_submission" >}}
{{< fig src="images/storyboard v2.jpg" caption="Second version of the storyboard" name="individual_submission" >}}
{{< /figcontainer >}}

After this fun and engaging introduction, the problem statement and solution would be described. VFX visualizations were made in order to convey the concept of our AR build system. The images would further show the potential of this app. Later on, we would explain the core functionalities of this app. 

{{< figcontainer class="small" >}}
{{< video src="images/shot1.mp4" caption="A VFX shot of someone placing assets in the world via the AR building system" gif="true" >}}

{{< video src="images/shot2.mp4" caption="Another video of the same assets" gif="true" >}}

{{< video src="images/shot3_v2.mp4" caption="Mockup prototype of the AR build system" gif="true" >}}

{{< video src="images/videodelmar.mp4" caption="Shot of someone using the AR build system" gif="true" >}}
{{< fig src="images/arjotekening.jpeg" caption="Potential of app visualisation 1" name="individual_submission" >}}
{{< fig src="images/arjotekening2.jpeg" caption="Potential of app visualisation 2" name="individual_submission" >}}
{{< fig src="images/arjotekening3.jpeg" caption="Potential of app visualisation 3" name="individual_submission" >}}
{{< fig src="images/arjotekening4.jpeg" caption="Potential of app visualisation 4" name="individual_submission" >}}
{{< /figcontainer >}}


However, we were not able to create a lot of video material for the midterm demo day such as mockup prototypes or more VFX shots. The storyboard could not be realized all the way through. Therefore, the moments someone was speaking without any visual support, our video could felt rather lengthy and hard to follow for the viewer.








## References
{{< link designing_sdgs_paper >}}
1. Stewart, B.(2011). Personality and Play Style: A Unified Model. https://www.gamasutra.com/view/feature/6474
