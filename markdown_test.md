# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

内联代码： a paragraphg with inline code `{code: 0}`。

**加粗**。

*倾斜*

超链接： [Github](https://github.com/Guanngxu/guanngxu-lyric-markdown-preview)

表格示例：

| Header 1 | Header 2 |
| --- | --- |
| Key 1 | Value 1 |
| Key 2 | Value 2 |
| Key 3 | Value 3 |

数学公式示例：

$$
f(x)=2x+1 \\
=2+1 \\
=3
$$

代码块示例：

```cpp
#include <stdio.h>

const int MAX = 10;
int cache[MAX] = {0};

int fib(int x) {
  if (x == 1) return 1;
  if (x == 0) return 0;
  if (cache[x] == 0) {
    int ret = fib(x - 1) + fib(x - 2);
    cache[x] = ret;
  }
  return cache[x];
}

int main() {
    int i;
    printf("fibonacci series:\n");
    for (i = 0; i < MAX; ++i) {
        printf("%d ", fib(i));
    }
    return 0;
}
```

图片：![githubusercontent](https://avatars.githubusercontent.com/u/24446756?s=100&v=4)