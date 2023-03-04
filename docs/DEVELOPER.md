# Building and Testing

This document describes how to set up your development environment to build and test CIS 5700 Project.
It also explains the basic mechanics of using `git`.

* [Prerequisite Software](#prerequisite-software)
* [Getting the Sources](#getting-the-sources)

See the [contribution guidelines](https://github.com/sciencejiho/CIS_5700_Project/blob/master/CONTRIBUTING.md) if you'd like to contribute to CIS 5700 Project.

## Prerequisite Software

Before you can build and test CIS 5700 Project, you must install and configure the following products on your development machine:

* [Git](http://git-scm.com) and/or the **GitHub app** (for [Mac](http://mac.github.com) or [Windows](http://windows.github.com)); [GitHub's Guide to Installing Git](https://help.github.com/articles/set-up-git) is a good source of information.

## Getting the Sources

Fork and clone the CIS 5700 Project repository:

1. Login to your GitHub account or create one by following the instructions given [here](https://github.com/signup/free).
2. [Fork](http://help.github.com/forking) the [main CIS 553 repository](https://github.com/sciencejiho/CIS_5700_Project).
3. Clone your fork of the CIS 5700 Projetct repository and define an `upstream` remote pointing back to the CIS 5700 Project repository that you forked in the first place.

```shell
# Clone your GitHub repository:
git clone git@github.com:<github username>/CIS_5700_Project.git

# Go to the CIS 553 directory:
cd CIS_5700_Project

# Add the main CIS 553 repository as an upstream remote to your repository:
git remote add upstream https://github.com/sciencejiho/CIS_5700_Project.git
