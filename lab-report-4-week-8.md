# Lab Report 4

## Snippet 1: Test 

Through the VSCode preview of what the md file should produce I have determined that snippet 1 should produced the following result:

"google.com", "google.com", "ucsd.edu" 

This can be seen by the following test:

![First Image]()

In the case of my test, this is the result:

In the case of the person I was reviewing's test, this was the result:

### Can this be fixed with a short change?

I believe that this result would need a more involved code change. I believe that I need to remake my while loop to consider spacing, and counting special characters as string text
in order to solve my issue. This would require a much more involved change than I have right now. 

## Snippet 2: Test

Through the VSCode preview of what the md file should produce I have determined that snippet 2 should produced the following result:

"a.com", "a.com(())","example.com"

This can be seen by the following test:

![Second Image]()

In the case of my test, this is the result:

In the case of the person I was reviewing's test, this was the result:

### Can this be fixed with a short change?

I believe that this result can be fixed with a short change. I can include conditionals to only consider a right bracket followed by a left parenthesis as the making of a link, thus
counting all other parenthetical statements as simple string objects. 


## Snippet 3: Test

Through the VSCode preview of what the md file should produce I have determined that snippet 2 should produced the following result:

"https://ucsd-cse15l-wi22.github.io/"

This can be seen by the following test:

![Second Image]()

In the case of my test, this is the result:

In the case of the person I was reviewing's test, this was the result:

### Can this be fixed with a short change?

I believe that this result requires more extensive change. Since most of the issues are likely caused by the fact that links span multiple links, I would need to add a statement
to check beginnings and ends of lines, and next lines, which would require more effort on my part. 
