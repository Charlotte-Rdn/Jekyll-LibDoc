---
title: Page split layout
description: Apply the first playground on the right panel.
layout: libdoc/page-split

#LibDoc specific below
category: Examples
order: 200
#assets:
#    path_from_root: /libdoc
#    extensions_enabled: # File extension to display
#        - js
#        - css
---
* 
{:toc}

```yaml
layout: libdoc/page-split
```

Intended to be used for featuring a playground, the page featured playground layout extends the syntax highlighter by running the first highlighted code found onto a right sided panel.

```html
    <h1>My custom playground</h1>
    <p>Gubergren sed aliquyam erat voluptua takimata duo est gubergren dolores.</p>
    <button>button</button>
```
{:.playground}

## Second playground example

```html
    <h1>2nd playground</h1>
    <p>Stet no amet elitr dolores eirmod sadipscing dolores ut lorem.</p>
    <button>button</button>
```
{:.playground}
