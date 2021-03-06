# Git Basics Diagnostic

Write your answers inside this file, where it's indicated by the comments.

1.We just forked a repo on GitHub and want to start working on it locally.
What command do we use to do that? Use the **correct** URL from your fork of
this repository in your answer.

```sh
git clone git@github.com:cpm5041/git-diagnostic.git```

2.What do you do after cloning a repository, before you start making any
changes/additions?

Install any depencencies if necessary, then change directories

3.What command do we use to create a new branch? Name this branch `response`
    in your answer. Then, how do we switch to that branch?

```sh
We can create and change directories in the same command with
"git checkout -b response"
"```

4.We just wrote some code. What command do we use to see a summary of the
    changes in our working directory?

```sh
git status
```

5.We want to prepare a change for a commit by adding a file to the staging
    area. What command do we use to stage a file named `diagnostic.md`?

```sh
git add diagnostic.md
```

6.Once `diagnostic.md` is staged, we have to make a commit by `git commit`.
What are the two formatting items you **need** to make up your commit message?

You should include a specific title similar to a email subject then a
summary of your changes in the body.

-7.Should you ever edit published history?

No, you would make a new branch and make your changes.
