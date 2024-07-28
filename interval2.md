#include <stdio.h>

int main() {
   int n, x, c, i, o;

   scanf("%d", &n);

   c = 0;
   i = 0;
   o = 0;

   while (c != n) {
        scanf("%d", &x);

        if (x>=10 && x<=20)
            i = i + 1;
        else
            o = o + 1;

        c = c + 1;
   }

   printf("%d in\n", i);
   printf("%d out\n", o);

    return 0;
}
