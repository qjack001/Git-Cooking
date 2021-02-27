# Where did all my files go?

I moved them. Sorry.

# Where are they now?

They are on a branch called `main`.

# Where am I right now?

You are on the `master` branch.

# How do I get to the `main` branch?

In Github Desktop, there is a drop down labeled “current branch” (which will say “master” underneath). Click on it at select “main” instead. If you have made changes, it will ask you if you want to leave them on `master`. Select “bring my changes with me”.

If you are using the commandline, checkout branch `main`.

# What are these “branches”?

Git (and by extension Github) use the concept of “branches” to store multiple different versions of a file. Creating a new branch makes a new copy of all your files, so you can edit them without messing with the origionals. Like starting Draft 2 by copy-paste-ing Draft 1. If you like it, Git allows you to merge your new branch into the main branch (overwriting it with your changes). This allows people to collaborate on projects without messing up each other’s files if the changes cause breaking-effects. It’s a nifty feature.

# Do I have to use them?

Nope. Git-Cooking doesn’t do anything complex enough to require such a workflow.

# Why do I have to switch to `main`?

Calling the main branch `main` is better for a number of reasons, and quickly becoming the standard. I wanted all my repositories to be set-up the same.