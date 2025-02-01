`git init`-> Powers your golder to be managed by git , and initialises a new empty repository. It also creates a .git folder that has all the relevant logic to manage version of your project

`ls-a`-> to see .git folder present or not
`rm -rf .git` -> to remove initialised git

`git status`->

2. `Working Area`-> There can be bunch of files that are not currently handled by git.
It means that changes done or to be done in those files are not managed by git yet.A file which is in working area is considered to be not in the staging area. when we do  `git status` and we see a bunch of `untracked files` then these are actually called to be in the working area.

`Staging Area`-> What all files are going to be part of next version that we will create. This staging area is the place where git knows what changes will be done from the last version to the next version.

