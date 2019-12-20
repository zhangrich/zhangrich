[TOC]

## 数组的复习

### 数组的拷贝 :100:

代码

```java
    public static void copy() throws Exception {
        String[] src = {"a", "b", "c", "d"};
        String[] dest = new String[4];

        //将src中的b和c复制到dest的[1]和[2]位置

        System.arraycopy(src, 1, dest, 1, 2);

        System.out.println(Arrays.toString(dest));
    }
```

```go
package main

import “fmt”
//go 代码
func main(){
    fmt.Println("hello world")
}
```

