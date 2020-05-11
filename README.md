# Augmented Reality app for CAD model 

This project presents a Augmented Reality app to visualize a Harvester CAD model.  

Check the results of the project in this video: 

<p align="center">
  <a href="https://www.youtube.com/watch?v=UnIzklv86Jo"><img src="https://github.com/joaoadpereira/Harvester_CAD-AR_Smartphone/blob/master/Images/youtube_screenshot_AR.PNG" height="250" alt="IMAGE ALT TEXT"></a>
</div>


## Table of contents:
- [Motivation](#motivation)
- [Harvester CAD model](#harvester-cad-model)
- [Unity project](#unity-project)
- [Results](#results)


### Motivation
The industry seeks new technologies and tools to achieve efficient solutions. When prototyping large and complex CAD models, it is essential that the design communication may be done most flexibly and effectively, allowing to the different stockholders (e.g. designers, engineers, customers, professional users) with different backgrounds remain engaged. 

Augmented Reality is becoming available to everyone since a smartphone is a common gadget in our pockets. Using this so well-known tool in complex environments, as virtual prototyping, may facilitate the design communication and enlarge model reviewing. In the end, improved products may be achieved.

This project intends to display a CAD model in a smartphone with Augmented Reality technology. 
  
### Harvester CAD model
The CAD model used is the [Forest Master Turbo Harvester](http://usewood.fi/en/forest-master-turbo-harvester/) by Usewood Oy. The model was provided in SolidWorks format file. For convenience, it was converted to [SpaceClaim CAD software](http://www.spaceclaim.com/en/default.aspx) from Ansys. 

The model contains more than 500 bodies modelled on their real size. Some dynamics simulations were performed with [AGX Momentum](https://www.algoryx.se/momentum/), allowing to export the model as a .fbx file. 


<p align="center">
<img src="https://github.com/joaoadpereira/Harvester_CAD-AR_Smartphone/blob/master/Images/harvester_CAD.PNG" height="250"> 
</p>

### Unity project
[Unity](https://unity.com/) is a game engine platform, frequently used for professional gaming development.  Due to its flexibility of embodying other software tools, it has been performing an important role in the industry as well, allowing to develop virtual environments to simulate prototypes or hypothetical real scenarios with human participation. 

This project was set up with [Vuforia engine](https://www.ptc.com/en/products/augmented-reality/vuforia?cl1=AR_Vuforia_General_Google_CLC-cpc-ARBrandedxxxVuforiaUKNordics-38010&cmsrc=Google&cid=7015A000001oRiBQAU&elqCampaignId=13184&gclid=EAIaIQobChMI373k_t-m6QIVyIeyCh2Hpg17EAAYASAAEgLiIvD_BwE) from PTC. Vuforia is a platform to develop Augmented Reality applications, with a high applicability range in the industry.

It was selected as an image ([Vuforia ThinkMark](https://github.com/joaoadpereira/Harvester_CAD-AR_Smartphone/blob/master/Vuforia_AR/Assets/Editor/Vuforia/ImageTargetTextures/thingmark/IMG_20190413_124844_scaled.jpg)) to perform as a target. This one, when recognized with a video camera, disposes of the harvester model (imported from SpaceClaim) with the same perspective view. 

The scene was then built for the Android platform, generating an apk. file to be installed in an Android smartphone.

<p align="center">
<img src="https://github.com/joaoadpereira/Harvester_CAD-AR_Smartphone/blob/master/Images/harvester_AR_Unity.PNG" height="250"> 
</p>

### Results
With the use of a smartphone, the user may obtain the harvester model when pointing the camera to the image target. When moving it, the perspective of the model also changes, as is possible to verify in [this video](https://www.youtube.com/watch?v=UnIzklv86Jo).

This project shows the process of converting industrial CAD models to Augmented Reality in a smartphone, using Unity and Vuforia engines. A similar process may be done with other complex CAD models and include dynamic simulation and human interaction. 

The results of this project were presented on [the Roadshow](https://www.youtube.com/watch?v=yKwv1fVc4s4) of [the Mobile VR/AR project](https://www.seamk.fi/yrityksille/tki-projektit/mobiilivrar/).   

<p align="center">
<img src="https://github.com/joaoadpereira/Harvester_CAD-AR_Smartphone/blob/master/Images/AR_harvester.png" height="250"> 
</p>

