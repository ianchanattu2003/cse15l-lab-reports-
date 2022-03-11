# Lab Report 5, Week 10 

## How did I get the files that did not match?
Since there were issues running my bash script (likely due to some infinite loop or other bug in my program), 
I **searched through files manually** to find places that didn’t match. This was most definitely inefficient,
however, it was a way for me to brute force around the problem I had and search for bugs in my 
program that weren’t related to some file that was stopping me from seeing what tests actually failed. 


## Test number 1:

**Professor Politz's**
[]

**Mine**
[url &quot;tit&quot;]

**Correct**
[]
I believe in this case, our implementation is correct.
This is because markdown doesn’t consider special characters in their links, 
therefore this is not a valid link, since the special characters are included in the link.
I think a fix for this would be to include a code snippet that checks if the link contains any special characters, 
and this can be fixed by adding an if statement to the code. 



## Test Number 2:

**Professor Politz's**

< [train.jpg]

**Mine**
 > []

**Correct*
< [train.jpg]

 I think that in this case, Joe’s test case is correct, since, despite the link having a .jpg it does follow the syntax of a link in markdown.
 The bug in the code that should be fixed is the following: 
