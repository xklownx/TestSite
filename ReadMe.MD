install git

install node js

    npm install -g http-server

# I'm a header

## and a smaller header

powershell notes
PS C:\Users\klopez\Downloads\GitHub> git
usage: git [--version] [--help] [-C <path>] [-c name=value]
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
PS C:\Users\klopez\Downloads\GitHub> git clone https://github.com/xklownx/TestSite.git
Cloning into 'TestSite'...
warning: You appear to have cloned an empty repository.
PS C:\Users\klopez\Downloads\GitHub> dir


    Directory: C:\Users\klopez\Downloads\GitHub


Mode                LastWriteTime         Length Name
----                -------------         ------ ----
d-----        12/8/2017   1:23 PM                TestSite


PS C:\Users\klopez\Downloads\GitHub> cd TestSite
PS C:\Users\klopez\Downloads\GitHub\TestSite> dir
PS C:\Users\klopez\Downloads\GitHub\TestSite> explorer .
PS C:\Users\klopez\Downloads\GitHub\TestSite> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        index.html

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Users\klopez\Downloads\GitHub\TestSite> git add .
PS C:\Users\klopez\Downloads\GitHub\TestSite> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   index.html

PS C:\Users\klopez\Downloads\GitHub\TestSite> git commit
Aborting commit due to empty commit message.
PS C:\Users\klopez\Downloads\GitHub\TestSite> git commit -m "inital commit"
[master (root-commit) cf645b4] inital commit
 1 file changed, 1 insertion(+)
 create mode 100644 index.html
PS C:\Users\klopez\Downloads\GitHub\TestSite> git push
Counting objects: 3, done.
Writing objects: 100% (3/3), 230 bytes | 230.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/xklownx/TestSite.git
 * [new branch]      master -> master
PS C:\Users\klopez\Downloads\GitHub\TestSite> git checkout -b gh-pages
Switched to a new branch 'gh-pages'
PS C:\Users\klopez\Downloads\GitHub\TestSite> git status
On branch gh-pages
nothing to commit, working tree clean
PS C:\Users\klopez\Downloads\GitHub\TestSite> git push
fatal: The current branch gh-pages has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin gh-pages

PS C:\Users\klopez\Downloads\GitHub\TestSite> git push -u origin gh-pages
Total 0 (delta 0), reused 0 (delta 0)
To https://github.com/xklownx/TestSite.git
 * [new branch]      gh-pages -> gh-pages
Branch 'gh-pages' set up to track remote branch 'gh-pages' from 'origin'.
PS C:\Users\klopez\Downloads\GitHub\TestSite> node
node : The term 'node' is not recognized as the name of a cmdlet, function, script file, or operable program. Check
the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ node
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (node:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\klopez\Downloads\GitHub\TestSite> node
node : The term 'node' is not recognized as the name of a cmdlet, function, script file, or operable program. Check
the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ node
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (node:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\klopez\Downloads\GitHub\TestSite> start cmd
PS C:\Users\klopez\Downloads\GitHub\TestSite>


command prompt notes
Your environment has been set up for using Node.js 9.2.1 (x64) and npm.

H:\>node
>
(To exit, press ^C again or type .exit)
>

H:\>C:\Users\klopez\Downloads\GitHub\TestSite
'C:\Users\klopez\Downloads\GitHub\TestSite' is not recognized as an internal or external command,
operable program or batch file.

H:\>c:\
'c:\' is not recognized as an internal or external command,
operable program or batch file.

H:\>C:

C:\Program Files\nodejs>cd C:\Users\klopez\Downloads\GitHub\TestSite

C:\Users\klopez\Downloads\GitHub\TestSite>npm

Usage: npm <command>

where <command> is one of:
    access, adduser, bin, bugs, c, cache, completion, config,
    ddp, dedupe, deprecate, dist-tag, docs, doctor, edit,
    explore, get, help, help-search, i, init, install,
    install-test, it, link, list, ln, login, logout, ls,
    outdated, owner, pack, ping, prefix, profile, prune,
    publish, rb, rebuild, repo, restart, root, run, run-script,
    s, se, search, set, shrinkwrap, star, stars, start, stop, t,
    team, test, token, tst, un, uninstall, unpublish, unstar,
    up, update, v, version, view, whoami

npm <command> -h     quick help on <command>
npm -l           display full usage info
npm help <term>  search for help on <term>
npm help npm     involved overview

Specify configs in the ini-formatted file:
    C:\Users\klopez\.npmrc
or on the command line via: npm <command> --key value
Config info can be viewed via: npm help config

npm@5.5.1 C:\Program Files\nodejs\node_modules\npm

C:\Users\klopez\Downloads\GitHub\TestSite>npm install -g http-server
C:\Users\klopez\AppData\Roaming\npm\http-server -> C:\Users\klopez\AppData\Roaming\npm\node_modules\http-server\bin\http-server
C:\Users\klopez\AppData\Roaming\npm\hs -> C:\Users\klopez\AppData\Roaming\npm\node_modules\http-server\bin\http-server
+ http-server@0.10.0
added 23 packages in 0.959s

C:\Users\klopez\Downloads\GitHub\TestSite>http-server
Starting up http-server, serving ./
Available on:
  http://192.168.1.74:8080
  http://127.0.0.1:8080
Hit CTRL-C to stop the server
[Fri Dec 08 2017 14:27:34 GMT-0700 (Mountain Standard Time)] "GET /" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/62.0.3202.94 Safari/537.36"
[Fri Dec 08 2017 14:27:34 GMT-0700 (Mountain Standard Time)] "GET /favicon.ico" "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/62.0.3202.94 Safari/537.36"
[Fri Dec 08 2017 14:27:34 GMT-0700 (Mountain Standard Time)] "GET /favicon.ico" Error (404): "Not found"
> http-server stopped.

C:\Users\klopez\Downloads\GitHub\TestSite>git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

C:\Users\klopez\Downloads\GitHub\TestSite>git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        ReadMe.MD

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\klopez\Downloads\GitHub\TestSite>git add .

C:\Users\klopez\Downloads\GitHub\TestSite>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   ReadMe.MD


C:\Users\klopez\Downloads\GitHub\TestSite>git commit -m "added readme"
[master 8728f95] added readme
 1 file changed, 3 insertions(+)
 create mode 100644 ReadMe.MD

C:\Users\klopez\Downloads\GitHub\TestSite>git push
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/xklownx/TestSite.git
   cf645b4..8728f95  master -> master

C:\Users\klopez\Downloads\GitHub\TestSite>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   ReadMe.MD

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\klopez\Downloads\GitHub\TestSite>git commit -am "add some readme examples --scott"
[master 4ce267d] add some readme examples --scott
 1 file changed, 7 insertions(+), 1 deletion(-)

C:\Users\klopez\Downloads\GitHub\TestSite>git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

C:\Users\klopez\Downloads\GitHub\TestSite>git push
Counting objects: 3, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 372 bytes | 372.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/xklownx/TestSite.git
   8728f95..4ce267d  master -> master

C:\Users\klopez\Downloads\GitHub\TestSite>