About splunk_handler
====================

Home: https://github.com/zach-taylor/splunk_handler

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: A Python logging handler that sends your logs to Splunk

Splunk Handler is a Python Logger for sending logged events to an installation
of Splunk Enterprise. This logger requires the destination Splunk Enterprise
server to have enabled and configured the Splunk HTTP Event Collector.


Current build status
====================

Linux: [![Circle CI](https://circleci.com/gh/conda-forge/splunk_handler-feedstock.svg?style=shield)](https://circleci.com/gh/conda-forge/splunk_handler-feedstock)
OSX: [![TravisCI](https://travis-ci.org/conda-forge/splunk_handler-feedstock.svg?branch=master)](https://travis-ci.org/conda-forge/splunk_handler-feedstock)
Windows: [![AppVeyor](https://ci.appveyor.com/api/projects/status/github/conda-forge/splunk_handler-feedstock?svg=True)](https://ci.appveyor.com/project/conda-forge/splunk-handler-feedstock/branch/master)

Current release info
====================
Version: [![Anaconda-Server Badge](https://anaconda.org/nomr/splunk_handler/badges/version.svg)](https://anaconda.org/nomr/splunk_handler)
Downloads: [![Anaconda-Server Badge](https://anaconda.org/nomr/splunk_handler/badges/downloads.svg)](https://anaconda.org/nomr/splunk_handler)

Installing splunk_handler
=========================

Installing `splunk_handler` from the `nomr` channel can be achieved by adding `nomr` to your channels with:

```
conda config --add channels nomr
```

Once the `nomr` channel has been enabled, `splunk_handler` can be installed with:

```
conda install splunk_handler
```

It is possible to list all of the versions of `splunk_handler` available on your platform with:

```
conda search splunk_handler --channel nomr
```




Updating splunk_handler-feedstock
=================================

If you would like to improve the splunk_handler recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nomr` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nomr` channel.
Note that all branches in the conda-forge/splunk_handler-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](http://conda.pydata.org/docs/building/meta-yaml.html#build-number-and-string)
   back to 0.
