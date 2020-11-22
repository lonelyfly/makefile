main : main.o add.o
	gcc main.o add.o -o main
main.o : main.c add.h
	gcc -c main.c -o main.o
add.o : add.c add.h
	gcc -c add.c -o add.o
.PHONY : clean
clean :
	rm -rf *.o main
