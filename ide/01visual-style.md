---
layout: page
type: detail
title: Style Guidelines for plug-ins
group: ide
permalink: /ide/visual-style.html
description: Visual style for IDE plug-ins
---

## Adhere to the IDE Core Concepts
When creating your plug-in, re-use the core visual concepts of the IDE to maintain consistent representation and meaning across plug-in functionality.  IDE and Editor design resources:
* <a href="https://wiki.eclipse.org/User_Interface_Guidelines#General_UI_Guidelines/" target="_blank">Eclipse UI Guidelines</a>
* <a href="https://docs.microsoft.com/en-us/visualstudio/extensibility/ux-guidelines/visual-studio-user-experience-guidelines?view=vs-2019" target="_blank">Visual Studio UI</a>
* <a href="https://docs.microsoft.com/en-us/visualstudio/extensibility/starting-to-develop-visual-studio-extensions?view=vs-2019" target="_blank">Visual Studio Code</a>

## Intel and OneAPI Branding in plug-ins
Avoid branding, logos and graphics in the plug-in, except where identified.  Because users will use your tool functionality alongside other tools as an itegraged experience, and because OneAPI is an Open Spec, proper brand placement is an important consideration. 

For questions about Intel tool names or when/how to use the registered trademark name in the UI, refer to the general branding guidelines.

## OneAPI Logo
Use the OneAPI logo to represent??  (for samples, should we use the OneAPI logo or C++ logo or??)

## Fonts and colors
Use the fonts and colors provided by the host operating system as much as possible. On Windows the platform color and font settings are found on the Preferences > Colors and Fonts page. The font used by most widgets in Eclipse is the one set in the Message Box settings of the properties. However, operating systems do not provide enough colors to handle all of the extra information that colors and fonts provide in Eclipse. 


## Including Help Files
https://wiki.eclipse.org/Eclipse_Doc_Style_Guide#Topic_Titles

## Text Style for both IDEs
IDEs and editors should follow the respective platform conventions.  
https://wiki.eclipse.org/User_Interface_Guidelines#General_UI_Guidelines
https://docs.microsoft.com/en-us/visualstudio/extensibility/ux-guidelines/visual-studio-user-experience-guidelines?view=vs-2019

**Use title case for**
Titles, menus, tabs and buttons

**Use sentence case with no ending punctuation for:**
All control labels in a dialog or window, including those for check boxes, radio buttons, group labels, and simple text fields.
Check boxes, radio buttons and group labels. 


 <a href="https://daniellecox.github.io/style-guide-guide/brand.html" target="_blank">Trademark & Branding GUI guidelines</a>