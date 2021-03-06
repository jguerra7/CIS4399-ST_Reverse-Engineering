# ASSEMBLY Crash course
* Hello World C code

![Screen Shot 2020-09-09 at 1 15 36 PM](https://user-images.githubusercontent.com/47218880/92637579-9f531c00-f29e-11ea-879c-ad0fbd7b08aa.png)

* Assembly generated by gcc for Hello World

![Screen Shot 2020-09-09 at 1 15 52 PM](https://user-images.githubusercontent.com/47218880/92637588-a24e0c80-f29e-11ea-8190-ba3cca1b0778.png)

# Assembly Instructions
![Screen Shot 2020-09-09 at 1 18 04 PM](https://user-images.githubusercontent.com/47218880/92637833-040e7680-f29f-11ea-9877-b77a83d75cbf.png)

## ATT vs INTEL


* ATT

![Screen Shot 2020-09-09 at 1 18 37 PM](https://user-images.githubusercontent.com/47218880/92637838-05d83a00-f29f-11ea-9b39-4e2a0932096f.png)


* INTEL

![Screen Shot 2020-09-09 at 1 18 42 PM](https://user-images.githubusercontent.com/47218880/92637851-08d32a80-f29f-11ea-8405-c4df108970e2.png)

# Structure of An x86 Instruction

![Screen Shot 2020-09-09 at 1 20 27 PM](https://user-images.githubusercontent.com/47218880/92638104-67000d80-f29f-11ea-99b6-1d27b82fe7b9.png)


* General purpose registers

![Screen Shot 2020-09-09 at 1 21 01 PM](https://user-images.githubusercontent.com/47218880/92638107-68c9d100-f29f-11ea-97e8-ad04f48ec913.png)
![Screen Shot 2020-09-09 at 1 21 11 PM](https://user-images.githubusercontent.com/47218880/92638110-69fafe00-f29f-11ea-9983-09973e8ed4eb.png)

# Common x86 Instructions

![Screen Shot 2020-09-09 at 1 23 13 PM](https://user-images.githubusercontent.com/47218880/92638356-c3632d00-f29f-11ea-9210-62e1556e4cf5.png)
![Screen Shot 2020-09-09 at 1 23 21 PM](https://user-images.githubusercontent.com/47218880/92638361-c4945a00-f29f-11ea-971e-a2bc3e0b3683.png)
![Screen Shot 2020-09-09 at 1 23 27 PM](https://user-images.githubusercontent.com/47218880/92638364-c5c58700-f29f-11ea-9f41-f1ebed9bc653.png)
![Screen Shot 2020-09-09 at 1 23 34 PM](https://user-images.githubusercontent.com/47218880/92638368-c78f4a80-f29f-11ea-92bd-85747ef94673.png)
![Screen Shot 2020-09-09 at 1 23 43 PM](https://user-images.githubusercontent.com/47218880/92638373-c9590e00-f29f-11ea-82c0-0f9dd2299806.png)
![Screen Shot 2020-09-09 at 1 23 50 PM](https://user-images.githubusercontent.com/47218880/92638732-59975300-f2a0-11ea-9377-6f30c185f6cd.png)
 


# Function Calls and Function Frames

* C function calls

![Screen Shot 2020-09-09 at 1 27 14 PM](https://user-images.githubusercontent.com/47218880/92638740-5e5c0700-f2a0-11ea-8df1-6a1d0e276c49.png)

* Assembly function calls

![Screen Shot 2020-09-09 at 1 27 25 PM](https://user-images.githubusercontent.com/47218880/92638744-6025ca80-f2a0-11ea-824b-b371bb083c4e.png)


# Conditional Jumps 

* Conditional branch in C

![Screen Shot 2020-09-09 at 1 30 32 PM](https://user-images.githubusercontent.com/47218880/92639002-d5919b00-f2a0-11ea-9a0d-21558576905e.png)


* Conditional branch in assembly

![Screen Shot 2020-09-09 at 1 30 51 PM](https://user-images.githubusercontent.com/47218880/92639005-d62a3180-f2a0-11ea-9f7a-28caf08cbc8a.png)


# Loops

* a while loop in C

![Screen Shot 2020-09-09 at 1 31 24 PM](https://user-images.githubusercontent.com/47218880/92639020-dc201280-f2a0-11ea-9642-a0205df6cf0a.png)


* a while loop in assembly

![Screen Shot 2020-09-09 at 1 31 32 PM](https://user-images.githubusercontent.com/47218880/92639024-dc201280-f2a0-11ea-9c60-370f6aa81cf6.png)




# THE PE FORMAT:



## THE MS-DOS HEADER AND MS-DOS STUB

THE PE SIGNATURE, FILE HEADER, AND OPTIONAL HEADER


![image](https://user-images.githubusercontent.com/47218880/92636773-85650980-f29d-11ea-8e9c-1fe2a0eada58.png)

```
objdump -x hello.exe

```
![Screen Shot 2020-09-09 at 1 33 49 PM](https://user-images.githubusercontent.com/47218880/92639268-2903e900-f2a1-11ea-81ca-685f21a0ccfe.png)
![Screen Shot 2020-09-09 at 1 34 02 PM](https://user-images.githubusercontent.com/47218880/92639273-2acdac80-f2a1-11ea-989d-5afab21ac852.png)



## The PE signature

## The PE File Header

## THe PE Optional Header

## Sections

![Screen Shot 2020-09-09 at 1 35 20 PM](https://user-images.githubusercontent.com/47218880/92639411-5e103b80-f2a1-11ea-9644-68ef86247e78.png)
![Screen Shot 2020-09-09 at 1 35 32 PM](https://user-images.githubusercontent.com/47218880/92639413-5f416880-f2a1-11ea-9924-b8b456e8b93b.png)

