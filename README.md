# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR  
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END

## OUTPUT
<img width="1919" height="1020" alt="Screenshot 2025-09-22 184246" src="https://github.com/user-attachments/assets/f2867d27-f0f1-496d-8b2e-0992333c9435" />
<img width="746" height="509" alt="Screenshot 2025-09-22 184304" src="https://github.com/user-attachments/assets/d5d297c0-6cff-474c-be2a-acae591eb343" />



## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END

## OUTPUT
<img width="1920" height="1080" alt="Screenshot 2025-09-22 191337" src="https://github.com/user-attachments/assets/ef8923c8-1027-4c7c-904f-4e745d37b33d" />
<img width="762" height="504" alt="Screenshot 2025-09-22 191402" src="https://github.com/user-attachments/assets/7e76e565-a2a5-4fed-bfdc-929714da89fa" />



## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
