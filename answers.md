Answer 1- git version 2.17.1
Answer 2-user.name=Your name
user.email=Your email
Answer 3-usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   reset      Reset current HEAD to the specified state
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   branch     List, create, or delete branches
   checkout   Switch branches or restore working tree files
   commit     Record changes to the repository
   diff       Show changes between commits, commit and working tree, etc
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.

Answer 4-siyer@odd05:~/git-lab$ git status
On branch main
nothing to commit, working tree clean

Answer 5 - On branch main
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   README.md

Answer 6-siyer@odd05:~/git-lab$ git status
On branch main
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	modified:   README.md

Answer 7-siyer@odd05:~/git-lab$ git status

On branch main
nothing to commit, working tree clean
siyer@odd05:~/git-lab$ 
siyer@odd05:~/git-lab$ 

Answer 8- siyer@odd05:~/git-lab$ git log
commit 62064aa58220fe81b0b597867bfeedde36202bc2 (HEAD -> main)
Author: Sheil Iyer <si625521@ohio.edu>
Date:   Tue Sep 6 18:05:20 2022 -0400

    Initial commit

Answer 9- On branch main
nothing to commit, working tree clean
siyer@odd05:~/git-lab$ 

Answer 10-They were reflected within my local copy

Answer 11- siyer@odd29:~/git-lab$ git push --set-upstream origin main
Authenticated to github.com ([140.82.113.3]:22).
Counting objects: 9, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (5/5), done.
Writing objects: 100% (9/9), 724 bytes | 34.00 KiB/s, done.
Total 9 (delta 0), reused 0 (delta 0)
Transferred: sent 3096, received 2728 bytes, in 0.9 seconds
Bytes per second: sent 3282.9, received 2892.7
To github.com:sheilxo/git-lab.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
siyer@odd29:~/git-lab$ 

Answer 12- Yes, they were reflected.

siyer@odd29:~/git-lab$ git pull
Warning: Permanently added the ECDSA host key for IP address '140.82.112.3' to the list of known hosts.
Authenticated to github.com ([140.82.112.3]:22).
Transferred: sent 2204, received 2760 bytes, in 0.2 seconds
Bytes per second: sent 11182.1, received 14003.0
Already up to date.
siyer@odd29:~/git-lab$ 

Answer 13- 
siyer@odd29:~$ ls -a
.	       .gitconfig		     .nv
..	       git-lab			     Pictures
.bash_history  .gnupg			     .profile
.cache	       .ICEauthority		     Public
.config        .local			     README.FOR.NEW.USERS
.cshrc	       .login			     .solregis
Desktop        .mailrc			     .ssh
Documents      .mozilla			     Templates
Downloads      Music			     Videos
.dtprofile     .nfs0000000010840ed70000000a
.gconf	       .nfs0000000010840efc0000010d
siyer@odd29:~$ 



