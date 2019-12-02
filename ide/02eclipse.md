---
layout: page
type: detail
title: Eclipse Specific
group: ide
permalink: /ide/eclipse.html
description: Design guidelines for OneAPI Eclipse plugins
---


https://wiki.eclipse.org/User_Interface_Guidelines#General_UI_Guidelines

## The Spirit of Eclipse
At its heart, Eclipse is a platform for tool plug-ins. These plug-ins may be developed by a single team or by a partnership of teams, or the user may assemble a set of plug-ins from diverse sources. In either case, the usability of an individual tool, and Eclipse as a whole, will be positively influenced by user interface consistency.

If you're in doubt about the appropriate look and feel for a tool, look to the platform first, then the Java development tooling and the Plug-in Development Environment (PDE) in Eclipse for guidance. In many cases, the workflow you imagine may already exist in Eclipse. If so, adopt the platform's workflow and user interface conventions. This will lead to greater consistency with the platform and other plug-ins, and an easier learning curve for your customers.

In some scenarios, it may be tempting to ignore the workflow of Eclipse and implement a "custom" user interface. This interface will almost certainly stand out like a sore thumb in an integrated environment, where other tools adopt the platform conventions. You lose the benefit of past experience, and force your customers to learn new ideas.

f you decide to reuse the conventions of Eclipse, be careful not to misappropriate Eclipse specific UI conventions. For instance, the active part in a workbench window is indicated by a shaded title. The use of shaded titles within an editor (see below) may be one way to indicate where the focus is, within that part, but it will also blur the concept of part activation in the window.

##Using Eclipse Documentation for OneAPI
https://wiki.eclipse.org/Eclipse_Doc_Style_Guide


## Eclipse UI Patterns
All elements in the Eclipse interface are derived from the plug-in and workbench concepts. Plugins provide functionality and control and are implemented as structured subsystems in the platform.  The workbench is the cockpit for navigating all that is provided by the plug-ins.  

## Follow Existing UI Conventions
As you consider the appropriate interaction for your component, look to the existing System Studio UI for guidance.  In many cases a plug-in will already exist which can be extended (to view existing plug-ins in Eclipse Help > Installation Details >Plug-Ins). 

## Eclipse UI Building Blocks
UI controls and Eclipse components are provided with the platform and come in the form of widgets, windows, dialogs, menus, and wizards, which define a framework for building deep user interactions.

 
The GUI elements in are defined by the Standard Widget Toolkit plug-in ( org.eclipse.swt.widgets ) .  

Standard Widget Toolkit
The SWT implementation accesses the native GUI libraries of the operating system using JNI (Java Native Interface), and uses those libraries to render the UI elements you see in ISS.

For a complete list of classes, including those that don't screenshot well, see the SWT Javadoc. 
View current Eclipse SWT documentation. 

 
