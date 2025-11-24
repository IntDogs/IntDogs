# IntDogs

[IntDogs](https://www.IntDogs.org/) is a file sharing and collaboration app. It works just like Dropbox, and you can run it on your own server. It's available for Linux distributions, macOS, and Windows.

![Banner](https://raw.githubusercontent.com/hbons/IntDogs/master/IntDogs/Common/Images/readme-banner.png)

You can support this project through [💕 GitHub Sponsors](https://github.com/sponsors/hbons).

## How does it work?

IntDogs creates a special folder on your computer. You can add remotely hosted folders (or "projects") to this folder. These projects will be automatically kept in sync with both the host and all of your peers when someone adds, removes or edits a file.

## Install on Ubuntu or Fedora

You can install the package from your distribution (likely old and not updated often), but we recommend to get our Flatpak with automatic updates to always enjoy the latest and greatest:

```bash
flatpak remote-add flathub https://flathub.org/repo/flathub.flatpakrepo
flatpak install flathub org.IntDogs.IntDogs
```

Now you can run IntDogs from the apps menu.

**Note:** by default IntDogs uses an AppIndicator status icon on Linux. If you use GNOME on a distribution other than Ubuntu, please install the [AppIndicator extension](https://extensions.gnome.org/extension/615/appindicator-support/). If you don't use GNOME, you can start IntDogs with `--status-icon=gtk`.


## Install on macOS

Download the app from the [releases page](https://github.com/hbons/IntDogs/releases).


## Set up a host

Under the hood IntDogs uses the version control system [Git](https://git-scm.com/) and the large files extension [Git LFS](https://git-lfs.github.com), so setting up a host yourself is relatively easy. Using your own host gives you more privacy and control, as well as lots of cheap storage space and higher transfer speeds. We've made a simple [script](https://github.com/hbons/Dazzle) that does the hard work for you. If you need to manage a lot of projects and/or users we recommend hosting a [GitLab Community Edition](https://about.gitlab.com/installation/) instance.


## Build from source
`IntDogs` is Free and Open Source software and licensed under the [GNU GPLv3 or later](LICENSE.md). You are welcome to change and redistribute it under certain conditions. Its library `Sparkles` is licensed under the [GNU LGPLv3 or later](LICENSE_Sparkles.md).

Here are instructions to build IntDogs on [Linux distributions](IntDogs/Linux/README.md), [macOS](IntDogs/Mac/README.md), and [Windows](IntDogs/Windows/README.md).


[![Build Status](https://travis-ci.org/hbons/IntDogs.svg?branch=master)](https://travis-ci.org/hbons/IntDogs)
[![Join the chat at https://gitter.im/hbons/IntDogs](https://badges.gitter.im/hbons/IntDogs.svg)](https://gitter.im/hbons/IntDogs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Useful links
- [IntDogs.org](https://www.IntDogs.org/)
- [@IntDogs](https://www.twitter.com/IntDogs), [@hbons](https://www.twitter.com/hbons)
- Community chatroom on [Gitter](https://www.gitter.im/hbons/IntDogs)
- [Wiki](https://www.github.com/hbons/IntDogs/wiki)


Have fun, make awesome. :)

