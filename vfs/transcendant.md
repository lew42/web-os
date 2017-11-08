![screenshot from 2017-11-08 09-38-23](https://user-images.githubusercontent.com/5721688/32557785-bfc769ee-c468-11e7-9d57-57959928136a.png)

This is a screenshot from Ubuntu/Gnome.  It shows the contents of the `/proc` directory, a root folder on any linux computer.  Try `ls /proc`.  I was able to navigate to the directory using the file explorer.  Why am I showing you this?

These files don't really exist.  As [this article](https://www.linux.com/news/discover-possibilities-proc-directory) suggests, the `/proc` directory is "a strange beast".  The linux system uses this virtual directory to list currently running processes.  Those numbers represent the process id, and they come and go as the system starts/stops processes.

This is an example of how a file system can **transcend** the real file system.

What if **everything** on my computer were explorable, down to the nuts and bolts?  What if I could explore a `.psd` (Photoshop file)?  It's layers, version tree, color palette, etc.  All without having to launch a separate UI (UX).

But what does a browsable version tree look like?  I can't really tell you that.  All examples I've seen make the simple concept of a version tree, and make it really complex.

Here are some images of existing "GUI" version control apps:

![from google image search for "git kraken"](http://3.bp.blogspot.com/-cLht0ZY8iog/VqCUC1F-46I/AAAAAAAABmM/2ahypePQ1J8/w1200-h630-p-k-no-nu/git_kraken.png)

![from google image search for "source tree"](https://ucarecdn.com/1adf1509-9f48-4b51-bff5-b226c98d886a/)

![from google image search for "github desktop"](https://d2.alternativeto.net/dist/s/github-for-mac_584497_full.png?format=jpg&width=1600&height=1600&mode=min&upscale=false)

I've used all three of these apps, and went back to using the command line.  I didn't really understand the branching diagrams (maybe I'm just stupid).  Maybe they didn't label the different branches well enough?  Maybe I don't understand git well enough?  Or maybe I just didn't give it enough time.  I think all of the above are true to some degree. 

This function (version control) needs to be consistent across all apps.  And needs to be able to touch all the things within files (transcend the file system).

Feel free to open an issue if this doesn't make sense, or if you have any comments.
