---
title: "AR Build System"
date: 2021-01-02T21:48:17+01:00
draft: false

menu:
    main:
        parent: "Iteration 4 - UrbanAR"
        weight: 3
---

At the center of our concept lies the AR Build System. It has taken great effort to transform the concept we had at the midterm demoday towards the fully working prototype we had at the end of the project. 

## High quality mockups
The moment the midterm demoday was finished, we started creating proper concept videos. This was initially the plan for the midterm video, but we underestimated how much time it would take to do properly. 

This was from 23 October to 28 October 2020

{{< figcontainer >}}
{{< video src="images/2020-10-25_blender_1.mp4" caption="First UI animation test in Blender with a faux finger (25/10/2020)" gif="true" >}}
{{< fig src="images/2020-10-27_assets.jpg" caption="Assets created in Photoshop" >}}
{{< fig src="images/2020-10-25_screenshot_blender.jpg" caption="UI animation in Blender" >}}
{{< fig src="images/2020-10-25_screenshot_blender_2.jpg" caption="3D Scene for UI mockup in Blender" >}}
{{< fig src="images/2020-10-25_screenshot_blender_3.jpg" caption="Composition 3D Scene, video and 2D UI in Blender" >}}
{{< video src="images/2020-10-27_render_1.mp4" caption="Final render app mockup" gif="true" >}}
{{< video src="images/2020-10-27_greenscreen.mp4" caption="Greenscreen recording of app mockup render" gif="true" >}}
{{< fig src="images/2020-10-27_screenshot_final_cut.jpg" caption="Final compositing done in Final Cut Pro" >}}
{{< video src="images/2020-10-27_render_final.mp4" caption="Final composited render (27/10/2020)" gif="true" >}}
{{< video src="images/2020-10-27_blender_3.mp4" caption="Library UI interaction mockup in Blender" gif="true" >}}
{{< video src="images/2020-10-27_render_2.mp4" caption="Final Render Library UI interaction mockup" gif="true" >}}
{{< /figcontainer>}}
* Screenshot toevoegen van de UI mockups in Adobe XD. 
* Mention creation of models etc. everything from masking to tracking and planning etc. rationale behind creating these high fidelity mockups. 
## Baby steps
28 October 2020 was the very first version of the AR Build System in action. Made using Unity + ARFoundation and tested on the iPad Pro. 

{{< figcontainer >}}
{{< video src="images/2020-10-28_build_system_1.mp4" caption="The very first version of the AR build system (28/10/2020)" gif="true" >}}
{{< video src="images/2020-10-28_build_system_2.mp4" caption="Further progress on the AR build system (28/10/2020)" gif="true" >}}
{{< /figcontainer>}}

## Overcoming long build times
11 November 2020

One of the main issues with developing for augmented reality in Unity is the long build times. This is because every change made in the code needs to be checked on the target device, since the Unity Editor, which can run the code without building, does not have augmented reality support. 

The recently introduced Unity MARS overcomes this problem and allows you to directly test augmented reality experiences inside the Unity Editor. However, due to the high price - €1000 per seat, per year - we were unable to use this. That's why we created a primitive testing environment that allows us to test the code directly inside the Unity Editor.

{{< fig src="images/2020-11-11_ARBuildSystemTestingEnvironment.png" caption="Primitive AR experience testing environment directly in the Unity Editor (11/11/2020)" >}}

## Progress 12 November 2020
Selection + moving objects now implemented + Tooltip. Multiple objects work, selecting and deselecting. 
Repositioning thus works. 

{{< containedyoutubevideo id="JfMccPT8gpo" name="" caption="Video" >}}

The week between this (13 November 2020 - 20 November 2020) I spent on creating the backend for Laravel etc.

## Progress 30 November 2020
Duplication of objects now implemented
{{< containedyoutubevideo id="LnJvVbO68QI" name="" caption="Video 2" >}}

{{< fig src="images/2020-11-30_first_ui_unity.jpg" caption="" >}}

## Progress 3 December 2020
Horizontal and vertical rotation of objects, revamped UI that actually resembles the UI Mockups. 
{{< containedyoutubevideo id="hzojpm_40H4" name="" caption="Video 3" >}}
{{< containedyoutubevideo id="clQtqjE5F7Q" name="" caption="Video 4" >}}
{{< figcontainer >}}
{{< fig src="images/2020-12-04_mockup_xd_1.jpg" caption="" >}}
{{< fig src="images/2020-12-04_mockup_xd_2.jpg" caption="" >}}
{{< fig src="images/2020-12-04_mockup_xd_3.jpg" caption="" >}}
{{< fig src="images/2020-12-04_ui_drawing.jpg" caption="" >}}
{{< fig src="images/2020-12-05_rotation_selection.jpg" caption="" >}}
{{< fig src="images/2020-12-05_ui.jpg" caption="" >}}
{{< /figcontainer >}}


## 6 / 7 / 8 December 2020
Progress on the library system, automatic population from ScriptableObjects and responsive to screen rotation / sizes. 
{{< figcontainer >}}
{{< video src="images/2020-12-06_inventory_update.mp4" caption="Generated and populated inventory slots on runtime (6/12/2020)" gif="true" >}}
{{< video src="images/2020-12-08_library_panel.mp4" caption="Libraries overview panel implemented (28/12/2020)" gif="true" >}}
{{< video src="images/2020-12-08_library_view.mp4" caption="Proper UI transitions implemented between libraries overview and library (08/12/2020)" gif="true" >}}
{{< fig src="images/2020-12-09_library_overview.jpg" caption="" >}}
{{< fig src="images/2020-12-09_sitting_with_models.jpg" caption="" >}}
{{< /figcontainer >}}


## 10 December 2020
Implemented object scaling


{{< containedyoutubevideo id="327xsNQ4dC8" name="" caption="Video 5" >}}
{{< containedyoutubevideo id="Ss2qSglUMXk" name="" caption="Video 6" >}}

## 11 December 2020
{{< figcontainer >}}
{{< fig src="images/2020-12-11_editing_tree.jpg" caption="" >}}
{{< fig src="images/2020-12-11_unity_scene.jpg" caption="" >}}
{{< fig src="images/2020-12-11_unity_scene_2.jpg" caption="" >}}
{{< fig src="images/2020-12-12_tree_drawing.jpg" caption="" >}}
{{< fig src="images/2020-12-12_improved_models.jpg" caption="" >}}
{{< /figcontainer >}}
Added all objects in the library

## 12 December 2020
Revamped models, added the tree and street lantern. 

16 December video af

18 December final Demoday

