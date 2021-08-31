# Github for dummies

github for dummies epub I purchased from humble bundle

## 1 - getting started with Github

github is a source control platform build on git the open source version control software.

* useful Commands
  * git init - initilizes a repository in your current directory.
  * git status - tells you of the current status of git in this directory.
  * git add - will stage a file to be commited to git.
  * git commit - will commit files to the version.
    * -m to make comment.
  * git log - shows all commits made.

for more information on how to use git on the command line, check out the following resources:

The GitHub Git Cheat Sheet at <https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf>
The Visual Git Cheat Sheet at <http://ndpsoftware.com/git-cheatsheet.html>
The Git Docs page at <https://git-scm.com/doc>
<https://learngitbranching.js.org/>

### Branching

Branching is an effective way to prevent conflicts between miltiple developers and features.

Another common way to use branching is to have each feature that you develop be on a different branch, regardless of the collaborator who is building the feature.

You can extend the idea of branching by feature to also have one branch that is your production branch. This branch is what your users will see. Then you can have a development branch, which is one that you can merge features into without changing what your users see.

This type of branching allows you to build a lot of different features, merge them each into the development branch, make sure they all work the way you want, and then merge the development branch into the production

## Github0CLI

GitHub-cli can be used to authinticate with Github using HTTPS or SSH. Instaling the CLI tool will allow you to easily configure these options. <https://help.github.com/articles/caching-your-github-password-in-git.>

### Developer settings
The last section on the Settings page is Developer settings, which you use only if you’re building an application that accesses the GitHub API, which means the application needs to access GitHub data in some way.

Three settings appear in this section:

OAuth apps: Applications you have registered to use the GitHub API.
GitHub apps: Applications that integrate with and extend GitHub.
Personal access tokens: Similar to SSH keys, tokens that allow you to access the GitHub API without requiring authentication.

## 2. Setting up your collaborative coding evnironemnt


