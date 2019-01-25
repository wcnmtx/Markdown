# Markdown语法

### 代码
```public static Singleton getInstance() {  
       if (instance == null) {  
          synchronized (Singleton.class) {  
              if (instance == null) {  
                  instance = new Singleton();  
              }  
          }  
      }  
      return instance;  
  }```
