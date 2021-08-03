---
title: Assets layout w/ overridden parameters
description: An example of LibDoc's assets layout with custom parameters sets on the page.
layout: styleguide/assets

#LibDoc specific below
category: Examples
order: 200
assets:
    path_from_root: /styleguide
    extensions_enabled: # File extension to display
        - jpg
        - gif
        - webp
        - png
---

```yaml
layout: styleguide/assets
assets:
    path_from_root: /styleguide
    extensions_enabled: # File extension to display
        - jpg
        - jpeg
        - gif
        - webp
        - png
```

Assets layout with custom settings that override default settings of [config file](libdoc-config.html#assets): Into this page, we display all the images files contained into the /styleguide folder.


