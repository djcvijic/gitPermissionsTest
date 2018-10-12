# gitPermissionsTest

## Hypothesis

Git is able to store permission bits along with files, and checking out those files will save them with the same permissions as those with which they were commited.

## Setup

New repository "gitPermissionsTest" created and cloned, create two empty .sh files, set one of them as executable, the other as non-executable, add & commit & push. Delete the repo locally. Re-clone from remote repository, and attempt to run each file.

## Result

The file that was initially set as executable was able to execute, the file that was initially set as non-executable was not able to execute. Hypothesis confirmed.
