# Exercise 8 - Viewing changes before committing

1. Ensure your working directory is clean

2. Add text to any one of your files

3. Delete different text from another of your files

4. Look at `git status`

5. View all the changes you've made

        git diff


6. Does the following command return anything?

        git diff --staged

The command doesnt return anything. 

________________________________________________________________
7. Add one of your changed files to the index

        git commit add <changed file>

8. What do these commands show?

        git diff:

diff --git a/fruits.txt b/fruits.txt
index 606ba2d..04daf09 100644       
--- a/fruits.txt
+++ b/fruits.txt
@@ -4,4 +4,5 @@ tomato
 blueberry
 strawberry
 kiwi
-grape
\ No newline at end of file
+grape
+honeydew

        git diff --staged

I didnt get anything from this command. 

9. Add the other changed file to the index

        git commit add <other changed file>

10. What do these commands show?

        git diff:

diff --git a/furniture.txt b/furniture.txt
index 990b2a2..85a62d2 100644
--- a/furniture.txt
+++ b/furniture.txt
@@ -1,4 +1,4 @@
 Bed
 Desk
-Chair
+
 Table
        git diff --staged

I didnt get anything from this command. 

_____________________________________________________________________

11. Commit the changes

12. Check that your working directory is clean

13. Create a new file named `clothing.txt`

14. Does the new untracked file show up in git diff?

        git diff

The new file doesnt show up in 'git diff'

_____________________________________________________________________

15. Add and commit the new file
