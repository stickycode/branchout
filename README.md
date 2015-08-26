# branchout
Gives you Git super powers

Worktree support gives Git the long missing support for managing multiple lifecycles in a single repository.

But you still need good conventions to do it well. Branchout is the process I've used for a long time and worked very well with Subversion and now Git.

# Structure

On the filesystem it looks like this

Reactor
- Group
  - Lifecycle 1
  - Lifecycle 2
  - Lifecycle 3
- Group 2
  - Lifecycle 4
  - Lifecycle 5
  - Lifecycle 6
