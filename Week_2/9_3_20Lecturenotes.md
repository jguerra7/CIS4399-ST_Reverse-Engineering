# Intro to C and Assembly
C is not object oriented, it known as a low-level, procedural programming language
```c
//hello.c 				        //customary comment of program name

#include <stdio.h> 		    //needed for screen printing

main ( ) {				           //required main function
 printf("Hello Cardinal");  //simply say hello
 
}            		          	//exit program

```
** Example Hello2.c**
```c
//meet.c

#include <stdio.h>							 // needed for screen printing

greeting(char *temp1,char *temp2){ 			// greeting function to say hello

 char name[400]; 							// string variable to hold the name
 strcpy(name, temp2); 						// copy the function argument to name
 printf("Hello %s %s\n", temp1, name);		 //print out the greeting
}

main(int argc, char * argv[]){ 				//note the format for arguments
 greeting(argv[1], argv[2]); 				//call function, pass title & name
 printf("Bye %s %s\n", argv[1], argv[2]);	 //say "bye"
}											 //exit program
```

## Sample Program

## Compiling with gcc
* To compile from c to binary(exe in windows and .out in linux)
* gcc name.c -o name   // gcc name.c ( will give you the default a.out)
* to get the assembly from a c file: gcc -S name.c -> name.s ( assembly code)

## 
Memory

smallest amount data is a bit (1 or 0)

4 bits equals a nibble 

8 bits is a byte

2 bytes is a word

two words is a double word (DWORD)

two DWORDS is a quadword (QWORD)

ENDIANNESS 
```
LSB - least significant bit

MSB - most significant bit

organizing byte order

big endian
1,055   10 MSB and 55 LSB

little endian
55 LSB and 10 MSB
```
## Assembly sections
* .text secion

The .text section, also known as the code segment, basically corresponds to the .text portion of the binary executable file. It contains the machine instructions to get the task done. This section is marked as readable and executable and will cause an access violation if a write attempt is made. The size is fixed at runtime when the process is first loaded

* .data section
The .data section is used to store global initialized variables, such as
```
int a = 0; 

```
The size of this section is fixed at runtime. It should only be marked as readable.

* .bss section

The below stack section (.bss) is used to store certain types of global uninitialized variables, such as
```
int a; 
```
The size of this section is fixed at runtime. This segment needs to be readable and writable, but should not be executable.
in C programming: malloc(), realloc() and free() functions. 

* heap section 
The heap section is used to store dynamically allocated variables and grows from the lower-addressed memory to the higher-addressed memory

**pointers**
char *str; /// this is read as Give me 4 or 8 bytes called str which is a pointer to a character variable

## Registers
32bit registers E- registers EAX,ECX.....
64bit registers R- registers RAX, RCX.....
EFLAGS register... ZF, SF

## AT&T vs INTEL format (nasm)
NASM format  CMD <dest>,<source>      ; comment
AT&T format  CMD <source>, <dest>     # comment
  
AT&T format uses a % before registers; NASM does not. The % means “indirect operand.”
AT&T format uses a $ before literal values; NASM does not. The $ means “immediate operand.”
AT&T handles memory references differently than NASM.

 https://www.intel.com/content/www/us/en/architecture-and-technology/64-ia-32-architectures-software-developer-vol-1-manual.html
 
commands: operands
instructions on what to do with the data
mov :   mov <dest>,<source>    move eax, 51h ; comment
```      
      mov eax, 1234h  ; store teh value of 1234 (hex) into eax
      mov cs , ax   ; then copy the value of AX into CS.
```
### Other common operands 
```  
add
sub
jmp
jne
cmp
test
```


## Assembly File Structure

## Assembling

## Debugging with GDB

## Disassembly with GDB


## Convert number 42(base 10) to binary (base 2)?
101010

## 0x70 in hexidecimal, converted to an ASCII meaning? 
'p'


## bDNhcm5fdGgzX3IwcDM1
l3arn_th3_r0p35

















