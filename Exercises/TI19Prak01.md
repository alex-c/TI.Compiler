# Praktikum 1

## Aufgabe 1

Program

![program syntax diagram](./diagrams/TI19Prak01-01-program.png "Program")

Input Variables

![input variables syntax diagram](./diagrams/TI19Prak01-01-inputVariables.png "Input Variables")

Output Variables

![output variables syntax diagram](./diagrams/TI19Prak01-01-outputVariables.png "Output Variables")

Variables

![output variables syntax diagram](./diagrams/TI19Prak01-01-variables.png "Output Variables")

Statements

![statements syntax diagram](./diagrams/TI19Prak01-01-statements.png "Statements")

Assignment

![assignment syntax diagram](./diagrams/TI19Prak01-01-assignment.png "Assignment")

While Statement

![while statement syntax diagram](./diagrams/TI19Prak01-01-whileStatement.png "While Statement")

Condition

![condition syntax diagram](./diagrams/TI19Prak01-01-condition.png "Condition")

## Aufgabe 2

While0 statement:

```
while V1 != V2 do begin α end
```

URM equivalent:

```
1: SUB(R1,R2,R3)
2: SUB(R2,R1,R4)
3: if R3 != 0 goto 5
4: if R4 == 0 goto 6
5: α
6: 
```