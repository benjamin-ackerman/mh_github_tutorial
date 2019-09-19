# Clone repo into RStudio project:
1. Make Github repo on Github.com
2. Click "Clone or Download" on top right and copy link
3. Open RStudio, click on "New project" —> "Version Control" —> "Git" —> paste the link you just copied
4. Create a new R script called "test_script.R" and add the code `print("Yay Github!")`
5. Look at the “git” pane in the upper right of RStudio to see the staging status of the files
6. In the bottom right "Files" pane, open the .gitignore and add `*.Rproj` to the file. What happens in the "git" pane?
7. Click “Commit” in "git" pane and check boxes of items you want to stage
8. Type commit message
9. PUSH!
10. Verify that the files are updated in the Github repo online.

# Push existing RStudio project to new Github repo:
1. Make Github repo (DO NOT INITIALIZE WITH README) and keep the page open. There will be text to copy under where it says "…or create a new repository on the command line." Highlight and copy it all.
2. Go to existing R project.
3. Go to the “Terminal” pane in the Console and paste the code from Github to add a README, initialize repo and push to Github
4. Close and re-open the R project to see that the "git" panel has appeared!
5. Add (stage) all files, commit them, and push.
6. Verify that the files are uploaded in the Github repo online.

# Good Team Workflow: Issues, Branches and Pull Requests
1. Create an issue on Github by going to “Issues” tab and clicking “New Issue” green button
2. Describe the issue with a title and a comment. Be informative, think about it as a “to do list”
3. Create a branch in RStudio's "git" panel using the little flowchart icon next to where it says "Master." Call the branch "issue_(issue number)"
4. Edit the scripts to make all changes related to the issue.
5. Add, commit, push to that branch. For your commit message, have it start with "Closes issue #(issue number): " and then add more informative message.
6. Switch branch to Master by clicking on the "issue_(issue number)" icon in the "git" pane
7. Then go back to github and click ‘Compare and open a pull request”
8. Pull request checks if there’s any merge conflict. If not: turns green, click “merge” to merge with master
9. Delete branch
10. Close issue! 
