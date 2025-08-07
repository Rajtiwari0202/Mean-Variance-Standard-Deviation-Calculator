Mean, Variance, and Standard Deviation Calculator

This project contains a Python function calculate() that uses the NumPy library to compute the mean, variance, standard deviation, max, min, and sum for a 3x3 matrix. The function takes a list of nine numbers as input, converts it into a 3x3 NumPy array, and returns the results in a structured dictionary format.
Project Files

    mean_var_std.py: Contains the calculate() function.

    main.py: A simple script to test the calculate() function with valid and invalid inputs.

How to Run

    Ensure you have Python and the NumPy library installed. If not, you can install NumPy using pip:

    pip install numpy

    Place mean_var_std.py and main.py in the same directory.

    Run main.py from your terminal to see the function in action:

    python main.py

Function Description

The calculate() function performs the following:

    Input Validation: It first checks if the input list contains exactly nine numbers. If not, it raises a ValueError.

    Matrix Conversion: The list is converted into a 3x3 NumPy array.

    Calculations: It computes the required statistics (mean, variance, standard deviation, max, min, sum) along three different axes:

        axis=0: Calculations for each column.

        axis=1: Calculations for each row.

        Flattened matrix: Calculations for all elements in the matrix.

    Output: The results are returned as a dictionary where each key corresponds to a statistic and its value is a list containing the results for each axis and the flattened matrix.
