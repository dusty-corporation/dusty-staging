# Dusty staging

This repository only runs GitHub's free CI before anything reaches Dusty's
public repository, [dusty-corporation/dusty](https://github.com/dusty-corporation/dusty).
It measures GitHub's runners and tests release candidates. It has no releases
or tags, and nothing here is meant to be downloaded or used.

Release candidates are pushed to `candidate-<version>` branches, where Dusty's
own workflows run unchanged. `native-macos.yml` is kept here on main only so it
can be started on a candidate branch.

Get Dusty from the [Dusty releases](https://github.com/dusty-corporation/dusty/releases).
