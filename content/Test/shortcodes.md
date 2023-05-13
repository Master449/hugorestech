---
authors: ['David']
title: "Short Codes Demo"
date: 2023-05-13T18:31:10-05:00
description: ""
draft: false
weight: 0
titleIcon: ''
---

## Shortcodes

These are custom made helped functions for resuable code chunks. They are all usable inside of markdown.

A good example is the [banner demo page](/test/banner/) 

Some more useful ones are:

### Plaintext

For escape long segments of html and markdown

{{< plaintext >}}
<p> Hello There! </p>

**mardown** format does ~~not work~~ here
{{< /plaintext >}}

### TreeView

This tree view updates automatically via the files in a given path.

{{< treeview rootpath="/General" />}}

### Collapsible Sections

{{< collapsible >}}
I am hidden
{{< /collapsible >}}

### Async API

I do not have a good example, [so here is the docs on it](https://shadocs.netlify.app/shortcodes/asyncapi/)

This might be useful for importing the inventory via Graph API

### Snippets

Snippets are chunks of reusable markdown. There are stored within the templates folder and inserted like so:

{{< snippet 
  file="templates/snippet.go"
  codelang="go"
  caption="Snippet Example"
/>}}

This function is not hardcoded into the webpage. It is all inside of the file `templates/snippet.go`

This might be more versatile over the GitLab snippets as when you update the snippet, it updates every page it is on.

### Custom Blockquotes

Not as useful but fancy looking:

{{< blockquote >}}
Blockquote
{{< /blockquote >}}

Blockquote with source:

{{< blockquote source="David">}}
Blockquote with source
{{< /blockquote >}}

### Force Markdown

From the docs: This would be useful for areas that don't use markdown syntax (like the inside of table cells)

| YeeHaw | Code |
|:---:|:---:|
| Code? | ```js console.log("Defaults to in-line comment"); ``` |
| Code? | {{< md >}} 
```js
console.log("Nice Block");
``` 
{{< /md >}} |

### Custom Parameters

No idea how useful [this would be](https://shadocs.netlify.app/shortcodes/parameter/) but seems very cool