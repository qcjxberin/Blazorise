---
title: "Numeric component"
permalink: /docs/components/numeric/
excerpt: "Learn how to use form numeric component."
toc: true
toc_label: "Guide"
---

## Basics

Use NumericEdit to have a field for any kind if numeric values. All basic types are supported, including nullables(`int`, `long`, `float`, `double`, `decimal`, etc.).

```html
<NumericEdit Value="123" />
```

<iframe src="/examples/forms/numeric-basic/" frameborder="0" scrolling="no" style="width:100%;height:50px;"></iframe>

## Rules

Since NumericEdit is a generic component you will have to specify the exact data type for the value. Most of the time it will be recognized automatically when you set the `Value` attribute, but if not you will just use the `TValue` attibute and define the type manually eg.

```html
<NumericEdit TValue="int?" />
```

## Attributes & Usage

NumericEdit is just a specialized version of `TextEdit` component so all of the rules and styles are still working all the same. See [TextEdit]({{ "/docs/components/text/" | relative_url }}) to find the list of supported attributes.