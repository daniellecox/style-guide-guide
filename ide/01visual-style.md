---
layout: page
type: detail
title: Plugin Style Guidelines
group: ide
permalink: /ide/visual-style.html
description: Visual style guidelines for IDE plug-ins
---


## Adhere to the IDE Core Concepts
When creating your plug-in, re-use the IDE core visual concepts to maintain consistent representation and meaning across plug-in functionality.
Eclipse Guildelines here: [an example](https://wiki.eclipse.org/User_Interface_Guidelines#General_UI_Guidelines "Eclipse Style Guide") inline link.
VS Guildelines here: [an example](https://wiki.eclipse.org/User_Interface_Guidelines#General_UI_Guidelines "Eclipse Style Guide") inline link.


## Intel and OneAPI Branding in plug-ins
Users will use your components alongside others as an itegraged experience so avoid branding, logos and graphics in the plug-in except where identified.  For questions about Intel tool names or when to use the registered trademark, refer to the general branding guidelines.

## OneAPI Logo
Use the OneAPI logo to represent??  (for samples, should we use the OneAPI logo or C++ logo or??)

## Text Style for both IDEs
IDEs and editors should follow the respective platform conventions.  
https://wiki.eclipse.org/User_Interface_Guidelines#General_UI_Guidelines
https://docs.microsoft.com/en-us/visualstudio/extensibility/ux-guidelines/visual-studio-user-experience-guidelines?view=vs-2019

**Use title case for**
Titles, menus, tabs and buttons

**Use sentence case with no ending punctuation for:**
All control labels in a dialog or window, including those for check boxes, radio buttons, group labels, and simple text fields.
Check boxes, radio buttons and group labels. 

## Fonts and colors
Use the fonts and colors provided by the host operating system as much as possible. On Windows the platform color and font settings are found on the Preferences > Colors and Fonts page. The font used by most widgets in Eclipse is the one set in the Message Box settings of the properties. However, operating systems do not provide enough colors to handle all of the extra information that colors and fonts provide in Eclipse. 






## Including Help Files
https://wiki.eclipse.org/Eclipse_Doc_Style_Guide#Topic_Titles