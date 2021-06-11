# git remote

When working with git, a **remote** is any git repository that is not on the machine you're working on. THe counterpoint to htis is **local**, or the machine that is being developed on.

Take GitHub for example. While git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that respoitory back down or share it with others.

**Note**: While the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two.

### Adding a remote

A remote can be added with teh `git remote add` command, folowed by the name and location of the remote. 

The name is a local naem, meaning it's yhour label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```
### Removing a remote

A remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## Resources

- [Git Remote Documentation](gttps://git-scm.com/docs/git-remote)
---
[Back to home](../README.md)