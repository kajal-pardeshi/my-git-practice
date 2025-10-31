# My Git Practice Project 
Microsoft Windows [Version 10.0.26100.6725]
(c) Microsoft Corporation. All rights reserved.

C:\Users\IBLAB3>md my_practice

C:\Users\IBLAB3>cd my_practice

C:\Users\IBLAB3\my_practice>cd..

C:\Users\IBLAB3>cd..

C:\Users>cd.

C:\Users>
C:\Users>cd..

C:\>md my_practice

C:\>cd my_practice

C:\my_practice>git clone https://github.com/kajal-pardeshi/my-git-practice.git
Cloning into 'my-git-practice'...
warning: You appear to have cloned an empty repository.

C:\my_practice>cd my-git-practice

C:\my_practice\my-git-practice>git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\my_practice\my-git-practice>echo # My Git Practice Project >README.md

C:\my_practice\my-git-practice>git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

C:\my_practice\my-git-practice>git add README.md

C:\my_practice\my-git-practice>git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


C:\my_practice\my-git-practice>git commit -m "Add initial README.md file"
[main (root-commit) a3d2489] Add initial README.md file
 Committer: BIIB LAB3 <IBLAB3@sbup.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\my_practice\my-git-practice>git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

C:\my_practice\my-git-practice>git push origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 251 bytes | 125.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/kajal-pardeshi/my-git-practice.git
 * [new branch]      main -> main

C:\my_practice\my-git-practice>
