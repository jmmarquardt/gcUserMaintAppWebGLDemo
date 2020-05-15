# Clarus 590/690 GC User Maintenance App-WebGL Demo

A Web GL Demo version of the GC User Maintenance App located at https://github.com/jmmarquardt/gcUser. All materials in this repository are copyrighted 2020 by PerkinElmer, Inc. All rights reserved. This is merely for demostration sharing purposes only.

A browser based demo of this app can be found here [GC User Maintenance App Demo](https://jmmarquardt.github.io/gcUserMaintAppWebGLDemo/index.html "GC User App Demo")

## Description

A mobile app for Android, developed in Unity3D and C# which describes some basic user maintenance steps from the gas chromatograph user manuals. Some of the text and images are sourced from OEM user manuals and are subject to original copyright.

Version 1.0 is focused primarily on the most common configurations of injectors and detectors. As such only the panels for the CAP, PSS and Packed injectors and the FID detector will be included. The column selection panels as well as the remaining injectors, autosamplers and detectors will be added in later versions.

![Splash Screen of the Mobile App][splash]

The Splash screen will load first, and then after a short delay load the Main menu panel. From the Main Menu Panel, users have the ability to navigate to the main sections of the app via buttons (Autosamplers, Injectors, Columns, Detectors, Parts & Tools), or use the nav bar buttons (top) to exit the application via the 'X' icon, or pull up a side menu that offers navigation back to the main menu (from anywhere in the app) or an about menu that loads the about splash screen. Additionally when available the bottom navigation bar will have forward and back buttons as well as an info button when enabled (dependent on panel and state).

An example of the overall panel flow for the UI is below:

![An example UI flow diagram for the app][UIFlow]

## Main Menu Panel

The Main Menu panel will have a series of buttons representing the main component groups of the Gas Chromatograph to allow navigation through the app:

* Autosampler
* Injectors
* Columns
* Detectors
* Parts and Tools

![An example Main menu UI panel for the app][main]

## Autosampler Menu Panel

The Autosampler Menu panel will have a series of buttons representing the main user maintenance procedure sections from the user hardware manual:

* Replacing a Syringe
* Replacing the Vial Locator
* Cleaning the Sample Tray

A later expansion of this app can include navigation to the different types of autosamplers offered as configuration options on the Clarus GC such as the Turbomatrix Headspace, Turbomatrix Headspace Trap, Turbomatrix Automated Thermal Desorber (ATD) or even a CombiPal high throughput autosampler.

![An example Autosampler Maintenance menu UI panel for the app][alsMain]

## Author

:copyright: John-Michael Marquardt ([jmmarquardt](https://github.com/jmmarquardt "Github Profile") :octocat:)\
Sr. Customer Support Engineer\
PerkinElmer | Discovery and Analytical Sciences

[UIFlow]:./doc/imgs/UIFlowDiagram.png "UI Workflow of the Mobile Application"
[splash]:./doc/imgs/SplashScreen.png "Splash Screen of the Mobile Application"
[main]:./doc/imgs/Main_Menu_Panel.png "Main menu of the Mobile Application"
[alsMain]:./doc/imgs/Autosampler_Menu_Panel.png "Main menu of the Mobile Application"

## Copyright

:copyright: Copyright 2020 John-Michael Marquardt. All Rights Reserved.

:copyright: Copyright 2020 [PerkinElmer, Inc](https://perkinelmer.com "PerkinElmer Inc"). All Rights Reserved.