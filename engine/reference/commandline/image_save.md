---
datafolder: engine-cli
datafile: docker_image_save
title: docker image save
---

<!--
Sorry, but the contents of this page are automatically generated from
Docker's source code. If you want to suggest a change to the text that appears
here, you'll need to find the string by searching this repo:

https://www.github.com/docker/docker
-->

{% include cli.md %}

## Examples

Save all fedora repository images to a fedora-all.tar and save the latest
fedora image to a fedora-latest.tar:

    $ docker image save fedora > fedora-all.tar

    $ docker image save --output=fedora-latest.tar fedora:latest

    $ ls -sh fedora-all.tar

    721M fedora-all.tar

    $ ls -sh fedora-latest.tar
    
    367M fedora-latest.tar