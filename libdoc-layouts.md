---
title: Layouts
description: Available Jekyll theme layouts.
layout: styleguide/page

#LibDoc specific below
category: Features
order: 100
#unlisted: true
#assets: # Only for styleguide/assets layout
#    path_from_root: /
#    extensions_enabled: # File extension to display
#        - js
#        - css
---
* 
{:toc}

## Page 

The most common LibDoc's layout to display content. [View an example](libdoc-layout-page.html)

```yaml
# Front matter
layout: styleguide/page
```

## Assets

The same as `styleguide/page`. This layout adds a grid of user specified assets folder available for download that are included into the project.
The default path of the assets source is set in the [config file](libdoc-config.html#assets) which can be overridden for each page.

[Example 1 - default](libdoc-layout-assets.html)

```yaml
# Front matter
layout: styleguide/assets
#assets: # Only for styleguide/assets layout
#    path_from_root: /
#    extensions_enabled: # File extension to display
#        - js
#        - css
```

[Example 2 - with overridden parameters](libdoc-layout-assets-alt.html)

```yaml
# Front matter
layout: styleguide/assets
assets: # Only for styleguide/assets layout
    path_from_root: /
    extensions_enabled: # File extension to display
        - js
        - css
```

## Page featured playground

Based on page layout, splits the main content in two sides: On the left, the page render, on the right, the first playground found on the page.

[Example](libdoc-layout-page-featured-playground.html)

```yaml
# Front matter
layout: styleguide/page-featured-playground
```

## Blank

Just a simple html render of the current page

[Example](libdoc-layout-blank.html)

```yaml
# Front matter
layout: styleguide/blank
```