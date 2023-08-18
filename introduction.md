---
layout: default
title: Introduction
nav_order: 3
---
<!-- 
This page will go over introductory content to the workshop. 
If your workshop has an introduction sequence, whether it be history, "Why should you use __", or anything of that matter, this is where it goes! If your workshop doesn't need this, delete introduction.md from the repository. 
Add, edit, or remove any content below for the workshop in question. 
-->

# Workshop Introduction 
<!-- Follow along with the introductory video, slides, or text below.

<iframe height="416" width="100%" allowfullscreen frameborder=0 src="https://echo360.ca/media/a65689c0-c35c-4f33-9c12-f0ac97883f54/public?autoplay=false&automute=false"></iframe>
[View original here.](https://echo360.ca/media/a65689c0-c35c-4f33-9c12-f0ac97883f54/public?autoplay=false&automute=false)

<embed width="100%" height="466" src="assets/docs/examplePDF.pdf" style="border:none;">
[Download slides here.](assets/docs/examplePDF.pdf) -->

<!-- Below the video/slides, this is where you put the text version of the page. -->
## What are Regular Expressions?

A regular expressions (also referred to as RegEx, RegExp, and rational expression), is a sequence of characters that specifies a search pattern. They're used to search for patterns in strings of text, allowing you to search for and manipulate text.

### History of Regular Expressions

Regular expressions started off as a mathematical concept in the 1950s by Stephen Cole Kleene. They were mainly used in theoretical computer science at the time.

However, it wasn't until 1968 that regular expressions really picked up in use, primarily for pattern matching in text editors and lexical analysis in compilers. Ken Thompson, one of the developers of the UNIX operating system, added the ability to search text using regular expressions to the Unix editor 'ed', which led up to the 'grep' search tool. 

Grep search commands would look like this: `g/regular expression/p`, where `g` and `p` are additional flags standing for "Global" (search the whole document) and "Print" (print all line results) respectively. Shortening regular expression to 're', you get `g/re/p`, or grep. Grep therefore stands for "Global search for Regular Expression and Print matching lines".

From there on, many programming languages, text editors, text analysis tools, and other applications started supporting regular expressions in one form or another.

### What can Regular Expressions be used for?

Text Searching
: Searching for text is an action you might use on a frequent basis. With regular expressions, you can search for more specific patterns within a text.

Text Validation
: Regular expressions allow you to verify a user's input. For example, you can verify whether an email input is valid:   
\[some text\]@\[some text\].\[some short text]

Text Extraction
: You can extract chunks of data from blocks of texts, such as dates, URLs, domains, file names, file types, and more.

Text Manipulation
: With regular expressions, you can narrow down "Find and Replace" to more specific occurences of patterns.

### What supports Regular Expression searches?

TODO: format this differently

Programming languages
: Perl, Python, R, Javascript, and more.

Text Editors and IDEs
: Notepad++, Visual Studio Code.

Database Systems
: MySQL, SQLite, MongoDB

Data Analysis Tools
: Excel, OpenRefine, Tableau

Command-line Utilities
: grep, sed, awk (Unix-like systems)  
  findstr (Windows)