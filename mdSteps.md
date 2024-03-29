## Steps to push a markdown file to GitHub

* Step 1: Open a new repository by clicking +New repository button on your github account. Give a name, say new_repo. Select public and Initialize this repository with a README.
* Step 2: Open the terminal, and set your working directory, say Desktop
* Step 3: Type git clone https://github.com/shoaibur/new_repo.git. This will automatically create a folder or subdirectory named new_repo in your current working directory.
* Step 4: Type cd new_repo
* Step 5: Type git remote -v. If you see the remote origin, then you do not need to add the origin, otherwise type git add remote origin https://github.com/shoaibur/new_repo.git
* Step 6: Type touch mdSteps.md. Assuming that the markdown file name is mdSteps.md. This will create a markdown file in the new_repo directory. The file is empty, and edit that according to requirement. Other existing files can also be edited, changed, renamed, deleted.
* Step 7: Type git status to see if the file is added into the directory
* Step 8: Type git add . or git add mdSteps.md to add the file for committing
* Step 9: Type git status to see if the file is ready for committing
* Step 10: Type git commit -m "msg"
* Step 11: Type git status to see if the file is committed, if so there will be no such file for committing
* Step 12: Type git log to see the changes in your current working directory. After these steps, the file is ready in the local machine, and is ready to push to github.
* Step 13: Type git push origin master. This will push master to remote origin that we created before, in step 5. Refresh the repository website, and you should see mdSteps.md file there.