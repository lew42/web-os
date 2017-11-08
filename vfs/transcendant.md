A virtual (transcendant) directory:

![screenshot from 2017-11-08 09-38-23](https://user-images.githubusercontent.com/5721688/32557785-bfc769ee-c468-11e7-9d57-57959928136a.png)

This is a screenshot from Ubuntu/Gnome.  It shows the contents of the `/proc` directory, a root folder on any linux computer.  Try `ls /proc`.  I was able to navigate to the directory using the file explorer.  Why am I showing you this?

These files don't really exist.  As [this article](https://www.linux.com/news/discover-possibilities-proc-directory) suggests, the `/proc` directory is "a strange beast".  The linux system uses this virtual directory to list currently running processes.  Those numbers represent the process id, and they come and go as the system starts/stops processes.

This is an example of how a file system can **transcend** the real file system.  I don't know if giving "transcedence" a strict definition is important.  You could consider a network drive as a transcendant directory.  Or one of those fancy dropbox/google drive folders (which is essentially a network drive).  I just mean it's a little more dynamic than the traditional file system.  Things might appear in there that aren't *exactly* files, or maybe they just behave a little differently (like sync to another machine in realtime).

In this example, the Operating System is providing this virtual directory.  What if each application could do the same?  What if each file could do the same?

# browse within files

What if **everything** on my computer were explorable, down to the nuts and bolts?  What if I could explore a `.psd` (Photoshop file)?  It's layers, version tree, color palette, etc.  All without having to launch a separate UI (UX).

What does this look like?  [I don't really know.](visual.md)


Feel free to open an issue if this doesn't make sense, or if you have any comments.
