# Rexeg Tutorial

This tutorial is created to help you better understand and define the sequence of special characters when verifying a search term. A regular expression is a sequence of characters that identify a certain search pattern. They are normally included in algorithims and code and can be used to find ceritan patterns of charachters within a string. 

## Summary

Today I will cover the componets used to match Hex values. This particular regex allows us to find any hex code, whether it begins with a numeral sign (#) or not, and whether it has 6 or 3 characters (digits and leters) in it.
```
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

```




## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors
``/^``#?([a-f0-9]{6}|[a-f0-9]{3})``$/``
First componet to breakdown is Anchors. Anchors are used at the beggining and end of any expression or string.  /^ $/
### Quantifiers
/^#`?`([a-f0-9]`{6}`|[a-f0-9]`{3}`)$/
Next quantifiers. They are used to annouce the amount of characters expected. Quantifiers let us know how many instances are expected for a match to be found.

### OR Operator
/^#?([a-f0-9]{6}`|`[a-f0-9]{3})$/
The "or" operator within a regular expression is defined using the `|` element . The operater lets us know that it can be either `[a-f0-9]{6}` or 3 characters `[a-f0-9]{3}`.

### Character Classes
/^#?(`[a-f0-9]`{6}|`[a-f0-9]`{3})$/
Now for charater class we can expect it to tell us waht type of characters to expect. They are confined  within `[]`

### Flags

### Grouping and Capturing

### Bracket Expressions
/^#?`([a-f0-9]{6}|[a-f0-9]{3})`$/

### Greedy and Lazy Match
/^#`?`([a-f0-9]{6}|[a-f0-9]{3})$/

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author
Richard Cardoza     
A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)