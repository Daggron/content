---
title: <munderover>
slug: Web/MathML/Element/munderover
tags:
  - MathML
  - MathML Reference
  - MathML:Element
  - MathML:Script and Limit Schemata
browser-compat: mathml.elements.munderover
---

{{MathMLRef}}

The MathML `<munderover>` element is used to attach accents or limits both under and over an expression.

It uses the following syntax: `<munderover> base underscript overscript </munderover>`

## Attributes

This element's attributes include the [global MathML attributes](/en-US/docs/Web/MathML/Global_attributes) as well as the following attributes:

- `accent`
  - : A [`<boolean>`](/en-US/docs/Web/MathML/Attribute/Values#mathml-specific_types) indicating whether the over script should be treated as an accent (i.e. drawn bigger and closer to the base expression).
- `accentunder`
  - : A [`<boolean>`](/en-US/docs/Web/MathML/Attribute/Values#mathml-specific_types) indicating whether the under script should be treated as an accent (i.e. drawn bigger and closer to the base expression).

## Examples

```html hidden
 <link
   rel="stylesheet"
   href="https://fred-wang.github.io/MathFonts/LatinModern/mathfonts.css"
  />
```

```html
<math display="block">
  <munderover>
    <mo>∑</mo>
    <mrow>
      <mi>n</mi>
      <mo>=</mo>
      <mn>1</mn>
    </mrow>
    <mrow>
      <mo>+</mo>
      <mn>∞</mn>
    </mrow>
  </munderover>
</math>
```

{{ EmbedLiveSample('munderover_example', 700, 200, "", "") }}

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{ MathMLElement("munder") }} (Underscript)
- {{ MathMLElement("mover") }} (Overscript)
