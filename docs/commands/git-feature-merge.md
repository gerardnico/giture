% git-feature-merge(1) Version ${VERSION} | git-feature-merge

# NAME

Merge 1 commit of the current feature branch into the default branch

## HOW IT WORKS

This command will:

* merge:
  * 1 commit of the current branch
  * into 1 commit on the default branch (ie `main`)
* push the commit to the origin
* switch the branch to the default branch

If you have more than 1 commit in your feature branch, you need to squash them before merging
with the [git-feature-squash](git-feature-squash.md) command.

## SYNOPSIS

${SYNOPSIS}

## SUBMODULE SUPPORT

We don't squash on [submodule](../submodule.md)
