# BCB546X_Assignments

Review comments by Axelle Weeger. 

At line 69, your code returns and error: 
  Error in rename(., SNPs_ID = "Row.names") : unused argument (SNPs_ID = "Row.names")"

looking at ?rename does not bring up  a vignette I can use to fix this particular line of code. You may want to review this function or use another way to rename this column of your data set. 
the same rename issue pops up on line 283. 

at line 293, another error pops up : 
  Error in FUN(X[[i]], ...) : object 'y' not found
It does not look like your "fill=" was properly assigned. 

Your mutate string for the final graph is efficient, but very verbose. You might consider another approach (maybe an if/else?) that would give you the same result in fewer code lines. 
Your entire code is in a single R segment, which means that I can't run just a small section. I either have to run the whole chunk, or go line by line. 
Consider breaking it up by section for ease of review. 

I do quite like how consistent your data naming scheme is, I always know what I'm working with when I look at the environment. 





