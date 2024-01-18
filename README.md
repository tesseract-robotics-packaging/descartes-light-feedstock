About descartes-light-feedstock
===============================

Feedstock license: [BSD-3-Clause](https://github.com/tesseract-robotics/descartes-light-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/swri-robotics/descartes_light

Package license: Apache-2.0

Summary: Library for generation motion plans for process toolpaths

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-descartes--light-green.svg)](https://anaconda.org/tesseract-robotics/descartes-light) | [![Conda Downloads](https://img.shields.io/conda/dn/tesseract-robotics/descartes-light.svg)](https://anaconda.org/tesseract-robotics/descartes-light) | [![Conda Version](https://img.shields.io/conda/vn/tesseract-robotics/descartes-light.svg)](https://anaconda.org/tesseract-robotics/descartes-light) | [![Conda Platforms](https://img.shields.io/conda/pn/tesseract-robotics/descartes-light.svg)](https://anaconda.org/tesseract-robotics/descartes-light) |

Installing descartes-light
==========================

Installing `descartes-light` from the `tesseract-robotics/label/dev_indv` channel can be achieved by adding `tesseract-robotics/label/dev_indv` to your channels with:

```
conda config --add channels tesseract-robotics/label/dev_indv
conda config --set channel_priority strict
```

Once the `tesseract-robotics/label/dev_indv` channel has been enabled, `descartes-light` can be installed with `conda`:

```
conda install descartes-light
```

or with `mamba`:

```
mamba install descartes-light
```

It is possible to list all of the versions of `descartes-light` available on your platform with `conda`:

```
conda search descartes-light --channel tesseract-robotics/label/dev_indv
```

or with `mamba`:

```
mamba search descartes-light --channel tesseract-robotics/label/dev_indv
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search descartes-light --channel tesseract-robotics/label/dev_indv

# List packages depending on `descartes-light`:
mamba repoquery whoneeds descartes-light --channel tesseract-robotics/label/dev_indv

# List dependencies of `descartes-light`:
mamba repoquery depends descartes-light --channel tesseract-robotics/label/dev_indv
```




Updating descartes-light-feedstock
==================================

If you would like to improve the descartes-light recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`tesseract-robotics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `tesseract-robotics` channel.
Note that all branches in the tesseract-robotics/descartes-light-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@johnwason](https://github.com/johnwason/)

