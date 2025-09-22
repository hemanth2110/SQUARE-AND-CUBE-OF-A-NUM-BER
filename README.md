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
<img width="1910" height="1018" alt="square1" src="https://github.com/user-attachments/assets/03968616-e596-4f52-8ae0-a0ac533a9249" />
<img width="850" height="578" alt="2sq" src="https://github.com/user-attachments/assets/1eb2dcd5-c448-4791-a349-443bfdd9c069" />



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
<img width="1919" height="1016" alt="31" src="https://github.com/user-attachments/assets/024b4bad-8cee-4679-9c7f-30662ce5bab3" />
<img width="654" height="482" alt="32" src="https://github.com/user-attachments/assets/c6d0a199-ffa8-46e4-8a4e-40ef8cdca8d4" />



## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
