Laptop
======

This is a script to set up a machine for development.

It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

Requirements
------------

Support For:

* macOS Silicon

Install
-------

Download, review, then execute the script:

#### Mac

```sh
curl -fsS 'https://raw.githubusercontent.com/advisr-io/laptop/main/mac' | sh
```

Debugging
---------

Read through it to see if you can debug the issue yourself.
If not, copy the lines where the script failed into a
[new GitHub Issue](https://github.com/advisr-io/laptop/issues/new) for us.

Contributing
------------

Edit the `mac` file.
Document changes in the `README.md` file.
Follow shell style guidelines by using [ShellCheck] and [Syntastic].

[ShellCheck]: http://www.shellcheck.net/about.html
[Syntastic]: https://github.com/scrooloose/syntastic
