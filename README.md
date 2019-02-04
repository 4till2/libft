# libft
A library of useful C functions authored by yserkez

## Description
The goal of this project is to recreate a library of useful functions to use throughout other projects. The library continues to grow as more projects are completed. 

The behaviour of all re-implementations of original C library functions follow their respective documentations. As for other I will try to add short descriptions here and more in depth with each file.

For a more thorough description and list of requirements (such as allowed functions) look at "libft.en.pdf".

### Functions
Listed below is each function that can be found in libft. At a later point I will include a description and their usage.

##### Original Library Functions:
`ft_memset`

`ft_bzero`

`ft_memcpy`

`ft_memccpy`

`ft_memmove`

`ft_memchr`

`ft_memcmp` 

`ft_strlen` 

`ft_strdup` 

`ft_strcpy`

`ft_strncpy`

`ft_strcat`

`ft_strncat` 

`ft_strlcat`

`ft_strchr` 

`ft_strrchr`

`ft_strstr` 

`ft_strnstr` 

`ft_strcmp` 

`ft_strncmp` 

`ft_atoi.c` 

`ft_isalpha`

`ft_isdigit` 

`ft_isalnum` 

`ft_isascii` 

`ft_isprint` 

`ft_toupper`

`ft_tolower`

##### Helper Functions:
`b_printf`

`ft_iswhite`

`ft_putchar` 

`ft_putnbr_fd`

`ft_strclr`

`ft_strjoinr` 

`ft_strsplit`

`b_putchar` 

`ft_itoa`

`ft_putchar_fd` 

`ft_putstr` 

`ft_strdel` 

`ft_strmap` 

`ft_strsub`

`b_putstr`

`ft_itoa_base` 

`ft_putendl`

`ft_putstr_fd`

`ft_strequ` 

`ft_strmapi` 

`ft_strtoupper`

`ft_chartostr` 

`ft_memalloc` 

`ft_putendl_fd` 

`ft_putstr_newline`

`ft_striter` 

`ft_strnequ` 

`ft_strtrim.c` 

`ft_countdigits`

`ft_memdel`

`ft_putnbr` 

`ft_strappend` 

`ft_striteri`

`ft_strnew` 

`ft_ftoa` 

`ft_nbrsize` 

`ft_putnbr_base`

`ft_strbin` 

`ft_strjoin`

`ft_strjoin2`

`ft_strrev` 

`ft_strncpyn` 

`ft_arrcdel`

`ft_printall`

`ft_indexof`

`ft_chrrp`

##### List Functions:
`ft_lstnew`

`ft_lstdelone`

`ft_lstdel`

`ft_lstadd`

`ft_lstiter`

`ft_lstmap`

##### Additional Funtions:
`ft_printf`

`get_next_line`

### Usage
```
$ make
```
Paste on top of your program.
```
#include "ft_libft.h"
```
Use in your program.
```
[function] [arguments ...];
```
Compile your program with executable.
```
gcc [yourprogram] libft.a
```
