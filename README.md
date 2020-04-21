# CS50-Problem-Set-1-Hello
CS50 Problem Set 1 Hello
// A program that says hello.

#include <stdio.h>
#include <cs50.h>

int main(void)
{
    string name = get_string("What is your name?\n");
    printf("hello, %s\n", name);
}
