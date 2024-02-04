---
layout: default
title: Lesson 2 - Quantifiers and Repetition
nav_order: 2
parent: Lessons
---

{: .no_toc}  
# Lesson 2 - Quantifiers and Repetition

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

## Quantifiers

A quantifier is another type of metacharacter that specifies the number of times a pattern or character should be matched.

### The Asterix (*)

When an asterix proceeds a character, RegEx will match the character zero or more times.

TODO - Example

When used in combination with the dot (.) from the previous lesson, you can start searching for things like "all the words that end with \_\_" or "all the words that start with \_\_". We do this in the example below to find \_\_\_\_.

TODO - Example

You might try to use the asterix to search for all numbers by using the `\d*' query. However, the issue here is that it will also match when there are 0 numbers. An example of that is shown below.

TODO - Example

### The Plus (+)

To solve the issue from the previous section, we now introduce the plus. Similarly to the asterix, when a plus sign proceeds a character, RegEx will match the character **one** or more times. This will prevent the matches with an empty result.

TODO - Example

### The Question Mark (?)

When a pattern may or may not appear, you can use the question mark. This will match a character or pattern zero or one time.

TODO - Example

### More Specific Quantifiers

If you want to match a character *exactly* *x* amount of times, you can use curly brackets -- {*x*}.

TODO - Example

You can also specify a range in this way too, from *x* to *y* amount of times (inclusive) -- {*x*, *y*}

TODO - Example  

Lastly, you can also match a character *at least* *x* amount of times -- {*x*, }

TODO - Example

## Lazy vs. Greedy Quantifiers

By default, quantifiers are considered "greedy". When matching a pattern, RegEx will search for the longest possible occurrence that matches your search pattern. This can sometimes be a problem. See the example below.

TODO - Example (search for every item in quotations)

A fix to this problem would be to use a "lazy" quantifier. Lazy quantifiers will search for the shortest possible occurrence that matches your search pattern.

To make a quantifier lazy, you have to add a question mark (?) following the quantifier.

TODO - Example

## Key Points / Summary

- Remind the student about what they just learned.
- You can also note down any key information to keep in mind.
