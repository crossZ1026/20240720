# GITHUB: markdown

## C
```c
#include <stdio.h>

int main() {
    int i, j;

    // 列印99乘法表
    for (i = 1; i <= 9; i++) {
        for (j = 1; j <= 9; j++) {
            printf("%d * %d = %2d\t", i, j, i * j);
        }
        printf("\n");
    }

    return 0;
}


```
  
