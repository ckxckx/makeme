
CC=gcc
CFLAGS= -I include/
LDFLAGS= -L lib/ -Wl,-rpath,$(shell pwd)/lib   #这个-Wl,-rpath,一定不能漏掉
LOADLIBES= #abort
LDLIBS=-lcollection

# 其生成命令：
# “$(CC) –c $(CPPFLAGS) $(CFLAGS)”
# “$(CC) $(LDFLAGS) <n>;.o $(LOADLIBES) $(LDLIBS)”。

main:main.o




.PHONY:clean echome
clean:
	rm *.o
	rm main
echome:
	@echo $(LDFLAGS)
