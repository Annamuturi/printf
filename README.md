 - printf

ABOUT THE PROJECT:

This is a recreation of the standard library function printF
The function writes output to standard output.
the project callss in various variadic function
The project was done as a team work with two contributor Austine Maina and Anna Muturi with the intension of learning about team collaboration using git and also enabling work flow with so many files.

DESCRIPTION
The function _printf uses  the prototype int _printf(const char *format, ...);. The format is a character string. The format string is composed of zero or more directives.See man 3 printf for more detail.

Conversation Specifiers
A conversion specifier begins with the percent sign (%) and is followed by one or more characters that specify the data type to be displayed or read.

d,i
the int argument is converted to signed decimal notation
Example Main.c
int main(void)
{
_printf("%d\n", 7);
}

output 
7
 
flag character
a flag character  is usually placed immediately after the percent sign (%) that introduces the conversion specifier in a format string.
'-' (hyphen): left-justify the output or input field
'0' (zero): pad the output or input field with zeroes instead of spaces
'#' (hash): add a prefix or suffix to the output, or modify the formatting of certain types of data
' ' (space): add a space before a positive number in the output

example main.c
int main(void)
{_printf("%#x\n" 7);
}

output
0x7

TASKS
Write a function that produces output with conversion specifiers c, s, and %.
Handle the following conversion specifiers: d, i.
create a man page for your function
Handle the following custom conversion specifiers: b
Handle the following conversion specifiers: u, o, x, X
Use a local buffer of 1024 chars in order to call write as little as possible.
Handle the following custom conversion specifier: S
Handle the following conversion specifier: p
Handle the following flag characters for non-custom conversion specifiers: + Space, and # for non-custom conversion specifiers.
Handle the following length modifiers for non-custom conversion specifiers: L and H
Handle the 0 flag character for non-custom conversion specifiers.
Handle the - flag character for non-custom conversion specifiers.
Handle the following custom conversion specifier: R : prints the reversed string

AUTHORS
Austine Maina
Anna Muturi
