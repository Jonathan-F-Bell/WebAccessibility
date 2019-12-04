---
name: Font size.
description: Make sure your fonts scale correctly for those with visual impairments.
---

Some users prefer larger text by default to make it easier for them to see and read. By sizing text using the `em` and `rem` units text will uniformly grow or shrink across your website based on the users system font size choices. Where `px` is a set and static font size, `em` and `rem` are relative sizes. For example, By default `1em` is equal to `16px`. This means that `2em` is equal to `32px`. If the user had their default text size set to `20px`, `1em` would become equal to `20px` and `2em` would become `40px`.

The difference between `em` and `rem` is where the sizing for `1em` is pulled from. If a block of text is set to `1rem` it will always pull the setting for text size from the browser. By default this would be `16px`. If a block of text is set to `1em` it takes the sizing of `1em` from it's parent element. So for example if a paragraph set to `1em` was inside a div set to `30px`, the text set to `1em` would be equal to `30px`. 

All the text on this website is sized using either `rem` or `em`. Try changing the default text size in your browser settings and see how the text on this page adjusts to the new sizing.

[Source](https://www.w3.org/TR/WCAG20-TECHS/C14.html)

{% include fontSizeExamples.html %}