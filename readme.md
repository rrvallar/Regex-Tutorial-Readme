# Regex Tutorial Application

(by: Robert Vallar )

This tutorial will explain regular expression or Regex. Regex is a set of characters that specifies a search patternomf text. This may include search finding algorithms such as "find" or "find and replace."

# Anchors

Regex begins with /b. This is canned an anchor. The purpose of this is to set a boundary. Using this at the beginning and end of a word, only the text within the anchors are searched for. An example being if the Regex was \b123456\b, then only 123456 would match up but not 1234567.

# Quantifiers

Quantifiers specify the number of occurances a character to match against. Quantifiers are shown through ( \* + ? and {}).
Spome quantifiers expand as far as any provided text is given.
Some examples would be:
(abc+), which matches a string that has ab followed by one or more c
(abc?), which matches a string that has ab followed by zero or one c
(abc{2,5}), whichmatches a string that has ab followed by 2 up to 5 c

# Character Classes

Character classes matches any enclosed characters.

Examples being:
/b - Matches a single character that is a number.
/w - Matches a word character.
/s - Matches a blank character.

# Flag

The flag is the "i" at the end of \b[a-z0-9] + @[a-z0-9]\b/i
the g flag is the global search for Regex matches.

m, or multi-line includes (^ and $) will match the beginning and end of a line instead of the entire sting

i makes the entire string case-insensitive. So /xYz/i will match XYz

gi will cover upper and lower casings.
