# Learning Regular Expressions in Python

## Overview

This repository documents my journey of learning about Regular Expressions (regex) in Python. Regular expressions are a powerful tool for searching and 
manipulating strings based on specific patterns. This README outlines the key topics I explored during my learning process.

## Topics Covered

1. **Searching Operations**
   - Understanding how to search for patterns within strings using regex.
   - Utilizing functions like `re.search()`, `re.match()`, and `re.findall()`.

2. **Meta Characters**
   - Learning about special characters that have specific meanings in regex, such as `.`, `^`, `$`, `*`, `+`, `?`, and `|`.

3. **Character Sets**
   - Exploring how to define a set of characters to match using square brackets `[]`.
   - Examples of character ranges and negations.
   - Examples of pre-defined characters such as `\d`,`\w`,`\s`,`\b`.

4. **Quantifiers**
   - Understanding how to specify the number of occurrences of a character or group using quantifiers like `*`, `+`, `?`, and `{m,n}`.

5. **Grouping**
   - Learning how to group patterns using parentheses `()`.
   - Understanding the significance of capturing groups and non-capturing groups.

6. **String Modifications**
   - Exploring how to modify strings using regex functions like `re.sub()` for substitution and `re.split()` for splitting strings.

7. **Assertions**
   - Understanding lookaheads and lookbehinds for asserting conditions without consuming characters.

8. **Flags**
   - Learning about various flags that modify regex behavior, such as `re.IGNORECASE`, `re.MULTILINE`, and `re.DOTALL`.

## Getting Started

To start using regular expressions in Python, you need to import the `re` module. Here’s a simple example:

```python
import re
```
