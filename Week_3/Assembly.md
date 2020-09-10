# Assembly
```
AT&T Syntax

<instruction>    <source operand>,<destination operand>

```

```
Intel Syntax

<instruction>    <destination operand>,<source operand>

```
Little endian

```
0x12345678 it really looks like this 0x78564312

```
EFLAGS link 
https://faculty.kfupm.edu.sa/COE/aimane/assembly/pagegen-31.aspx.htm


INTEL MANUAL
Link: https://software.intel.com/sites/default/files/managed/39/c5/325462-sdm-vol-1-2abcd-3abcd.pdf

ASSEMBLY INSTRUCTIONS

in assembly [note].     note = 'hello'


```

global _start

section .text

_start:

    ; MOV examples
    mov    ebx,eax
    mov    ecx,[ebx]
    mov    eax,2
    mov    edx,0x0a
    
     ; LEA and XCHG examples
    lea    eax,[ecx+4]
    xchg   edi,esi

    ; PUSH and POP examples
    push   edi
    pop    esi

    ; XOR, AND, OR examples
    xor    eax,eax
    and    ah,al
    or     bx,bx
    or     cx,0xfff 
    
      ; ADD examples
    add    ebx,eax
    add    bx,ax
    add    bh,bl
    add    ecx,0x2

    ; SUB examples
    sub    edx,ecx
    sub    dx,cx
    sub    dh,dl
    sub    ecx,0x2
    
    
     ; INC examples
    inc    eax
    inc    al
    inc    [ax]

    ; DEC examples
    dec    ebx
    dec    bl
    dec    [bx]
    
    ```
    STACK has basically two operations PUSH and POP
    Push onto a stack and Pop off the stack
    
LIFO - last in first out

    
    
    
    
    
    
    
    
    
    
    
    
