# git remote

When working with git, a **remote** is any git repository that is not on the machine youre working on.
GitHub is the site that will host your remote repositories.

### Adding a remote

A remote can be added with the `git remote add` command, followed by the name and location of the remote.

the name is a local name, meaning its your label and does not impact the actual remote.

```
git remote add origin https://github.com/ElevenFiftyAcademy/GitFundamentals.git
```
### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote
```
git remote remove origin
```

## Resources

-[Git Remote Documentation](https://git-scm.com/docs/git-remote)
---
[Back to home](../README.md)