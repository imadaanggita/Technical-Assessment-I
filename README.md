# Arithmetic Sequence with N Numbers - Python Program

## Overview

This Python program calculates the values and the sum of an **arithmetic sequence** with `N` numbers, where the difference between consecutive terms is constant. The program is developed as part of **Technical-Assessment-I** and leverages a formulaic approach to compute both the sequence and its sum based on user inputs for:
- **First Term (`a1`)**
- **Common Difference (`d`)**
- **Number of Terms (`N`)**

### Key Formula:
The formula to calculate the nth term (`an`) in the sequence:
\[
an = a1 + (n - 1) \times d
\]

## Features

- **Interactive Input:** The program prompts the user for the number of terms.
- **Validation:** Ensures that the number of terms (`N`) is positive.
- **Efficient Calculation:** The program calculates both the sequence using arithmetic formulas.
- **Easy to Extend:** The modular code design allows easy extension for further customization.

## Prerequisites

- Python 3.x
- Jupyter Notebook or Google Colab to run the `.ipynb` notebook file

## How to Run the Program

### Option 1: Using Jupyter Notebook (Locally)

1. Install Jupyter Notebook by following instructions from [Jupyter.org](https://jupyter.org/install).
2. Clone or download the project and open the `Technical_Assessment_I.ipynb` file.
3. Execute the notebook cells to run the program.

### Option 2: Using Google Colab (Online)

1. Upload the `Technical_Assessment_I.ipynb` notebook to Google Colab.
2. Run the cells directly in the Colab environment.

### Inputs

The program will prompt you to enter the **number of terms** (`N`).

### Example Input:

```plaintext
N: 10
```

### Example Output:

```plaintext
The arithmetic sequence is: 2,5,8,11,14,17,20,23,26,29
```

## Code Example

```python
print("// ARITHMETIC SEQUENCE WITH N NUMBERS //") #title of program
a = 2 #initial number
N= int(input('N: ')) #input
#execute the program
if N == 0:
  print('The arithmetic sequence is:',0)
elif N < 0:
  print("Answer is not found. Please input N >= 0")
elif N > 0:
  print('The arithmetic sequence is:',str(a), end='')
  for i in range(N-1):
    a+=3
    print(","+ str(a), end='')
```

## Author

This program was developed for **Technical-Assessment-I**.
