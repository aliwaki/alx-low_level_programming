this is all about c programming
#include <stdio.h>
/**
 * main - A program that prints the size of various computer types
 * Return 0 (Success)
 */
int main(void)
{
        char a;
        int b;
        long int c;
        long long int d;
        float f;

printf("size of the char: %lu byte(s)/n", (unsigned long)sizeof(a));
printf("size of the int: %lu byte(s)/n", (unsigned long)sizeof(b));
printf("size of the long int: %lu byte(s)/n", (unsigned long)sizeof(c));
printf("size of the long long int: %lu byte(s)/n", (unsigned long)sizeof(d));
printf("size of the float: %lu byte(s)/n", (unsigned long)sizeof(f));
return (0);
} 
gcc -S -masm=intel $CFILE:Write a script that generates the assembly code (Intel syntax) of a C code and save it in an output file.
#include<unistd.h>

/**
  *main - Our starting point
  *
  *Description: Print a string without using printf & puts
  *
  *Return: 1 to signify success
  */

int main(void)
{

	write(2,
			"and that piece of art is useful\" - Dora Korpar, 2015-10-19\n",
		  59);

	return (1);
}
