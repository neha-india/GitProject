# Add, Modify, Rename, Delete Multiple Files, Commit to Git and Push to GitHub

#### Write steps to do the following
1. Create and edit following files
	- File501.txt
	- File502.txt
2. Modify following files
	- File4.txt
	- File5.txt
3. Rename following files
	- File6.txt to File503.txt
	- File7.txt to File504.txt
4. Delete following files
	- File8.txt
	- File9.txt
5. Commit to local git.
6. Push to GitHub.

#### Make following file changes
	1. Create and edit following files
		- File501.txt
		- File502.txt
	2. Modify following files
		- File4.txt
		- File5.txt
	3. Rename following files
		- File6.txt to File503.txt
		- File7.txt to File504.txt
	4. Delete following files
		- File8.txt
		- File9.txt

#### 2. Git Command
	git status
	
	git add -i
	# Choose 4 to add untracked
	# Choose * to add the files
	# Enter.
	# Choose 2 to update the file.
	# Choose * to update the file.
	# Enter.
	# Choose 7 to quit.
	
	git status
	
	git commit -m 'Modify, Rename, Delete Multiple Files.'
	
	gitk
	
	git push origin master
	
	# Check the file on GitHub.

