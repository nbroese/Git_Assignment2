Merge is used to combine 2 branches and often requires manual merging unless a fast-forward is done.
Rebase merges and also rewrites the history to create a linear path.
squash condenses multiple commits into one. 
Cherry-pick brigs over only a specific commit.
Each feature had git history recorded differently and offered varying degrees of usefulness.
Each operation had distinct advantages and disadvantages so it is important to use the correct strategy to make projects clear.
If a more complete history with branching paths to show development paths is desired a merge should be used.
If a liner history is desired rebase should be used. If history needs to be simplified squash can be used.
If a single independent commit is desired cherry-picking can be used.

I kept having issues with gradlew updating. I had to add it to the git ignore in each branch but that caused a lot of unnecessary commits and kept generating eerrors when I attempted to squash.
I troubleshooted for a while but could not fid a workaround on my own.