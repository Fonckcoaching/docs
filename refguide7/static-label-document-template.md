---
title: "Static Label (document template)"
space: "Mendix 7 Reference Guide"
parent: "document-templates"
---


A static label shows a line of static text. You can use it to place custom text inside a data view, template grid or table.

<div class="alert alert-info">{% markdown %}

![](attachments/819203/918130.png)]
A label with text 'Customer name'.

{% endmarkdown %}</div>

If you want to insert the current page number or the total page count in your document, you can use a token inside a static label (and only in a static label).
Before version 2.5.4, spaces were automatically inserted on either side of the token. This is no longer the case.

<div class="alert alert-info">{% markdown %}

Static label content: Page [%pageNumber%] of [%totalPageCount%]
Will print: Page 2 of 4

{% endmarkdown %}</div>

## Common Properties

{% snippet Name+Property.md %}

## Appearance Properties

### Caption

This is the value that will be displayed in the document.

### Style

See [Style](style)
