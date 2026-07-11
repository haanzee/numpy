# numpy
Numpy Master in Data Science
# Git Commands

Git Repository Commands

git init                  		# Initialize a repository
git clone <repo-url>      		# Clone a remote repository
git status                		# Show repository status
git log                   		# Show commit history
git log --oneline         		# One-line commit history
git show                  		# Show commit details

Git Staging Command

git add <file>            		# Stage a file
git add .                 		# Stage all changes
git restore <file>        		# Discard unstaged changes
git restore --staged <file>  	# Unstage a file

Git Commit Command

git commit -m "message"   	# Commit staged changes
git commit -am "message"  	# Stage tracked files and commit
git commit --amend        	# Modify last commit

Git Branch Command

git branch                		# List branches
git branch <branch-name>  	# Create branch
git checkout <branch>     	# Switch branch
git switch <branch>       		# Switch branch (new command)
git switch -c <branch>   		# Create and switch
git checkout -b <branch>  	# Create and switch (older command)
git branch -d <branch>    	# Delete branch
git branch -D <branch>    	# Force delete branch

Git Merge Command

git merge <branch>        		# Merge branch
git merge --abort         		# Cancel merge

 Git Remote Command

git remote   -v                     	# View remotes
git remote add origin <url>       	# Add remote
git fetch                          		# Fetch changes
git pull                           		# Fetch and merge
git push origin main               	# Push to main branch
git push -u origin main            	# Set upstream and push
git push                           		# Push changes

Git Reset & Revert Command

git reset --soft HEAD~1     		# Undo commit, keep changes staged
git reset --mixed HEAD~1    		# Undo commit, keep changes unstaged
git reset --hard HEAD~1     		# Remove commit and changes
git revert <commit-id>      		# Reverse a commit safely

Git Stash Command

git stash                  			# Save uncommitted changes
git stash list             			# List stashes
git stash apply            			# Apply latest stash
git stash pop              			# Apply and remove stash
git stash drop             			# Delete stash
git stash clear           			# Remove all stashes

Git Tag Command

git tag                    			# List tags
git tag v1.0               			# Create tag
git push origin v1.0        			# Push tag
git push --tags             			# Push all tags

Git Difference Command

git diff                   			# Unstaged changes
git diff --staged          			# Staged changes
git diff HEAD~1 HEAD       		# Compare commits

Git File Operations

git mv old.txt new.txt     		# Rename file
git rm file.txt            			# Remove file
git rm --cached file.txt   			# Remove from Git only

Git Cherry Pick

git cherry-pick <commit-id>

Git Clean Repository

git clean -n    				# Preview files to remove
git clean -f    				# Remove untracked files
git clean -fd  				# Remove untracked files and directories




Git Common Workflow

git clone <repo-url>
git checkout -b feature
git add .
git commit -m "Add feature"
git push origin feature

Git Useful Shortcuts

git status
git add .
git commit -m "message"
git pull
git push
git log --oneline
git branch
git switch main
git merge feature

 ======================================

Any note : __________________________________________________________________ 

