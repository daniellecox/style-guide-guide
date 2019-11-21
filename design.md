---
layout: page
title: Design Principles
description: descripion here
---


description: This is the guidelines overview description. It will elaborate on the guidelines and principles that need to be followed to build applications.

cards:
- title: Design Principles
  link: /guidelines/principles.html
  description: Design principles
---

**this text is bold**
 
####  Start With the End User
We earn the right to personalize the experience for our users by having empathy for them, by being clear about what we say, and transparent about what we do. When we do this, we establish a relationship built on trust that grows over time and brings end users more value with each interaction.

####
Earn Their Trust
We earn the right to personalize the experience for our users by having empathy for them, by being clear about what we say, and transparent about what we do. When we do this, we establish a relationship built on trust that grows over time and brings end users more value with each interaction.

Nudge When Needed
We inspire intuitive action by giving perceivable hints, feedback, and cues that nudge our users in the right direction naturally and easily. By guiding them, we make our users feel more confident and help them overcome a natural resistance to change.

Build with a Single Focus
We define the primary function of our products in simple, user-centric terms so that our product evolves with a single focus and clear value that our users can understand. This in turn makes decision, making clear—what enhances the primary functionality stays, and the rest goes.

Craft Shows Care
We demonstrate the integrity of our products by paying attention to detail, both in design and execution. When we do this, we not only give users a reason to believe in us, but we show that we value their choice to use our products and services.

Be Consistent and Familiar
When we establish patterns that are consistent within an experience and familiar across contexts, we help our users do more with less effort each time. The result is the creation of an experience that is easy to use and distinctly Intel.

Be Two Steps Ahead
We anticipate our users’ needs and design for them. This means we understand what our end users will need next, and we build accessible solutions that delight them by helping them before they even expect it.

Old ISS Style Guide for plug-in creation

  
Focus on The User’s Primary Task
When designing your component, identify a concise, conceptually coherent set of functionalities that you want to provide, and be careful to avoid over-engineering. Focus the user experience on the primary task that the user is attempting to accomplish. A OneAPI plugin or component that tries to do too many disparate things will end up being complex and potentially confusing.
 
Minimize Complexity in your Designs
Include only essential parameter controls and information in your plugin. When adding a new piece of functionality, always take a moment to question whether it is necessary. Hide parameters that are not in use. An example is hiding a disabled control, rather than displaying it as disabled. An exception to this is if the disabled values remain relevant even when disabled.

Create Clear Hierarchy
A plug-in works best with an organized workflow of controls. Give the most relevant and frequently used controls the most prominence. People tend to “read” an interface from left to right and top to bottom. Items that are encountered first are seen to be dominant over those that come later. Placing dominant controls prior to other controls they affect communicates which parts of your application are most important. - when arranging components on a screen

Anticipate Errors
People make mistakes, anticipating these mistakes will make your plugin more pleasurable and satisfying to use. The first line of defense here is to design the plugin so that mistakes cannot be made, for example using inline validation. Secondly, if it is possible to make a mistake, make it easy to recover. If it's necessary to show an error message, clearly demarcate the error show/tell the user exactly where the problem occurred and what to do about it. - ADD LINK TO ERROR MESSAGE GUIDANCE

Avoid Interruptions
Interruptions cause frustration and annoyance, and prevent people from focusing on what they are interested in. Design your plugin so that it stays out of the way when it is not in use, and does not surprise when it is in use. Use notifications with restraint, always avoid spontaneously popping up dialogs without user intent, and avoid disruptive feedback mechanisms like message dialogs

Human Interface Guidelines Resources
Continue to consult the below guidelines for basic UI design and implementation recommendations.
Microsoft Windows User Experience Guidelines
macOS Human Interface Guidelines
GNOME Human Interface Guidelines
Java Look and Feel Design Guidelines


https://soco.intel.com/docs/DOC-2614796

 	Guideline	Acceptance Criteria/ Measurable Metrics
