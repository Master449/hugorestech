---
weight: 0
title: "ResTech KB"
description: "Landing Page"
author: "David"
---

This is just a nice place I am going to write notes documenting the process of playing around with this. All of these are a work in progress and the order of things is very sporatic.

This will be a mish mash of [Hugo's Documentation](https://gohugo.io/documentation/) and [Shadocs Documentation (this theme)](https://shadocs.netlify.app/theme/introduction/)

# Example Front Matter

```
---
title: 'Markdown Test'
description: 'Markdown Testing File'
category: 'Research'
tags: ['Test', 'Home']
titleIcon: "fa-sharp fa-solid fa-flask"
---
```

# Theme Customization

There is a file inside of `themes/shadocs/assets/sass/custom/`

There are custom SASS variables for changing various things about the theme.

Some of them include 
 - Header Font Size
 - Text Color
 - Gap Width
 - Font Size

While these files are nice, they do **not** have everything. If you're looking to edit something thats not in those files, you're going to have to:

 - *Inspect Element* 
 - Look for an ID or class of the element
 - Use something like VSCodes search for that element in the SASS files.

Images, Fonts, and Extra CSS go inside of `static`, most examples I see, split them into their own folders. This also means the static portion is not included in file location.

So for the Huskie logo up in the top corner, the config.toml contains 

```toml
  logo = "images/Huskie.png"
  logoTouch = "images/Huskie.png"
  favicon = "images/Huskie.png"
```

# Posts / Articles / Knowledge Base

Most of what we are putting on this website will be placed inside of `content` folder.

Not only can you use front matter to categorize stuff, this theme also lets you use the folder directories themselves. If you look at the sidebar to the left, there is a dropdown called `Posts` this is an actual folder named Posts and I have a test markdown file placed inside of there.

For each folder you can specify an `_index.md`, think of this like the "Landing Page" for that specific section.

This can have similar front matter to any page, but what is nice about that is you can leave it blank and it won't be a landing page, only a "Folder" like organization

Images

![Image](/images/Huskie.png)