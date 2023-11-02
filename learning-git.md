# Learning Git

## Commits

A commit in a git repo records a snapshot of all the (tracked) files in your directory. It's like a giant copy and past, but even better!

Git wants to keep commits as lightweight as possible though, so it doesn't just blindy copy the entire directory every time you commit. It can (when possible) compress a commit as a set of changes, or a "delta", from one version of the respository to the next. 

Git also maintains a history of which commits were made when. That's why most commits have ancestor commits above them - we designate this with arrows in our visualization. Maintaining history is great for everyone working on the project!

It's a lot to take in, but for now you can think of commits as snapshots of the project. Commits are very lightweight and switching between them is swift.

##

Let's see what this looks like in practice. On the right we have a visualization of a (small) git repository. There are two commits right now - the first initial commit, `c0`, and one commit after that `c1` that might have some meaningful changes.

## Git Branches

Branches in Git are incredibly lightweight as well. They are Git are incredibly lightweight as well. They are simply pointers to a specific commit -- nothing more. This is why many Git enthusiasts chant the mantra:

**branch early, and branch often**

---
