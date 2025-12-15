# SubModule Support

Commands supports submodule command recursion.

## Default behavior

They get a default behavior:

* [recurse on](#recurse-on) - recurse
* [recurse off](#recurse-off) - don't recurse

### Recurse on

The following commands will also execute themselves on submodules by default

* [git-branch](commands/git-branch.md)
* [git-commit](commands/git-commit.md)
* [git-feature-log](commands/git-feature-log.md)
* [git-log](commands/git-log.md)
* [git-status](commands/git-status.md)
* [git-tag](commands/git-tag.md)

You can disable this behavior with the `no-recurse` flag. ie

* `-nr`
* or `--no-recurse`

Example:

```bash
git-log -nr
```

### Recurse off

These commands will not recurse by default

* [git-amend](commands/git-amend.md)
* [git-feature-merge](commands/git-feature-merge.md)
* [git-feature-squash](commands/git-feature-squash.md)

You can recurse by adding the recurse flag. ie:

* `-r`
* or `--recurse`

Example:

```bash
git-feature-squash -r
```
