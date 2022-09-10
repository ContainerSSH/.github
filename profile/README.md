# ContainerSSH

ContainerSSH launches a **new container for each SSH connection** in Kubernetes, Podman or Docker. The user is transparently dropped in the container and the container is removed when the user disconnects. **Authentication and container configuration are dynamic** using webhooks, **no system users** required.

## Website

On [containerssh.io](https://containerssh.io/), you can find the documentation as well as all the relevant project information and links in one place.

![ContainerSSH social media screenshot](https://containerssh.io/images/social.png)

## Roadmap

There are several new features planned for the next releases. You can view them on the [website dashboard](https://containerssh.io/development/dashboard/).

## Community
For our general community-relevant files like licensing, code of conduct, and contribution guidelines, please check out the [community repository](https://github.com/ContainerSSH/community).

Check out the [ContainerSSH Slack](https://join.slack.com/t/containerssh/shared_invite/zt-w2ulatkm-hjGHk8OaxQCBX79XKJHAQQ) and participate in shaping this project's future. You can also join us in the [Working Group](https://github.com/ContainerSSH/community/blob/main/CHARTER.md)!

## GitHub Structure

All repositories are public. If you would like to contribute more and need a new repository, you can add a pull request to [github-terraform](https://github.com/ContainerSSH/github-terraform).

### ContainerSSH
The [ContainerSSH](https://github.com/ContainerSSH/ContainerSSH) repository contains the main ContainerSSH releases, and all issues for ContainerSSH.

### libcontainerssh
The [libcontainerssh](https://github.com/ContainerSSH/libcontainerssh) repository contains the core ContainerSSH codebase, and also serves as a library that you can embed for building an authentication/configuration webhook server, or to embed ContainerSSH itself.

### Branding

Our [branding repository](https://github.com/ContainerSSH/branding) contains all logos and additional imagery. While the code and accompanying documentation are free to use under the [Apache 2.0 license](https://github.com/ContainerSSH/community/blob/main/LICENSE.md), ContainerSSH' visual identity has its own [license](https://github.com/ContainerSSH/branding/blob/main/LICENSE.md).
