Write a Java program that performs the following tasks:

Prompts the user to input:

A target value (integer).
The number of measurements (minimum 1000).
Generates the specified number of measurements (real numbers) randomly using the formula:
approximate value = target value +/- (0.001 ... 0.999)

Calculates for each measurement:

Absolute error.
Relative error.
Saves the data to a CSV file, where each row contains:

The generated measurement.
The absolute error.
The relative error.
Example Output File

measurement,absolute_error,relative_error
123.456,0.123,0.001
...  
