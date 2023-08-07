Git Assignment Q.3

a.  Create a New Branch:<br>
- Created a new branch named "feature/circle-area" to work on the circle-area feature.<br>
      "git checkout -b feature/circle-area"<br>
- Create a new file "geometry-calculator" with Circle Area Feature in the "feature/circle-area" branch<br>

b. Stash Changes for Circle Area Feature:<br>
-  Before committing the changes, stash them using git stash to save the incomplete feature implementation.<br>
   1. Add the Git file & Stash this File<br>
      "git add geometry-calculator.py"<br> 
       "git stash "<br>

   2. The File should not appear while checking git status
   -"git status"
   c.  Create a New Branch for Rectangle Area Feature:

- Create a new branch named "feature/rectangle-area" to work on the rectangle area
	"git checkout dev"
	"git checkout -b feature/rectangle-area"
	
	1. create a new file named "geometry-calculator" with Rectangle Area Feature in "feature/rectangle-area" branch & Stash it.
	-"git add geometry-calculator.py" 
	-"git stash "

   2. The File should not appear while checking git status
   -"git status"
	
e.  Switch Back to Circle Area Branch commit and Push Circle Area Feature::

	1. Switch back to the "feature/circle-area" branch to continue working on the circle-area feature.
	- "git checkout feature/circle-area"
2. view all the stash presents.
	 “git stash list”
	3. Retrieve the stash for circle-area code
	- "git stash apply {stash-id of the stash made for circle-area code}"
	4. Complete the circle area feature implementation and save the changes.
	“git add *”
	 “git commit -m ”commit circle-area code”

g.  Switch Back to Rectangle Area Branch & commit and Push Rectangle Area Feature:
-  Switch back to the "feature/rectangle-area" branch to continue working on the rectangle area feature.
"git checkout feature/rectangle-area "
-  Retrieve the stashed changes
“git stash list”
"git stash apply {stash-id of the stash made for rectangle-area code}"
-  Complete the rectangle area feature implementation and save the changes.
“git add *”
	 “git commit -m ”commit rectangle-area code”
i.  Create Pull Requests:
-    Create a pull request to the ‘dev’ branch.
**from the git hub create a pull request from feature/rectangle-area & feature/circle-area to Dev Branch.
 
j.  Review and Merge

-  Have another team member or reviewer review your pull requests.

After receiving approval, merge both pull requests into the main branch.


