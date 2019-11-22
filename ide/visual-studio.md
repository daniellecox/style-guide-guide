---
layout: page
type: detail
title: Visual Studio Plugins
group: ide
permalink: visual-studio.html
description: Design guidelines for OneAPI Visual Studio plug-ins
---

Eclipse UI Patterns
Skip to end of metadata
Go to start of metadata
All elements in the Eclipse interface are derived from the plug-in and workbench concepts. Plugins provide functionality and control and are implemented as structured subsystems in the platform.  The workbench is the cockpit for navigating all that is provided by the plug-ins.  

Follow Existing UI Conventions
As you consider the appropriate interaction for your component, look to the existing System Studio UI for guidance.  In many cases a plug-in will already exist which can be extended (to view existing plug-ins in Eclipse Help > Installation Details >Plug-Ins). 

Eclipse UI Building Blocks
UI controls and Eclipse components are provided with the platform and come in the form of widgets, windows, dialogs, menus, and wizards, which define a framework for building deep user interactions.


The GUI elements in are defined by the Standard Widget Toolkit plug-in ( org.eclipse.swt.widgets ) .  

Standard Widget Toolkit
The SWT implementation accesses the native GUI libraries of the operating system using JNI (Java Native Interface), and uses those libraries to render the UI elements you see in ISS.

For a complete list of classes, including those that don't screenshot well, see the SWT Javadoc. 
View current Eclipse SWT documentation. 

 
