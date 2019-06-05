# PIGSquad Git Workshop
_June 5th, 2019_

## Hello!

This is the repository I've prepared for the PIGSquad June 2019 workshop on git. My hope is it'll contain everything you need to follow along through the workshop itself, and it can also serve as a reference point to come back to when you get lost or need to look something up.

Learning git can be a little disorienting at first because, in many cases, you're learning how to solve a problem you may not yet have run into. But I promise that if you stick with me for the duration of this workshop, you'll understand:

1. What a version control system (VCS) is and how it works
2. When a VCS, such as git, is useful — or _not_ useful
3. How to use git to manage and track a programming project (such as a website, a video game, or anything else that involves digital files)

## Workshop outline

It's right [here!][outline]

## What next?

After this workshop, you should have a pretty decent understanding of what git is and how it's used. And maybe you even got a small taste of web development, too. So where should you go from here? I have a few ideas:

### 1) Keep building out your portfolio page

This is your webpage to own and do with as you'd like. If you want to host your portfolio on GitHub, for example, it should be pretty easy to get that up and running. However, you'll probably find vanilla HTML kind of a drag to maintain.

[GitHub Pages] recommends [Jekyll], a static site generator that makes it easy to create templates and publish blog posts for your content. It does have a learning curve, but I've built a few Jekyll sites and I'm happy to help answer questions if you get stuck. The community is pretty strong around Jekyll online, too, so a quick Google search should yield answers to most of your questions.

### 2) Practice creating branches and pull requests

Now that you've got your repo set up, try checking out a new branch to add a new feature to your site! Branches are most effective when they set out to do one thing — for example, "update-background-colors" sounds like a reasonable branch because it says what it does and just does that one thing. You can then practice creating a pull request on GitHub to merge your changes from that branch back into the `master` branch.

This branch => pull request => merge loop is the key of collaborative development. It ensures collaborators are all reviewing code, and it also prevents people from pushing directly to `master`. That means there's less stepping on toes _and_ more oversight into who's building what. It's a win-win!

### 3) Try adding git to a game you're making

If you've already got a game in progress, why not initialize a git repository within its root directory? You can go through the process of making an initial commit, setting up a `.gitignore`, setting a remote server (like GitHub) as "origin" to back up your repository, and so on. If you're nervous, I totally get that — just make a copy of your project first and try setting git up in that copy first.

## Resources
**This repository**

If you're reading [this][this repo], that's great! You're right where you need to be.

Don't forget that you can view the entire history of this repo by viewing all the [commits][this repo - commits] on the `master` branch.

**_[Pro Git]_, by Scott Chacon and Ben Straub**

This is the git bible, and it's available for free. It's shockingly readable, accessible, and human, and if you really want to go deep into how git works, it'll take you there. Absolutely essential as a reference. If you take away one resource from this workshop, please make it this one.

**The _[Learn Enough]_ series, by Michael Hartl**

When I was first learning how to program, I was scared of the command line. But this series of books — all free, all online, all about an hour to work through — was the perfect introduction. Those books are:

1. _[Learn Enough Command Line to Be Dangerous][Hartl - command line]_
2. _[Learn Enough Text Editor to Be Dangerous][Hartl - text editor]_
3. _[Learn Enough Git to Be Dangerous][Hartl - git]_

While the third book in the trilogy is all about git, and I'd highly recommend it as a way to reinforce and expand upon what we talked about today, I'd really encourage you to start with book 1 and work through all three.

**[GitHub for Unity]**

I just learned this exists, so I have no idea if it's any good, but it sounds handy if you prefer GUIs to the command line. Might be useful if you're primarily familiar with Unity, especially if you expect to work with large files — it says it has LFS baked in.

**Me!**

I'm also happy to help answer any questions you may have from this workshop. Feel free to shoot me a message on Twitter, where I'm [@nickcummings], or DM me on the PIGSquad Slack. And if you're feeling so inclined, please feel free to give me a follow on [whymog.itch.io]!

[outline]: https://docs.google.com/document/d/1GZQM01takXnKCuqo6QVdJosd2pbo2jw7v7Phr71u-tk/edit?usp=sharing
[this repo]: https://github.com/whymog/pigsquad-git-workshop
[this repo - commits]: https://github.com/whymog/pigsquad-git-workshop/commits/master
[Pro Git]: https://git-scm.com/book/en/v2
[Learn Enough]: https://www.learnenough.com/
[GitHub Pages]: https://pages.github.com/
[Jekyll]: https://jekyllrb.com/
[Hartl - command line]: https://www.learnenough.com/command-line-tutorial/basics
[Hartl - text editor]: https://www.learnenough.com/text-editor-tutorial/vim
[Hartl - git]: https://www.learnenough.com/git-tutorial/getting_started
[GitHub for Unity]: https://unity.github.com/
[@nickcummings]: https://twitter.com/nickcummings
[whymog.itch.io]: https://whymog.itch.io/