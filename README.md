# EXPERIMENT 01 ALP FOR 8086
Name : SRIVATSAN G

Ref no : 212223230216

Date of experiment :

## Aim:
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required:
 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory.
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window).It has green color logo.  
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,DIVISION,AND,OR,NOT AND XOR operations 
4.	 Compile the program and check for the errors.
5.	Run (once there is no syntax error).
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table.
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)
8.	Click on emulate to start emulation.
   
![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

9.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below.

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

## Addition  of 8 bit numbers ALP 
```assembly
MOV AL,88H
MOV BL,65H
ADD AL,BL
HLT
```
## Output  
![image](https://github.com/user-attachments/assets/b63641fe-9601-4058-a0d8-25b9187b9f16)

## Subtraction  of 8 bit numbers  ALP 
```assembly
MOV AL,84H
MOV BL,63H
SUB AL,BL
HLT
``` 
## Output 
![image](https://github.com/user-attachments/assets/b99c5407-2193-4a7c-8b4d-9750af3cf086)

## Multiplication of 8 bit numbers  ALP
```assembly
MOV AL,75H
MOV BL,32H
MUL BL
HLT
```
## Output  
![image](https://github.com/user-attachments/assets/ca1160c1-30b6-4ba2-b927-d22ff0e92ca4)

## Division of 8 bit numbers  ALP
```assembly
MOV AL,68H
MOV BL,18H
DIV BL
HLT
```
## Output  
![image](https://github.com/user-attachments/assets/2aea426f-9cce-46a8-b40d-108f44fcf89f)

## And of 8 bit numbers ALP
```assembly
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/77a223dd-59b0-47c6-9e0b-62f0b7630ce2)

## OR of 8 bit numbers ALP
```assembly
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/c25e7f98-4226-4f3e-a16f-97d2e380e101)

## NOT of 8 bit number ALP
```assembly
MOV AL,65H
NOT AL
HLT
```
## Output
![image](https://github.com/user-attachments/assets/871cea8f-477b-45a8-a9dd-da109e0c2705)

## XOR of 8 bit number ALP
```assembly
MOV AL,66H
MOV BL,77H
XOR AL,BL
HLT
```

## Output
![image](https://github.com/user-attachments/assets/eaf9b470-2000-46bf-80b7-999ac66e2b83)

## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








