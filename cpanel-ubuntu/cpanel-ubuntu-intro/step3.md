
# Package Management

Package management in Ubuntu Server, as it is in most modern distributions, is an extremely important component of the operating system.

If you're like me, and you're coming from a basis of Redhat-based environments where you've dealt with the use of tools like `yum` and `rpm` to manage your packages, you're in a bit of luck. The terminology is different, the commands are different, and the package file type is different... but ultimately, the usage and even the syntax are _pretty_ much the same.

`apt` is the tool of choice for retrieval and management of packages from remote repositories (compare with `yum` in RHEL/CentOS).

`dpkg` is the tool of choice for manipulating and managing packages locally on the system (compare with `rpm` in RHEL/CentOS).

It goes quite a bit deeper than this, and there are a handful of variations on the usage of these tools, as well as additional derivations of these tools (ie, `apt-get`, `apt-cache`, etc), and this is precisely why we want to take a closer look at package management in a course all of its own.

## The Challenge

For now, let's keep it basic. You know how to get information on something using `man`, and you know the basic role of `apt`.

Let's install the `vim-snippets` package. You can search for it first, or you can try to install it directly; it's entirely up to you. **Go ahead and do that now**. After you've got it installed, find out how to output the files installed by this package using the `dpkg` utility, and use that output to answer the question below.

<details>
  <summary>**Need help?**</summary>
  If you can't find what we're looking for here, make sure you ran the `apt install vim-snippets`{{execute}} command, first. Then after this is successfully installed, you can use `dpkg -L vim-snippets`{{execute}} to view the files installed by this package.
</details>

>>In the text field below, enter the full path of the **last file** (the final line of output) shown by the dpkg output you used to view the files installed by the `vim-snippets` package (be careful not to include any extra whitespace):<<
=== /usr/share/doc/vim-snippets/changelog.Debian.gz

Once you've answered the above question successfully, you can proceed to the next segment.