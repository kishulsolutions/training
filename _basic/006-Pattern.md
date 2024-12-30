# Pattern Programming

## Tutorial
https://www.youtube.com/playlist?list=PLdo5W4Nhv31Yu1igxTE2x0aeShbKtVcCy

## Practice

### 1. Right-Angle Triangle of Stars
```plaintext
*
**
***
****
*****
```
**Hint:** Use a nested loop, where the outer loop runs for the number of rows, and the inner loop runs for the number of stars in that row.

### 2. Inverted Right-Angle Triangle
```plaintext
*****
****
***
**
*
```
**Hint:** Decrease the number of stars printed in each subsequent row.

### 3. Square Pattern
```plaintext
*****
*****
*****
*****
*****
```
**Hint:** Use two loops to print a fixed number of stars in each row.

---


### 4. Pyramid of Stars
```plaintext
    *
   ***
  *****
 *******
*********
```
**Hint:** Combine spaces and stars. Use two loops inside the outer loop: one for spaces and another for stars.

### 5. Diamond Pattern
```plaintext
    *
   ***
  *****
 *******
  *****
   ***
    *
```
**Hint:** First print an upward pyramid and then a downward pyramid.

### 6. Number Triangle
```plaintext
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
```
**Hint:** Inner loop prints numbers from `1` to the current row number.

---


### 7. Pascal's Triangle
```plaintext
     1
    1 1
   1 2 1
  1 3 3 1
 1 4 6 4 1
```
**Hint:** Use combinations formula: `nCr = n! / (r! * (n-r)!)`.

### 8. Hollow Diamond
```plaintext
    *
   * *
  *   *
 *     *
  *   *
   * *
    *
```
**Hint:** Print stars at the boundaries and spaces in between.

### 9. Hourglass Pattern
```plaintext
*********
 *******
  *****
   ***
    *
   ***
  *****
 *******
*********
```
**Hint:** Combine inverted and regular pyramids.

### 10. Spiral Numbers (Matrix)
```plaintext
1  2  3  4
12 13 14 5
11 16 15 6
10  9  8 7
```
**Hint:** Use a matrix and adjust boundaries dynamically for each direction (right, down, left, up).
