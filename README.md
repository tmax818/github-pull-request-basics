# Github Pull Request Basics

## Problem Statement

The concept of a pull request is unique to Github--so don't feel nervous about
not knowing what it is! Pull requests power the open source community.
Through this process, anyone can fork a repo, make changes and submit
a pull request. Instead of the owner working on their codebase alone, _anyone_
can contribute: tests, documentation fixes, new features, layout, graphics, etc.
How does this feature work?

## Objectives

1. Explain what a pull request is
1. Identify how to create a pull request from a fork to a repo
2. Identify how to add commits to an existing pull request

## Explain What a Pull Requests Is

A pull request is a request to the owner of another org take changes you
made to your copy of the repo and integrate it into theirs _as if_ you had
done the work _on theirs directly_. It is a request for the owner of a repository
to accept your changes, that you made on your own copy of the repo ("your fork"),
and "pull" them into the owner's repository. [Here][pr] is a great example of a
pull request on the `Ruby` codebase.

## Identify How to Create a Pull Request from a Fork to a Repo

Let's go over a conceptual, hypothetical example. It's okay if this feels a bit confusing at
first. You'll work through this countless times and eventually your brain and
fingers will both grasp what's going on. Let's look at the following example:

1. Let's pretend that the learn-co-students organization has a repo called awesome-lab, and we make a "fork" from this repo at `https://github.com/learn-co-students/awesome-lab`.
2. You would now have a _copy_ of that repo on your Github account ("organization") i.e.
   `https://github.com/your-user-name/awesome-lab`. Technologists would say
   you "forked" the `awesome-lab` repo from the `learn-co-students` organization
   to the `your-user-name` organization.
3. However, you still would not have a *local* copy of this repository on your computer.
4. You would clone from **your** fork to your computer. There's no reason you _couldn't_
   clone from the _original_ repo. However, most repo owners don't want random
   people on the internet (like you!) committing to their repo. What you're
   going to do is establish a "parallel" repo in _your_ org and then tell the
   "source" repo "Hey, I added something awesome, I'm requesting that you _pull_
   it in."
5. Make some changes on your local machine
6. Push your code from your local system _back_ to _your_ fork
7. Create a `pull request` that requests your improved code be "pulled" into the
   source repo. Observe the steps for initiating a `pull request` below:

#### Step 1

![](https://curriculum-content.s3.amazonaws.com/gitpulls/2.png)

#### Step 2

Here you can choose the base fork, which will be `their-user-name/awesome-lab`.
Then choose the head fork, which will be `your-user-name/awesome-lab`

Now click Create pull request, and you're all set!

![](https://curriculum-content.s3.amazonaws.com/gitpulls/4.jpg)

What if another student now forks the repository `https://github.com/learn-co-students/awesome-lab` 
as `https://github.com/their-user-name/awesome-lab`, then you make some changes and you 
want to send a pull request to their fork `https://github.com/their-user-name/awesome-lab`? 
How do you do this?

Luckily, `git` doesn't care whether one repository is the "source" or is
"another fork of the source." If GitHub magically vanished tomorrow, local copies on 
hundreds of laptops 'round the world are _just as good as the copy that GitHub_ had!
This is why `git` is called a "Distributed Version Control System." So, to share a
pull request with another student follows the same process as forking some famous
project (like Ruby or jQuery).

## Identify How to Add Commits to an Existing Pull Request

Let's say you make a pull request from
`https://github.com/your-user-name/awesome-lab` to
`https://github.com/learn-co-students/awesome-lab`. Then you notice you made a
typo in your code. All you have to do is fix the typo, commit it and push up
the changes to your branch. As long as the pull request already exists, the
commits will be added automatically.

## Conclusion



<p data-visibility='hidden'>View <a href='https://learn.co/lessons/github-pull-request-basics' title='Github Pull Request Basics'>Github Pull Request Basics</a> on Learn.co and start learning to code for free.</p>

[pr]: https://github.com/ruby/ruby/pull/1051
