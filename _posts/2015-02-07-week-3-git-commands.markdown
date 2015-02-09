---
layout: post
title:  "Week 3 and git commands they don't teach you in school"
---

Six months ago, I thought I knew how to use git... Little did I know how much of a git n00b I was because so much of my work had been on my own and on one branch (Please don't hold this against me. For the most part, I've changed my ways.) When I first took Object Oriented Programming with Downing and was using git to push code to the cloud for storage, my partners and I were definitely not taking advantage of what was given to us. 

In this course, I highly recommend you put yourself in uncomfortable git situations early on and push yourself to use all aspects of it to increase development skills. 

Here's a few of the commands that I have grown to love and aren't talked about in the beginner guide to git from the course material ([http://rogerdudler.github.io/git-guide/](http://rogerdudler.github.io/git-guide/)):

Sometimes you forget to close an issue in a commit message or make a typo that drives you nuts. This is where `git commit --amend` is super helpful to change past commit messages. It's basically like rewriting history. See more here: [http://git-scm.com/book/en/v2/Git-Tools-Rewriting-History](http://git-scm.com/book/en/v2/Git-Tools-Rewriting-History)

This one is not a git command but something that saves a lot of keystrokes. You should set a git command alias for `git status`. I can't even imagine how many times I probably type `git st` in one week looking to see the status of my current branch. It saves a lot of time. If you have never set up an alias before here's a useful StackOverflow post: [http://stackoverflow.com/questions/2553786/how-do-i-alias-commands-in-git](http://stackoverflow.com/questions/2553786/how-do-i-alias-commands-in-git)

Before I knew about `git stash` I would copy the code of files I didn't want to commit yet before changing branches and save them on my desktop. Don't be old me. When you want the files again you can either `git stash apply` to not pop them off the stack of stashed files or `git stash pop` to pop them off (aka you won't be able to get them again). See more here: [http://git-scm.com/book/en/v1/Git-Tools-Stashing](http://git-scm.com/book/en/v1/Git-Tools-Stashing)

First thing I did at my internship last summer was separate out commits on a branch that should have all been in different branches so they could be separate pull requests. Note: These were not my own commits. `git cherry-pick` was so helpful to have. It allows you to pick out specific commits by their SHA id. Read more here: [http://git-scm.com/docs/git-cherry-pick](http://git-scm.com/docs/git-cherry-pick)

Last but not least: `git bisect`. So somewhere in the last x number of commits a bug appeared, but you have zero clue where it happened. `git bisect` to the rescue! It will help you via binary search to track down where your code is working and where it is not. See how to use it more depth here: [http://robots.thoughtbot.com/git-bisect](http://robots.thoughtbot.com/git-bisect) and here: [http://git-scm.com/book/en/v2/Git-Tools-Debugging-with-Git](http://git-scm.com/book/en/v2/Git-Tools-Debugging-with-Git)

> Tip of the Week:
> Everything I said above.