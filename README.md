# EXPERIMENT--01-ALP-FOR-8086
### Name : ARULARASI U
### Roll no : 212223100002 
### Date of experiment : 20.08.2025

## Aim
To Write and execute ALP on fundamental arithmetic and logical operations

## Components required
8086  emulator 

## Theory 
EMU8086 → Emulator of Intel 8086 microprocessor (AMD compatible).
Has a built-in assembler and tutorials for beginners.
Runs on PC desktops and laptops.
Emulates hardware → CPU, RAM, I/O devices, memory, display screen.
Main Uses → Assembly programming, reverse engineering, hardware architecture learning, creating small OS.
Execution → Can run in forward or backward mode, supports step-by-step execution.
Displays → Registers, memory, stack, variables, flags.
User Interface:
Buttons: Load, Reload, Step Back, Single Step, Run.
Menu: File, View, Virtual Devices, Virtual Drive, Help.
Registers panel (H/L).
Right-side panel for Reset, Debug, Flags, etc.

 ## Running the Emulator :
1. Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)














9.	Click on emulate to start emulation



![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)











10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below
11.	
![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)




## ARITHMETIC OPERATORS
## Addition  
```
MOV AX,0F0Eh
MOV BX,808Eh
ADD AX,BX
``` 
<img width="1919" height="1079" alt="Screenshot 2025-08-20 102149" src="https://github.com/user-attachments/assets/bc293a74-52b4-49e2-91e3-2ea17c1da9a1" />

## Subtraction  
```
MOV AX,0F0Eh
MOV BX,4040h
SUB AX,BX
```  
<img width="1919" height="1079" alt="Screenshot 2025-08-20 102516" src="https://github.com/user-attachments/assets/06485051-3cf2-43a2-b7db-a27d622d2eea" />

## Multiplication 
```
org 100h
MOV AX,0F0Eh
MOV BX,4040h
MUL AX
HLT
ret
``` 
<img width="1919" height="1079" alt="Screenshot 2025-08-20 102743" src="https://github.com/user-attachments/assets/d1cc76fa-c8aa-4ba1-a0a4-73290f57ca4c" />

## Division 
```
MOV AX,0F0Eh
MOV BX,4040h
DIV AX
HLT
ret 
```
<img width="1919" height="1079" alt="Screenshot 2025-08-20 102855" src="https://github.com/user-attachments/assets/424f2732-08d1-4580-9b41-91cd3f6adff2" />

## LOGICAL OPERATORS
## AND
```
MOV AX,0F0Eh
MOV BX,4040h
AND AX,BX
```
<img width="1919" height="1079" alt="Screenshot 2025-08-20 103048" src="https://github.com/user-attachments/assets/6824aa8c-f0f7-41be-ba02-3c1282643bbb" />

## OR
```
MOV AX,0F0Eh
MOV BX,4040h
OR AX,BX
```
<img width="1919" height="1079" alt="Screenshot 2025-08-20 103125" src="https://github.com/user-attachments/assets/935a17a3-52bc-49d5-a735-b830c5a9c69d" />

## XOR
```
MOV AX,0F0Eh
MOV BX,4040h
XOR AX,BX
```
<img width="1919" height="1079" alt="Screenshot 2025-08-20 103307" src="https://github.com/user-attachments/assets/4d63b0b2-49d4-44e1-8532-5174813b363f" />

## NOT
```
MOV AX,OFOEh
NOT AX
```
<img width="1919" height="1079" alt="Screenshot 2025-08-20 103206" src="https://github.com/user-attachments/assets/293791f8-0dc0-4664-a3c0-84891a532b5b" />

## Result :
 
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.






