---
layout: default
title: Lesson 3 - Alternation and Capture Groups
nav_order: 3
parent: Lessons
---

{: .no_toc}  
# Lesson 3 - Alternation and Grouping

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

## Alternation

With alternation, you can tell RegEx to match one pattern *or* the other. If you wanted to find all occurrences of the words "word" and "word", you can split them apart with a pipe character ( \| ). 

TODO - Example

## Grouping

### Quantifiers with Groups

If you want to use a quantifier on a group of characters, you'll need to surround the group of characters with round brackets ( ). The quantifier will follow.

TODO - Example

### Alternation with Groups

You can also use groups to limit the extent of alternation. Without groups, RegEx will check for either the left side or the right side of the pipe character, limiting what we can do with it. However, RegEx will stop the alternation search after reaching a bracket, meaning we can expand upon our query.

TODO - Example
TODO - change wording

### Capture Groups

Some implementations of RegEx allow for "capture groups". In languages like Python and Javascript, you can use capture groups to "capture" pieces of your search query. Any captured text is then saved to some sort of data (variable or otherwise), allowing you to use or manipulate that text as part of a program.

In RegEx101, you can see the captured groups in the "Match Information" tab on the right hand side.

TODO - Example

TODO - examples of it being used in Python, R, JavaScript?

### Ignoring Captures

Sometimes, you'll want to use groups without capturing the content. To ignore the content, add `?:` after the first bracket.

TODO - Example

### Nesting Capture Groups

Rarely, you might also need to nest capture groups together.

TODO - Example

## Key Points / Summary

- Remind the student about what they just learned.
- You can also note down any key information to keep in mind.
