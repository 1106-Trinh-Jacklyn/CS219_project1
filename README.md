# jacklyn_trinh_proj1

Run this code:
1. make
2. ./machine

Purpose: This program simulates a basic machine language operation with addition. It reads input from a file containing commands then performs addition with the given hexadecimal values. It also detects whether or not an overflow has occurred and then displays the results.

Working Process:
1. The input is read line by line.
2. Each line is split into an operation and two hexadecimal values.
3. The two hexadecimal values are then stored using uint32_t.
4. The two values are added.
5. The sum is checked for overflow, which occurs when the sum is smaller than a value being added.
6. The inputs and results are then displayed in hexadecimal format following the example format. The detection of overflow is also displayed.

Results:
1. Prints the operation (ADD).
2. Prints the two input numbers in hexadecimal format.
3. Prints the results of the addition in hexadecimal format.
4. Prints whether or not an overflow occurred.

Correct Output: Yes, the output is correct based on the provided commands. The results match the expected outcomes, and the overflow is correctly detected when it occurs.