1	Meet me where I am	Discoverable, easy to figure out what/where to download, ease of installation
2	Contextualize me	Value prop clarity, ease of finding when/why to use a capability, ease of explaining how a capability works toward my goal
3	Don’t surprise me	Behavior matches expected patterns, Behavior is consistent across versions + HW
4	Don’t make me hunt	GSG, Developer guide, samples, readmes, release notes, etc. exist, are in expected locations, and have useful information
5	Make me the hero	Samples are•Easy to use (compile and run)•Easy to comprehend •Easy to integrate and customize
6	Don’t fight with me	Easy coexistenceClear messaging about what will and will not work together
7	Show me how to interoperate	Samples exist showing interoperabilitySamples exist showing better together value propsInstaller and validation aligned to interoperability matrix
From Corporate

  
 Intel Design Language for User Interface
 
Start With the End User
We earn the right to personalize the experience for our users by having empathy for them, by being clear about what we say, and transparent about what we do. When we do this, we establish a relationship built on trust that grows over time and brings end users more value with each interaction.

Earn Their Trust
We earn the right to personalize the experience for our users by having empathy for them, by being clear about what we say, and transparent about what we do. When we do this, we establish a relationship built on trust that grows over time and brings end users more value with each interaction.

Nudge When Needed
We inspire intuitive action by giving perceivable hints, feedback, and cues that nudge our users in the right direction naturally and easily. By guiding them, we make our users feel more confident and help them overcome a natural resistance to change.

Build with a Single Focus
We define the primary function of our products in simple, user-centric terms so that our product evolves with a single focus and clear value that our users can understand. This in turn makes decision, making clear—what enhances the primary functionality stays, and the rest goes.

Craft Shows Care
We demonstrate the integrity of our products by paying attention to detail, both in design and execution. When we do this, we not only give users a reason to believe in us, but we show that we value their choice to use our products and services.

Be Consistent and Familiar
When we establish patterns that are consistent within an experience and familiar across contexts, we help our users do more with less effort each time. The result is the creation of an experience that is easy to use and distinctly Intel.

Be Two Steps Ahead
We anticipate our users’ needs and design for them. This means we understand what our end users will need next, and we build accessible solutions that delight them by helping them before they even expect it.

Old ISS Style Guide for plug-in creation
Focus on The User’s Primary Task
When designing your component, identify a concise, conceptually coherent set of functionalities that you want to provide, and be careful to avoid over-engineering. Focus the user experience on the primary task that the user is attempting to accomplish. A OneAPI plugin or component that tries to do too many disparate things will end up being complex and potentially confusing.
 
Minimize Complexity in your Designs
Include only essential parameter controls and information in your plugin. When adding a new piece of functionality, always take a moment to question whether it is necessary. Hide parameters that are not in use. An example is hiding a disabled control, rather than displaying it as disabled. An exception to this is if the disabled values remain relevant even when disabled.

Create Clear Hierarchy
A plug-in works best with an organized workflow of controls. Give the most relevant and frequently used controls the most prominence. People tend to “read” an interface from left to right and top to bottom. Items that are encountered first are seen to be dominant over those that come later. Placing dominant controls prior to other controls they affect communicates which parts of your application are most important. - when arranging components on a screen

Anticipate Errors
People make mistakes, anticipating these mistakes will make your plugin more pleasurable and satisfying to use. The first line of defense here is to design the plugin so that mistakes cannot be made, for example using inline validation. Secondly, if it is possible to make a mistake, make it easy to recover. If it's necessary to show an error message, clearly demarcate the error show/tell the user exactly where the problem occurred and what to do about it. - ADD LINK TO ERROR MESSAGE GUIDANCE

Avoid Interruptions
Interruptions cause frustration and annoyance, and prevent people from focusing on what they are interested in. Design your plugin so that it stays out of the way when it is not in use, and does not surprise when it is in use. Use notifications with restraint, always avoid spontaneously popping up dialogs without user intent, and avoid disruptive feedback mechanisms like message dialogs

Human Interface Guidelines Resources
Continue to consult the below guidelines for basic UI design and implementation recommendations.
Microsoft Windows User Experience Guidelines
macOS Human Interface Guidelines
GNOME Human Interface Guidelines
Java Look and Feel Design Guidelines


