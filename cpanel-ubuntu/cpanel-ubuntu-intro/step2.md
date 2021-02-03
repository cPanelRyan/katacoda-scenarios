
# The File System

Ubuntu Server supports a fairly wide variety of file systems. What works for one purpose might not work for another, and though there are standard defaults, it's worth noting that options _do exist_, and some might be more appropriate in specific scenarios than others.

So how do you find out what your options are? Well, you can use my favorite approach: use the `man` pages.

A `man` page doesn't have to relate specifically to a command, and often you can find information relevant to the environment you're operating directly within by specifying a more generalized _topic_. In this case, your first guess is probably the right one:

Using the terminal to the right, pull up the `man` page for `filesystems`.

<details>
  <summary>**Need help?**</summary>
  If you're having trouble figuring it out, the command you're looking for is as simple as running: <br />
  `man filesystems`{{execute}} <br />
  Click the command shown above, and we'll execute this for you.
</details>

Once you've done that, answer this quick question:

## Keeping up?

>>In the text field below, enter the name of the supported file system type that supports journaling, was developed by IBM, and into Linux in kernel 2.4.24 (answer is case-sensitive):<<
=== JFS

<details>
  <summary>**Need help?**</summary>
  If you can't find what we're looking for here, make sure you ran the `man filesystems`{{copy}} command and were able to see output from the filesystems man pages within the terminal. Within this output, you should see a list of file system types, and among this list there is one specific file system type that very specifically matches the description provided above.
</details>

Once you've submitted the correct answer to the above question, you'll be able to proceed ahead to the next step.