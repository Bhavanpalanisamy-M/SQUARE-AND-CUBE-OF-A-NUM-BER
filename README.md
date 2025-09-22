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
```
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
```
## OUTPUT
<img width="1919" height="1079" alt="Screenshot 2025-09-22 232505" src="https://github.com/user-attachments/assets/2f629b08-e6fc-4d4d-ae02-25a5254c1d15" />

<img width="688" height="370" alt="Screenshot 2025-09-22 232547" src="https://github.com/user-attachments/assets/0527c450-abf6-4e4f-9e2a-e76d9c7fdbab" />


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
```
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
```
## OUTPUT
<img width="1919" height="1079" alt="Screenshot 2025-09-22 235642" src="https://github.com/user-attachments/assets/513798aa-f93b-4ea5-b0de-41f6188d3231" />
<img width="766" height="499" alt="Screenshot 2025-09-22 235722" src="https://github.com/user-attachments/assets/b30cd36d-2a43-4a6a-983f-2bafd8fb3b8b" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
