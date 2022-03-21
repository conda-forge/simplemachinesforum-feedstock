About simplemachinesforum
=========================

Home: https://github.com/oliver-zehentleitner/python-simplemachinesforum

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/simplemachinesforum-feedstock/blob/main/LICENSE.txt)

Summary: Python request API to simplemachinesforum

Development: https://about.me/oliver-zehentleitner

Documentation: https://oliver-zehentleitner.github.io/python-simplemachinesforum

Python request API to Simple Machines Forum: https://www.simplemachines.org/

A forum is for humans, please use this piece of software only in combination with YOUR OWN FORUM or by order of the forum owner itself to provide
a valuable service. Be aware that bots are not tolerated on most boards and its use will lead to a ban.

- It can create a new topic with `new_topic()` on a remote simple machines forum over the network, all it needs is a valid user account to login.
- Given a topic ID, toggle the topic's stickiness with `toggle_sticky()`.
- Given a subject name and board, return the topic id for the matching topic with `get_topic_id`.
- Use the advanced search feature, and return the list of matches with `advanced_search()`.
- Given a board, return the topic id for all currently stickied topics with `get_stickied_posts()`.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=15723&branchName=main">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/simplemachinesforum-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-simplemachinesforum-green.svg)](https://anaconda.org/conda-forge/simplemachinesforum) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/simplemachinesforum.svg)](https://anaconda.org/conda-forge/simplemachinesforum) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/simplemachinesforum.svg)](https://anaconda.org/conda-forge/simplemachinesforum) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/simplemachinesforum.svg)](https://anaconda.org/conda-forge/simplemachinesforum) |

Installing simplemachinesforum
==============================

Installing `simplemachinesforum` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `simplemachinesforum` can be installed with:

```
conda install simplemachinesforum
```

It is possible to list all of the versions of `simplemachinesforum` available on your platform with:

```
conda search simplemachinesforum --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating simplemachinesforum-feedstock
======================================

If you would like to improve the simplemachinesforum recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/simplemachinesforum-feedstock are
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

* [@oliver-zehentleitner](https://github.com/oliver-zehentleitner/)

