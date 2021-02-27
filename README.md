1 . Assuming that you aren't sure whether you're currently inside of a Git repository, write the command (or commands) that will give you this information.

Answer: There are 2 commands that allow you see the information about a git repository if you are in a repo or not. 
	git status - this command allows you to see if you are working in a git repository or not. This also checks if the repository is the latest version.
	git log - this command shows us if the current work is already logged into the local repository or not. 

2. Assuming that you are currently within a Git repository, write the command (or commands) that will create a new file named 'hello-world.txt' then stage and commit it.

Answer: Steps that are followed are:
	touch hello-world.txt
	git add .
	git commit -m " adding hello-world.txt to the repo" 
	
