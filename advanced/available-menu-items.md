---
layout: default
title: Menu Items Available for TinyMCE
title_nav: Available Menu Items
description_short: Complete list of menu items available for the menu bar and context menus.
description: Complete list of menu items available for the menu bar and context menus.
keywords: menuitems menu menubar
---

The following tables show all available menu items, including items provided by plugins. To retrieve a list from the editor, run the following command from the browser console:

```js
tinyMCE.activeEditor.ui.registry.getAll().menuItems
```

{% include misc/menu-item-settings.md %}

## The core menu items

The following menu items are available for all {{site.productname}} instances without enabling any plugins:

{% include menu-item-ids/core-menu-items.md %}

{% assign pluginname = "A11yChecker" %}
{% assign plugincode = "a11ychecker" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Advanced Code Editor" %}
{% assign plugincode = "advcode" %}
{% assign altplugincode = "code" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Advanced Tables" %}
{% assign plugincode = "advtable" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Anchor" %}
{% assign plugincode = "anchor" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Autosave" %}
{% assign plugincode = "autosave" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Case Change" %}
{% assign plugincode = "casechange" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Character Map" %}
{% assign plugincode = "charmap" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Checklist" %}
{% assign plugincode = "checklist" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Code" %}
{% assign plugincode = "code" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Code Sample" %}
{% assign plugincode = "codesample" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Comments" %}
{% assign plugincode = "comments" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Emoticons" %}
{% assign plugincode = "emoticons" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Export" %}
{% assign plugincode = "export" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Full Page" %}
{% assign plugincode = "fullpage" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Full Screen" %}
{% assign plugincode = "fullscreen" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Help" %}
{% assign plugincode = "help" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Horizontal Rule" %}
{% assign plugincode = "hr" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Image" %}
{% assign plugincode = "image" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Insert Date/Time" %}
{% assign plugincode = "insertdatetime" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Link" %}
{% assign plugincode = "link" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Media" %}
{% assign plugincode = "media" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Nonbreaking Space" %}
{% assign plugincode = "nonbreaking" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Page Break" %}
{% assign plugincode = "pagebreak" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Page Embed" %}
{% assign plugincode = "pageembed" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Paste" %}
{% assign plugincode = "paste" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Permanent Pen" %}
{% assign plugincode = "permanentpen" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "PowerPaste" %}
{% assign plugincode = "powerpaste" %}
{% assign altplugincode = "paste" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Preview" %}
{% assign plugincode = "preview" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Print" %}
{% assign plugincode = "print" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Search and Replace" %}
{% assign plugincode = "searchreplace" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Spell Checker" %}
{% assign plugincode = "spellchecker" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Spell Checker Pro" %}
{% assign plugincode = "tinymcespellchecker" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Table" %}
{% assign plugincode = "table" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Template" %}
{% assign plugincode = "template" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Tiny Drive" %}
{% assign plugincode = "tinydrive" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Table of Contents" %}
{% assign plugincode = "toc" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Visual Blocks" %}
{% assign plugincode = "visualblocks" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Visual Characters" %}
{% assign plugincode = "visualchars" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}

{% assign pluginname = "Word Count" %}
{% assign plugincode = "wordcount" %}
{% include misc/plugin-menu-item-id-boilerplate.md %}