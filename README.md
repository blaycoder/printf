# C - printf project.
## Contributors ##
* Onatola Ayomide
* Mojolaoluwa Fadahunsi

# The project consists of normal functions, derived functions a man page and a README.md file.

This produces output according to a format specifiers,as shown below.

~~~
_printf("Length:[%d, %i]\n", len, len);

printf("Length:[%d, %i]\n", len2, len2);

_printf("Negative:[%d]\n", -762534);

printf("Negative:[%d]\n", -762534);

_printf("Unsigned:[%u]\n", ui);

printf("Unsigned:[%u]\n", ui);

_printf("Unsigned octal:[%o]\n", ui);

printf("Unsigned octal:[%o]\n", ui);

_printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);

printf("Unsigned hexadecimal:[%x, %X]\n", ui, ui);

_printf("Character:[%c]\n", 'H');

printf("Character:[%c]\n", 'H');

_printf("String:[%s]\n", "I am a string !");

printf("String:[%s]\n", "I am a string !");

_printf("Address:[%p]\n", addr);

printf("Address:[%p]\n", addr);

len = _printf("Percent:[%%]\n");

len2 = printf("Percent:[%%]\n");

_printf("Len:[%d]\n", len);

printf("Len:[%d]\n", len2);

_printf("Unknown:[%r]\n");

~~~

## Files contained in this repository ##

| Name | Information | Relevant Files
| ----------- | ---------- |:-----------:|
| man_3_printf | Man page of the _printf() function. | None
| main.h Header | file with the data type struct, standard libraries and custom prototypes. *.c compilation

| printf.c | Main printf function file. Calls other functions.
| printf(name of var).c file

| print_numbers.c | Contains decimal and integer functions. None

| print_chars.c | Custom function for char data type. None

| printf_sting.c | Function that calls string type variable. None

| printf_oct.c | Functions that returns octal number. None

| printf_hex.c | Calls hexadecimal numbers (lowercase). None

| printf_HEX.c | Calls hexadecimal numbers (Uppercase). None

| printf_unsigned.c Returns an unisgined data type. None
| print_unsigned_int.c | contains the functions print_u, print_o, and print_b, which handle the conversion specifiers u, o, and b, respectively, | None
| printf_srev.c | Returns a string in reverse. | None
| print_rot13.c | Returns a string in Rot13. | None
| printf_str.c | Auxiliary functions such as strlen and strcpy. | None
| _putchar.c | Custom putchar function. | None

## Handle the following custom conversion specifier S :
prints the string. Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters).

#How is the world ruled and led to war?
Diplomats lie to journalists and believe these lies when they see them in printHandle the following conversion specifier:
* p

The big print gives and the small print takes away Handle the following flag characters for non-custom conversion specifiers:

´+´ space ´#´ Sarcasm is lost in print Handle the following length modifiers for non-custom conversion specifiers:

l h Conversion specifiers to handle: d, i, u, o, x, X Print some money and give it to us for the rain forests Handle the field width for non-custom conversion specifiers.

The negative is the equivalent of the composer's score, and the print the performance Handle the precision for non-custom conversion specifiers.

It's depressing when you're still around and your albums are out of print Handle the 0 flag character for non-custom conversion specifiers.

Every time that I wanted to give up, if I saw an interesting textile, print what ever, suddenly I would see a collection Handle the - flag character for non-custom conversion specifiers.

Print is the sharpest and the strongest weapon of our party Handle the following custom conversion specifier:

r : prints the reversed string The flood of print has turned reading into a process of gulping rather than savoring Handle the following custom conversion specifier:

R: prints the rot13'ed string * All the above options work well together.