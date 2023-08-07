# Git Assignment Q.3

a. Create a New Branch:<br>
- Created a new branch named "feature/circle-area" to work on the circle-area feature.<br>
                       "git checkout -b feature/circle-area"<br>
- Create a new file "geometry-calculator" with Circle Area Feature in the "feature/circle-area" branch<br>

b. Stash Changes for Circle Area Feature:<br>
-  Before committing the changes, stash them using git stash to save the incomplete feature implementation.<br>
   1. Add the Git file & Stash this File<br>
       "git add geometry-calculator.py"<br> 
        "git stash "<br>
   2. The File should not appear while checking the  git status<br>
   	"git status"<br>

c. Create a New Branch for Rectangle Area Feature:<br>
 - Create a new branch named "feature/rectangle-area" to work on the rectangle area<br>
	"git checkout dev"<br>
	"git checkout -b feature/rectangle-area"<br>
	
 - create a new file named "geometry-calculator" with Rectangle Area Feature in the  "feature/rectangle-area" branch & Stash it.<br>
	 "git add geometry-calculator.py"<br>
	 "git stash"<br>

 - The File should not appear while checking the  git status<br>
         "git status"<br>
	
e.  Switch Back to Circle Area Branch commit and Push Circle Area Feature:<br>
 - Switch back to the "feature/circle-area" branch to continue working on the circle-area feature.<br>
	"git checkout feature/circle-area"<br>
 - View all the stash presents.<br>
	 “git stash list”<br>
 - Retrieve the stash for circle-area code<br>
	 "git stash apply {stash-id of the stash made for circle-area code}"<br>
 - Complete the circle area feature implementation and save the changes.<br>
	 “git add *”<br>
	 “git commit -m ”commit circle-area code”<br>

g.  Switch Back to Rectangle Area Branch & commit and Push Rectangle Area Feature:<br>
 -  Switch back to the "feature/rectangle-area" branch to continue working on the rectangle area feature.<br>
     "git checkout feature/rectangle-area "<br>
 -  Retrieve the stashed changes<br>
    “git stash list”<br>
   "git stash apply {stash-id of the stash made for rectangle-area code}"<br>
 -  Complete the rectangle area feature implementation and save the changes.<br>
   “git add *”<br>
   “git commit -m ”commit rectangle-area code”<br>

i.  Create Pull Requests:<br>
  -  Create a pull request to the ‘dev’ branch.<br>
     *Fromm the git hub create a pull request from feature/rectangle-area & feature/circle-area to Dev Branch.<br>
 
j.  Review and Merge<br>
  -  Have another team member or reviewer review your pull requests.<br>

   After receiving approval, merge both pull requests into the main branch.<br>


