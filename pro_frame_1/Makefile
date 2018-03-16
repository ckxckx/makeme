
# target:prerequests
	# command


myprog:src/main.o
	gcc src/main.o lib/libcollection.so -o myprog


src/main.o:src/main.c
	gcc -c src/main.c -o src/main.o -I include/


.PHONY:clean
clean:
	rm src/*.o
	rm myprog
