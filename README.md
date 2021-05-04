The prototype of ft_printf is int ft_printf(const char *, ...);
Recoded libc’s printf function
It doesn't do the buffer management like the real printf
It manages the following conversions: cspdiuxX%
It manages any combination of the following flags: ’-0.*’ and minimum field
width with all conversions
Our make file creates library libftprintf.a. To see results you can create your main in ft_printf.c and run that file to see results.
