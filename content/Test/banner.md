---
weight: 0
title: "Banner Demo"
description: "How to use a banner"
tags: ["Useful"]
authors: ['David', 'Michael', 'Bingus']
banner: true
bannerContent: "We do not support this software anymore!"
---

This is an examle of a banner on a page.

The banner at the top is typed out in the front matter like so

```yaml
---
banner: true
bannerContent: "We do not support this software anymore!"
---
```

There is also many alerts that you can add to the pages. This is included with some themes shortcodes.

{{< alert
    type="info"
>}}
I'm a **info** type alert
{{< /alert >}}


{{< alert
    type="success"
>}}
I'm a **success** type alert
{{< /alert >}}


{{< alert
    type="warning"
>}}
I'm a **warning** type alert
{{< /alert >}}


{{< alert
    type="error"
>}}
I'm a **error** type alert
{{< /alert >}}
