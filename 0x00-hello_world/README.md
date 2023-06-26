this is about C programming
gcc -c $CFILE: script that compiles a C file but does not link.
gcc -S $CFILE: generates the assembly code of a C code and save it in an output file.
gcc $CFILE -o cisfun:script that compiles a C file and creates an executable named cisfun.
#include<stdio.h>

/**
  *main - Starting point
  *
  *Description: The puts function will print the string of characters
  *in the brackets
  *
  *Return: Always 0
  */

int main(void)
{
	puts("\"Programming is like building a multilingual puzzle");

	return (0);
}
