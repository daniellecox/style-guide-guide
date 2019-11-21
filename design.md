---
layout: page
title: DX Design Principles
description: Keep these principles in mind when developing for DX
---


developer tools target a very specific user: the developer. These tools typically serve critical functions and are used habitually for highly consequential actions.

What about time saved? What about ease of use? What about scalability and reliability? What about the ability to make informed decisions? I can show someone a spreadsheet of tabular data or I could show them some informative charts. Both present the same data. Both functionally deliver. But, one works much better at delivering the information and fulfilling its purpose.



Old ISS Style Guide for plug-in creation

  
##### Focus on The User’s Primary Task
When designing your freature or tool, identify a concise, conceptually coherent set of functionalities that you want to provide, and be careful to avoid over-engineering. Focus the experience on the primary task that the user is attempting to accomplish. A OneAPI plugin or component that tries to do multiple disparate things will end up being complex and potentially confusing.
 
#### Minimize Complexity in your Designs
Include only essential parameter controls and information in your plugin. When adding a new piece of functionality, always take a moment to question whether it is necessary. Hide parameters that are not in use. An example is hiding a disabled control, rather than displaying it as disabled. An exception to this is if the disabled values remain relevant even when disabled.

### Create Clear Hierarchy
A plug-in works best with an organized workflow of controls. Give the most relevant and frequently used controls the most prominence. People tend to “read” an interface from left to right and top to bottom. Items that are encountered first are seen to be dominant over those that come later. Placing dominant controls prior to other controls they affect communicates which parts of your application are most important. - when arranging components on a screen

## Anticipate Errors
People make mistakes, anticipating these mistakes will make your plugin more pleasurable and satisfying to use. The first line of defense here is to design the plugin so that mistakes cannot be made, for example using inline validation. Secondly, if it is possible to make a mistake, make it easy to recover. If it's necessary to show an error message, clearly demarcate the error show/tell the user exactly where the problem occurred and what to do about it. - ADD LINK TO ERROR MESSAGE GUIDANCE

# Avoid Interruptions
Interruptions cause frustration and annoyance, and prevent people from focusing on what they are interested in. Design your plugin so that it stays out of the way when it is not in use, and does not surprise when it is in use. Use notifications with restraint, always avoid spontaneously popping up dialogs without user intent, and avoid disruptive feedback mechanisms like message dialogs



 	Guideline	Acceptance Criteria/ Measurable Metrics
1	Meet me where I am	Discoverable, easy to figure out what/where to download, ease of installation
2	Contextualize me	Value prop clarity, ease of finding when/why to use a capability, ease of explaining how a capability works toward my goal
3	Don’t surprise me	Behavior matches expected patterns, Behavior is consistent across versions + HW
4	Don’t make me hunt	GSG, Developer guide, samples, readmes, release notes, etc. exist, are in expected locations, and have useful information
5	Make me the hero	Samples are•Easy to use (compile and run)•Easy to comprehend •Easy to integrate and customize
6	Don’t fight with me	Easy coexistenceClear messaging about what will and will not work together
7	Show me how to interoperate	Samples exist showing interoperabilitySamples exist showing better together value propsInstaller and validation aligned to interoperability matrix
From Corporate

  
