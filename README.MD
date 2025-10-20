Step 1 (Branch Descriptions):



main - stable production branch

-> This branch has only one commit hash# 45767c4

--> hash# 45767c4 Initial Number guessing game



Dev - Integration branch for features. Adds encouraging message for players.

-> This branch as had only one commit hash# 5f95961

--> hash#  5f95961 Add encouraging message for players



Experimental Branches with multiple commits:



Feature1 - Add Version comment documenting quit features

-> This branch has had four commits hash# 3bbc201, f8dfe81, 9df380f, f48cf81 (in order from oldest to newest)

--> hash# 3bbc201 Add ability to quit game with negative number input

--> hash# f8dfe81 Add play-again loop functionality

--> hash# 9df380f Improve user feedback messages for guesses

--> hash# f48cf81 Add version comment documenting quit feature



Feature2 - Implement max attempts, logic, and game over condition

-> This branch has two commits hash# 45aa640, e367776

--> hash# 45aa640 Add maxAttempts constant and game over state

--> hash# e367776 Implement max attempts logic and game over condition



Feature3 - hint implementation with multiple commits

-> This branch has had four commits hash#

--> hash# f1097b6 started hint

--> hash# c070288 got it done

--> hash# 3631e47 had to fix

--> hash# 1f23d1c (feature3) done



hotfix - bug fix to include max value in range, ready for main

-> This branch as had only one commit hash# 5f95961

--> hash#

 

documentation - README documentation created and updated.

-> This branch as had only one commit hash# 5f95961 (so far)

--> hash# 9750abe (documentation) Step 1: Added README with branch descriptions





Step 8:

• Differences between merge, rebase, squash, and cherry-pick

Merge: this combines two branches and presereves both histories 

rebase: creates a linear history by reaplying your commits on top of another branch.

squash: compbines multiple commits into one (I will most likely be using this a lot)

cherry-pick: coppies a single specific commit from one banch to another. 



• What you observed in the git history for feature1 vs feature2 vs feature3

Step three had us delete branch feature1, but I would assume that it would be two brances merging into one. 

feature2 we used rebase so the history is linear without any extra merg or commits

feature3 we squashed the commits from four to one and merged it inot dev. we see a single commit now that merges 



• When you would use each strategy in real projects

Merge: when I want a branch to merge but I don't care about the history of the branch (and am ok with deleting it). maybe I am working with others

rebase: when I am not working with others and I want to clean up my history and make things readable

squash: when I make a bunch of little commits on a branch and would like to clean it up.

cherry-pick: When I want to apply a specific commit I made on one branch to another. 

