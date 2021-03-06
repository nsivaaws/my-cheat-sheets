# SOFTWARE INSTALL METHODS CHEAT SHEET

`software install methods` _is a very high level view on
software/app installs._

View my entire list of cheat sheets on
[my GitHub Webpage](https://jeffdecola.github.io/my-cheat-sheets/).

## INSTALL METHODS

* [SOURCE](https://github.com/JeffDeCola/my-cheat-sheets/tree/master/development/development-environments/software-install-methods-cheat-sheet#source)
* [BINARY](https://github.com/JeffDeCola/my-cheat-sheets/tree/master/development/development-environments/software-install-methods-cheat-sheet#binary)
* [INSTALLER / PACKAGES](https://github.com/JeffDeCola/my-cheat-sheets/tree/master/development/development-environments/software-install-methods-cheat-sheet#installer--packages)
* [VIRTUAL MACHINE / CONTAINER](https://github.com/JeffDeCola/my-cheat-sheets/tree/master/development/development-environments/software-install-methods-cheat-sheet#virtual-machines--containers)

Each have their own strengths and drawbacks.

## SOURCE

The purest form of the install. Download source code
(e.g. go, python c, etc...) and compile.

There is most likely a lot of provisioning and configuration involved.
To update software, you need to grab the new source.

## BINARY

Download the binary (e.g. _something.exe_) that has been already
compiled for your machine.

## INSTALLER / PACKAGES

An installer/provisioning type program is
used to install your App.

Linux has many types of software that can be used
as installers (and I use this term very loosely)
since they are much more then just installation (e.g. BOSH and
[ansible](https://github.com/JeffDeCola/my-cheat-sheets/tree/master/operations-tools/configuration-management/ansible-cheat-sheet)).

Linux systems use packages, that contains everything a particular
program needs to run. (e.g., `apt-get` is used in ubuntu).

## VIRTUAL MACHINES / CONTAINERS

Sometimes its easier just to grab a virtual machine or container
where someone who has already done all the work.

For example, [vagrant](https://github.com/JeffDeCola/my-cheat-sheets/tree/master/development/development-environments/vagrant-cheat-sheet)
will allow you to quickly fire up a VM.
Or use [docker](https://github.com/JeffDeCola/my-cheat-sheets/tree/master/operations-tools/orchestration/builds-deployment-containers/docker-cheat-sheet)
to get a container with the App you want.
