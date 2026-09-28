# Strings

Strings are sequence of characters written inside quotes. It can include letters, numbers, symbols and spaces.

- A single character is treated as a string of length one.
- Strings are commonly used for text handling and manipulation.

**Syntax of String Slicing**\
`substring = s[start:end:step]`

**Parameters:**\
s = Original string\
start = Starting index (inclusive)\
end = Stopping index (exclusive)\
step = Interval between indices. A positive value slices from left to right, while a negative value slices from right to left.

**Creating a String**\
Strings can be created using either single ('...') or double ("...") quotes. Both behave the same.

**Multi-line Strings**\
Use triple quotes ('''...''' ) or ( """...""") for strings that span multiple lines.

## **Accessing Characters in String**

Strings are indexed sequences. Positive indices start at 0 from the left, negative indices start at -1 from the right.

## **String Length**

To get the length of a string, `len()` function is used.

## **String Slicing**

Slicing is a way to extract a portion of a string by specifying the start and end indexes. The syntax for slicing is string[start:end], where start starting index and end is stopping index (excluded).

**1. Slice From the Start**\
If we leave out the starting index, the range will start at the first character.

**2. Slice To the End**\
If we leave out the ending index, the range will go to the end.

**3. Negative Indexing**\
Negative indexes are used to start the slice from the end of the string.

## **Formatting a String**

**1. Using f-strings:** \
f-strings allows to directly insert variables and expressions inside a string using {} brackets.

**2. Using format:** \
format() method allows inserting values into placeholders {} inside a string.

**3. Placeholder** \
A placeholder can contain variables, operations, functions, and modifiers to format the value.

**4. Modifier** \
A modifier is included by adding a colon : followed by a legal formatting type, like .2f which means fixed point number with 2 decimals.

## **String Methods**

| Method | Description |
|---|---|
| capitalize() | Converts the first character to upper case |
| casefold() | Converts string into lower case |
| center() | Returns a centered string |
| count()	| Returns the number of times a specified value occurs in a string |
| encode() | Returns an encoded version of the string |
| endswith() | Returns true if the string ends with the specified value |
| expandtabs() | Sets the tab size of the string |
| find() | Searches the string for a specified value and returns the position of where it was found |
| format() | Formats specified values in a string |
| format_map() |Formats specified values from a dictionary in a string |
| index()	| Searches the string for a specified value and returns the position of where it was found |
| isalnum()	| Returns True if all characters in the string are alphanumeric |
| isalpha()	| Returns True if all characters in the string are in the alphabet |
| isascii()	| Returns True if all characters in the string are ascii characters |
| isdecimal()	| Returns True if all characters in the string are decimals |
| isdigit()	| Returns True if all characters in the string are digits |
| isidentifier() | Returns True if the string is an identifier |
| islower()	| Returns True if all characters in the string are lower case |
| isnumeric()	| Returns True if all characters in the string are numeric |
| isprintable()	| Returns True if all characters in the string are printable |
| isspace()	| Returns True if all characters in the string are whitespaces |
| istitle()	| Returns True if the string follows the rules of a title |
| isupper()	| Returns True if all characters in the string are upper case |
| join() | Converts the elements of an iterable into a string |
| ljust()	| Returns a left justified version of the string |
| lower()	| Converts a string into lower case |
| lstrip() | Returns a left trim version of the string |
| maketrans()	| Returns a translation table to be used in translations |
| partition()	| Returns a tuple where the string is parted into three parts |
| replace()	| Returns a string where a specified value is replaced with a specified value |
| rfind()	| Searches the string for a specified value and returns the last position of where it was found |
| rindex() | Searches the string for a specified value and returns the last position of where it was found |
| rjust()	| Returns a right justified version of the string |
| rpartition() | Returns a tuple where the string is parted into three parts |
| rsplit() | Splits the string at the specified separator, and returns a list |
| rstrip() | Returns a right trim version of the string |
| split()	| Splits the string at the specified separator, and returns a list |
| splitlines() | Splits the string at line breaks and returns a list |
| startswith() | Returns true if the string starts with the specified value |
| strip()	| Returns a trimmed version of the string |
| swapcase() | Swaps cases, lower case becomes upper case and vice versa |
| title() | Converts the first character of each word to upper case |
| translate()	| Returns a translated string |
| upper()	| Converts a string into upper case |
| zfill()	| Fills the string with a specified number of 0 values at the beginning |
