---
title: "Evaluation"
date: 2021-01-02T21:48:17+01:00
draft: false

menu:
    main:
        parent: "Iteration 4 - UrbanAR"
        weight: 4
---

## Study set-up and execution

ARJO SCHRIJF OVER BACKEND

The user-test of the final AR building systemprototype was focused mainly on validating the usability of the building system and; the way people interact with the system and whether it was nice and fun to use. Afterwards a semi-structured interview would be conducted to get more knowledge about people's actual experience with the app: whether they find it intuitive, whether they like the visual style and whether they would take time to apply this app in the real world.

Because it seemed like one of our group members had the corona virus, the user-test could not be performed in real life and needed to be done online. A mockup prototype of how this online app would look like was created in Adobe XD.

{{< figcontainer class="large" >}}
{{< fig src="images/arapp1.png" caption="The first screens of the online user-test prototype" name="whiteboard1" >}}
{{< fig src="images/arapp2.png" caption="More screens of the online user-test prototype" name="whiteboard1" >}}
{{< fig src="images/arapp3.png" caption="The last screens of the online user-test prototype" name="whiteboard1" >}}
{{< /figcontainer >}}

Luckily, the test returned negative and the user-test could be performed in real life after all. To make sure users can appropriately apply the functionalities offered by this app, an artificial town was build as can be seen on image .... This made sure people were able to adequately decide on the proportions and quantities of the chosen assets to be placed in the scene. 

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

## Qualitative analysis of the results
In order to analyze people’s experience with the app while performing the test, the users were asked to perform the think-aloud technique. They would say what’s on their mind, why they want to perform certain actions and how it turned out. We performed the critical-incident analysis to analyze the qualitative data. It allowed us to scan through everything that has been said and note down the most important ones. Even though the results were very positive, there were some minor troubles the users experienced which we will quote below.

>”It might also be cool if you could 'align' things.”\
>”It would also be nice that if you double clicked, the object would be placed.”\
>”Okay, I thought that if you would press this, you would go right back to the screen.”\
>”It should actually be even freer.”

All of these troubles were related to the efficiency of the system. Some additional ways of tapping or aligning could be great implementations in order to improve its overall usability.

After the session in which the user worked with the app, a semi-structured interview was conducted. This would allow us to get more insights into people’s experience with the app and ask further on their answers. Another critical incident-analysis would be performed for the same reason. See the following quotes:

>”I thought it was super cool and was especially surprised that it worked so smoothly”\
>”It helps a lot with thinking and so forth ... you don't have to imagine it because it's there.”\
>”I didn't have to think about the placement, I found it super intuitive.”\
>”...an accessible tool for the public to give input with”.”

The responses were clearly very positive. People thought the system was very intuitive and fun to use. They did not have to think a lot about what buttons meant what. As envisioned, people could directly see their build in the environment, which really helped to visualize their ideas. A very funny moment happened when one of the users even took a look to the right of the iPad to see how her build looks like in real life, but of course, the build wasn’t there. This clearly shows how AR messes with your mind and makes it feel so realistic. Thereby, people saw it as an accessible tool which is appropriate to be applied in urban design and planning. 

Of course, there also were some little things that users thought could be improved, which will be quoted below:

>”The app is intuitive, maybe you should be able to determine which items are taken out of your inventory.”\
>”...so if the block had been around the whole tree, maybe I'd have seen it better.”\
>”I would prefer a fixed realistic size for some objects, and that you can always adjust it afterwards.”

Also here, the most reactions revolve around the app’s efficiency. People have to reselect objects from their inventory if too many items have been added to the inventory. Thereby, a larger fixed size would mean the user needs to increase the size of an asset less. The block around the tree means the visualization of a selection could be made more visible. These are all relatively easy features to implement, and could be implemented in the app to improve its usability and accessibility.

## Quantitative analysis of the results
Because all actions performed by the user were loggged, analyzation of these results could be performed with pandas, a python library for analyzing data. The locations where people clicked on the screen, as well as the locations in the scale-model of the city where assets were maniupated were logged.

The initial logs consisted of two rows: the timestamp and a logstring. The logstring contained data about what action was performed and at what location. However, because of this format it became near impossible to analyze the different types of data as everything was defined as a string. For that reason the database needed to be adjsuted in excel beforehand and all data was split using commas. 

{{< figcontainer class="large" >}}
{{< fig src="images/csvvoor.png" caption="People knowing ways of contacting the municipality" name="whiteboard1" >}}
{{< fig src="images/pythoncsvvoor.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/pythoncsvna.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< /figcontainer >}}

Eventually, the data could be analyzed. It is clear to. Most of the taps on the screen happened on the right side, as visible in the scatter plots below. Probably because the users were right-handed.  

To rotate an object people would have place there finger on the screen and swipe horizontally or vertically. Interestingly, these actions happened mostly at the middle right of the screen. 

The bottom scatter plot indicates where all users manipulated their assets in the scale-model of the city. As the origin of graphs vary based on where the iPad was calibrated (0,0), these values cannot be stacked. However, they an be compared relative to eachother. Fun to see are the locations of the row of lamp posts at the top, showing why an alignment function was preferred.

{{< figcontainer class="large" >}}
{{< fig src="images/plots.jpg" caption="People knowing ways of contacting the municipality" name="whiteboard1" >}}

{{< fig src="images/locationtableplots.jpg" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< /figcontainer >}}

The street lantern was the most popular asset to be placed in the scene, whereas the bench was the item most often added to the inventory. It’s highly possible the bench is often chosen first and therefore is thrown out of the inventory once other items were selected, which means it had to be added to the inventory once again. This again indicates why people wanted this functionality improved to increase the app's efficiency.


{{< figcontainer class="large" >}}
{{< fig src="images/timesassetadded.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< fig src="images/timesassetplaced.png" caption="People having participated in co-design sessions" name="whiteboard1" >}}
{{< /figcontainer >}}




