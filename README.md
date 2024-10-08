# git-collab

1. Both merges above are fast-forward merges. Explain.
  Both merges are fast-forward merges because there are only changes made to branches that are not the master branch. The new branches are      created, changes are made, and then the branches are merged. This effectively forces the master branch to "catch up" with the branch that     is merging to the master branch. If a change had been made to the master branch before the non-master branch was merged, this would not be    a fast forward merge.


c. A scenario that would not involve a merge conflict between develop and conflict_branch despite some change, would be if there was a change but on a different line in the file. This would not cause a merge conflict because both changes could co-exist. There is only a merge conflict if both commits have competing information.
