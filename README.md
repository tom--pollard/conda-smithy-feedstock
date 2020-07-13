About conda-smithy
==================

Home: https://github.com/conda-forge/conda-smithy

Package license: BSD-3-Clause

Feedstock license: BSD-3-Clause

Summary: The tool for managing conda-forge feedstocks



Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <img src="https://img.shields.io/badge/noarch-disabled-lightgrey.svg" alt="noarch disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-conda--smithy-green.svg)](https://anaconda.org/anaconda_channel_name/conda-smithy) | [![Conda Downloads](https://img.shields.io/conda/dn/anaconda_channel_name/conda-smithy.svg)](https://anaconda.org/anaconda_channel_name/conda-smithy) | [![Conda Version](https://img.shields.io/conda/vn/anaconda_channel_name/conda-smithy.svg)](https://anaconda.org/anaconda_channel_name/conda-smithy) | [![Conda Platforms](https://img.shields.io/conda/pn/anaconda_channel_name/conda-smithy.svg)](https://anaconda.org/anaconda_channel_name/conda-smithy) |

Installing conda-smithy
=======================

Installing `conda-smithy` from the `anaconda_channel_name` channel can be achieved by adding `anaconda_channel_name` to your channels with:

```
conda config --add channels anaconda_channel_name
```

Once the `anaconda_channel_name` channel has been enabled, `conda-smithy` can be installed with:

```
conda install conda-smithy
```

It is possible to list all of the versions of `conda-smithy` available on your platform with:

```
conda search conda-smithy --channel anaconda_channel_name
```




Updating conda-smithy-feedstock
===============================

If you would like to improve the conda-smithy recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`anaconda_channel_name` channel, whereupon the built conda packages will be available for
everybody to install and use from the `anaconda_channel_name` channel.
Note that all branches in the tom--pollard/conda-smithy-feedstock are
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

* [@conda-forge/Core](https://github.com/conda-forge/Core/)

