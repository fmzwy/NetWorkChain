NETC: A distributed network for the Smart Economy
================

NETC uses digital identity and blockchain technology to digitize assets and leverages smart contracts for autonomously managed digital assets to create a "smart economy" within a decentralized network.

To learn more about NETC,website：（www.nether.top ）

Supported Platforms
--------

We already support the following platforms:

* CentOS 7
* Docker
* macOS 10 +
* Red Hat Enterprise Linux 7.0 +
* Ubuntu 14.04, Ubuntu 14.10, Ubuntu 15.04, Ubuntu 15.10, Ubuntu 16.04, Ubuntu 16.10
* Windows 7 SP1 +, Windows Server 2008 R2 +

We will support the following platforms in the future:

* Debian
* Fedora
* FreeBSD
* Linux Mint
* OpenSUSE
* Oracle Linux

Development
--------

To start building peer applications for NETC on Windows, you need to download [Visual Studio 2017](https://www.visualstudio.com/products/visual-studio-community-vs), install the [.NET Framework 4.7 Developer Pack](https://www.microsoft.com/en-us/download/details.aspx?id=55168) and the [.NET Core SDK](https://www.microsoft.com/net/core).

If you need to develop on Linux or macOS, just install the [.NET Core SDK](https://www.microsoft.com/net/core).

To install Netc SDK to your project, run the following command in the [Package Manager Console](https://docs.nuget.org/ndocs/tools/package-manager-console):

```
PM> Install-Package Netc
```

For more information about how to build DAPPs for NETC, please read the [documentation]

How to Contribute
--------



We use and recommend the following workflow:

1. Create an issue for your work.
    * You can skip this step for trivial changes.
	* Reuse an existing issue on the topic, if there is one.
	* Clearly state that you are going to take on implementing it, if that's the case. You can request that the issue be assigned to you. Note: The issue filer and the implementer don't have to be the same person.
1. Create a personal fork of the repository on GitHub (if you don't already have one).
1. Create a branch off of master(`git checkout -b mybranch`).
    * Name the branch so that it clearly communicates your intentions, such as issue-123 or githubhandle-issue.
	* Branches are useful since they isolate your changes from incoming changes from upstream. They also enable you to create multiple PRs from the same fork.
1. Make and commit your changes.
1. Add new tests corresponding to your change, if applicable.
1. Build the repository with your changes.
    * Make sure that the builds are clean.
	* Make sure that the tests are all passing, including your new tests.
1. Create a pull request (PR) against the upstream repository's master branch.
    * Push your changes to your fork on GitHub.

Note: It is OK for your PR to include a large number of commits. Once your change is accepted, you will be asked to squash your commits into one or some appropriately small number of commits before your PR is merged.

License
------

The NETC project is licensed under the [MIT license](LICENSE).
