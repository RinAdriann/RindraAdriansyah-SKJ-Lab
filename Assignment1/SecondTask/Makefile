all: mul_numbers

mul_numbers: mul_numbers.cpp
	g++ -o mul_numbers.exe mul_numbers.cpp

dump: mul_numbers
	objdump -d mul_numbers.exe > mul_numbers.asm

clean:
	del -f mul_numbers.exe mul_numbers.asm

run: mul_numbers
	mul_numbers.exe
