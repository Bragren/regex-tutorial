# Email Matching Regex

## Summary

This is a tutorial explaining how a regular expression used to find emails. It can be used to validate the format of an email.
The regex in question is /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
The ^ and $ are anchors. ^ means the start of a string and $ is to end the string.

### Quantifiers
There are two quantifiers in this regex {2,6} and "+". The {2,6} means there can be 2 to 6 copies of [a-z\.].The "+" 
connects the portions of the regex together and expands the match.

### Character Classes
There is only one character class in this regex. It is \d and it indicates there is a digit.

### Grouping and Capturing
There are three sets of grouping. The groups are set up with (). The groups are ([a-z0-9_\.-]+) the 
beginning of the email, ([\da-z\.-]+) for the emails server, and finally ([a-z\.]{2,6}) for the domain of the email service.

### Bracket Expressions
The brackets are used to show what is allowed in each grouping. The [a-z0-9_\.-] section allows any letter a to z,
any number 0 to 9, and the sybols ".", "_", and "-". The other groups follow almost the same pattern minus a few differences.

### Greedy and Lazy Match
There is only one of these operators used and its the "+". It expands the match further.

## Author

Braden Sandgren
GitHub: https://github.com/Bragren