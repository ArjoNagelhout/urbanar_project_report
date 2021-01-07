---
title: "Evaluation"
date: 2021-01-02T21:48:17+01:00
draft: false

menu:
    main:
        parent: "Iteration 4 - UrbanAR"
        weight: 4
---

## Validating our chosen opportunity
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

From here we can indeed validate that creating an engaging tool that serves as a communication platform between the municipality and citizens certainly offers the potential to give citizens the power to have a saying in what happens in their own neighborhood. We believe the possibility for citizens to clearly visualize their ideas, as well as vote for them, will help the municipality to understand the needs and wishes of their citizens and to integrate these into the real world.




## user-testing our final prototype

ARJO SCHRIJF OVER BACKEND

The user-test of the final AR building systemprototype was focused mainly on validating the usability of the building system and; the way people interact with the system and whether it was nice and fun to use. Afterwards a semi-structured interview would be conducted to get more knowledge about people's actual experience with the app: whether they find it intuitive, whether they like the visual style and whether they would take time to apply this app in the real world.

To make sure users can appropriately apply the functionalities offered by this app, an artificial town was build as can be seen on image .... This made sure people were able to adequately decide on the proportions and quantities of the chosen assets to be placed in the scene. 

All actions performed by the user were logged and send to a server controlled by us. Subsequently, we could analyze this data and easily compare it to other log files, as all assets were placed in a similar setting. 

{{< figcontainer class="small" >}}
{{< fig src="images/IMG_6007.JPG" caption="People knowing ways of contacting the municipality" name="whiteboard1" >}}
{{< fig src="images/IMG_6010.JPG" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/IMG_6013.PNG" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/IMG_6015.JPG" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/utkatrien.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/utkoen.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/utrandi.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< /figcontainer >}}

{{< figcontainer class="large" >}}
{{< fig src="images/csvvoor.png" caption="People knowing ways of contacting the municipality" name="whiteboard1" >}}
{{< fig src="images/csvna.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/pythoncsvvoor.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/pythoncsvna.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< /figcontainer >}}

{{< figcontainer class="large" >}}
{{< fig src="images/timesassetadded.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/timesassetplaced.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/locationtableplots.jpg" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/plots.jpg" caption="People knowing ways of contacting the municipality" name="whiteboard1" >}}


{{< /figcontainer >}}


