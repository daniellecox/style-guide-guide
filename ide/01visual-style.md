---
layout: page
type: detail
title: Plugins Guidelines
group: ide
permalink: /ide/visual-style.html
description: Visual style for IDE plug-ins
---


## Adhere to the IDE Core Concepts
If you're in doubt about the appropriate look and feel when creating your plugin, look to the platform first, in many cases, the workflow you imagine may already exist. If so, adopt the platform's workflow and re-use the core visual concepts of the IDE.
Using existing conventions will lead to greater consistency with other plug-ins, and an easier learning curve for users.
<br>
In some scenarios, it may be tempting to ignore the workflow of Eclipse and implement a "custom" user interface. This interface will almost certainly stand out like a sore thumb in an integrated environment, where other tools adopt the platform conventions and we lose the benefit of past experience, forcein the user to learn new ideas.
  <br>
IDE and Editor design resources:
* <a href="https://wiki.eclipse.org/User_Interface_Guidelines#General_UI_Guidelines/" target="_blank">Eclipse UI Guidelines</a>
* <a href="https://docs.microsoft.com/en-us/visualstudio/extensibility/ux-guidelines/visual-studio-user-experience-guidelines?view=vs-2019" target="_blank">Visual Studio UI</a>
* <a href="https://docs.microsoft.com/en-us/visualstudio/extensibility/starting-to-develop-visual-studio-extensions?view=vs-2019" target="_blank">Visual Studio Code</a>

___
## Intel and OneAPI Branding in plug-ins
OneAPI is Open Spec with efforts underway to establish an industry brand, because of this avoid branding, logos and graphics in the plug-in, except where identified.  
Furthermore, your plugin will be used alongside other tools as an integratged experience making trademark and brand adherence important.  
For questions about Intel tool names or when/how to use the registered trademark name in the UI, refer to the <a href="https://daniellecox.github.io/style-guide-guide/brand.html" target="_blank">general branding guidelines page</a>.

## OneAPI Logo
> Details about when to use the OneAPI Logo  (for samples, should we use the OneAPI logo or C++ logo or??)
___
## Fonts and colors
Use the fonts and colors provided by the host operating system as much as possible. 
> Direction needed here
___
## Leverage the IDE Native Help for Plugin Documentation
>https://wiki.eclipse.org/Eclipse_Doc_Style_Guide#Topic_Titles
