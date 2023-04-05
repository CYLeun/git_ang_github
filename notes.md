# Init Git
git: version control

github - allows collaborations

# In termineal
git init            (once - start tracking process flow)
git add <filename>  (start tracking specific files)
git commit -m "<string-comments>"  (add comments)
git diff <filename> (shows all changes)
git log             (shows what's been done)
git lg              (Shorten version of git log)
git status          (status of current folders)
git branch          (Shows where you are)
    # when type git log --> show commit <Long Hash letters>

                    # Never work from the main branch
git branch dev/<new branchname> (Add a new branch)
git switch dev/<new branchname> (Switch to new branch)
    # Bascially creating different versions/ copy in each branch and different people can work on different branch --> ultimatly merge into same one
git merge dev/<branch name>     (merge branch into master)
vim                 (vim mode)

git config --global init.defaultBranch main 
                    (Change branch name from master to main) 
git checkout -b <new_branch> (create new branch and switch)

# once pull request been made --> dont work on the same brance again

# pushing to staging & test before pushing to main
staging -> dev (push everything to staging first and then when approve, push it to main) # can change default branch from <main> to <staging>
main -> production
db -> backup

# General terminal commands
ls      (Show files in this directory)
ls -F   ()
ls -aF  (Shows hidden files as well)


# Extra info
(Add whole folder but not some specific files)
adding .gitignore file that contain name of files that you dont want to add [REMEMBER TO ADD .DS_Store to .gitignore cause there's password]
git add .
git commit -m "add gitignore"

# next to the file in VScode
A - added
U - Not tracked
M - Modified


cmd + j = open terminal in vscode
