About pcl-feedstock
===================

Feedstock license: [BSD-3-Clause](https://github.com/tesseract-robotics/pcl-feedstock/blob/main/LICENSE.txt)

Home: http://www.pointclouds.org/

Package license: BSD-3-Clause

Summary: Point Cloud Library (PCL)

Development: https://github.com/pointcloudlibrary/pcl

Documentation: http://www.pointclouds.org/

The Point Cloud Library (PCL) is a standalone, large scale, open project for 2D/3D image and point cloud processing.

Current build status
====================


<table><tr>
    <td>GitHub Actions</td>
    <td>
      <a href="https://github.com/tesseract-robotics/pcl-feedstock/actions/workflows/conda-build.yml">
        <img src="https://github.com/tesseract-robotics/pcl-feedstock/actions/workflows/conda-build.yml/badge.svg?event=push&branch=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pcl-green.svg)](https://anaconda.org/tesseract-robotics/pcl) | [![Conda Downloads](https://img.shields.io/conda/dn/tesseract-robotics/pcl.svg)](https://anaconda.org/tesseract-robotics/pcl) | [![Conda Version](https://img.shields.io/conda/vn/tesseract-robotics/pcl.svg)](https://anaconda.org/tesseract-robotics/pcl) | [![Conda Platforms](https://img.shields.io/conda/pn/tesseract-robotics/pcl.svg)](https://anaconda.org/tesseract-robotics/pcl) |

Installing pcl
==============

Installing `pcl` from the `tesseract-robotics/label/dev` channel can be achieved by adding `tesseract-robotics/label/dev` to your channels with:

```
conda config --add channels tesseract-robotics/label/dev
conda config --set channel_priority strict
```

How to use
----------

<details>
<summary>With conda</summary>

```
conda install pcl
```

</details>

<details>
<summary>With mamba</summary>

```
mamba install pcl
```

</details>

<details>
<summary>With pixi</summary>

```
# for adding to your local project
pixi add pcl
# for installing globally
pixi global install pcl
```

</details>

Search package versions
-----------------------

It is possible to list all of the versions of `pcl` available on your platform:

<details>
<summary>With conda</summary>

```
conda search pcl --channel tesseract-robotics/label/dev
```

</details>

<details>
<summary>With mamba</summary>

```
mamba search pcl --channel tesseract-robotics/label/dev
```

</details>

<details>
<summary>With pixi</summary>

```
pixi search pcl --channel tesseract-robotics/label/dev
```

</details>

<details>
<summary>With mamba repoquery, which may provide more information</summary>

```
# Search all versions available on your platform:
mamba repoquery search pcl --channel tesseract-robotics/label/dev

# List packages depending on `pcl`:
mamba repoquery whoneeds pcl --channel tesseract-robotics/label/dev

# List dependencies of `pcl`:
mamba repoquery depends pcl --channel tesseract-robotics/label/dev
```

</details>




Updating pcl-feedstock
======================

If you would like to improve the pcl recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`tesseract-robotics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `tesseract-robotics` channel.
Note that all branches in the tesseract-robotics/pcl-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks, and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@Tobias-Fischer](https://github.com/Tobias-Fischer/)
* [@chambbj](https://github.com/chambbj/)
* [@hobu](https://github.com/hobu/)
* [@oursland](https://github.com/oursland/)
* [@traversaro](https://github.com/traversaro/)

