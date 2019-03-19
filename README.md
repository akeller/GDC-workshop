# Hands On Watson SDK for Unity Workshop

Please arrive with [Unity](https://unity3d.com/) installed on your laptop. The personal license will work just fine.

You will also need an IDE to write C#. You can select Visual Studio to be included in the install of Unity.

Between the hands-on portions of this workshop, we'll go into a little more detail about each of the services, what you can do with them after the workshop. If at any point you feel like working ahead, please wait to ask questions until we are working on that particular section.

**Agenda**
* Watson Services
* Setting Up Project & Watson SDK for Unity
* Scripting in Unity

Depending on the pace of the workshop, we may not get through everything so be sure to star/bookmark this repo to continue at home.

This workshop is based on this pattern: https://developer.ibm.com/patterns/build-an-ai-powered-ar-character-in-unity-with-arkit/

## Setting up your IBM Cloud Account

During this workshop you will be able to create services under the free, lite plan. You'll also be able to keep it long after this workshop is over!

Use this link to sign up for an IBM Cloud Account: [ibm.biz/GDC-workshop](http://ibm.biz/GDC-workshop)

Once you've created an account you are ready to create the services for this workshop.

## Creating your services

From your dashboard, click ```catalog``` in the upper menu. This will show a list of all the catalog options in IBM Cloud. 

Select ```AI``` from the menu on the left. This will show all the AI services, platforms, and other offerings available in the IBM Cloud. 

In this workshop we will create 3 services: Watson Assistant, Speech to Text, and Text to Speech to bring an immersive dialog experience into Unity.

### Watson Assistant

Click on the ```Watson Assistant``` tile.

Give your Assistant service a descriptive name. You can keep the default region and resource group. Notice the thresholds/features of the lite service and keep those in mind if you plan on pushing your solution into production or into an app store.

Click ```Create```.

It make take a few minutes to spin up the service.

Take note of the URL and API token (your credentials), we'll need that later in the workshop.

Once you've created your Watson Assistant service, let's chat about what it is and what you can do with it. 

### Speech to Text & Text to Speech

Click ```Catalog``` from the upper menu. Select ```AI``` from the menu on the left.

Click on the Speech to Text tile.

Give you Speech to Text service a descriptiove name. You can keep the default region and resouce group. Notice the thresholds/features of the lite service and keep those in mind if you plan on pushing your solution into production or into an app store.

Click ```Create```.

It make take a few minutes to spin up the service.

Take note of the URL and API token (your credentials), we'll need that later in the workshop.

Repeat this for the Text to Speech service.

Once you've created your Speech to Text and Text to Speech services, let's chat about what they are and what you can do with them.

## Brief Unity Overview

This workshop is not designed to be an intro to Unity, you'll just get a few tips and tricks on how to get to writing code and working with Watson. For more Unity based tutorials, check out their [website](https://unity3d.com/learn/tutorials).

Depending on what you want to do in the future with this particular project, take a look at the asset store. There is a mix of free and cost assets for fully rigged models.

The free asset I recommend is this: https://assetstore.unity.com/packages/3d/characters/robots/cyber-soldier-52064 (note this is rigged by not animated).

## Create a Project in Unity

Start Unity and choose the 3D project template. This will setup your project with the correct initial game objects including a light source and a main camera. 

## Adding the Watson Unity SDK to Your Unity Project

Clone or Download the Watson SDK for Unity. You can clone it directly to your Unity project or drag and drop it into the Unity editor.

## Brief C# Overview (Scripting in Unity)

Even though you've included the SDK into your project, you will need to include it as a namespace. 

## How to incorporate AR into this project?

If time permits, we can take a look at what this might look like in AR.

*This is not part of the hands on portion of the workshop.*

You have a couple options to choose from when extending this workshop. 

Vuforia or AR Foundations are your two main options, while you could also natively target ARKit and ARCore as well, depending on your device. If you want to see an AR example working on your laptop using your integrated webcam, Vuforia will be the best place to start.

# More resources
https://developer.ibm.com/industries/gaming/
https://developer.ibm.com/patterns/build-an-ai-powered-ar-character-in-unity-with-arkit/