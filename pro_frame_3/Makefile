
CC=gcc
CFLAGS= -I include/
LDFLAGS= -L lib/ -Wl,-rpath,$(shell pwd)/lib   #这个-Wl,-rpath,一定不能漏掉
LOADLIBES= #abort
LDLIBS=-lcollection

# 其生成命令： 
# “$(CC) –c $(CPPFLAGS) $(CFLAGS)”
# “$(CC) $(LDFLAGS) <n>;.o $(LOADLIBES) $(LDLIBS)”。


aaa%:%.o
	$(CC) -c $(CFLAGS) $*.c
	$(CC) $(LDFLAGS) $^ $(LOADLIBES) $(LDLIBS) -o $@


aaamain:main.o




.PHONY:clean
clean:
	rm *.o
	rm ckx_main
