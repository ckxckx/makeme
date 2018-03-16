# 注释

利用gcc完成编译
```
gcc src/main.c -I ./include -L./lib -lcollection -Wl,-rpath,`pwd`/lib -o main
```

---
