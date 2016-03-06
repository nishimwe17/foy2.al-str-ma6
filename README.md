#include <stdio.h>
int main()
{
  int c;
  c=getchar();
  while(c !=EOF)
  { 
    if (c>=97 && c<=122)
    c = c-32;
    putchar(c);
    c = getchar();
  }
  return 0;
}
