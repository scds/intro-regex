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

Line anchors allow us to query for the beginning or the ending of a line.

### The Caret (^)

If you wanted to match the start of a line, you can begin your query with a caret (^).

```
abcabc abcabc
abcabc abcabc abcabc
abcabc abcabc
```

<img src="../assets/img/anchors1.png" width="100%" style="border: 2px solid #000;">

### The Dollar Sign ($)

Similarly, end your query with a dollar sign ($) to match the end of a line.

<img src="../assets/img/anchors2.png" width="100%" style="border: 2px solid #000;">

## Word Boundaries

When searching for a short word, like "is", you'll often find matches that contain "is", such as "island" or "miss". You might then search for " is " (note the spaces), but now you'll miss all the occurences of is that don't necessarily come after a space -- starting a line with is, or ending a sentence with is.

Word boundaries (\b) match any non-word characters (such as whitespace and punctuation) that appear right before or right after an alphanumeric character, so you can search for all occurrences of that word without having to worry about the type of character that follows/preceeds it.

By querying for only `\b`, we can see where all the word boundries are for the following sample text.

```
I visited these islands a couple years back. 
```

<img src="../assets/img/anchors3.png" width="100%" style="border: 2px solid #000;">

By surrounding your word with word boundaries, it'll specifically search for the full word. Below, we search for all occurrences of the word "a" without matching for the letter a inside 'years' and 'islands',

<img src="../assets/img/anchors4.png" width="100%" style="border: 2px solid #000;">


## Key Points / Summary

- Remind the student about what they just learned.
- You can also note down any key information to keep in mind.
