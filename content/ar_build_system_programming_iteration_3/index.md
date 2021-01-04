---
title: "Programming the AR Build System"
date: 2021-01-02T21:48:17+01:00
draft: false

menu:
    main:
        parent: "Iteration 3"
        weight: 3
---

# Programming the AR Build System



## Overcoming long build times
One of the main issues with developing for augmented reality in Unity is the long build times. This is because every change made in the code needs to be checked on the target device, since the Unity Editor, which can run the code without building, does not have augmented reality support. 

The recently introduced Unity MARS overcomes this problem and allows you to directly test augmented reality experiences inside the Unity Editor. However, due to the high price - €1000 per seat, per year - we were unable to use this. That's why we created a primitive testing environment that allows us to test the code directly inside the Unity Editor.

{{< fig src="images/2020-11-11_ARBuildSystemTestingEnvironment.png" caption="Primitive AR experience testing environment directly in the Unity Editor (11/11/2020)" >}}

{{< containedyoutubevideo id="JfMccPT8gpo" name="" caption="Video" >}}
{{< containedyoutubevideo id="LnJvVbO68QI" name="" caption="Video 2" >}}
{{< containedyoutubevideo id="hzojpm_40H4" name="" caption="Video 3" >}}
{{< containedyoutubevideo id="clQtqjE5F7Q" name="" caption="Video 4" >}}
{{< containedyoutubevideo id="327xsNQ4dC8" name="" caption="Video 5" >}}
{{< containedyoutubevideo id="Ss2qSglUMXk" name="" caption="Video 6" >}}