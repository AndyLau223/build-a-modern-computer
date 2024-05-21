# Concepts and Implementations

## Gates

### Nand Gate(Not And)

Nand gate produces an output which is false only if all its inputs are true;
thus its output is complement to that of an AND gate.  
A LOW(0) output results only if all the inputs to the gate are HIGH(1);
if any input is LOW(0), a HIGH(1) output results.

Truth table

| Input(A,B) | Output(A NAND B) | 
|------------|------------------|
| A=0, B=0   | 1                |
| A=0, B=1   | 1                |
| A=1, B=0   | 1                |
| A=1, B=1   | 0                |



given a and b 
if a and b both are 1, then output 1

(a Nand b) Nand (a Nand b)