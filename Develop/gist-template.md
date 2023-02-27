# Magical Tutorial(Matching tag)

# Introductory and Summary 

This regular expression matches an HTML tag. it starts with an opening angle bracket `<`,followed by the tag name(which consists of one or more lowercase alphabetical characters),followed by zero or more attributes (which consist of one or more lowercase alphabetical characters, an equals sign, and a value surrounded by a single or double quotes),followed by an optional forward slash `/` if the tag is self-closing, and ends with a closing angle bracket `>`.


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
None are used in this regular expression,since we are not trying to match a pattern at the beginning or end of the string.

### Quantifiers

The `*` quantifier is used to match zero or more attributes in the opening tag.
### OR Operator
None are used in this regular expression.
### Character Classes
The `[a-z]`character class is used to match any lowercase alphabetical character in the tag name and attribute names. The `[' "] `character class us used to match either single or double quote in the attribute values
### Flags
None are used in this regular expression,since we are not using any options that modify the behavior of the regular expression 
### Grouping and Capturing
Parantheses`()` are used to group the tag name and attributes together. The first group captures the tag name, and the second group is a non-capturing group that matches zero or more attributes.Within the non-capturing group, parentheses are used to group the quote character used in the attribute value.
This helps to ensure that the opening and closing quotes match.
### Bracket Expressions
None are used in this regular expression
### Greedy and Lazy Match
The `+` and `*` quantifiers are greedy, which means they will match as many characters. if we wanted to make them lazy instead, we could use the `+?` abd `*?` quantifiers instead.
### Boundaries
None are used in this regular expression 
### Back-references
None are used in this regular expression 
### Look-ahead and Look-behind
None are used in this regular expression 
## Author

My name is Richard Mutunzi a full stack web developer based in Nashville,TN . For anymore question kindly check my Github Profile: https://github.com/muturich/magical_tutorial
