git revert commitID

used to go back to the previous changes from the given commit ID.

when git revert undoes the changes it will automatically create a commit with latest changes.

When reverting the changes of an intermediate commit id then there is a chance we might end up with conflict.

when revert is applied for an initial commit id of a file, then it deletes the file.

git revert will never delete any commit ids.





### Get changes from remote repository

Changes made in remote rep can be taken into local rep

\* In git, changes can be taken to into local rep by using commands:

1\) git clone - used to make a copy of the entire repository

&#x09;	Git clone should not be used in a already existing local repository,

&#x09;	It always keeps the changes in a folder named same as remote repository.

&#x09;	When we clone a repository it already comes with initialization, remote connection and all the branches into local remote branches

&#x20;  git clone <Remote URL>

&#x20;  git clone <Remote URL> <Folder Name> - Used to clone the remote repository in a given foldername.

&#x09;	

2\) git fetch - used to get the changes from remote repository to local branches

&#x09;	

&#x09;	the merge need to be done manually to see the changes in local repository or local branches

&#x09;git fetch <alias> <branchname>



3\) git pull - used to get the changes from remote rep and merge automatically into local repository and branches

&#x09;	\*\*\* Git Pull is a combination of 'git fetch' and 'git merge'

&#x09;	 Git pull will always merge changes into the current branch irrespective of given branch

&#x09;git pull <alias> <branchname>



How to become collaborators in git hub?
-> Open your repository -> Settings -> collaborators -> add people -> find people(GitHub username or GitHub email address)-> add to repository
* Once we add a user to collaborator, the user will get a confirmation mail to become collaborator.



