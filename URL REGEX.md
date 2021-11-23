# REGULAR EXPRESSION FOR URL

Regular Expressions  or "Regex" are typically strings representing a pattern that typically are used to match portions of your targeted string. Regular Expressions ususally tend to be general, very complex that contain many diffrent types of operations that are represented as special characters also known as meta-characters.

## Summary

Syntax for the regular expression are usually described in grammatical form. In this tutorial I will discuss the Regex for URL and identifying the following atoms of the URL Regex- Anchor, Quantifiers, Group Constructs, Bracket Expressions, Character Classes, the or Operator, Flags and last but not least Character Escapes. 

Regex uses the following syntax to match a URL given to the program.
## /^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

By using this Regex it allows programmers to validate URLs with any program or app that the programmer is working on or developing. 

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
 Regular Expressions or REGEX can look like random mumbo jumbo to the untrained eye BUT in reality has meaning and is important to coding . By breaking the syntax down you can learn the logic and usefullness and use it to your specific needs.

## Anchors
 The URL matching sequence has "^" at the start and the special character money sign at the end(I am not putting the money sign because it messes up the markdown). These 2 Regex Anchors must be at the begining and ends of the code sequence. if we use both of these in the same syntax statement we are asking the computer to find an exact match. A couple ways to expand the funcionality of the sequence is to just use ^, this will tell it to match any URL with the begining input. And if we just use $ this will tell it to match any URL that ends with our input.


## Quantifiers
 Qualifiers tell a program to identify a particular expression and by how many times. For example, if it's ending with a ? the computer knows to only excecute it a SINGLE time. On the other hand * instructs the computer to excecute it multiple times. Curly brackets {}tells the program to look for matches in more than 1 context.

## Grouping Constructs
 Parantheses () are used for Grouping Constructs which seperate the groups of code you wish to match. If you want to match diffrent parts of the code using multiple pairs of () can be used with the program.


## Bracket Expressions
 If you need to look for certain charaters Bracket Expressions [] are used. Heres an example- if you needed to look for x,y,z in the targeted string you would wrap x,y,z in brackets like this [xyz]. Heres another example- if you want to match all characters regardless of case you would write it like this [a-zA-Z].


## Character Classes
 This Regex has 2 character classes - the first tells the program to find a given digit \d and the second is used to find the given alphanumeric character.


## The OR Operator
 The OR Operator tells a prgram that you need it to match anything between [] brackets. So []brackets are the OR Operator.


## Flags
 Flags are optional and can be used to change the way the search is conducted. For instance, g (aka global) searches for every instance of a match rather than just one. Then, i (short for 'ignore') instructs the regex to ignore case sensitivity.


## Character Escapes
 Charcacter Escapes enable you to escape special character use so you can use it as a literal, this is done by using the backslash \. Using the double backslash \\ enables you to escape the special character all togethor.

## Author

Jaime A Martinez
University of Texas at Austin
Coding Bootcamp Student 2021
GitHub Profile
JAMATX38
https://github.com/JAMATX38

