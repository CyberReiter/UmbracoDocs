---
description: The Server side part of a Property Editor
---

# Property Editor Schema

{% hint style="warning" %}
This page is a work in progress. It will be updated as the software evolves.
{% endhint %}

The Property Editor Schema is server code, written in C#. This handles the storage of a Property Editor and defines _Server Side Validation_ and _Property Value Converts_.

### Property Editor Schema

**Manifest**

```json
{
	"type": "propertyEditorSchema",
	"name": "Text Box",
	"alias": "Umbraco.TextBox",
};
```
