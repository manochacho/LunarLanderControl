# Thruster Control Program

## What It Does
This C# program controls a spacecraft's thruster based on its altitude. It has two functions: `Control` and `Test`.

- **Control**: Takes an altitude (integer) and returns `0` (thruster off) or `1` (thruster on).
  - Above 100: thruster off (`0`).
  - Between 0 and 100: thruster on (`1`).
  - 0 or below: thruster off (`0`).
- **Test**: Tests the `Control` function with an altitude, checks if the thruster is correct, and prints the result with a ✅ (correct) or ❌ (incorrect).

## How It Works
The program tests altitudes: 150, 100, 50, 0, and -1. It prints the altitude, thruster state, and if it’s correct.

## Example Output

For altitude 150, your thruster is 0 |✅|
For altitude 100, your thruster is 1 |✅|
For altitude 50, your thruster is 1 |✅|
For altitude 0, your thruster is 0 |✅|
For altitude -1, your thruster is 0 |✅|
