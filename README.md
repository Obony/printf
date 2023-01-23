##**ALX Software Enginering Printf Team Project**

This team project is a custom made printf function for the C programming language called _printf. It has been optimized to take various inputs and optional arguments based exactly on how the standard library function printf works. We submitted this as part of the ALX software engineering course requirement for grading.

*Synopsis*

 - This function _printf() writes output to stdout, the standard output stream with the format and options without making use of any of the standard library files. It was written to use a local buffer of 1024 bytes when printing although it can print larger sets of data.

 - The _printf() function returns the total number of characters printed to the stdout(excluding the null byte at the end of strings) after a successful execution.

 - If an output error is encountered, a negative value of -1 is returned.

 - The prototype of this function is: **int _printf(const char format, ...)**;

 - This means that it has one mandatory format argument, and an extra number of arguments that can be none, or many.

 - Format of the format string

 - The format string is a character string starting and ending with double quotes. The format string is composed of zero or more directives; ordinary characters (not %), and conversion specifications, each of which results in fetching zero or more subsequent arguments.

 - Each conversion specification is introduced by the character % and ends with a conversion specifier. In between there may be (in this order):

| Zero or more flags

| An optional field width

| An optional precision modifier

| An optional length modifier

The flag characters

| Flag | Description |
| --------| ------------ |
| # | For o conversions the first character of the output string is made zero (by prefixing a 0 if it was not zero already). For x and X conversions, a nonzero result has the string "0x" or "0X" respectively added. |
| 0 | (Not implemented yet) The value should be zero padded. For d, i, o, u, x, and X the converted value is padded on the left with zeros. If the 0 and - flags both appear,the 0 flag is ignored. If a precision is given with a numeric conversion, the 0 flag is ignored. |
| - | (Minus sign, not implemented yet) The converted value is to be left adjusted on the field boundary, (Default is right justification) and padded with blanks in the right rather than on the left with blanks or zeros. This flag overrides 0 if both are given. |
| ' ' | (Blank Space) The argument is padded with a single blank space before a positive number or empty string produced by a signed conversion. |
| + | A sign (+ or -) should always be placed before a number produced with a signed conversion. By default, only negative numbers have this sign. |

Creating Myown printf in C


AUTHORS
 - LYDIA KAMUYU
 - FAITH NYABERI

