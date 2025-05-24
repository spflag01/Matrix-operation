🧮 Matrix Operations Program in C
This is a C-based console application that performs various operations on two user-defined matrices, including addition, subtraction, multiplication, transpose, and square matrix check.

📋 Features
✅ Matrix Addition

✅ Matrix Subtraction

✅ Matrix Multiplication

✅ Transpose of Matrix A and B

✅ Check if Matrix A or B is square

ℹ️ The program dynamically allocates matrix sizes based on user input and validates matrix dimensions before performing operations.

🛠️ How It Works
User inputs the number of rows and columns for Matrix A and Matrix B.

User fills in each element of both matrices.

A menu is displayed with different operations.

Based on the user's choice, the corresponding operation is performed.

📦 How to Compile and Run
🔧 Using gcc:
bash
Copy
Edit
gcc -o matrix matrix.c
./matrix
Or on Windows (if using MinGW):

bash
Copy
Edit
gcc -o matrix.exe matrix.c
matrix.exe
📑 Sample Menu
markdown
Copy
Edit
MENU:
1. Addition
2. Subtraction
3. Multiplication
4. Transpose of A
5. Transpose of B
6. Check if A is square
7. Check if B is square
8. Exit
Choose operation:
⚠️ Validations
Matrices must be of the same dimensions for addition or subtraction.

Columns of A must equal rows of B for multiplication.

Transpose and square checks work with any valid matrix size.

🔄 Future Improvements
You can enhance this program further by:

Adding element-wise division

Supporting inverse (for 2x2 or 3x3 matrices)

Including determinant calculation

Using dynamic memory allocation instead of VLAs

Adding a matrix file input/output system

📄 License
This project is free to use and modify. Attribution is appreciated but not required.
