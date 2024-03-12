# Fun Regex Tutorial

This project is a tutorial explaining various regular expressions (regex) commonly used in web development. It aims to provide web developer learnings with a comprehensive understanding of regex patterns and their applications.

## Table of Contents

- [Introduction](#introduction)
- [Summary](#summary)
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
- [Regex Components](#regex-components)
- [Author](#author)

## Introduction

A regular expression (regex) is a sequence of characters that defines a specific search pattern. In web development, regex is widely used for tasks such as validating user input, searching and replacing patterns within strings, and parsing data.

## Summary

Each section will include a detailed explanation of the regex component along with examples illustrating its usage.

## Anchors

Anchors are regex elements that assert a position in the string, rather than matching a character. They specify the beginning (^) or end ($) of a line or string, ensuring that a match occurs only at that specific position.

Example:

```regex
^Start
End$
```

## Quantifiers

Quantifiers specify the number of occurrences of the preceding element in a regex pattern. Common quantifiers include:

\*: Matches zero or more occurrences.
+: Matches one or more occurrences.
?: Matches zero or one occurrence.
{n}: Matches exactly n occurrences.
{n,}: Matches n or more occurrences.
{n,m}: Matches between n and m occurrences.

Example:

```regex
\d{3}-\d{2}-\d{4}
```

In the above example, \d{3} matches exactly three digits, followed by a hyphen, \d{2} matches exactly two digits, followed by another hyphen, and \d{4} matches exactly four digits.

## OR Operator

The OR operator in regex uses two methods: one using the pipe symbol (|) to denote alternatives, and another using the question mark (?) as a quantifier to match zero or one occurrence of a character.

Example using the pipe symbol:

`cat|dog `

## Character Classes

TO DO: Explanation of character classes regex components.

## Flags

TO DO: Explanation of flags regex components.

## Grouping and Capturing

TO DO: Explanation of grouping and capturing regex components.

## Bracket Expressions

TO DO: Explanation of bracket expressions regex components.

## Greedy and Lazy Match

TO DO: Explanation of greedy and lazy match regex components.

## Boundaries

TO DO: Explanation of boundaries regex components.

## Back-references

TO DO: Explanation of back-references regex components.

## Look-ahead and Look-behind

TO DO: Explanation of look-ahead and look-behind regex components.

## Author

This tutorial is authored by [Mel W]. You can find more about the author on [GitHub](https://github.com/Mwrightvet).
M
