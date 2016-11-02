<div align="center">
	<a href="https://stenci.la/about">
		<img src="https://raw.githubusercontent.com/stencila/stencila/master/images/logo-name.png" alt="Stencila">
	</a>
	<br>
	<a href="#about">About</a>&nbsp;|&nbsp;<a href="#packages">Packages</a>&nbsp;|&nbsp;<a href="#discuss">Discuss</a>&nbsp;|&nbsp;<a href="#develop">Develop</a>
	<br>
</div>

### About

[Stencila](http://stenci.la) is a platform for creating, collaborating on, and sharing data driven content. Content that is **transparent** and **reproducible** like [RMarkdown](https://github.com/rstudio/rmarkdown) and [Jupyter](http://jupyter.org/). Content that can be **versioned** and **composed** just like we do with open source software using tools like [CRAN](https://cran.r-project.org/web/packages/available_packages_by_name.html), [PyPi](https://pypi.python.org/pypi) and [NPM](https://www.npmjs.com/). And above all, content that is as **accessible** to non-coders as [Google Docs](https://en.wikipedia.org/wiki/Google_Docs,_Sheets_and_Slides) and [Microsoft Office](https://en.wikipedia.org/wiki/Microsoft_Office).

<img src="https://raw.githubusercontent.com/stencila/stencila/master/images/document-screenshot.png" alt="Stencila Document">

### Packages

Stencila is implemented as an ecosystem of software packages, each exposing the platform to different types of users and use cases. So, for example if you're a Python coder, you'll probably be most interested in the `py` package. Or, if you just want a quick way to get started with a desktop client, check out the `electron` package. This repository doesn't contain any active code itself, it's just here as a central place for shared documentation and issues.

We're currently undertaking a major rewrite of the platform, moving to a more modular and decoupled architecture. It's still a work in progress. Confused? [Talk to us](https://gitter.im/stencila/stencila). Really.

Currently, four packages expose the platform in alternative host languages (packages for other languages, including Julia and Go, are planned)

- [node](https://github.com/stencila/node) : Stencila for Node.js
- [py](https://github.com/stencila/py) : Stencila for Python
- [r](https://github.com/stencila/r) : Stencila for R
- [cpp](https://github.com/stencila/cpp): Stencila for C++

All these packages make use of the browser based user interfaces provided by the `web` package: 

- [web](https://github.com/stencila/web) : Stencila in the browser

A cross platform desktop application is provided by the `electron` package:

- [electron](https://github.com/stencila/electron) : Stencila on the desktop

### Discuss

We love feedback. Chat with members of the community on [Gitter](https://gitter.im/stencila/stencila). For general suggestions you can create a [new issue](issues/new) or add to [existing issues](stencila/issues) in this repo. For package specific issues, please go to Issues page for the package repository (links below). 

### Develop

Want to help out with development? Great, there's a lot to do! Please see the roadmaps and issues for each of the repos:

               | Build status | Test coverage | Issues
-------------- |:------------:|:-------------:|:------:
[cpp](https://github.com/stencila/cpp) | [![Build status](https://travis-ci.org/stencila/cpp.svg?branch=master)](https://travis-ci.org/stencila/cpp) | [![Test coverage](https://codecov.io/gh/stencila/cpp/branch/master/graph/badge.svg)](https://codecov.io/gh/stencila/cpp) | [![Issues](http://img.shields.io/github/issues/stencila/cpp.svg)]( https://github.com/stencila/cpp/issues )
[electron](https://github.com/stencila/electron) | [![Build status](https://travis-ci.org/stencila/electron.svg?branch=master)](https://travis-ci.org/stencila/electron) | [![Test coverage](https://codecov.io/gh/stencila/electron/branch/master/graph/badge.svg)](https://codecov.io/gh/stencila/electron) | [![Issues](http://img.shields.io/github/issues/stencila/electron.svg)]( https://github.com/stencila/electron/issues )
[node](https://github.com/stencila/node) | [![Build status](https://travis-ci.org/stencila/node.svg?branch=master)](https://travis-ci.org/stencila/node) | [![Test coverage](https://codecov.io/gh/stencila/node/branch/master/graph/badge.svg)](https://codecov.io/gh/stencila/node) | [![Issues](http://img.shields.io/github/issues/stencila/node.svg)]( https://github.com/stencila/node/issues )
[py](https://github.com/stencila/py) | [![Build status](https://travis-ci.org/stencila/py.svg?branch=master)](https://travis-ci.org/stencila/py) | [![Test coverage](https://codecov.io/gh/stencila/py/branch/master/graph/badge.svg)](https://codecov.io/gh/stencila/py) | [![Issues](http://img.shields.io/github/issues/stencila/py.svg)]( https://github.com/stencila/py/issues )
[r](https://github.com/stencila/r) | [![Build status](https://travis-ci.org/stencila/r.svg?branch=master)](https://travis-ci.org/stencila/r) | [![Test coverage](https://codecov.io/gh/stencila/r/branch/master/graph/badge.svg)](https://codecov.io/gh/stencila/r) | [![Issues](http://img.shields.io/github/issues/stencila/r.svg)]( https://github.com/stencila/r/issues )
[web](https://github.com/stencila/web) | [![Build status](https://travis-ci.org/stencila/web.svg?branch=master)](https://travis-ci.org/stencila/web) | [![Test coverage](https://codecov.io/gh/stencila/web/branch/master/graph/badge.svg)](https://codecov.io/gh/stencila/web) | [![Issues](http://img.shields.io/github/issues/stencila/web.svg)]( https://github.com/stencila/web/issues )

### Museum

As with many software projects, Stencila has evolved a lot as we have learned what works and what doesn't. Two independent branches have been preserved in this repo for historical interest (and because they contain a significant amount of work and some useful code!):

#### [`triassic`](https://github.com/stencila/stencila/tree/triassic) c. 2012-2013. 305 commits

#### [`jurassic`](https://github.com/stencila/stencila/tree/jurassic) c. 2014-2016. 2414 commits
