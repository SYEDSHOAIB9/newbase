mkdir stashex
cd stashex
git init
echo "statsh example" > file.txt
git add .
git stash
 git commit -m "Initial commit"
 git stash
 git checkout branch_a
 git branch branch_a
 git checkout branch_a
 echo "some contents to stash" > fil1.txt
 git add .
 git stash
 git checkout branch_B_name
 git branch branch_B_name
 git checkout branch_B_name
 echo "some text to add" > bfile.txt
 git add .
 git commit -m "Fix the bug in branch B"
 git checkout branch_a
 git stash pop
