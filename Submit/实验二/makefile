fat12:main.c my_print.o
	gcc -o fat12 main.c my_print.o
my_print.o:my_print.asm
	nasm -f elf -o my_print.o my_print.asm
clean:
	rm -f my_print.o fat12
