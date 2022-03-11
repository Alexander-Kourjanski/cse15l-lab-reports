# Lab Report 5: Comparing Different Implementations

The way that I found a difference in output of the two different implementations was by using diff, which compares the output of each test file that was put in results.txt. This command compares the output of each implementation with each other, and prints out all the instances where the results are different from each other.

![Image](RunningDiffCommand.PNG)

## Difference 1: File 212.md

The first file that we are going to be talking about where the implementations gave two different results is with 212.md. The file itself looks like this

![Image](212MarkdownCode.PNG)

Since there are no links that follow the proper bracket and parenthesis format, that means there should be no links taken, however, we end up with this from diff.

![Image](212MarkdownOutputs.PNG)

The output of my Markdown Parse is an empty list, but the other implementation contains url in the output. There is no link within parenthesis in the code, so the expected output should be an empty list, so the implementation given for week 9 is incorrect.

## Difference 2: File