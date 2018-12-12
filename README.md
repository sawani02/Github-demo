# Github-demo

Create a new Github repo:

On your computer, go to the folder, where you want to save the copy of git repo

git clone https://github.com/sawani02/Github-demo

The github repository will get saved.

cd Github-demo

ls

You will see readme.md file

cat README.md
To see the demo text

echo 'Hello Sawani Soman' > test.txt

git add test.txt

Sawanis-MacBook-Pro:Github-demo sawani$ git commit -m "added test.txt"
[master a30e838] added test.txt
 1 file changed, 1 insertion(+)
 create mode 100644 test.txt
Sawanis-MacBook-Pro:Github-demo sawani$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/sawani02/Github-demo.git
   b95cf37..a30e838  master -> master
   
  Refresh github repo and you should be able to see the changes with test.txt file.
  
  # Create New Branch
  git branch navbar
  git checkout navbar  
  
  this will go to that branch
  git branch
  you can see on which branch you are currently working, branch highlighted in green is the one on which you are working.
  Sawanis-MacBook-Pro:Github-demo sawani$ git branch
  master
* navbar


echo "Navbar feature" > feature.txt
git add feature.txt
git commit -m "new feature added"
git push origin navbar

On master branch you will only see one file test.txt
On navbar branch you will see feature.txt

##Merge navbar branch to master branch
git checkout master

- go to master branch

git merge navbar

git push

git push origin master --force





