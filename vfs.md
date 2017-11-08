# Virtual File System (vfs)

* realtime
* version controlled
* transcends the "real" file system, and the in-memory "file system" (aka JavaScript objects)
* GUI all the things

This solution replaces the need for git.  This solution replaces the need for dropbox or google drive.

## What does it look like?

This is always the most important question.  This was the turning point for personal computing: the GUI.  Yet, there are so many things (like git) that we do without a GUI.  The GUI for this [#vfs](vfs.md) will run in your browser, and you will have full access to the underlying code.  Extending it should be trivial.

Designs and mockups will be helpful to visualize what this looks like.  We need help.  We need [unity](unity.md).

See the [shortcomings](#shortcomings-of-the-current-systems) section to see the problems with the current file system.

See the [implementation](#implementation) section to see an overview of how this would work.

## Shortcomings of the Current Systems

### realtime + visual version control
We don't really have a realtime + version controlled file system.  If you want version control, you get `git`, which is far from user-friendly, and not "realtime".

And what we really need is a **visual** version control.  Every GUI for git I've seen leaves me confused, and I resort to using the CLI, which is more familiar.  But it needs to be visual.  I used Source Tree for a while, but really couldn't make sense of the branching visuals.  And it was never clear to me  

Realtime version control would mean: automatically save

Organizing a file system is still one of those gray areas that computer scientists still struggle to solve.

For example, is it a folder, or a tag?  In reality, tags are folders are the same thing.
