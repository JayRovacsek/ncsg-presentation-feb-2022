# Title

Nix: Repoducable, Declarative and Reliable System Management

## Overview

It's been 12 months since we last talked about home labs very directly and I've got some new Kool-Aid to sell.
What's a Nix? Why do I care about reproducibility and why am I here?

Nix is a package manager, system configuration tool, cloud image generator, docker image generator and development environment tool that cares
far too much about solving problems in it's own language (nix) that is downright painful at times.
We'd want to use nix with the above said if we want to abstract away some of the intricacies of system management and
the hell that can be understanding Linux or MacOS.

How does this relate to security? Glad you asked! Nix enables the management of system configuration akin to Puppet/Ansible et. al,
without the fear of system changes. Sure we could snapshot and all that jazz, but these problems are approached differently in Nix.

This talk is ideal for those who are home-lab curious, care about system reproducibility & reliability as well as those who might just be curious how could package management be flipped on it's head.

Warning: this talk focuses on hyped and buzzword topics and might give you horrendous ideas of making the systems you use into
a Homunculus of declarative files that while written in one of the worst languages I've encountered. Will give you unlimited power
to act superior to other Linux nerds (i_use_arch_btw.jpg or alike), consistently rebuild a system without failure and generally move fast and break things.
