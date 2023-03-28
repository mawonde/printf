

0. # I'm not going anywhere. You can print that wherever you want to. I'm here and I'm a Spur for life

### Write a function that produces output according to a format.

Prototype: int _printf(const char *format, ...);
Returns: the number of characters printed (excluding the null byte used to end output to strings)
write output to stdout, the standard output stream
format is a character string. The format string is composed of zero or more directives. See man 3 printf for more detail. You need to handle the following conversion specifiers:
```
c
s
%
```

- #### Print Character Function (print_chr)

##### Resources
1. https://www.academia.edu/10297206/Secrets_of_printf_  // for format specifiers
2. ``` man 2 write ```  // buf
3. Variadic Functions  // man 3 va_start
4. https://gcc.gnu.org/onlinedocs/gcc/Warning-Options.html

