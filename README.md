This project recreates libc’s printf function.

The prototype of ft_printf is int ft_printf(const char *, ...).

It doesn't do the buffer management like the real printf, but manages the following conversions: cspdiuxX% and any combination of the following flags: ’-0.*’ and minimum field width with all conversions.

Our make file creates library libftprintf.a. To see results you can create your main in ft_printf.c and run that file to see results.
