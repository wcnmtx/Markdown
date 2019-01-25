# Markdown语法


### 代码
```
public static Singleton getInstance() {  
       if (instance == null) {  
          synchronized (Singleton.class) {  
              if (instance == null) {  
                  instance = new Singleton();  
              }  
          }  
      }  
      return instance;  
  }
 ```
  
### 表格

语言|书籍|价格
-|:-|-
Java|编程思想|￥10
kotlin|Kotlin开发快速入门与实战|￥2


