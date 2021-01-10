# numerative text converter
This program is a python3 implementation of a numerative text converter which implements two main functions:
- convert a text as string to a base 32 decimal number (which can be VERY large)
- convert a decimal number to text, based on the same given base 32 alphabet as above\n

Furthermore this program can also be used with other (also larger or smaller alphabets), the preset however is the base 32 alphabet from 0 to 9 and from a to v.

# How to convert text into a number:
`python3 b32converter.py "text"`

# How to convert a number back into text:
`python3 b32converter.py 1234567890`


# Additional information: 
- The letters of the text which is supposed to be converted will be __interpreted as lowercase__.
- __Any other characters__ which are not listed in the alphabet (for instance the letters w, x, y, z or any other characters than letters or numbers), they __will be replaced with a 0__. 