---
title: "Research"
date: 2021-01-02T21:48:17+01:00
draft: false

menu:
    main:
        parent: "Iteration 4 - UrbanAR"
        weight: 1
---

Whereas a lot of research was performed at the start of the design process to find out whether there was an opportunity to apply AR technology in the area of urban design and urban planning, we had not validated yet whether there was an interest among citizens to actually be involved more in the process of urban design and urban planning. 

A questionnaire was created to find out the following aspects:
1. Citizens' current satisfaction with their environment.
2. Citizens' knowledge about possibilities to be involved in urban design and planning.
3. Citizens’ interest in being involved more in urban design and planning.

The questionnaire can be found here: https://forms.gle/6A4h2F8bhfxVveUd6

We eventually got [59 responses](#plotage) from a wide range of ages. Their answers were analyzed used pandas, a python library for analyzing data.

The [bar graph](#bar) shows the majority of users are interested in participating more in the process of urban planning and design. Both heatmap show it is generally perceived that the municipality does not include citizens enough in the process and does not offer enough and appropriate tools. In many cases, people [don’t even know of methods to contact the municipality](#plotknow) about this matter. The ones who did find the opportunity to [participate in a co-design](#plotcodesign) session were often left unsatisfied as they felt they weren’t listened to appropriately: 

>“I was invited by email to give input on redesigning the nearby park. I gave lots of new ideas ... nothing was done with any of my or other's input since they decided to throw in tiles only. No, I wasn't heard, even angry, and will never participate again.”

{{< figcontainer class="medium" >}}
{{< fig src="images/age2.png" caption="The age division of all participants" class="full_width" name="heatmap1">}}
{{< fig src="images/gooutside.png" caption="How often people go outside for recreational purposes" class="full_width" name="heatmap1">}}
{{< fig src="images/influence.png" caption="A graph showing how many people are interested in participating more in urban design and planning" class="full_width" name="bar">}}
{{< fig src="images/included.png" caption="People's perception of whether they are included enough in the process" class="full_width" name="bar">}}
{{< fig src="images/knowingways.png" caption="People knowing ways of contacting the municipality" name="plotknow" >}}
{{< fig src="images/participationincodesignsession.png" caption="People having participated in co-design sessions" name="plotcodesign" >}}
{{< /figcontainer >}}

Apart from the visuals created by Google itself based on the questionnaire's data, we analyzed this data in python. Heatmaps were created as these could clearly show the data's correlation. Both heatmaps show the assessment of citizen's satisfaction with their environment, their interest to participate more in the process of urban design and planning and whether they feel like they are included enough in this process by the municipality. This is analyzed per frequency of going outside and per age group (by means of being provided appropriate tools) on a scale on 1 to 5 (1 = Not at all and 5 = Yeah totally)

From the [left heatmap](#heatmapv1) and [right heatmap](#heatmapv2) we can conclude that in general people are relatively satisfied with their environment, no matter the frequency they go outside. A fun result was the satisfaction was the lowest, the interest to participate in the process the highest and the assessment of being included enough the least for people who go outside only a few times a week. This could be because they are not fully satisfied with their environment to go outside more and therefore want to change that, but are not offered the appropriate tools. Our app offers the opportunity to vote for ideas from their own homes. This makes the app more accessible to especially these people. An unexpected insights was given by the right heatmap. The least satisfaction and highest interest to participate in the process was amongst people in the age group of 23-28 years. They also thought the municipality does not include them enough. This could be because at this age one is more conscious about their environment because they are older and feel like they want to do something about it.

{{< figcontainer class="large">}}
{{< fig src="images/heatmapv5.png" caption="Percepting of satisfaction, interest and enough opportunities per frequency of going outside" class="full_width" name="heatmap1">}}
{{< fig src="images/heatmapv2.png" caption="Percepting of satisfaction, interest and enough opportunities per age group" name="heatmapv2" >}}
{{< /figcontainer >}}

However, the [multiple bar graphs](#satisfactionperaspect) also show there is a big fluctuation in satisfaction among different aspects of people's environment: we need to mainly focus on implementing assets such as benches to sit down, bins against littering, playground-related objects for recreational purposes and some primitive shapes for people to create art or decoration. 

{{< fig src="images/allitems4.svg" caption="Amount of satisfaction per aspect of people's environment" class="full-width" name="satisfactionperaspect" >}}


The results indicates the an engaging communication tool between citizens and municipalities certainly offers the potential to give citizens the power to have a saying in what happens in their own neighborhood. We believe the possibility for citizens to clearly visualize their ideas, as well as vote for these builds, will help the municipality to better understand the needs and wishes of their citizens.

{{< button href="/platform_iteration_4" caption="Read further at Platform" >}}