# Matching a Hex Value
Matching a hexadecimal value can be done without the Ox prefix but the Ox prefix makes it easier. This is because without the OX prefix \b(?:[hexadecimal]{number of hexadecimals digits to match together}+\b) must be used 


## Summary
This Regex shows the breakdown of matching Hexadecimal values together without the Ox prefix. 

## Regex Example for Hexadecimal Matching 
"/^#?([a-f0-9]{6}|[a-f0-9]{3})$/"


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

## Regex Components of Hexadecimal Values

### Anchors
Anchors in the matching of hexadecimal values are ^ and $ 
^ identifies the start of a string 
$ identifies the end of the string 


### Optional Characters
Optional Characters are part of hexadecimal matching. They include ? and #. The ? means that the previous figure is optional. 
 

### Quantifiers
Quantifiers are place in {3} or {6}
The {3} identifies that 3 occurrences of the previous character and that the short version si being used
The {6} identifies that 6 occurrences of the previous character and that the short version si being used

### OR Operator
This is also the alteration operator the | 
This means that before oe after the | can be utilized its kind of an and symbol 


### Character Classes
[A-F] [a-f] [0-9] are all character classes for the 


### Flags
Flags are not used in the hexadecimal but for common ones used in Javascript i and g are options


### Grouping and Capturing
([]{}|[]{}) the () on are used to enclose the character classes and quantifiers and the alteration so that this information can be processed

### Bracket Expressions
[] are used to enclose the character classes 

### Greedy and Lazy Match
Lazy match matches as little as possible which is why its called lazy, it does as little work as it can. 
Greedy is the opposite, matching as much as it can. Hexadecimal matching tends to be greedy. 

### Boundaries
// keeps everything inside together 


### Back-references
Not used in hexadecimal matching 

### Look-ahead and Look-behind
Not used in hexadecimal matching 

## Author

Emily is a student at Rutgers University currently enrolled in their Full-Stack Coding BootCamp. Her favorite part of coding is the CSS. She opted for Hexadecimal because of its mix of numbers and letters which she finds interesting nad enjoys for picking specific colors. 

https://github.com/EmilyCassel
