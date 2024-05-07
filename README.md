# EXPERIMENT--01-ALP-FOR-8086
### Name :Pravin Raj A
### Roll no : 212222240079
### Date of experiment :

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	 Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 

3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

9.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h
mov AL,59h;
mov BL,79h;
ADD AL,BL;
HLT
ret
```
## Output  
 ![Screenshot 2024-03-19 181900](https://github.com/Saravana-kumar369/EXPERIMENT--01-ALP-FOR-8086/assets/117925254/12cff806-9a6f-4c8e-b70d-f4072e554b8f)

## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h
mov AL,83h;
mov BL,33h;
SUB AL,BL;
HLT
ret
```
## Output  
![Screenshot 2024-03-19 182631](https://github.com/Saravana-kumar369/EXPERIMENT--01-ALP-FOR-8086/assets/117925254/e6c81de2-1cfc-44a6-a28e-d419aef37f3b)

## Multiplication alp 
```
org 100h
mov AL,75h;
mov BL,12h;
MUL BL;
HLT
ret
```
 ## Output  
![Screenshot 2024-03-19 183050](https://github.com/Saravana-kumar369/EXPERIMENT--01-ALP-FOR-8086/assets/117925254/e4f86edb-6f72-4de5-bc18-76463f6f3be1)

## Division alp 
```
org 100h
mov AL,65h;
mov BL,15h;
DIV BL;
HLT
ret
```
## Output  
![Screenshot 2024-03-19 183329](https://github.com/Saravana-kumar369/EXPERIMENT--01-ALP-FOR-8086/assets/117925254/8e6afe1b-a76c-44fc-ba9c-40e33d633386)

## Programs for logical operations
## AND
```
org 100h
mov AL,66h;
mov BL,70h;
AND AL,BL;
HLT
ret
```
## Output  

![Screenshot 2024-03-19 175618](https://github.com/Saravana-kumar369/EXPERIMENT--01-ALP-FOR-8086/assets/117925254/2e28febb-74e4-4dd7-a27c-e595747c151d)

## OR
```
org 100h
mov AL,66h;
mov BL,70h;
OR AL,BL;
HLT
ret
``` 
## Output
![Screenshot 2024-03-19 175801](https://github.com/Saravana-kumar369/EXPERIMENT--01-ALP-FOR-8086/assets/117925254/b97bac58-42ed-4d66-b80e-0b8ae4b3b8b3)

## NOT
```
org 100h
mov AL,66h;
NOT AL;
HLT;
ret
```
## Output  
![Screenshot 2024-03-19 180312](https://github.com/Saravana-kumar369/EXPERIMENT--01-ALP-FOR-8086/assets/117925254/61616ca5-60fd-490d-98eb-5a39b1e35df3)

## XOR 
```
org 100h
mov AL,66h;
mov BL,70h;
XOR AL,BL;
HLT
ret
```
## Output  
![Screenshot 2024-03-19 181006](https://github.com/Saravana-kumar369/EXPERIMENT--01-ALP-FOR-8086/assets/117925254/5f39f2c3-0492-4842-9480-f4f07edfb90c)

## Result :
 Thus the  ALP on fundamental arithmetic and logical operations executed successfully.
