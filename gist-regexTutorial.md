# Regex - Tutorial

> Regular expressions are patterns used to match character combinations in strings. In JavaScript, regular expressions are also objects. These patterns are used with the `exec()` and `test()` methods of RegExp, and with the `match()`, `matchAll()`, `replace()`, `replaceAll()`, `search()`, and `split()` methods of String. This chapter describes JavaScript regular expressions.

    Source : https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions

## Example

#### `/(["'])((?:(?=(?:\\)*)\\.|.)*?)\1/gm`

This Regex Expression is for quote matching with escape.

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

---

### **Regex Components**

>A regex component that matches a specific condition at a particular position in an input string. struct Lookahead. A regex component that allows a match to continue only if its contents match at the given location.

### **Anchors**

>Anchors belong to the family of regex tokens that don't match any characters, but that assert something about the string or the matching process. Anchors assert that the engine's current position in the string matches a well-determined location: for instance, the beginning of the string, or the end of a line.

### **Quantifiers**

>Quantifier in JavaScript is used to find the match of any string which is not followed by a specific string m.

### **OR Operator**
>Alternation is the term in regular expression that is actually a simple “OR”. In a regular expression it is denoted with a vertical line character `|`.

>For instance, we need to find programming languages: HTML, PHP, Java or JavaScript.

### **Character Classes**

>Matches any one of the enclosed characters. You can specify a range of characters by using a hyphen, but if the hyphen appears as the first or last character enclosed in the square brackets, it is taken as a literal hyphen to be included in the character class as a normal character.

### **Flags**
>When specified, these flags change the default match behavor of the RegExp object. Performs a global match, finding all matches rather than just the first. Makes matches case-insensitive. Matches both uppercase and lowercase.

### **Grouping and Capturing**
>Capturing groups are a way to treat multiple characters as a single unit. They are created by placing the characters to be grouped inside a set of parentheses. For example, the regular expression (dog) creates a single group containing the letters "d" "o" and "g" .

### **Bracket Expressions**
>A bracket expression is either a matching list expression or a non-matching list expression. It consists of one or more expressions: ordinary characters, collating elements, collating symbols, equivalence classes, character classes, or range expressions.

### **Greedy and Lazy Match**
>'Greedy' means match longest possible string. 'Lazy' means match shortest possible string

### **Boundaries**
>The word boundary \b matches positions where one side is a word character (usually a letter, digit or underscore—but see below for variations across engines) and the other side is not a word character (for instance, it may be the beginning of the string or a space character).<br>
>Word boundaries are useful when you want to match a sequence of letters (or digits) on their own, or to ensure that they occur at the beginning or the end of a sequence of characters.</br>

### **Back-references**
>Backreferences refer to a previously captured group in the same regular expression.

### **Look-ahead and Look-behind**
>Lookaheads are the patterns that ask JavaScript to look ahead in the string to check for intended patterns in the string. Lookahead and Lookbehind are together referred to as Lookaround. Using Lookaheads we can easily capture a particular group of characters only if they appear before another set of characters

---

## Author & Credit

Allison Ang
GitHub - https://github.com/Allie-Ang <br>
LinkedIn - https://www.linkedin.com/in/allison-ang-a4959093/ </br>
Regex Expression - https://regex101.com/library/dT0vT3?filterFlavors=javascript&orderBy=MOST_POINTS&page=1&search= </br>
