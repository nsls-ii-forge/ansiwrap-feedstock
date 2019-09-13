About ansiwrap
==============

Home: https://github.com/jonathaneunice/ansiwrap

Package license: Apache 2.0

Feedstock license: BSD 3-Clause

Summary: textwrap, but savvy to ANSI colors and styles

ansiwrap wraps text, like the standard textwrap module. But it also correctly wraps text that contains ANSI control sequences that colorize or style text.

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=100&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/ansiwrap-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-ansiwrap-green.svg)](https://anaconda.org/nsls2forge/ansiwrap) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/ansiwrap.svg)](https://anaconda.org/nsls2forge/ansiwrap) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/ansiwrap.svg)](https://anaconda.org/nsls2forge/ansiwrap) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/ansiwrap.svg)](https://anaconda.org/nsls2forge/ansiwrap) |

Installing ansiwrap
===================

Installing `ansiwrap` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `ansiwrap` can be installed with:

```
conda install ansiwrap
```

It is possible to list all of the versions of `ansiwrap` available on your platform with:

```
conda search ansiwrap --channel nsls2forge
```




Updating ansiwrap-feedstock
===========================

If you would like to improve the ansiwrap recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/ansiwrap-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


