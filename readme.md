# Regex Tutorial Application

(by: Robert Vallar )

This tutorial will explain regular expression or Regex. Regex is a set of characters that specifies a search patternomf text. This may include search finding algorithms such as "find" or "find and replace."

## Table of Contents:

- [Anchors](#Anchors)
- [Quantifiers](#Quantifiers)
- [Character Classes](#Character-Classes)
- [Flags](#Flags)
- [Bracket Expression](#Bracket-Expressions)
- [Author](#Author)
- [GitHub Profile](#Github)
- [Acceptance Criteria](#Acceptance-Criteria)

### Anchors

Regex begins with /b. This is canned an anchor. The purpose of this is to set a boundary. Using this at the beginning and end of a word, only the text within the anchors are searched for. An example being if the Regex was \b123456\b, then only 123456 would match up but not 1234567.

### Quantifiers

Quantifiers specify the number of occurances a character to match against. Quantifiers are shown through ( \* + ? and {}).
Spome quantifiers expand as far as any provided text is given.
Some examples would be:
(abc+), which matches a string that has ab followed by one or more c
(abc?), which matches a string that has ab followed by zero or one c
(abc{2,5}), whichmatches a string that has ab followed by 2 up to 5 c

### Character Classes

Character classes matches any enclosed characters.

Examples being:
/b - Matches a single character that is a number.
/w - Matches a word character.
/s - Matches a blank character.

### Flags

The flag is the "i" at the end of \b[a-z0-9] + @[a-z0-9]\b/i
the g flag is the global search for Regex matches.

m, or multi-line includes (^ and $) will match the beginning and end of a line instead of the entire sting

i makes the entire string case-insensitive. So /xYz/i will match XYz

gi will cover upper and lower casings.

### Bracket Expressions

Bracket expressions use ([]) to define the character class. Anything placed with the brackets will make a match to the regex pattern unless a (^) character is used. So [a-z] will match any character in the alphabet.

### Author

Rob currently works in the medical field, looking to expand on his knowledge by taking an online coding Bootcamp course. Having always been interested in taking coding courses, he found this opportunity perfect to hone these new skills. Rob believes these skills can be useful in helping create the practice website.

### Github

https://github.com/rrvallar

### Acceptance Critera



