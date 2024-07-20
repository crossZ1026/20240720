# GITHUB: markdown
- 請幫我完成9*9乘法表的X程式設計
## C：請幫我完成9*9乘法表的X的程式設計
- [online c](https://www.programiz.com/c-programming/online-compiler/)
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
- ![image](https://github.com/user-attachments/assets/44fbbd7d-c566-4d6a-b1e4-d9e91dfe47cf)
## C++：請幫我完成9*9乘法表的C++程式設計
- [online c++](https://www.programiz.com/cpp-programming/online-compiler/)
```c++
#include <iostream>
#include <iomanip> // 用於設定輸出的格式

int main() {
    // 使用兩層迴圈來列印9x9乘法表
    for (int i = 1; i <= 9; i++) {
        for (int j = 1; j <= 9; j++) {
            // 使用setw來設定輸出寬度，使表格對齊
            std::cout << std::setw(4) << i * j;
        }
        std::cout << std::endl; // 換行
    }

    return 0;
}

```
- ![image](https://github.com/user-attachments/assets/a6ccb4ce-f4d3-4155-a1e4-2d578d6ca047)

  
