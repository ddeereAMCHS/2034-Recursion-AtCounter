# At Counter

## Due: Thur 10/26 at 11:59 PM

- Create a program called `AtCounter.java`
- Create a recursive method that:
  - Takes a char matrix and two ints that are the row and column index
  - Returns an int that is how many @ signs connect to the original location
    - Make sure you don't double count an @ (think through how you would do this)
- Inside the main method:
  - Prompt the user for a filename
  - Prompt the user for two more numbers (0 to 9) that are the row and column index, respectively
  - Create an empty 10 x 10 matrix of chars
  - Read in the values from the file into the matrix
  - Call the method with the filled matrix and the two numbers the user entered and print the result

***Example Input:***\
mat1.txt\
4\
2\
***Example Contents of mat1.txt:***\
`- @ - @ - @ @ - @ @`\
`@ @ @ @ - @ - @ @ @`\
`@ @ @ - @ @ @ @ - @`\
`@ - @ - @ @ - - @ @`\
`@ @ @ @ - - - - - @`\
`@ @ @ @ - - - - - @`\
`@ @ @ - @ @ - @ @ @`\
`- - @ - @ - - - @ -`\
`- @ - @ - @ - - @ -`\
`@ - - @ @ @ @ @ @ -`\
***Example Output:***\
The matrix at location [4][2] has 23 @ symbols
