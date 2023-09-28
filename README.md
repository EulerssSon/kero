# this is a command to boost ur time and donot forget any file
# it will be updated after every task

 touch 0-puts_recursion.c  1-print_rev_recursion.c  2-strlen_recursion.c  3-factorial.c  4-pow_recursion.c  5-sqrt_recursion.c  6-is_prime_number.c  100-is_palindrome.c  101-wildcmp.c


touch {0..6}main-c &&  touch {100..101}-main.c

#FOR MAIN.H
 #ifndef MAIN_H
#define MAIN_H

#include <stdio.h>
 void _puts_recursion(char *s);
 void _print_rev_recursion(char *s);
 int _strlen_recursion(char *s);
 int factorial(int n);
 int _pow_recursion(int x, int y);
 int _sqrt_recursion(int n);
 int is_prime_number(int n);
 int is_palindrome(char *s);
 int wildcmp(char *s1, char *s2);
 int _putchar(char c);
#endif

#include <unistd.h>

/**
 * _putchar - writes the character c to stdout
 * @c: The character to print
 *
 * Return: On success 1.
 * On error, -1 is returned, and errno is set appropriately.
 */
int _putchar(char c)
{
	return (write(1, &c, 1));
}
