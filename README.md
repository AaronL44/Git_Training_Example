# Git and GitHub notes/cheat sheet

### LIST OF USEFUL COMMANDS:
- <span style="color: green;">*git init*</span> = Provides all basic git files needed to start.
<br>

- <span style="color: green;">*git remote add origin <(link)>*</span> = Links your local repository to a remote repository (e.g., GitHub).
  
- <span style="color: green;">*git branch -M main*</span> = Renames the current branch to main (if it's not already named main).

- <span style="color: green;">*git push -u origin main*</span> = Pushes your local commits to the remote repository and sets origin/main as the default upstream branch.

- <span style="color: green;">*git reset <(file)>*</span> = Unstage a file. 
 
- <span style="color: green;">*git add*</span> followed by filename = Adds the file to the staging area. 

- <span style="color: green;">*git add .*</span> = Adds everything to staging area.

- <span style="color: green;">*git commit -m “meaningful message”*</span> = Move file from staging area to local repo.

  - <span style="color: green;">*-m*</span> = Message command which allows us to keep track of commits (Version Tag).

- <span style="color: green;">*git status*</span> = Shows the current state of your repository, including **modified**, **stages** and **untracked files**, helping you see what changes need ot be committed.

- <span style="color: green;">*git diff*</span> = Shows the differences between file versions, helping identify changes made but not yet staged or committed.

- <span style="color: green;">*git push*</span> = Uploads your committed changes from your local repository to a remote repository (Github).

  - <span style="color: green;">*git push origin main*</span> = Pushes to the main branch specifically.

- <span style="color: green;">*git pull*</span> = Fetches the latest changes from a **remote repo** and merges them into your **local branch**.

    - <span style="color: green;">*git pull origin main*</span> = Pulls updates from the **main** branch of the remote repo.

- <span style="color: green;">*git log*</span> = Shows the **history of commits** in a repo, including commit IDs, authors, dates and messages.

  - <span style="color: green;">*git log --oneline*</span> = Shows a shorter one lined log.

- <span style="color: green;">*git ls-files*</span> = Shows all git files. However the files which start with "." still won't show (hidden files).

- <span style="color: green;">*:q*</span> = Used to **exit** vim or nano editors.

- <span style="color: green;">*git diff HEAD*</span> = Shows changes to current branch since the last commit.

<br>

### FILE NAMES IN GIT DIRECTORIES:

- <span style="color: yellow;">*./*</span> = Refers to the **current directory** in the file system. Used for working with files.
<br>

- <span style="color: yellow;">*.//*</span> = Location I was in previously.

- <span style="color: yellow;">*HEAD file*</span> = The latest commit in your current branch. It represents where you are in the Git history.

- <span style="color: yellow;">*config file*</span> = Stores configuration of the repository.

- <span style="color: yellow">*Description file*</span> = A text file describing the repository (mainly for Git hosting services, but unused in standard Git). 

- <span style="color: yellow;">*hooks/*</span> = Contains scripts that run automatically at certain Git events (e.g., pre-commit, post-commit). Useful for automation.

- <span style="color: yellow;">*info/*</span> = Stores global excludes (ignored files) and other repository metadata.

- <span style="color: yellow;">*objects/*</span> = Stores all commits, files, and other Git data in a compressed format.

- <span style="color: yellow;">*refs/*</span> = 	Contains references to branches, tags, and remote tracking branches.


