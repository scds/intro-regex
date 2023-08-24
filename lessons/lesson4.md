---
layout: default
title: Lesson 4 - Anchors and Boundaries
nav_order: 4
parent: Lessons
---

{: .no_toc}  
# Lesson 4 - Anchors and Boundaries

A small description about the lesson.

<details markdown="block" class="toc">
  <summary>
    Table of Contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

## Lesson Objectives
- A learning objective.
- Second learning objective.
- Another learning objective.

<!-- ## Lesson Video
The following video demonstrates each of the steps outlined below in text.

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/a65689c0-c35c-4f33-9c12-f0ac97883f54/public?autoplay=false&automute=false"></iframe>
[View original here.](https://echo360.ca/media/a65689c0-c35c-4f33-9c12-f0ac97883f54/public?autoplay=false&automute=false) -->

## Line Anchors

### The Caret (^)

If you wanted to match the start of a line, you can begin your query with a caret (^).

TODO - EXAMPLE

### The Dollar Sign ($)

Similarly, end your query with a dollar sign ($) to match the end of a line.

TODO - Example

## Word Boundaries

When searching for a short word, like "is", you'll often find matches that contain "is", such as "island" or "miss". You might then search for " is " (note the spaces), but now you'll miss all the occurences of is that don't necessarily come after a space -- starting a line with is, or ending a sentence with is.

Word boundaries (\b) match any non-word characters (such as whitespace and punctuation), so you can search for all occurrences of that word without having to worry about the type of character that follows/preceeds it.

By surrounding your word with word boundaries, it'll specifically search for the full word.

TODO - Example

Note that it's not perfect. If there's any numbers or non-punctuation symbols before/after your word, it won't match those.

TODO - Example


## Key Points / Summary

- Remind the student about what they just learned.
- You can also note down any key information to keep in mind.
