---
authors: ['David']
title: "Onboarding"
date: 2023-05-13T18:31:10-05:00
description: ""
draft: false
weight: 0
titleIcon: ''
---

{{< intro
  introtitle="Onboarding Demo"
  id="introTest"
>}}
{
  "showBullets": true,
  "showStepNumbers": true,
  "onexit": "console.log(\"I'm exiting the intro\");",
  "oncomplete": "console.log(\"I'm exiting the intro after completing it\");",
  "steps": [
    {
      "title": "Hugo Onboarding",
      "intro": "Welcome! I hope this will be a neat feature."
    },{
      "title": "This is Step 2",
      "intro": "You can add as many steps as you want.",
      "triggeronly": ["desktop"]
    },{
      "title": "Logo",
      "element": "#globalLogo",
      "intro": "This is the logo. Clicking on it will bring you back to the landing page."
    },{
      "title": "Sidebar",
      "element": "#sidebar",
      "intro": "This is the sidebar",
      "position": "right"
    },{
      "title": "Sidebar",
      "element": "#sidebar",
      "intro": "All of the markdown documents will be shown here.",
      "position": "right"
    },{
      "title": "Table of Contents",
      "element": "#tocWrapper",
      "intro": "This is the Table of Contents",
      "position": "left"
    },{
      "title": "Table of Contents",
      "element": "#tocWrapper",
      "intro": "It is auto generated based on the headings inside of the article.",
      "position": "left"
    },{
      "title": "Search Bar",
      "element": "#navbarItemsStart",
      "intro": "For Searching of course.",
      "position": "bottom"
    },{
      "title": "Printing",
      "element": "#printButton",
      "intro": "This is neat. Dedicated printing button. It hides the sidebar, ToC, nav, and sets the colors to standard printing colors (mostly black)",
      "position": "bottom"
    },{
      "title": "QR Code",
      "element": "#qrCodeButton",
      "intro": "Generates the current URL as a QR Code. Useful for taking a specific page on your phone for a ticket or to the workbench.",
      "position": "bottom"
    },{
      "title": "Shortcuts",
      "element": "#shortcutsInfo",
      "intro": "Built-In Keyboard shortcuts, and more can be defined inside of config.toml.",
      "position": "bottom"
    },{
      "title": "Taxonomies",
      "element": "#taxonomiesSelectorContainer",
      "intro": "This is where you can view all taxonomies, right now it is just Tags and Authors",
      "position": "bottom"
    },{
      "title": "Mobile",
      "intro": "This theme is apparently mobile friendly (not tested), these steps can also be only shown based on triggers (i.e. desktop or mobile)"
    },{
      "title": "That's a wrap!",
      "intro": "glhf"
    }]
}
{{< /intro >}}