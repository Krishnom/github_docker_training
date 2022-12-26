GIT training
	What is Version Control System aka VCS?
	Git as VCS and Its advantages.
	GIt installation and initial setup
	Git lifecycle.
	Basic operations-I - Initialize new repo, create files, add changes, commit changes, 
	





----
CVS --- very very old but this was building block for everyone. 
	- server 
	- laptop 
SVN --- old beast
Git --- most advance version of VCS
	--- server
	--- laptop

Basic terminologies
building-app -- BE
		    FE
1. Repo/Repository ---- repo is a remote that links to a folder in your server 
		BE_code/
		FE_code/
2. Remote - Points to the server url to you repo.
3. Branch - Way to split the entry points to repo.
4. Platform - Github, Bitbucket, Gitlab



Git --- Repos
	- locally 
	- Online platform - GitHub, BitBucket(atlassian)






### Git installation and initial setup
	-- macOx/Linux  --- git installed by default
	-- Windows 	    --- GitBash  - https://git-scm.com/download/win
	-- WSL -- Linux running on windows

Create a local git repo.
 git init  -- to create a new repo locally
git status -- Show status of local changes
		  -- shows changed files
		  -- shows staged/unstaged files
		  -- shows untrackted file
 git add 1 -- adds a file to staging


	-- staging	: files in commit area (Changes to be committed:)
	-- unstaging : to remove a file from commit area

git commit -m "first commit"
	-- commit all changes in staging area.
	-- -m command is for the commit message

git diff
	-- shows diffence between staged area and unstaged area. Changes between the staged and unstaged files.



--- Why do we need branches?
	app -- master/main/prod branch/trunk is deployed in production
	|
		Feature1
		Create a new branch -- dev/feature1-> changecode -> Push code-> Review -> Deploy a devopment env - Testing -> Pull Request ->
	
		Feature2
		Create a new branch -- dev/feature2-> changecode -> Push code-> Review -> Deploy a devopment env - Testing -> Pull Request ->	




-- Exercise
1. Init a git repo named streaming-app
2. Add a Readme.md file and commit with message "Readme file added"
3. Add another file "License.md" and commit with message "License file added"
4. add line "# Streaming app to see videos" in README.md file and commit with message "Header added"
5. Add line "## video 1 added" to README.md file and run "git diff" command to identify changes
6. Stage the changes in README.md file and commit.
7. Add line "Copyright: Syeda" to license.md and README.md file both. Staged README.md file only and commit. Do the same for License.md file.





 