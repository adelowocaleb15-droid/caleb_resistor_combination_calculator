# Resistor Combination Calculator

## What it does
This program asks how many resistors you have and the value of each one in ohms. It then calculates the total resistance when the resistors are connected in series and in parallel. It also checks for wrong input, like letters or negative numbers.

## How to run it
Install Python 3, then run: python resistor_calculator.py

## Sample output
How many resistors do you have? 3
Enter value of resistor 1 (ohms): 100
Enter value of resistor 2 (ohms): 220
Enter value of resistor 3 (ohms): 330
Your resistors are: [100.0, 220.0, 330.0]
Total resistance in series: 650.0 ohms
Total resistance in parallel: 56.9 ohms
Enter the supply voltage (volts): 12
Current in series circuit: 0.018 A
Current in parallel circuit: 0.211 A

## My own twist
After calculating the total resistance, the program asks for a supply voltage and uses Ohm's law (I = V / R) to calculate the current in both the series and parallel circuits.

## What I learned
I learned how to use try/except so the program does not crash when someone types a letter instead of a number. I also learned how to write functions that return values and how to store inputs in a list.

## Author
Caleb Adelowo, ND2 Mechatronics Engineering, YabaTech.
