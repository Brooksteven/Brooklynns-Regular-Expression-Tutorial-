# Regex Tutorial on MAtching an email

Regular expressions can be used to find certain patterns of characters within a string. You can also find and replace a character or sequence of characters within a string. They are also frequently used to validate input. This regex matches character information for valid e-mail addresses.

## Summary

This is the regex code that we will be anaylizing today is: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

## Table of Contents

- [Anchors](#anchors) `^` `$`
- [Quantifiers](#quantifiers) `+` `{}`
- [Character Classes](#character-classes)`[a-z\d]`
- [Grouping and Capturing](#grouping-and-capturing) `([a-z0-9_.-]+)`
- [Bracket Expressions](#bracket-expressions) `[]`
- [Greedy and Lazy Match](#greedy-and-lazy-match)


## Regex Components

### Anchors
- `^` You can use the caret symbol `(^)` at the end of a regular expression to indicate that a match must occur at the beginning of the searched text 

matches at the beginning of the target string
- `$` You can use the dollar symbol `($)` at the start of a regular expression to indicate that a match must occur at the
text ending of content or text searched

`/^[content]$/`


^abc$	start / end of the string

The caret `^` matches the position before the first character in the string. Applying `^a` to `abcd` matches `a`. ^b and ^c does not match `abcd` at all, because the b and c cannot be matched right after the start of the string, matched by `^`. See below for the inside view of the regex engine.
Similarly, `$` matches right after the last character in the string. `d$` matches `d` in abc, while a$ does not match at all.

In regular expressions, anchors mark the beginning and end of a string, line, or word. The beginning of the email string is marked by `^` and the end is marked by `$`.
/^[content]$/
A start of a new line of string would be marked by `^` and ended with a `$`


### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
