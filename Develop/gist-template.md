# Title (replace with your title)

In this tutorial we are going to break down a Regular Expression. Regex are used to validate text and to search through text.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

Anchors assert that the Regex current position in the string matches a well-determined location like the beginning or ending of the expression. The below code written signifies our anchors used in our Regex.

The "/^" signifies the start of the string and the "$/" signifies the end of the string. Its used to make sure the Regex has a start and a beginning.

/^$/

### Quantifiers

Quantifiers are used to match a character or sequence zero or more times.

The below code shows where we used a quantifier.

{2,6} We are making sure at the end of our email we have atleast between two to six characters.

### OR Operator

### Character Classes

Character classes distinguish kinds of characters. This helps differentiate between numbers and digits.

When refrencing our email regex we use character classes multiple times.

a-z - this represents any letter from a-z 0-9 - this represents any number 0-9

When putting these in your Regex it allows the user to put in any number 0-9 or letter a-z.

### Flags

Flags allow you to make the case sentive or insensitive. You can also do this on a global scale. We didn't input flags anywhere, but this is something you can do to ame the Regex even better/more efficient.

### Grouping and Capturing

### Bracket Expressions

A bracket expression matches a specific set of single characters. It allows you the Regex to return all possiblites for that portion of your expression.
We used a bracket expression in three places.

1. Before the @ symbol - our regex makes sure we are only allowing lower case letters, number 0-9, hyphens and underscores. [a-z0-9_\.-]
2. After the @ symbol - our regex makes sure we are only allowing numbers and any lower case letters and hyphens. [\da-z\.-]
3. After the "." - our regex make sure we are only allowing lower case letters a-z. [a-z\.]

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

I am a recent graduate from the SMU Coding Bootcamp and I am looking to move forward with a career in software development.
Github lnk: https://github.com/AmaechiMcMillan
