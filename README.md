# -Set-Matrix-Zeroes
Given an  𝑚 × 𝑛 m×n matrix. If an element is 0, set its entire row and column to 0. Do it in-place.
Explanation:
Marking Rows and Columns: Use the first row and column as markers to track which rows and columns need to be set to 0.
Set Inner Matrix to Zero: Traverse the inner matrix and set cells to 0 based on the markers.
Handle First Row and Column: Update the first row and column if needed, as they serve as markers.
