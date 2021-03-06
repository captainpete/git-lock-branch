Git Lock Branch
==================

Protect your local branches from yourself.

Introduction
------------

Sometimes you're working on a project which uses git hosting with protected
branches that you can't push to, because you're expected to use feature
branching and pull requests.

And sometimes you forget that and make commits to your local branches that have
protected remotes.

Using `git lock-branch` you can avoid this!


Installation
------------

Put `git-lock-branch` somewhere on your PATH. Git is smart enough to figure
out the rest.


Usage
-----

From your git repo directory, just run:

```
git lock-branch <branchname>
```

Now when you try to commit to that branch you will see `<branch> is locked`

Run `git lock-branch -h` for more options
