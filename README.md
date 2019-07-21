# Get Next Line

C function that takes a file descriptor and pointer to C character strings.
This function fills the character string given as an argument with a line on 

  - A function that returns a line read from a file descriptor.
  - The return value can be 1, 0 or -1 depending on whether a line has been read,
when the reading has been completed, or if an error has happened respectively.

### Use

```C
make -C libft
gcc /path/to/C/file/*.c get_next_line.c -I get_next_line.h -lft -L libft
```
