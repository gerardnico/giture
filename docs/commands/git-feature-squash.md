% git-feature-squash(1) Version ${VERSION} | git-feature-squash
# git-feature-squash

## DESCRIPTION

This command will squash all feature branch commits to 1 commit.

You can see all commits to be squashed with the [git-feature-log command](git-feature-log.md).

## SYNOPSIS

${SYNOPSIS}


## COMMIT MESSAGE HANDLING

The message shown in the editor will be a concatenation of all subject and body commits.

You can give the subject as argument.

The body of the commit message is created automatically.
It's created via concatenation if all subjects and body of commits message
of the working branch.

At the end, the editor is open to give you the possibility to change it.
(tip: `ZZ` to save and close VIM).

We had a scissor line at the end of the commit message.
This line will make git ignore everything below.

## SUBMODULE SUPPORT

By default, we don't recurse on [submodule](../submodule.md).
