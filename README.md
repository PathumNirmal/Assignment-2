# Assignment-2

#1. Create a repository named as “Assignment 2” in github with Readme.md file, Questions must be paste in the readme file.

#2. Clone your repository.
git clone https://github.com/PathumNirmal/Assignment-2.git
Cloning into 'Assignment-2'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 598 bytes | 598.00 KiB/s, done.

#3. Add the text file that should have the answer of Q1.
git add Q1.txt

#4. Add another file to do the following
touch anotherfile.txt

#5. Create another branch .
branch1
Switched to a new branch 'branch1'

#6. Make changes to your files

#7. see if the file change is detected with git status.
git status
On branch branch1
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Q1.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        anotherfile.txt

#8. stage the changes with git add .
git add .

#9. check that the add did what you expected with git status.
On branch branch1
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   README.md
	modified:   anotherfile.txt

#10. make the commit with git commit.

#11. Write a meaningful commit message (e.g. "Answers question 1").
git commit -am "Questions Answers"
On branch branch1
nothing to commit, working tree clean

#12. check that your working directory is clean with git status
git status
On branch branch1
nothing to commit, working tree clean



