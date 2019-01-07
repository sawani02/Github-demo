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

$ git commit -m "added test.txt"

$ git push


   
  Refresh github repo and you should be able to see the changes with test.txt file.
  
  # Create New Branch
  git branch navbar
  git checkout navbar  
  
  this will go to that branch
  git branch
  you can see on which branch you are currently working, branch highlighted in green is the one on which you are working.
  $ git branch
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





