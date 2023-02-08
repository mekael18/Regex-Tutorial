# URL Matching Regular Expression Tutorial

A regex is a pattern that can be used to match a string of text.
This regex, /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/
is used to match URLs. 

## Summary

This regular expression matches URLs. It checks for optional protocols, a domain name
consisting one or more characters including digits, lowercase letters, periods, and hyphens,
a top-level domain of two to six characters that can be either a lowercase letter or a period, 
and an optional path with zero or more characters including forward slashes, word characters, spaces, periods, and hyphens.

## Table of Contents

- #Anchors
- #Quantifiers
- #Grouping Constructs
- #Bracket Expressions
- #Character Classes
- #The OR Operator
- #Flags
- #Character Escapes

## Regex Components

### Anchors
Anchors are characters that specify the position of the match in the string.
In this regex, the `^` character specifies the start of the string.
The `$` character specifies the end of the string.

### Quantifiers

Quantifiers are characters that specify the number of times a character, group, or character class should be matched.
In this regex, the `?` character specifies that the preceding character should be matched zero or one times.
The `*` character specifies that the preceding character should be matched zero or more times.

### Grouping Constructs

Grouping constructs are characters that group characters, character classes, or other grouping constructs together.
In this regex, parentheses `( )` are used to group characters and character classes together.

### Bracket Expressions

Bracket expressions are characters that specify a set of characters to match.
In this regex, bracket expressions are used in the domain name and path components to specify the set of characters that can be matched.

### Character Classes

Character classes are predefined sets of characters that can be matched.
In this regex, character classes are used to match digits `\d`, word characters `\w`, and spaces ``.

### The OR Operator

The OR operator is used to specify alternative matches. In this regex, the OR operator is not used.

### Flags

Flags are used to modify the behavior of the regex. In this regex, no flags are used.

### Character Escapes

Character escapes are characters that are used to match special characters.
In this regex, character escapes are used to match periods `\.` and forward slashes `\/`.

## Author 

https://github.com/mekael18