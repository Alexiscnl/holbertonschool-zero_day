<div align="center"><img src="https://github.com/ksyv/holbertonschool-web_front_end/blob/main/baniere_holberton.png"></div>

# Git and GitHub

## Resources&#x20;

- [Resources to learn Git](https://git-scm.com/doc)
- [About READMEs](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes)
- [How to write a Git commit message](https://cbea.ms/git-commit/)
- [Learning branching](https://learngitbranching.js.org/)
- [Effective pull requests and other good practices for teams using GitHub](https://github.blog/2015-06-30-summer-of-code-best-practices-for-pull-requests/)

## Learning Objectives&#x20;

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- **General**
  - What is source code management
  - What is Git
  - What is GitHub
  - What is the difference between Git and GitHub
  - How to create a repository
  - What is a README
  - How to write good READMEs
  - How to commit
  - How to write helpful commit messages
  - How to push code
  - How to pull updates
  - How to create a branch
  - How to merge branches
  - How to work as collaborators on a project
  - Which files should and which files should not appear in your repo

## Requirements&#x20;

- **General**
  - A `README.md` file at the root of the repo, containing a description of the repository
  - A `README.md` file, at the root of the folder of *this* project (i.e. `git`), describing what this project is about
  - Do not use GitHub’s web UI, but the command line to perform the exercise (except for operations that cannot possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
  - Your answer files should only contain the command, and nothing else

## More Info&#x20;

### Install Git

If Git is not already installed on your terminal:

```bash
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```

> **Note:** If you’re already the `root` user in the sandbox (e.g. your username starts with `root`), you can omit the `sudo` from the commands above as you already have sufficient user permissions.

### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:

```bash
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin main
```



