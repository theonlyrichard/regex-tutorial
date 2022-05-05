# Rexeg Tutorial

This tutorial is created to help you better understand and define the sequence of special characters when verifying a search term. A regular expression is a sequence of characters that identify a certain search pattern. They are normally included in algorithims and code and can be used to find ceritan patterns of charachters within a string. 

## Summary

Today I will cover the componets used to match Hex values. This particular regex allows us to find any hex code, whether it begins with a numeral sign (#) or not, and whether it has 6 or 3 characters (digits and leters) in it.
`
/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

`




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
A regex usually comes within this form /abc/, where the search pattern is delimited by two slash characters /. At the end we can specify a flag with these values.
### Grouping and Capturing

### Bracket Expressions
/^#?`([a-f0-9]{6}|[a-f0-9]{3})`$/
Bracket expressions in our regular expression signify the beginning of a character class or quantifier statement. In our example we use parenthesis to define our bracket expressions.


### Greedy and Lazy Match
/^#`?`([a-f0-9]{6}|[a-f0-9]{3})$/

 A greedy match tries to match an element as many times as possible. Whereas, a lazy match tries to match an element as few times as possible. In our example we have `?` which signifies lazy quantifier. This is referred to a lazy quantifier because it causes the regular expression engine to match as few occurances as possible. We can simply turn this lazy match into a greedy one by adding a `?`.

### Boundaries
Does Not Apply!
### Back-references
Does Not Apply!

### Look-ahead and Look-behind
Does Not Apply!

## Author
Richard Cardoza     

Current Insurance Agent trying to switch careers into the tech world!
https://github.com/theonlyrichard