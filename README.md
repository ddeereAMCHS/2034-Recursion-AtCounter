# At Counter

- Create a program called `AtCounter.java`
- Create a recursive method that:
  - Takes a char matrix and two ints that are the row and column index
  - Returns an int that is how many @ signs connect to the original location
    - Make sure you don't double count an @ (think through how you would do this)
- Inside the main method:
  - Prompt the user for a number
  - Create a Random object with this number as the seed
  - Prompt the user for two more numbers (0 to 9) that are the row and column index, respectively
  - Create an empty 10 x 10 matrix of chars
  - Fill the matrix randomly with @s and -s
    - HINT: There should be a 50/50 chance of getting an @ or a -
  - Call the method with the filled matrix and the two numbers the user entered
  - Print the filled matrix
  - Print a blank line
  - Print the result of the matrix call with the specified output
    - The matrix at location [row][col] has ## @ symbols

Example input:\
1234\
4\
2\
Example output:\
@ @ @ @ - - @ @ - -\
@ @ @ @ - - @ @ - -\
@ @ - @ - @ @ @ - @\
@ - @ - - - @ @ - -\
\- @ @ @ - - @ @ - @\
@ - @ @ - @ @ @ - @\
@ - @ - - - @ @ - -\
@ @ - @ - - @ - - -\
@ @ @ @ - - @ @ - -\
@ @ @ @ - - @ @ - -\
\
The matrix at location [4][2] has 7 @ symbols
