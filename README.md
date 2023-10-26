# Factorize All the Things!

This repository contains a program that factors natural numbers into a product of two smaller numbers. The program can handle multiple numbers at once, with each number provided in a separate line in a file.

## Usage

To factorize numbers, follow these steps:

1. Clone this repository to your local machine.
2. Ensure that you have the necessary permissions to run the program.
3. Create a file containing the natural numbers you want to factorize, with each number on a separate line.
4. Open a terminal and navigate to the cloned repository's directory.
5. Run the program using the following command:
   ````
   ./factors <file>
   ```
   Replace `<file>` with the path to your input file.
6. The program will output the factorizations for each number in the file, with the format `n=p*q` where `p` and `q` are the factors.

## Constraints and Specifications

- All numbers in the input file are natural numbers greater than 1.
- There will be no empty lines or spaces before/after the valid numbers.
- The input file will always end with a new line.
- The program should run without any external dependencies.
- The execution time limit is 5 seconds. If the program hasn't finished within this timeframe, it will be terminated.

## Example

Consider the following input file `tests/test00`:

```
4
12
34
128
1024
4958
1718944270642558716715
9
99
999
9999
9797973
49
239809320265259
```

Running the program with this input produces the following output:

```
4=2*2
12=6*2
34=17*2
128=64*2
1024=512*2
4958=2479*2
1718944270642558716715=343788854128511743343*5
9=3*3
99=33*3
999=333*3
9999=3333*3
9797973=3265991*3
49=7*7
239809320265259=15485783*15485773
```

## Repository

This program is part of the RSA Factoring Challenge repository:

GitHub repository: [RSA-Factoring-Challenge](https://github.com/your-username/RSA-Factoring-Challenge)

Files:
- `factors`: The executable program for factorizing numbers.
- `rsa`: The executable program for the RSA factoring challenge.
- `tests/`: Directory containing sample input files for testing.
- `README.md`: Documentation and instructions.

Feel free to explore the repository for more information and challenges related to RSA factoring.
