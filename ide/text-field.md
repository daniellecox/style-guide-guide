---
layout: page
group: ide
permalink: ide/text-field.html

title: Text field
description: Text field description
---

variations:
- title: Text field
  description: Text field description
  styleModifier: c-text-field
  includeClassification: molecules
  includeCategory: 02-blocks
  includeName: card

usage:
- title: When to use
  description: Usage description.
- title: When to consider an alternative
  description: Alternative usage.

classes:
- className: c-hero
  required : yes
  description: Apply to the hero block's containing HTML element. This class sets up the background-image handling and text color for the unit. The `c-hero` element should have just one immediate child, the `c-hero__body` element. Note, too, that the unit's hero image should be applied as a background image to this `c-hero` element.
- className: c-hero--bare
  modifier : yes
  description: Add to the `c-hero` element to remove the default gradient overlay from the hero image.
- className: c-hero--tinted
  modifier : yes
  description: Add to the `c-hero` element to replace the default gradient overlay with a solid, uniform tint.
- className: c-hero__body
  required: yes
  description: Apply to the container for the card body, Which typically includes a title and description (see below) but can include any arbitrary markup including buttons for a call to action. The class manages the card's background gradient.
- className: c-hero__title
  recommended: yes
  description: Apply to the card's heading inside the card body. The recommended element for this class is `<h1>`.
- className: c-hero__desc
  recommended: yes
  description: Apply to the card's description text inside the card body. The recommended element for this class is `<p>`.


Eclipse UI Patterns
Skip to end of metadata
Go to start of metadata
All elements in the Eclipse interface are derived from the plug-in and workbench concepts. Plugins provide functionality and control and are implemented as structured subsystems in the platform.  The workbench is the cockpit for navigating all that is provided by the plug-ins.  

 

Follow Existing UI Conventions
As you consider the appropriate interaction for your component, look to the existing System Studio UI for guidance.  In many cases a plug-in will already exist which can be extended (to view existing plug-ins in Eclipse Help > Installation Details >Plug-Ins). 


Eclipse UI Building Blocks
UI controls and Eclipse components are provided with the platform and come in the form of widgets, windows, dialogs, menus, and wizards, which define a framework for building deep user interactions.

GUI Widgets
Workbench
Menus and Toolbars
Views and Perspectives
Dialogs and Wizards
