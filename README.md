# [umov-bootstrap](http://umovme.github.com/bootstrap) [![Build Status](https://secure.travis-ci.org/umovme/bootstrap.png)](http://travis-ci.org/umovme/bootstrap)

umov-bootstrap is a uMov.me customized version of Twitter Bootstrap.

Twitter Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development, created and maintained by [Mark Otto](http://twitter.com/mdo) and [Jacob Thornton](http://twitter.com/fat). See also [http://twitter.github.com/bootstrap](http://twitter.github.com/bootstrap).

## Versioning

For transparency and insight into our release cycle, and for striving to maintain backward compatibility, Bootstrap will be maintained under the Semantic Versioning guidelines as much as possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit [http://semver.org/](http://semver.org/).


## Bug tracker

Have a bug or a feature request? [Please open a new issue](https://github.com/umovme/bootstrap/issues). 

## Community

Keep track of development and community news. (Official Twitter Bootstrap Channels)

* Follow [@twbootstrap on Twitter](http://twitter.com/twbootstrap).
* Read and subscribe to the [The Official Twitter Bootstrap Blog](http://blog.getbootstrap.com).
* Have a question that's not a feature request or bug report? [Ask on the mailing list.](http://groups.google.com/group/twitter-bootstrap)
* Chat with fellow Bootstrappers in IRC. On the `irc.freenode.net` server, in the `##twitter-bootstrap` channel.


## Compiling CSS and JavaScript

Bootstrap includes a [makefile](Makefile) with convenient methods for working with the framework. Before getting started, be sure to install [the necessary local dependencies](package.json):

```
$ npm install
```

When completed, you'll be able to run the various make commands provided:

#### build - `make`
Runs the recess compiler to rebuild the `/less` files and compiles the docs. Requires recess and uglify-js.

#### test - `make test`
Runs jshint and qunit tests headlessly in [phantomjs](http://code.google.com/p/phantomjs/) (used for ci). Depends on having phantomjs installed.

#### watch - `make watch`
This is a convenience method for watching just Less files and automatically building them whenever you save. Requires the Watchr gem.

Should you encounter problems with installing dependencies or running the makefile commands, be sure to first uninstall any previous versions (global and local) you may have installed, and then rerun `npm install`.



## Contributing

Please submit all pull requests against *-wip branches. If your pull request contains JavaScript patches or features, you must include relevant unit tests. All HTML and CSS should conform to the [Code Guide](http://github.com/mdo/code-guide), maintained by [Mark Otto](http://github.com/mdo).

Thanks!


## Copyright and license

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

  [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
