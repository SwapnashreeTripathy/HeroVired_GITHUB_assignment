# Question1- CaculatorPlus.py

This is an Application written in Python. 
This application provides basic arithmetic operations, such as addition, subtraction, multiplication, and division.
A new feature has been implemented that adds support for calculating the square root of a number as well.

## Steps Performed


1. Create GitRepo named "git_assignment_HeroVired" and Clone the repo to your Local environment.

       "git clone GitHub repo SSH link)"

2. Create a new branch "dev" to make changes to the code in this branch.

       "git checkout -b dev"  -- this will create a new branch and will switch to it at the same time

3. Create a Python file as "CalculatorPlus" and add the basic arithmetic calculation
 

4. Stage this file in the "dev" Branch & then Commit this File.

	   "git status"

	   "git add <CalculatorPlus.py>"

	   "git commit -m "add some message for this commit here" <CalculatorPlus.py>

	   "git log"  -- to view the recently made Commit details

5. Merge the recent commit from the "dev" Branch to the "Main" branch.

	   "git checkout main"

	   "git merge dev"     -- Merge all the recent commits of Dev to the Main branch

	   "git log" 		 -- to check whether commits have been reflected on Main or not

6. Push the commit from "Main local" to Main GitHub or "Origin/main".

	   "git log"  -- now you can see "origin/main" should have moved to "HEAD -> main" commit 

       "git push" -- to push changes from local Main to "origin/main"
	
7. Release the First Version of the code.

   ![image](https://github.com/SwapnashreeTripathy/git_assignment_HeroVired/assets/139486876/7fc5d35c-65b6-460f-a5ed-0fd9a312799b)

 
9. create a new branch as "feature/sqrt" & check out to it.
   "git branch feature/sqrt"

       "git checkout  feature/sqrt"
	 
10. Add the ‘sqrt’ code to the "feature/sqrt" branch. and Stash it to save the code temporarily.

        “git stash”
11. As a critical bug is reported in the main branch, switch back to the ‘dev’ branch to fix the bug.

	 i. Add the "divide function" code fix to the "CalculatorPlus.py" file in the "Dev" Branch.

	 ii. then Stage & commit the "CalculatorPlus.py" in Dev Branch & Push the newly fixed code into Dev Origin.

	    “git add CalculatorPlus.py”

	    “git commit -m "message" 

        “git log”      -- to check the newly added commit info

		
	**In order to Push the "dev" code from Local to Origin/main, create an Origin/main using the below command.

	    “git push -u origin dev” - will create an Origin/dev branch & will push to it as well.

	**You can check the same if reflecting or not from "Git Log" or from "Git Hub".

12. Create a "Pull Request" from Hub to Pull code from DEV to Main, so that the Collaborator can review the code to Merge.

13. Once the PR is reviewed by Collaborator, check out to the feature/sqrt branch & bring the temporarily saved code for the "Square" function back.

	    “git stash pop”

	 i. A Merge Conflict occurs as there "Square" function was saved in the CalculatorPlus.py file. 

	 ii. To Resolve to Merge conflict, go to VS code editor, remove the unwanted characters, and keep the required code.

	 iii. Then click on Resolve Conflict & Merge the code.

	 iv. Commit the "CalculatorPlus.py" file in the "feature/sqrt" branch.

	    “git commit -m "message"

14. This code can now be merged to the DEV branch & then Push to DEV Origin.

	    “git checkout dev”

	    “git merge feature/sqrt”

	    “git log”

	    “git push”  -- the origin/dev will be moved to the latest commit or the same as local HEAD in Git Log.

	i. Test if the Code working fine, create a Pull request from DEV origin to MAIN origin, so that all the codes will reflect on Main Branch.

	ii. And create a ‘version 2’ Release from GitHub.
 
     ![image](https://github.com/SwapnashreeTripathy/git_assignment_HeroVired/assets/139486876/a8692f67-42d0-4ee8-bb14-293a6f124d8b)

	


