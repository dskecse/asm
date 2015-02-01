all:
	nasm -f macho64 -o hello.o hello.asm
	ld -macosx_version_min 10.10 -e _start -o hello hello.o -lSystem

clean:
	rm hello hello.o
