# Virtual File System (vfs)

* [virtual: transcends the file system](#transcendant)
* [realtime, visual version control](#realtime-visual-version-controlled)
* provide a consistent user experience (UI) for the version tree (and all its workflows), across all applications
* allow developers to easily utilize this version tree for anything within their apps (settings, content, database records)
* this is possible, right now, cross platform, with node and file watchers (like npm's `chokidar`)
* the process of performance and ux optimiziation is never finished, but this is a good start

This is the core functionality of any **operating system**, and hence, we call this project, the Web OS.

But this runs deeper.  We can use the file system for browsing 

Should include the functionality for (and eliminate the need for):
* git, npm, JavaScript modules
* user authentication/authorization
* custom database implementations
* dropbox, google drive, google docs
* every piece of software, ever

Yes, as you can see, when you build your module system on top of a realtime, version controlled platform, you have to build in several important features, like access control (user auth).  The "version control" part of the platform will uniquely identify every version of every file.  Modules (like npm, or git repos) are still just sets of files. 

## What does it look like?

This is always the most important question.  This was the turning point for personal computing: the GUI.  Yet, there are so many things (like git) that we do without a GUI.  The GUI for this [#vfs](vfs.md) will run in your browser, and you will have full access to the underlying code.  Extending it should be trivial.

Designs and mockups will be helpful to visualize what this looks like.  We need help.  We need [unity](unity.md).

See the [shortcomings](#shortcomings-of-the-current-systems) section to see the problems with the current file system.

See the [implementation](#implementation) section to see an overview of how this would work.

## Realtime, Visual Version Control

Realtime: changes to a file on one device instantly update on all devices.  This is what we've come to expect with "Google Docs".

Visual Version Control: the typical Undo history is a linear sequence of steps.  This history should be visual (if you've used Photoshop, you'll know what this might look like).  But, this history should also allow branching.  And it should be persistent and distributed.  In Photoshop, and most apps, when you close the application, the history disappears.

What does a version tree look like?  Like a tree... You start with something, and can branch at any time, any number of times.  You can back up to any point, and branch again.

Do you think realtime, visual version control is important?  Do you think git is the culmination (peak) of realtime visual version control?  I've never found a git GUI that makes sense to me. 

## Shortcomings of the Current Systems

Let's compare to 
### realtime + visual version control
We don't really have a realtime + version controlled file system.  If you want version control, you get `git`, which is far from user-friendly, and not "realtime".

And what we really need is a **visual** version control.  Every GUI for git I've seen leaves me confused, and I resort to using the CLI, which is more familiar.  But it needs to be visual.  I used Source Tree for a while, but really couldn't make sense of the branching visuals.  And it was never clear to me  

Realtime version control would mean: automatically save

Organizing a file system is still one of those gray areas that computer scientists still struggle to solve.

For example, is it a folder, or a tag?  In reality, tags are folders are the same thing.
