***Git Assignment***

*Procedure*

**Step 1:**
 - Created the repository on Github and cloned it in local enviroment.
 - Created HotFix and Integration Branch which is braching out of Main Branch.
 
**Step 2:**
 - Creating two branches Feature1 and Feature2 out of Integration Branch.
 - Adding changes then adding 2 reviewers, merging the pull request to integration after reviewer's approval.

 
**Step 3:**
  - In Local Enviroment , changing and commit in Feature1.
  - But Now, we want ahead of the merge happend in the origin/Feature2. So we do this command to rebase `git pull --rebase`. It means our local commit will     ahead of previous commit while pulling from the remote.
  
**Step 4:**
   -  Changes in Integration branch merged into Production(main) and HotFix branch
 
**Step 5:**
   -  In HotFix branch made a quick fix and merged into Integration and Production branch

**Step 6:**
   -  Finally deleted Feature1, Feature2, HotFix branches after completing the above steps.
 
 ![image](https://user-images.githubusercontent.com/123351581/214658476-a6beb7be-ce2d-404f-ac04-36e8452b0ed0.png)
 
**Commands**	

- To clone the repository: `git clone`
- To view the current logs graph for the repository `git log --online`
- To push the local changes onto origin `git push`
- To pull changes from origin to local `git pull`
- To navigate between the branches created by git branch `git checkout`
- To create or delete branches: `git branch`
- To delete a particular branch `git checkout -d [branch name]`
- To switch in a branch or create then switch to that branch if it doesn't exist `git checkout -b [branch name]`
