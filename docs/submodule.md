# SubModule Support


## Recurse on

The actual command will also execute themselves on submodules

* [git-status](commands/git-status.md)
* [git-amend](commands/git-amend.md)
* [git-commit](commands/git-commit.md)

By default, this command will recurse applying the command to the submodules.

You can disable this behavior with the no-recurse flag: `-nr` or `--no-recurse`

Example:
```bash
git-amend -nr
```

## Recurse off

These operations will not recurse

* [git-feature-merge](commands/git-feature-merge.md)
* [git-feature-squash](commands/git-feature-squash.md)

You need to do it first on each submodule, then on the main repo.
