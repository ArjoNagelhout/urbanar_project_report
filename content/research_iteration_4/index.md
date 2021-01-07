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

{{< figcontainer class="medium" >}}
{{< fig src="images/age.png" caption="People having participated in co-design sessions" name="plotage" >}}
{{< fig src="images/knowingways.png" caption="People knowing ways of contacting the municipality" name="plotknow" >}}
{{< fig src="images/participationincodesignsession.png" caption="People having participated in co-design sessions" name="plotcodesign" >}}
{{< /figcontainer >}}

{{< fig src="images/p2.svg" caption="Amount of satisfaction with environment, interest in urban design and planning and perceping of being offered enough tools per frequency of going outside" name="manyplots" >}}



From the [3x3 grid plot](#manyplots) we can conclude that in general people are relatively satisfied with their environment, no matter the frequency they go outside. The middle row shows the majority of users are interested in participating more in the process of urban planning and design. No matter the frequency of going outside, it is generally perceived that the municipality does not offer the appropriate tools for citizens to actually do so. In many cases, people [don’t even know of methods to contact the municipality](#plotknow) about this matter. The ones who did find the opportunity to [participate in a co-design](#plotcodesign) session were often left unsatisfied as they felt they weren’t listened to appropriately: 

>“I was invited by email to give input on redesigning the nearby park. I gave lots of new ideas ... nothing was done with any of my or other's input since they decided to throw in tiles only. No, I wasn't heard, even angry, and will never participate again.”

From here we can indeed conclude that creating an engaging tool that serves as a communication platform between the municipality and citizens certainly offers the potential to give citizens the power to have a saying in what happens in their own neighborhood. We believe the possibility for citizens to clearly visualize their ideas, as well as vote for these builds, will help the municipality to better understand the needs and wishes of their citizens.

{{< button href="/platform_iteration_4" caption="Read further at Platform" >}}