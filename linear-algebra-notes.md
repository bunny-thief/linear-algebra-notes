# Linear Algebra Notes

## Determinant of a Matrix
- The Determinant can only be calculated for a square matrix
- When the determinant equals zero the matrix is singular and linearly dependent
- When the determinant is non-zero the matrix is non-singular and linearly independent

### 2 x 2 Matrix

$$A = \begin{bmatrix}
       a & b \\[0.3em]
       c & d
     \end{bmatrix}$$

$$|A| = (a \cdot d) - (b \cdot c)$$

### 3 x 3 Matrix

$$B = \begin{bmatrix}
       a & b & c \\[0.3em]
       d & e & f \\[0.3em]
       g & h & i
     \end{bmatrix}$$

$$|B| = (a \cdot e \cdot i + d \cdot h \cdot c + b \cdot f \cdot g) - (g \cdot e \cdot c + d \cdot b \cdot i + h \cdot f \cdot a)$$

The Determinant for an upper triangular, lower triangular and diagonal matrix is equal to the product of the main diagonal

$$C = \begin{bmatrix}
       a & b & c \\[0.3em]
       0 & d & e \\[0.3em]
       0 & 0 & f
     \end{bmatrix}
     \hspace{0.7cm}
     
  D = \begin{bmatrix}
       g & 0 & 0 \\[0.3em]
       h & i & 0 \\[0.3em]
       j & k & l
     \end{bmatrix}
     \hspace{0.7cm}
     
  E = \begin{bmatrix}
       m & 0 & 0 \\[0.3em]
       0 & n & 0 \\[0.3em]
       0 & 0 & o
     \end{bmatrix}$$

$$|C| = (a \cdot d \cdot f) \hspace{1.1cm} |D| = (g \cdot i \cdot l) \hspace{1.1cm} |E| = (m \cdot n \cdot o) $$

If row or column contains all zeros, then the Determinant is zero

$$\begin{bmatrix}
       1 & 2 & -1 \\[0.3em]
       0 & 1 & 3 \\[0.3em]
       \textbf{0} & \textbf{0} & \textbf{0}
     \end{bmatrix}
     \hspace{1.5cm}
     
     \begin{bmatrix}
       1 & \textbf{0} & -1 \\[0.3em]
       0 & \textbf{0} & 1 \\[0.3em]
       0 & \textbf{0} & 3
     \end{bmatrix}
     $$