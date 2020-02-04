#### git status

The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven’t, and which files aren’t being tracked by Git.

#### cd..

Move up a directory

#### mkdir bash-git-basics-eng53

Makes a directory (folder)

### git init
Initialized empty Git repository in C:/Users/Tefileo Stephens/code/bash-git-basics-eng53/.git/

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ touch README.md

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ ls
README.md

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ git add .

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ git commit -m 'initial commit'
[master (root-commit) 5fec9b9] initial commit
 Committer: Tefileo Stephens <TStephens@spartaglobal.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ git remote add origin git@github.com:Tefileo/git-bash-eng53.git

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ get remote --v
bash: get: command not found

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ get remote --v
bash: get: command not found

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ git remote add origin git@github.com:Tefileo/git-bash-eng53.git
fatal: remote origin already exists.

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ git push -u origin master
Warning: Permanently added the RSA host key for IP address '140.82.118.4' to the list of known hosts.
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 220 bytes | 220.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To github.com:Tefileo/git-bash-eng53.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ get remote --v
bash: get: command not found

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$ git push --help

Tefileo Stephens@lt-lon-W061 MINGW64 ~/code/bash-git-basics-eng53 (master)
$
