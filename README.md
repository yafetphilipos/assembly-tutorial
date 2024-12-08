# Commands to run in Linux environment  
Assembly program to run 
## install package 
```
sudo apt-get install nasm gcc
```

## To run a program titled assembly.asm
```
nasm -f elf64 assembly.asm 
ld -s -o assembly assembly.o 
./assembly 
```

## all in one code 
```
nasm -f elf64 assembly.asm && ld -s -o assembly assembly.o  && ./assembly 
```
