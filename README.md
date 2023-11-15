### GIT BASIC INSTRUCTION ###


# Start git in folder
git init

# Add a reference to the server
git remote add origin /HOST/
# Show reposetoris
git removte -v

# Check tracking and modifed files
git status

# Operations with files
git add . (Track all files)
gir add filename.extension

# Commit changes
git commit -m "CHANGE INFO MESSAGE" // -m for message 
git commit -am "MESSAGE" // -a to commit modified files (IGNORING ALL NEW)

# Send to the host
git push
git push origin master

# Take from host
git clone
git pull origin BRANCH_NAME


### BRANCHES ###

# Branches check
git branch NAME

# Change or create branch
git checkout (Change)
git checkout -b NAME (Create)

# Compound branches and other
git diff (SHOW CHANGES)
git merge NAME
git check out NAME

# Abort Changes in GIT
git reset HEAD~1 / Number stands for steps to undo

HELLO!

git rm --cached git-demo