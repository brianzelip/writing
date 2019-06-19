# On (re)learning python

Now that I have a somewhat deep understanding of JavaScript, it's time to get back into Python.

The kind of things I know I need to read about via learning js:

- data structures, their types, functions, appearence, etc.
- syntax
- key words
- key resources and docs
- js obj vs python list or dict
- js this vs python self
- object orientation
- classes
- math

## Bibliography

- Python.org's _Beginner's Guide to Python_, [HowToEditPythonCode](https://wiki.python.org/moin/HowToEditPythonCode)

  - statements and control flow
  - expressions
  - syntax and white space
  - unit testing!
  - standard library
  - history

- [_The Hitchhiker’s Guide to Python_](https://docs.python-guide.org/)

  - I followed [these](https://docs.python-guide.org/starting/install3/osx/#install3-osx) instructions for installing python3 on my personal laptop (ie: `brew install python`)

    - here are the relevant homebrew outputs from installing python:

    ```bash
    ==> Installing python
    ==> Downloading https://homebrew.bintray.com/bottles/python-3.7.3.sierra.bottle.tar.gzj
    ==> Downloading from https://akamai.bintray.com/b0/b07ec3a40f58fa317e1bb937992dc0dca7d60812c60de99bde14fbadb6c27cc5?_
    ######################################################################## 100.0%
    ==> Pouring python-3.7.3.sierra.bottle.tar.gz
    ==> /usr/local/Cellar/python/3.7.3/bin/python3 -s setup.py --no-user-cfg install --force --verbose --install-scripts=
    ==> /usr/local/Cellar/python/3.7.3/bin/python3 -s setup.py --no-user-cfg install --force --verbose --install-scripts=
    ==> /usr/local/Cellar/python/3.7.3/bin/python3 -s setup.py --no-user-cfg install --force --verbose --install-scripts=
    ==> Caveats
    Python has been installed as
      /usr/local/bin/python3

    Unversioned symlinks `python`, `python-config`, `pip` etc. pointing to
    `python3`, `python3-config`, `pip3` etc., respectively, have been installed into
      /usr/local/opt/python/libexec/bin

    If you need Homebrew's Python 2.7 run
      brew install python@2

    You can install Python packages with
      pip3 install <package>
    They will install into the site-package directory
      /usr/local/lib/python3.7/site-packages

    See: https://docs.brew.sh/Homebrew-and-Python
    ```

    then:

    ```
    ==> python
    Python has been installed as
      /usr/local/bin/python3

    Unversioned symlinks `python`, `python-config`, `pip` etc. pointing to
    `python3`, `python3-config`, `pip3` etc., respectively, have been installed into
      /usr/local/opt/python/libexec/bin

    If you need Homebrew's Python 2.7 run
      brew install python@2

    You can install Python packages with
      pip3 install <package>
    They will install into the site-package directory
      /usr/local/lib/python3.7/site-packages

    See: https://docs.brew.sh/Homebrew-and-Python
    ```

    - to understand and get the bit working above about "Unversioned symlinks" to python3, [this !so answer helped me get it working](https://stackoverflow.com/a/51912712/2145103)
