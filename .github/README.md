# brew-a-coffee

This is a demo of a GitHub action that I use to brew a coffee at home. It makes use of
[longshot](https://github.com/mmastrac/longshot), my command-line interface for De'Longhi coffeemakers, running in the
simulator mode.

The process here is much slower than the real system as we need to download the list of cargo packages and rebuild the executable for every
coffee that gets brewed.

You can read more [technical details about this project](https://grack.com/blog/2022/12/01/hacking-bluetooth-to-brew-coffee-on-github-actions-part-1/) in my blog posts
on how I reverse engineered the protocol for the coffeemaker, wrote a CLI, and finally integrated it with GitHub Actions.

## Try it out!

This repository will allow anyone to brew a coffee. File a new issue using one of the templates, and feel free to modify the parameters. Please be patient: because we're waiting
on GitHub's runners, it might take a minute for the action to pick up your request (this is much more responsive on my hosted runner!).

https://github.com/mmastrac/brew-a-coffee-demo/issues/new/choose

