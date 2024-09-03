all: equivalent
equivalent: equivalent.cpp
	g++ -o equivalent .\equivalent.cpp
dump: equivalent
	objdump -d equivalent > equivalent.asm
clean:
	rm -f equivalent equivalent.asm
run: equivalent
	./equivalent