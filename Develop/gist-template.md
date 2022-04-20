<span style="color:green;font-weight:700;font-size:12px">
    

# Title
<h1 align="center">REGEXP Tutorial </h1>

# Intro
In this tutorial, I will be going over regexp for validating email input.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ <br/>

## Summary

There are many ways to validate an email input, but the fastest and most accurate is using REGEXP. <br/> 
There are different REGEXP to check for valid email input such as: <br/>
- /^\S+@\S+$/
It all comes down to how accurate you want your validation to be. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Learn more about REGEXP](https://www.w3schools.com/jsref/jsref_obj_regexp.asp)
## Regex Components:

### Anchors
In this REGEXP the anchor is '^'.
- '^' marks the start of the wanted pattern

### Quantifiers
In this REGEXP quantifiers are: <br/>
- '+' which joins between the name, the email provider "@gmail" for example, and the ".com" parts of the email <br/>
- '{2,6}' which allows a range of 2-6 characters in the given set of characters "[a-z\.]"<br/>

### Character Classes
In this REGEXP the character class is:<br/>
- '/d' which automatically matches character digits 0-9, it matches single characters only.<br/>

### Grouping and Capturing
In this REGEXP there multiple grouping that serve different purposese:
- `([a-z0-9_\.-]+)` matches user and email. 
- `([\da-z\.-]+)` captures email service provider "@anything".  
- `([a-z\.]{2,6})`looks for the `.com`.  <br/>
### Bracket Expressions
In this REGEXP there are multiple bracket expressions:
- `[a-z0-9_\.-]` matches any letter a-z(Case Sensitive), as well as a character between 0-9 and matches characters "_" , "-" , and ".".
- `[\da-z\.-]` matches a single digit from 0-9, any character a-z (case senstive),".", and "-".
- `[a-z\.]`matches any letter a-z(case senstive) and the character "."


### Greedy and Lazy Match
In this REGEXP:
- The '+' quantifier acts as a greedy match. It will try to match as many times as possible.
- The '{2,6}' is also another greedy match


## Author
[DahhanCodes](https://github.com/DahhanCodes)

</span>
