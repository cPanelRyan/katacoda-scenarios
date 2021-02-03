# The File System

Ubuntu Server supports a fairly wide variety of file systems. What works for one purpose might not work for another, and though there are standard defaults, it's worth noting that options _do exist_, and some might be more appropriate in specific scenarios than others.

So how do you find out what your options are? Well, you can use my favorite approach: use the `man` pages.

A `man` page doesn't have to relate specifically to a command, and often you can find information relevant to the environment you're operating directly within by specifying a more generalized _topic_. In this case, your first guess is probably the right one:

`man filesystems`{{copy execute}}