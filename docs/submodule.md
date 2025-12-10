# SubModule Support

The actual command will also execute themselves on submodules

* [git-status](commands/git-status.md)
* [git-amend](commands/git-amend.md)
* [git-commit](commands/git-commit.md)


## No recurse option

By default, the command will recurse applying the command to the submodules.

You can disable this behavior with the no-recurse flag: `-nr` or `--no-recurse`

Example:
```bash
git-amend -nr
```
