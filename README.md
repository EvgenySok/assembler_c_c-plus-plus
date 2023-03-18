# assembler_c_c-plus-plus

sudo apt-get -y install nasm
nasm -f elf print_hello_5.asm
ld -m elf_i386 print_hello_5.o -o print_hello_5
./print_hello_5
