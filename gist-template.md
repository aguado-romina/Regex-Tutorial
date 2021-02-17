# Regex Tutorial: Matching an Email

The purpose of this tutorial, for me as a current coding boot camp student is to learn about regex expressions, how they work and what each component means.

## Summary

What a Regex (short for Regular Expression) is?
A Regex is a secuence of characters that defines a search pattern. This pattern matches strings or pieces of strings.
A Regular Expression, or Regex, is a pattern we search for in a text. This regex helps with matching, locating, and managing text.

Matching an Email Regex: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

This Regex expression will search for a string that contains a group of at least one lower case letters from a to z, numbers from 0 to 9 and can include these characters \_\.-.
Followed by the @, and after the @ can contain another group of lower Case Letters from a to z and can contain these \.- characters.
Followed by a .
Finally, should contain a groups of lower case letters from a to z with a minumun lenght of 2 and a max of 6

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

### Anchors

### Quantifiers

- One or More
  {2,6} Between 2 and 6 like (2,3,4,5 or 6)

### Grouping Constructs

() Grouping

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Sources used for this tutorial

https://www.youtube.com/watch?v=7DG3kCDx53c&feature=youtu.be&ab_channel=TheCodingTrain
https://cs.lmu.edu/~ray/notes/regex/
https://www.c-sharpcorner.com/article/understanding-regular-expressions/

## Author

Romina Aguado - Currently enrolled at the University of Minnesota Coding Boot Camp - Full Stack Flex Program.
https://github.com/aguado-romina
