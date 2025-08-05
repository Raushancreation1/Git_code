1. `git init` -> Powers your folder to be git, and managed by git, and initialises a new empty 
repository. It also creates a .git folder that has all the relevant logic to menage versions of your project.


2. `Working Area` -> There can be a  bunch of files that are not currently handled by git.
It means that changes done or to be done in those files are not managed by git yet.
A file which is in Working Area is considered to be not in the stagin area.
When we do `git Status` and we see abunch if `untracked files` then these are actually called to be in the Working area.

 
3. `Staging area` -> What all files are going to be part of the next versions that we will create.
This staging area is the place where git knows What changes will be done from the last version to the next version.

4. `repository Area` --> This area actually contains the details of all you previous registerd version. and the files in This area, git already managed them and knows their version history. 


5. `git and <file>` -> moves file from Working area to staging area to Working area 

6. `git re --cached <file>` -> moves file back from staging area to Working area 

7. `commit` -> commit is a particular version of the project. It captures a snapshot of the project`s staged changes and creates a version out of it. 

8. 'git commit' -> registers stagin changes to a commit


9. ` git log ` -> list downs all the commit of the repository. if you want to exit out of git log prompt press `q`.  

10. `git restore <file> ` -> it removes all files changes froms the staging area to be committed. this can be useful, if we did some dirty piece of code and now no more want it. Instead of deleting every change line by line, we can restore it or can you say restore last clean version of the file.

11. `git restore --staged <file>` -> it removes file from changs from staging area to the Working area.
this only works if changes are in your staging area 

12. ``