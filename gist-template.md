Regex Tutorial / Email Matching 

In this tutorial i will be explaining what regrex(Regular Expressions) is. A Regrex is a sequence of characters that defines a specfic search pattern. An example would be in code and algorithms. Which find ceratin patterns that are within the text.

## Summary

Today we will be analyzing the content of regex. That uses to find and define. 

Matching Email:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

 ## Anchors 
 The Anchor starts and ends the regular expression. The Matching Email code; 
 /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

 The anchors here are ^ and $. We are looking for the code that starts with: 
 ^([a-z0-9_\.-]+)
 
 Then we find a match that will end with:
 .([a-z\.]{2,6})$

The code must start and end with the above code, if not then it does not match.

### Quantifiers
A Quantifiers is to determines the times of a specific character or group. the following code in our regex code is xyz+ this code will match any string of xy along with z.

Our code Matching the Email: ([a-z0-9_\.-]+) this string will match any string that has a-z,0-9,_,.,-. The + means it has to have one of the charcters to match.

### OR Operator
The Matching Email code does not give a OR Operator in the email code. However we can show with a Hex Value code.

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/

In this regex the matching of hex code uses OR Operator. This starts the match with a # it has to be first and then followed by: 
[a-f0-9{3}] the 3 character contains a list of a-f letters and 0-9 numbers. 

### Character Classes
/d is given in the matching email code that will match a letter code from a-z after the @ sign in the email.

### Flags
Regular expressions have optional flags which allow functionally like global. Matching Email does not use flags. 

A form of flag is :
/pattern/flags;

One flag is g: 
meaning it means "global" will allow for matching newline characters within a string that are regualr expressions guidelines.


### Grouping and Capturing
Matching an email: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

([a-z0-9_\.-]+) is the first group that is in regex. This part has to be true and match before going on to the next code. ([\da-z\.-]+) this the second group in regex. ([a-z\.]{2,6}) this is the the thrid group in the regex.

You have to make sure to follow the guidelines when matching so that you can move on to the next group and so on.


### Bracket Expressions
Bracket Expressions are in guidelines for matching this code right here:
[a-z0-9_\.-]
this code snippet conatins letters a-z, numbers 0-9, also a underscore,hyphen, or period.

A period only matches if it has backslash for it to be matched.

### Greedy and Lazy Match
The matching email code does included a greedy or lazy match.

### Boundaries
In a string of code you are looking for certain words. Boundaries are not really used to match a email code.

### Back-references
No Back-references are included in the code of a matching email.

### Look-ahead and Look-behind
Matching Email does not included look-ahead or look-behind in this string of code. 

look-ahead is: (?=a)
look-behind is: (?<=a)

## Author
This Regex Tutorial was created by Celeste Farris.


