# Upload a Large File using Git LFS 
Uploaded a 200 MB ".pdf" file using Git LFS
1. Install Git LFS.<br>
   “git lfs install”<br>
   
2. Create a Branch LFS and checkout into it.
   "git branch lfs"<br>
   "git checkout lfs"<br>
   "git status"<br>
   
3. Keep a pdf file of more than 200 MB in the directory git is initialized<br> & Track the large file(pdf in this case).<br>
    git lfs track "*.pdf"<br>
   "git status"<br>
   
   ![image](https://github.com/SwapnashreeTripathy/git_assignment_HeroVired/assets/139486876/e977ea87-0bc9-4f83-8247-190baa3fa5ea)
   
5. Add the files & Commit it.<br>
   “git add .gitattributes”<br>
   “git add 200MB PDF File-lfs.pdf”<br>
    git commit -m "Track the Large 200MB file via Git LFS"<br>
    "git log"<br>
   
   ![image](https://github.com/SwapnashreeTripathy/git_assignment_HeroVired/assets/139486876/57b3fa0f-5cd8-42d1-8bb1-4d8cf56e3b55)
   
   ![image](https://github.com/SwapnashreeTripathy/git_assignment_HeroVired/assets/139486876/65e7e864-b7eb-415e-ad1f-aac26c70617b)
   
7. To View all the LFS files getting tracks.<br>
   "git lfs track"<br>
   
8.  Push the commit to the origin lfs.<br>
   "git push -u origin lfs"<br>
   
    ![image](https://github.com/SwapnashreeTripathy/git_assignment_HeroVired/assets/139486876/0e8650d0-e250-4bc9-a32e-9a400556d867)

   
10. Clone the Repo in any other folder to Check if the Large File is getting downloaded properly<br>
   "git clone < ssh repo link>"<br>
   
   ![image](https://github.com/SwapnashreeTripathy/git_assignment_HeroVired/assets/139486876/81e18baf-e446-48eb-a531-8b0e72453ba6)

   


