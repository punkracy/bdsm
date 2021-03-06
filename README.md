# About

Bash Development & Scripting Management Framework (BDSM) is a...
scripting framework! (go figure)

# Goal

The goal is to create a framework for maintaining and sharing server side
scripts while exposing them through a consistent command line interface (CLI).

# Architecture

BDSM itself is a scripting framework. Users may write and/or install 'extensions'
(think plugins) to the core framework in order to add CLI functionality to BDSM.

# Creating Extensions

There are only a few requirements for the 'extensions'. The extension must be a
directory. Within this directory are (at least) the subdirectory bin/ with at
least one executable file called 'help'. Additionally in the root of the
extension directory there must be a text file called VERSION with a version
number that follows semantic versioning (http://semver.org/) in the format of
X.Y.Z where X,Y and Z are positive integers. An extension must also have a
README file in which you should explain about the extension.

The contents of the bin directory can be *any* execuatble file.  This means for
example that C compiled binaries, Ruby Scripts, python, lua, etc... may all be
used according to requrements and/or user preferences.  Of course the extensions
which *I* write will likely be in bash ;) Additionally if you write your
extensions in bash a nice DSL is automatically loaded for you. Read more
about the DSL in the online documentation.

  ~Wayne

Wayne E. Seguin
wayneeseguin@gmail.com
http://github.com/wayneeseguin
http://twitter.com/wayneeseguin

