# Git Tutorial


…or create a new repository on the command line
echo "# git" >> README.md
git init
git add README.md


git config --global user.name "Kiyong Park"
git config --global user.email hunter0x01@gmail.com
git commit --amend --reset-author

git commit -m "first commit"
git remote add origin https://github.com/hunter0x01/git.git
git push -u origin master



…or push an existing repository from the command line
git remote add origin https://github.com/hunter0x01/git.git
git push -u origin master


touch file1.txt
touch file2.txt
touch file3.txt
touch file4.txt
touch wrongfile1.txt
touch wrongfile2.txt
touch wrongfile3.txt
touch wrongfile4.txt


Use git rm:

git rm wrongfile1.txt
git commit -m "remove file1.txt"


git rm --cached wrongfile1.txt
git commit -m "remove file1.txt"

git push origin master  


