---
layout: page
title: DX Design Principles
description: DX Principles to Consider
---

With OneAPI toolsets, our goal is to provide developers with a streamlined solution for multiple architectures.  Because of the complex nature of the project, we must adhere to the specific design standards that will most quickly enable developers to achieve *their* goals on behalf of *their* end-users. 

  
## Focus on The User’s Primary Task
When designing your freature or tool, identify a concise, conceptually coherent set of functionalities that you want to provide, and be careful to avoid over-engineering. Focus the experience on the primary task that the user is attempting to accomplish. A OneAPI plugin or component that tries to do multiple disparate things will end up being complex and potentially confusing.
 
## Minimize Complexity in your Designs
Include only essential parameter controls and information in your plugin. When adding a new piece of functionality, always take a moment to question whether it is necessary. Hide parameters that are not in use. An example is hiding a disabled control, rather than displaying it as disabled. An exception to this is if the disabled values remain relevant even when disabled.

## Create Clear Hierarchy
A plug-in works best with an organized workflow of controls. Give the most relevant and frequently used controls the most prominence. People tend to “read” an interface from left to right and top to bottom. Items that are encountered first are seen to be dominant over those that come later. Placing dominant controls prior to other controls they affect communicates which parts of your application are most important. - when arranging components on a screen

## Anticipate Errors and Include Status Messages
People make mistakes, anticipating these mistakes will make our toolsets more pleasurable and satisfying to use. The first line of defense here is to design so that mistakes cannot be made, for example using inline or real-time validation. Secondly, if it is possible to make a mistake, make it easy to recover. If it's necessary to show an error message, clearly demarcate the error show/tell the user exactly where the problem occurred and what to do about it.  When errors do occur, developers need to be able to easily identify where the problem occurred and what specifically was unexpected.

## Avoid Interruptions
Interruptions cause frustration and annoyance, and prevent people from focusing on what they are interested in. Design your plugin so that it stays out of the way when it is not in use, and does not surprise when it is in use. Use notifications with restraint, always avoid spontaneously popping up dialogs without user intent, and avoid disruptive feedback mechanisms like message dialogs

## Use Industry Best Practices
Tool behavior should matches expected patterns, and the behavior should remain consistent across versions.  Follow best practices for code organization, design patterns, and naming conventions.  
Developer guides, documenation, release notes, and readmes should be in expected locations.

## Invest Time and Effort in Sample Creation
Samples should be easy to use (compile and run), easy to comprehend, and easy to integrate and customize.  Show users how to interoperate between samples.