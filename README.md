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


#13. check that your commit succeeded as expected with git log
commit ce133a520f7231e5a151a2f7bc607fb96948fd8e (HEAD -> branch1)
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:58:56 2021 +0530

    Q12 answer

commit dead9fd477376f8886574ee88156661a07a8f9c0
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:57:31 2021 +0530

    Q11 answer

commit 9dfd67278ee8cd711d85376a0accf2afb4d5380b
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:51:07 2021 +0530

    Q10 answer

commit 24614a6ece7562494505bfa831a1bf05ffbc14b7
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:49:42 2021 +0530

    Q9 answer

commit a3c26bc4cde1134347d8f19b128cfe399a677bae
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:48:30 2021 +0530

    Q8 answer

commit f63b13da42493b1ac81cedf7ef5d6dbcc7ec3702
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:45:23 2021 +0530

    Q7 answer

commit e8ea4632f1373f788854cab87fa0824ae912b91f
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:41:49 2021 +0530

    Q6 answer

commit a7003ef110ae7363298114ec666cb6f2cbb78b6e
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:36:08 2021 +0530

    Q5 answer

commit fa61ba453212e44ffe8320dc7435bb339e0f422d (main)
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:33:29 2021 +0530

    Q4 answer

commit 756f28c6173ef1d9aee927bb0d3163be65d8d2f4
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:30:21 2021 +0530

    Q3 answer

commit bd5d185dad44b5528b77d8f13ea4c1f6a837c778
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:26:41 2021 +0530

    Q2 answer

commit c514d55aa473a8b974a993f0947e7b83a770eda3
Author: PathumNirmal <pathum.nirmal6@gmail.com>
Date:   Mon Sep 13 00:24:35 2021 +0530

    Q1 answer

commit 4e3a5ba213b3dfc9622352981b0c22d047b0f19e (origin/main, origin/HEAD)
Author: PathumNirmal <85049981+PathumNirmal@users.noreply.github.com>
Date:   Sun Sep 12 22:05:23 2021 +0530

    Initial commit



#14. Push your code up to a github repository
git push origin branch1

