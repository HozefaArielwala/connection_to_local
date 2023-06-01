1. `git init` - Powers your folder to be managed by git and initializes the new empty repository.It also creates a .git folder thats has all the relevant logic to manage the versions of your project
2. `Working area` --> There can be bunch of files that are not currently handled by git. It means that changes done or to be done in those files are not managed by git yet.A file which is in working area is considered to be not in the staging area.
when we do git status and we see a bunch of untracked files then these are actually called to be in a working area.
3. `Staging area` --> What all files are going to be part of the next version that we will create . This staging area is the place where git knows what changes will be done from the last version to the next version.
4. `Repository Area` --> This area actually contains the details of all you previously registered versions. And the files in this area, git already manages them and knows them and knows their version history.
5. `git add <file>` --> moves files from working area to staging area
6. `git rm --cached <file>` --> moves files back from staging area to working area
7. In git the version are managed using commits
8. One commit is equal to one version
9. `Commit` --> commit is the particular version of the project. It captures a snapshot of the project staged changes and creates a version out of it.
10. `git commit -m <commit_name>` --> registers staging changes to a commit. Here -m denotes message for the commit then we writes the commit message in double inveryted commas
11. If it is committed then basically it is the part of the repository area
12. `git log` --> To see all of the commits or list down all the commits of the repository
13. If you want to get out of the git log then press q
14. `git restore <file>` --> delete everything which is in staging area but not commited.this can be useful, if we did some dirty piece of code and now no more want it. Instead of changing line by line we can restore it or you can say restore last clean version of the file.
15. `git restore --staged <file>` --> It removes file from changes from staging area to the working area.
this only works if changes are in your staging area.
