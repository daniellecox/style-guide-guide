---
layout: page
type: detail
title: IDE plugins Guideline
group: ide
permalink: /ide/visual-style.html
description: Visual style guidelines for IDE plugins
---

## Branding
Avoid branding and graphical logos in your component. Adding logos or other elements that aren’t part of the functionality takes space from other controls such as sliders, checkboxes, and pop-up menus. Users will use your components alongside others, so keep the interface simple in order to offer users a cleaner window space and better user experience.

	 ***


## Text Style
Consistent capitalization of text within a plug-in leads to a more polished feel, and greater perception of quality. Use headline capitalization on: Titles, menus, tooltips, tabs and buttons. For example, "Open Setup Log" can be used as a menu item label. Use sentence style capitalization on: all check boxes, radio buttons and group labels. For example, "Choose an option for the Java file" can be used as a group label. Guideline Use Headline style capitalization for menus, tooltip and all titles, including those used for windows, dialogs, tabs, column headings and push buttons. Capitalize the first and last words, and all nouns, pronouns, adjectives, verbs and adverbs. Do not include ending punctuation. Guideline Use Sentence style capitalization for all control labels in a dialog or window, including those for check boxes, radio buttons, group labels, and simple text fields. Capitalize the first letter of the first word, and any proper names such as the word Java.


## Fonts and colors in Eclipse
Eclipse uses the fonts and colors provided by the operating system as much as possible. On Windows the platform color and font settings are found on the Preferences > Colors and Fonts page. The font used by most widgets in Eclipse is the one set in the Message Box settings of the properties. However, operating systems do not provide enough colors to handle all of the extra information that colors and fonts provide in Eclipse. 



## Visual Style Guideline
Re-use the core visual concepts to maintain consistent representation and meaning across Eclipse plug-ins and functionality. 
Note: if writing a component that will not be integrated into the IDE, follow the IT Master Look and Feel Stylesheet
 
This is [an example](http://example.com/ "Title") inline link.

<img src="smiley.gif" alt="Smiley face" height="42" width="42">