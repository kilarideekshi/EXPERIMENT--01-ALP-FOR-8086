# EXPERIMENT--01-ALP-FOR-8086

# Name : K DEEKSHITHA
# Roll no : 2305002005
# Date of experiment :





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
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






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AL,14H
MOV BL,12H
ADD AL,BL
HLT
```


## Output  
 ![WhatsApp Image 2024-10-14 at 14 03 52_e940f717](https://github.com/user-attachments/assets/44ddf421-fe73-49ff-95d4-0e89b2e1fea5)

## Subtraction   of 8 bit numbers  ALP 
 ```
MOV AL,14H
MOV BL,12H
SUB AL,BL
HLT
```
## Output  
![WhatsApp Image 2024-10-14 at 14 05 27_dee2b974](https://github.com/user-attachments/assets/28b7ee99-ae86-449a-8b35-2fcc82c46aff)

## Multiplication alp 
```
MOV AL,14H
MOV BL,12H
MUL BL
HLT
```
 ## Output  
![WhatsApp Image 2024-10-14 at 14 07 13_6dbfaf98](https://github.com/user-attachments/assets/ae7532e9-b9bb-444c-a0a4-a5f9475ca9cd)


## Division alp 
```
MOV AL,24H
MOV BL,12H
DIV BL
HLT
```
## Output  
![WhatsApp Image 2024-10-14 at 14 09 03_3af96acc](https://github.com/user-attachments/assets/e842d99f-c0f1-4590-846c-0dcda37d6b0c)
# AND of 8 bit ALP
```
MOV AL,14H
MOV BL,12H
AND AL,BL
HLT
```
# OUTPUT
![WhatsApp Image 2024-10-14 at 14 11 18_0fa13824](https://github.com/user-attachments/assets/9b470deb-c3a8-4592-a8c5-1bf9f41e6711)
# OR of 8 bit ALP
```
MOV AL,45H
MOV BL,66H
OR AL,BL
HLT
```
# OUTPUT
![WhatsApp Image 2024-10-14 at 14 12 36_d9c96fc7](https://github.com/user-attachments/assets/f521420b-1374-47f4-83cb-24be5677eaae)

# XOR OF 8 BIT ALP
```
MOV AL,66H
MOV BL,27H
XOR AL,BL
HLT
```
# OUTPUT
![WhatsApp Image 2024-10-14 at 14 15 32_a9523504](https://github.com/user-attachments/assets/6a886f0a-3629-4285-84e5-59d796d7170b)

# RESULT
Thus the ALP on the fundamental Arithmetic and Logical operations has been written and executed successfully.








