---
layout: post
author: nroux
title: "Release of UFrameIT 3.0"
---

We have released **UFrameIT 3.0** ([binaries for Windows/Linux/macOS](https://github.com/UFrameIT/UFrameIT/releases/tag/3.0), [source](https://github.com/UFrameIT/UFrameIT/tree/3.0)):
the third version of our game prototyping the [*FrameIT approach*](https://uframeit.org/#the-uframeit-framework-and-serious-games).
The release aggregates new features, UI improvements, and many bug fixes &mdash; something we have been working on for in the last months:

**Added:**

- Dynamic labels for fact slots of a scroll

  Consider the sample scroll in the screenshot. It offers slots for three points "A", "B", "C" and some corresponding angles (C, ABC) and a distance (BC).
  If you now assign points "D", "A", "E" to the point slots, the labels of these slots *and* of the other ones are updated to reflect that.
  In particular, what was previously labeled "BC" is now "AE", and what was "ABC" is now "DAE".
  
  This fits how players, and mathematicians for that matter, think of applying scrolls (theorems): they usually possess a half-applied model in their minds.
  The UFrameIT UI now reflects that.

- Hint feature: having assigned some (but not all) slots of a scroll, you can request hints for how you might want to fill the remaining slots

  The hints are displayed visually. Do we have a screenshot for this?

Both added features have been implemented generically in the MMT system and benefit from our logic view...

**Changed:**

- Performance increases on the MMT server side; entailing that the Unity UI is more reactive

- Made UI much slicker: Do we have a screenshot?

- write about new features, maybe copy from https://github.com/UFrameIT/UFrameIT/issues/38

{% post_url 2010-07-21-name-of-post %}
