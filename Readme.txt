`git init`-> Powers your golder to be managed by git , and initialises a new empty repository. It also creates a .git folder that has all the relevant logic to manage version of your project

`ls-a`-> to see .git folder present or not
`rm -rf .git` -> to remove initialised git

`git status`->

2. `Working Area`-> There can be bunch of files that are not currently handled by git.
It means that changes done or to be done in those files are not managed by git yet.A file which is in working area is considered to be not in the staging area. when we do  `git status` and we see a bunch of `untracked files` then these are actually called to be in the working area.

`Staging Area`-> What all files are going to be part of next version that we will create. This staging area is the place where git knows what changes will be done from the last version to the next version.
    to add in staginn area:- git add <FileName>
    to remove:- use "git rm --cached <file>..." to unstage

4. `Repository Area` -> This area actually contains the details of all your previous registered version and the files in this area,git already manages then and knows their version history.

5. `git add <files>`-> move files from working area to stagin area

6. `git rm --cached <files>` -> moves files back from staging area to working area

7. `commit` -> Commit is a particular version of the project. It captures a snapshot of the project's staged changes and create a version out of it.

8. `Git commit`-> registers staging changes to a commit

9. `Git log`-> List down all the commits of the repository. if you want to exit out of git log prompt pres `q`.

10. `git restore <file>` -> it removes all the file changes from the staging area to be committed.This can be useful, if we did some dirty piece of code and now no more want it. instead of deleting every change line by line, we can restore it or you can say restore last clean version of the file.


11. `git restore --staged <file>`:- it removes file from changes from stagin area to the working area.
this only work if changes are on your staging area


