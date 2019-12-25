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


 ✘ steve@baggiyong-ui-MacBook-Air  ~/Desktop/git   master ●  git add README.md
 steve@baggiyong-ui-MacBook-Air  ~/Desktop/git   master ✚  git commit -m "Change README.md"
[master c17f974] Change README.md
 1 file changed, 45 insertions(+)
 steve@baggiyong-ui-MacBook-Air  ~/Desktop/git   master  git commit -m "Change README.md"
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working tree clean
 ✘ steve@baggiyong-ui-MacBook-Air  ~/Desktop/git   master  git push origin master
Counting objects: 3, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 619 bytes | 0 bytes/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/hunter0x01/git.git
   0738a45..c17f974  master -> master


