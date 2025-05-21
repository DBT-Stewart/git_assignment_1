Question 3 and 4 are combined in this folder


Question 3
Step 1: Create a feature branch.
Step 2: Switch to the new branch.
Step 3: open the file and make some changes to it.
Step 4: Add and commit the changes to the new branch.
Step 5: Push the changes to the new feature branch.
Step 6: Create a pull request.
Step 6: As another user in the master branch make some changes to the same file.
Step 7: Add and commit the changes to the master branch.
Step 8: Push the changes to the master branch.
Note: There will be a conflict in the pull request, how do we resolve it??
Hint: git rebase


Question 4
Step 1: Step 1: Create a feature branch.
Step 2: Switch to the new branch.
		open the file and make some changes to it.
		Add and commit the changes to the new branch.
		open the same file and make some changes to it.
		Add and commit the changes to the new branch.
		open the same file and make some changes to it.
		Add and commit the changes to the new branch.
Step 3: Identify the commit or commits that you want to "cherry-pick"(Note the hash of the commit or commits that you want to "cherry-pick")
Step 4: Use the "git checkout" command to switch to the branch where you want to apply the changes.
Step 5: Use the "git cherry-pick" command followed by the commit hash(es) that you want to apply.
