# PalindromeNASM_LINUX32
NASM homework assignment, test if input is a "palindrome"

To compile on 64bit linux:

nasm -f elf32 Palindrome.asm

ld -m elf_i386 Palindrome.o io.o

----
Instituto Tecnológico de Costa Rica - 2015
