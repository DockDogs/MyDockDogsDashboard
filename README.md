# MyDockDogsDashboard

[![Documentation Status](https://readthedocs.org/projects/mydockdogs-dashboard/badge/)](http://mydockdogs-dashboard.readthedocs.org/en/latest/?badge=latest)

[![Build Status](https://travis-ci.org/DockDogs/MyDockDogsDashboard.svg?branch=master)](https://travis-ci.org/DockDogs/MyDockDogsDashboard)

### Pre-requesites

* [Git](https://git-scm.com/)
* [Sphinx](http://www.sphinx-doc.org/en/stable/) or check the [Sphinx Github Repository](https://github.com/sphinx-doc/sphinx)
* Python (for using Sphinx)
* Pip (for using/installing Sphinx)
* Text editor such as Atom, Notepad++, or SublimeText.
* Terminal/Powershell access (iTerm2, Terminal.app, etc.)
* Git Desktop client _(if you prefer a GUI instead of a shell prompt). Suggested applications would be Github Desktop Client, Sourcetree, or Tower (Mac OS X Only)_.
### Checkout Documentation for Editing

* If you've never obtained the documentation before you'll want to clone the repository. The default branch is `master`, this is good.
    * `$ git@github.com:DockDogs/MyDockDogsDashboard.git`
* If you've already cloned the repository navigate to where this is in your computer using Terminal or Powershell. Once in this directory you'll be able to execute the following:
    * `$ git fetch && git checkout master`

### How to Edit

* Edit files in `docs` folder using a text editor such as Atom, SublimeText, or Notepad++.
* Files are written in `reStructuredText` syntax.

### Deploying Edits to Production Environment

* `$ git commit -am "commit message documenting what you've changed"`
* `$ git push`
* Once pushed to `master` branch `Travis-CI` will attempt to compile the documentation via a combination of wizardry and science.
* If [Travis-CI](https://travis-ci.org/DockDogs/MyDockDogsDashboard/builds) is satisfied that the build compiles properly it will send it for compiling and deployment at [ReadTheDocs](https://readthedocs.org/projects/mydockdogs-dashboard/builds/)
* Confirm updates are live & accessible via accessing [http://help.dockdogs.com](http://help.dockdogs.com). _This may take a few minutes to fully deploy, please be patient. Check the `Travis-CI` page & `ReadTheDocs` build pages linked above._


#### Deployment Status

[![Documentation Status](https://readthedocs.org/projects/mydockdogs-dashboard/badge/?version=latest)](http://mydockdogs-dashboard.readthedocs.org/en/latest/?badge=latest)

[![Build Status](https://travis-ci.org/DockDogs/MyDockDogsDashboard.svg?branch=master)](https://travis-ci.org/DockDogs/MyDockDogsDashboard)


### License & Copyright

* Copyright 2015-2016, All Rights Reserved - [DockDogs Worldwide](http://dockdogs.com).


### Contributors

* [Brian J King](http://github.com/brianjking)
