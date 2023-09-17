# Regex for Phone Number Identification

A regular expression, often abbreviated as regex, is a string of characters that specifies a search pattern for text. Regex uses 'literal characters' to pinpoint specific characters or patterns you want to locate within a text.

## Summary

Regex: /^\b\d{3}[-.]?\d{3}[-.]?\d{4}\b$/

With the regex expression above you can match many of the commonly used numbers such as 305-123-4567 for example.

## Table of Contents

- [Explanation](#explanation)
- [Components](#components)
- [Examples](#examples)


## Explanation

## Components

/^ - This is the starting anchor that initiates

\b\d{3} - This section begins with a word boundary to tell regex to match the alpha-numeric characters. It then matches 3 of any digit between 0-9 followed by either a hyphen, a period, or nothing [-.]?.

\d{3} - The second section is quite similar to the first section, it matches 3 digits between 0-9 followed by another hyphen, period, or nothing [-.]?.

\d{4}\b - Lastly, this section is slightly different in that it matches 4 digits instead of three. The word boundary assertion is also used at the end of the expression.

$/ - This is the ending anchor that finalizes

## Examples

Therefore, with the above regex expression for finding phone numbers, it would identify a number in the format of 123-123-1234, 123.123.1234, or 1231231234.

## Author

I'm Pete Tookey, and I'm a student web developer with a deep passion for crafting digital experiences. My journey involves mastering the art of web development, where I blend my creative eye for design with coding expertise. My goal is to create websites that not only look great but also offer a seamless user experience. Beyond coding, I love staying updated with the latest web development trends and continuously expanding my skillset. Join me as I explore the exciting world of web development!
