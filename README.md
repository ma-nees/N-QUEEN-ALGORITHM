#  N-Queens Solver in C (Backtracking)

A classic **C program** to solve the **N-Queens Problem** using elegant **recursive backtracking**.  
It prints **all valid solutions** for placing `N` queens on an `N×N` chessboard such that no two queens attack each other.

---

## 📌 What is the N-Queens Problem?

> The challenge is to place **N** queens on an **N×N** chessboard such that:
> - No two queens are in the same row
> - No two queens are in the same column
> - No two queens are on the same diagonal

---

##  Features

- ✅ Finds **all possible solutions**
- ✅ Clean **matrix-style output**
- ✅ Easy to understand **recursive backtracking**
- ✅ Board size customizable up to **10×10**
- ✅ Perfect for students and algorithm learners

---

##  Algorithm Logic

1. Start placing queens **row by row**
2. For each row, **try each column**:
   - Check if placing a queen is **safe**
   - If safe → place it and move to next row
   - If not safe → try next column
3. **Backtrack** if no column is valid in a row
4. When all queens are placed → print the solution

> The solution uses:
> - 🔁 Loops for column trials  
> - 🔒 Safety check for rows, diagonals  
> - 📦 2D array `board[N][N]` to track placement

---

## 🧪 Input / Output Example

###  Sample Input
Enter the size of the board (N): 4



###  Sample Output

Solution 1: <br>
0 1 0 0 <br>
0 0 0 1 <br>
1 0 0 0 <br>
0 0 1 0
 <br>
Solution 2: <br>
0 0 1 0 <br>
1 0 0 0 <br>
0 0 0 1 <br>
0 1 0 0 <br>
