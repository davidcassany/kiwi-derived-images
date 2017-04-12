# kiwi-derived-images

This repository provides a simple example of how to use [KIWI](https://suse.github.io/kiwi/)
in order to produce derived docker images from DockerHub. Note that KIWI doesn't require the docker
daemon to be installed or running for the build, as KIWI relies on **umoci** and **skopeo** to
perform the build.

Kiwi supports zypper, dnf, yum and apt package managers, so the example derived images are based on
openSUSE, Fedora, CentOS, Ubuntu and Debian.
