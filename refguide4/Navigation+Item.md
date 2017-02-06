---
title: "Navigation Item"
category: "refguide4"
space: "Reference Guide 4"
---
Each menu, menu item and item in the navigation tree is a navigation item. Navigation items can contain other navigation items within certain limits. Menus can have menu items (2 levels) and the navigation tree can have three levels.

## Appearance Properties

### Caption

The caption is the text that will apear in the menu or the navigation tree. This is a translatable text. See [Translatable Texts](Translatable+Texts).

### Image

The image will appear before the caption in the menu or navigation tree. Note that images of menus will not be shown.

## Behavior Properties

### Target

The target of the navigation item is the form or microflow that will be opened when the item is clicked.

<div class="alert alert-success">{% markdown %}

You can open a form that contains a data view from a navigation item by setting as target a microflow that first retrieves an object for the data view and then opens the form.

{% endmarkdown %}</div>

## Related Articles

*   [How To: Create a new navigation item](https://world.mendix.com/display/howto25/Create+a+new+navigation+menu+item)