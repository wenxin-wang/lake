Lake: self-made package manager
===

Introduction
---

lake is a self made package manager for clfs. It is made to work with command files like pacman's PKGBUILD.

Current state
---

Currently lake and liblake won't work. lake is splitted into mkcmd, mkpkg, inspkg, rmpkg and qpkg.

1. mkcmd will generate a command file;
2. mkpkg will use that command file and make a package;
3. inspkg will install that package

But lake will be back, using these components, and a dependency parser.
