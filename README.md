'''
Microsoft Windows [Version 10.0.18362.356]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\Users\IME42>git commit -m "new one"
warning: could not open directory 'Application Data/': Permission denied
warning: could not open directory 'Cookies/': Permission denied
warning: could not open directory 'Local Settings/': Permission denied
warning: could not open directory 'My Documents/': Permission denied
warning: could not open directory 'NetHood/': Permission denied
warning: could not open directory 'PrintHood/': Permission denied
warning: could not open directory 'Recent/': Permission denied
warning: could not open directory 'SendTo/': Permission denied
warning: could not open directory 'Templates/': Permission denied
warning: could not open directory '시작 메뉴/': Permission denied
On branch master

Initial commit

Untracked files:
        .dotnet/
        .eclipse/
        .gitconfig
        .idlerc/
        .jmc/
        .p2/
        .tooling/
        3D Objects/
        AppData/
        Contacts/
        Desktop/
        Documents/
        Downloads/
        Favorites/
        IntelGraphicsProfiles/
        Links/
        MicrosoftEdgeBackups/
        Music/
        NTUSER.DAT
        NTUSER.DAT{cddd3bcf-aca1-11e9-9349-d03bee570365}.TM.blf
        NTUSER.DAT{cddd3bcf-aca1-11e9-9349-d03bee570365}.TMContainer00000000000000000001.regtrans-ms
        NTUSER.DAT{cddd3bcf-aca1-11e9-9349-d03bee570365}.TMContainer00000000000000000002.regtrans-ms
        OneDrive/
        Pictures/
        Saved Games/
        Searches/
        Source/
        Videos/
        eclipse-workspace/
        eclipse/
        ntuser.dat.LOG1
        ntuser.dat.LOG2
        ntuser.ini

nothing added to commit but untracked files present

C:\Users\IME42>git add 20190924_Quiz1.py
fatal: pathspec '20190924_Quiz1.py' did not match any files

C:\Users\IME42>cd C:\patternRecognition

C:\patternRecognition>git add 20190924_Quiz1.py

C:\patternRecognition>git commit -m "hello"
[master (root-commit) 90e1aee] hello
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 20190924_Quiz1.py

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git remote add "hello" "https://github.com/zxas14/git-.git"

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git remote add "https://github.com/zxas14/git-.git"
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


C:\patternRecognition>git remote -m "https://github.com/zxas14/git-.git"
error: unknown switch `m'
usage: git remote [-v | --verbose]
   or: git remote add [-t <branch>] [-m <master>] [-f] [--tags | --no-tags] [--mirror=<fetch|push>] <name> <url>
   or: git remote rename <old> <new>
   or: git remote remove <name>
   or: git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand


C:\patternRecognition>git remote add 20190924_Quiz1.py "https://github.com/zxas14/git-.git"

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git push 20190924_Quiz1.py
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream 20190924_Quiz1.py master


C:\patternRecognition>git push --set-upstream 20190924_Quiz1.py master
To https://github.com/zxas14/git-.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/zxas14/git-.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition>git push --help

C:\patternRecognition>git push -f
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git add 20190924_Quiz1.py

C:\patternRecognition>git commit --help

C:\patternRecognition>git commit -m "hello"
On branch master
Untracked files:
        20190930_Quiz2_solution.py
        git-/

nothing added to commit but untracked files present

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git add 20190930_Quiz2_solution.py

C:\patternRecognition>git commit -m "hello"
[master e4a424f] hello
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 20190930_Quiz2_solution.py

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git push https://github.com/zxas14/git-.git
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/zxas14/git-.git master


C:\patternRecognition>git push --set-upstream https://github.com/zxas14/git-.git master
To https://github.com/zxas14/git-.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/zxas14/git-.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition>git pull
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=<remote>/<branch> master


C:\patternRecognition>git push https://github.com/zxas14/git-
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/zxas14/git- master


C:\patternRecognition>git push --set-upstream https://github.com/zxas14/git- master
To https://github.com/zxas14/git-
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/zxas14/git-'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition>git --help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

C:\patternRecognition>git clone https://github.com/zxas14/git-.git
fatal: destination path 'git-' already exists and is not an empty directory.

C:\patternRecognition>git push\
git: 'push\' is not a git command. See 'git --help'.

The most similar command is
        push

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git add 20190924_Quiz1.py

C:\patternRecognition>git commit -m "hello"
On branch master
Untracked files:
        git-/

nothing added to commit but untracked files present

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git remote add 20190924_Quiz1.py https://github.com/zxas14/git-
fatal: remote 20190924_Quiz1.py already exists.

C:\patternRecognition>git clone https://github.com/zxas14/git-
fatal: destination path 'git-' already exists and is not an empty directory.

C:\patternRecognition>git remote add https://github.com/zxas14/git-
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


C:\patternRecognition>git remote add 20190924_Quiz1.py https://github.com/zxas14/git-.git\
fatal: remote 20190924_Quiz1.py already exists.

C:\patternRecognition>git remote add 20190930_Quiz2_solution.py https://github.com/zxas14/git-.git

C:\patternRecognition>git push --help

C:\patternRecognition>git push -f
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git config --help

C:\patternRecognition>git config -l
core.symlinks=false
core.autocrlf=true
core.fscache=true
color.diff=auto
color.status=auto
color.branch=auto
color.interactive=true
help.format=html
rebase.autosquash=true
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
http.sslbackend=openssl
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge --skip -- %f
filter.lfs.process=git-lfs filter-process --skip
filter.lfs.required=true
credential.helper=manager
user.email=zxas14@naver.com
user.name=bubble-star
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.hello.url=https://github.com/zxas14/git-.git
remote.hello.fetch=+refs/heads/*:refs/remotes/hello/*
remote.20190924_Quiz1.py.url=https://github.com/zxas14/git-.git
remote.20190924_Quiz1.py.fetch=+refs/heads/*:refs/remotes/20190924_Quiz1.py/*

C:\patternRecognition>git branch solution_branch

C:\patternRecognition>git branch checkout

C:\patternRecognition>git branch --help

C:\patternRecognition>git brabch -a
git: 'brabch' is not a git command. See 'git --help'.

The most similar command is
        branch

C:\patternRecognition>git branch -a
  checkout
* master
  solution_branch

C:\patternRecognition>git --help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git psuh https://github.com/zxas14/git-
git: 'psuh' is not a git command. See 'git --help'.

The most similar command is
        push

C:\patternRecognition>git push https://github.com/zxas14/git-
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/zxas14/git- master


C:\patternRecognition>git push --set-upstream https://github.com/zxas14/git- master
To https://github.com/zxas14/git-
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/zxas14/git-'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition>git fetch

C:\patternRecognition> git push --set-upstream https://github.com/zxas14/git- master
To https://github.com/zxas14/git-
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/zxas14/git-'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git push https://github.com/zxas14/git-.git
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/zxas14/git-.git master


C:\patternRecognition> git push --set-upstream https://github.com/zxas14/git-.git master
To https://github.com/zxas14/git-.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/zxas14/git-.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition>git fetch  git push --set-upstream https://github.com/zxas14/git-.git master
error: unknown option `set-upstream'
usage: git fetch [<options>] [<repository> [<refspec>...]]
   or: git fetch [<options>] <group>
   or: git fetch --multiple [<options>] [(<repository> | <group>)...]
   or: git fetch --all [<options>]

    -v, --verbose         be more verbose
    -q, --quiet           be more quiet
    --all                 fetch from all remotes
    -a, --append          append to .git/FETCH_HEAD instead of overwriting
    --upload-pack <path>  path to upload pack on remote end
    -f, --force           force overwrite of local reference
    -m, --multiple        fetch from multiple remotes
    -t, --tags            fetch all tags and associated objects
    -n                    do not fetch all tags (--no-tags)
    -j, --jobs <n>        number of submodules fetched in parallel
    -p, --prune           prune remote-tracking branches no longer on remote
    -P, --prune-tags      prune local tags no longer on remote and clobber changed tags
    --recurse-submodules[=<on-demand>]
                          control recursive fetching of submodules
    --dry-run             dry run
    -k, --keep            keep downloaded pack
    -u, --update-head-ok  allow updating of HEAD ref
    --progress            force progress reporting
    --depth <depth>       deepen history of shallow clone
    --shallow-since <time>
                          deepen history of shallow repository based on time
    --shallow-exclude <revision>
                          deepen history of shallow clone, excluding rev
    --deepen <n>          deepen history of shallow clone
    --unshallow           convert to a complete repository
    --update-shallow      accept refs that update .git/shallow
    --refmap <refmap>     specify fetch refmap
    -o, --server-option <server-specific>
                          option to transmit
    -4, --ipv4            use IPv4 addresses only
    -6, --ipv6            use IPv6 addresses only
    --negotiation-tip <revision>
                          report that we have only objects reachable from this object
    --filter <args>       object filtering
    --auto-gc             run 'gc --auto' after fetching
    --show-forced-updates
                          check for forced-updates on all updated branches


C:\patternRecognition>git fetch https://github.com/zxas14/git-.git
warning: no common commits
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), done.
From https://github.com/zxas14/git-
 * branch            HEAD       -> FETCH_HEAD

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git push https://github.com/zxas14/git-.git
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream https://github.com/zxas14/git-.git master


C:\patternRecognition> git push --set-upstream https://github.com/zxas14/git-.git master
To https://github.com/zxas14/git-.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/zxas14/git-.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition>git push
fatal: No configured push destination.
Either specify the URL from the command-line or configure a remote repository using

    git remote add <name> <url>

and then push using the remote name

    git push <name>


C:\patternRecognition>git push  git push --set-upstream https://github.com/zxas14/git-.git master
fatal: invalid refspec 'https://github.com/zxas14/git-.git'

C:\patternRecognition> git push --set-upstream https://github.com/zxas14/git-.git master
To https://github.com/zxas14/git-.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/zxas14/git-.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition>git --help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

C:\patternRecognition>cd C:\patternRecognition\git-

C:\patternRecognition\git->git push
To https://github.com/zxas14/git-.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/zxas14/git-.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition\git->git fetch https://github.com/zxas14/git-.git
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/zxas14/git-
 * branch            HEAD       -> FETCH_HEAD

C:\patternRecognition\git->git push
To https://github.com/zxas14/git-.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/zxas14/git-.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition\git->git push
To https://github.com/zxas14/git-.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/zxas14/git-.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition\git->git push --set-upstream https://github.com/zxas14/git-.git master
To https://github.com/zxas14/git-.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/zxas14/git-.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

C:\patternRecognition\git->git pull
From https://github.com/zxas14/git-
   7dfce4a..9959cce  master     -> origin/master
Updating 7dfce4a..9959cce
Fast-forward
 README.md | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\patternRecognition\git->git push
Everything up-to-date

C:\patternRecognition\git->git add 20190924_Quiz1.py

C:\patternRecognition\git->git commit "m"
error: pathspec 'm' did not match any file(s) known to git

C:\patternRecognition\git->git commit -m "1"
[master a85ccfd] 1
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 20190924_Quiz1.py

C:\patternRecognition\git->git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 275 bytes | 275.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/zxas14/git-.git
   9959cce..a85ccfd  master -> master

C:\patternRecognition\git->git add 20190930_Quiz2_solution.py

C:\patternRecognition\git->git commit -m "2"
[master a68a605] 2
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 20190930_Quiz2_solution.py

C:\patternRecognition\git->git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 283 bytes | 283.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0)
To https://github.com/zxas14/git-.git
   a85ccfd..a68a605  master -> master

C:\patternRecognition\git->git branch -l
* master

C:\patternRecognition\git->git branch solution_branch

C:\patternRecognition\git->git branch -l
* master
  solution_branch

C:\patternRecognition\git->
'''
