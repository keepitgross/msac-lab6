# Exercise 7 - More than one changed file

1. Ensure you have a clean working directory

        git status

2. Edit one of your `fruits.txt`, add a few items

        blueberry
        strawberry
        

3. Edit `appliances.txt` and add a few items

        dishwasher
        dryer
        etc.

4. Look at git status, paste the output here

        git status


On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my_r/

nothing added to commit but untracked files present (use "git add" to track)

____________________________________________________________________________________________________________________

5. Can you commit both of the changed files in a single commit?

git commit fruits.txt appliances.txt 

_____________________________________________________________________________________________________________________

6. After you do so, check that you have a clean working directory by running `git status`, and pasting the output here

On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my_r/

nothing added to commit but untracked files present (use "git add" to track)

_____________________________________________________________________________________________________________________

7. Create a new file `equipment/furniture.txt`. Add content to both `vegetables.txt` and `furniture.txt`


8. How can you commit just one of the changed files?

On the source control, it has a list of the changes that have been made. From there you can only commit one of the files.

______________________________________________________________________________________________________________________
9. Check your `git status`

On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        my_r/

nothing added to commit but untracked files present (use "git add" to 
track)

______________________________________________________________________________________________________________________
10. What does red text mean in the output of `git status`?

That the file is in a merge conflict
______________________________________________________________________________________________________________________
11. What does green text mean in the output of `git status`?

That the file has been added to the index.

______________________________________________________________________________________________________________________
12. How can you make a single file show in both red and green in the output of `git status`?

I don't think you can, the colors mean two completly different things. 