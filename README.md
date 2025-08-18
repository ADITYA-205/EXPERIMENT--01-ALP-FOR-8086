# EXPERIMENT--01-ALP-FOR-8086
### Name : ADITYA S
### Roll no : 212223040007
### Date of experiment : 18-08-2025





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

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
mov al,74h
mov bl,69h
add al,bl
```


## Output  
 <img width="1919" height="1018" alt="image" src="https://github.com/user-attachments/assets/08cdaba4-a180-468b-b61e-38aa4b2d1e81" />

## Subtraction   of 8 bit numbers  ALP 
 ```
mov al,74h
mov bl,69h
sub al,bl
```
## Output  
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/38366fc3-a77a-4701-b2e4-9b8bf194169c" />

## Multiplication alp
```
mov al,74h
mov bl,69h
mul bl
```
 ## Output  
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/de06d4a4-19e2-420c-9b7b-b581c34477b9" />


## Division alp 
```
mov al,74h
mov bl,69h
div bl
```
## Output  
<img width="1919" height="1010" alt="image" src="https://github.com/user-attachments/assets/7d55efd2-fd91-4908-9725-68a1b37ead0b" />

## AND of 8 bit numbers ALP
```
mov al,74h
mov bl,69h
and al,bl
```
## Output
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/cd492b4a-e02b-4f69-924f-580242c0e3c3" />

## OR of 8 bit numbers ALP
```
mov al,74h
mov bl,69h
or al,bl
```
## Output
<img width="1919" height="1013" alt="image" src="https://github.com/user-attachments/assets/48829f40-ec04-45a5-a359-31ae32b1f469" />

## NOT of 8 bit numbers ALP
```
mov al,74h
mov bl,69h
not al,bl
```
## Output
<img width="1919" height="1009" alt="image" src="https://github.com/user-attachments/assets/5d1859d5-7c42-4f9c-abaa-0b417fc25278" />


## XOR of 8 bit numbers ALP
```
mov al,74h
mov bl,69h
xor al,bl
```
## Output
<img width="1919" height="1012" alt="image" src="https://github.com/user-attachments/assets/98ffe11b-ed93-4fde-96ec-dfdf7fdc6df8" />

## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








