# Regex Tutorial by Natalya

Regular Expressions, also known as "REGEX", are sequences of characters that define search patterns in text. These expressions do not belong to any one coding language and can be used in any text document. User can set parameters to search with, instead of having to search for exact match to the symbols typed.

## Summary

For this tutorial I chose to use the regex that would search for email addresses in text document. 
The expression looks as such: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`
It contains both literal and meta characters to look through a text document and find all possible matches. 
Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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


### Anchors

Anchors is what the regex begins and ends with; they define what the expression is looking for, everything within it. Sympbols ^ and $ serve as beginning and end, respectively.

### Quantifiers

In this expression, the qualifier is the {2,6} at the end that relates to the number or letters there may be, in this case 2 to 6 letters after the .dot in email address (.io would be two letters whereas .com is 3; and so on).

### Grouping Constructs

In this example, Grouping Constructs are ([a-z0-9_\.-]+) and ([\da-z\.-]+) and ([a-z\.]{2,6}) where each set is contained within the parentesis that is almost like a phrase within the parameters. Just by looking at it, we can assertain that the first grouping construct is an email name that is expected to contain letters of alphabet, numbers 

### Bracket Expressions

"The main purpose of bracket expressions is that they adapt to the user’s or application’s locale. A locale is a collection of rules and settings that describe language and cultural conventions, like sort order, date format, etc. The POSIX standard defines these locales." (https://www.regular-expressions.info/posixbrackets.html). For example: [a-z\.] sets rules for what it expects to see at the end of email address only letters from a to z, but those can repeat.

### Character Classes

Character Classes allow you to match any one of the specified character sets, for example in this expression a-z in [a-z\.] bracket expression is a character class that gives you any character in the alphabet.

### The OR Operator



### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
