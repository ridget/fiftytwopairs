---
title: pairing-tools-and-where-to-find-them
date: 2015-03-17 10:00 UTC
tags: pairing, remote tools, tmux, vim
---

## Current Status: 9 down, 43 to go. 

Over the past weeks, I've been experimenting with a number of pairing tools, I've been trying to wrestle with the great tragedy that is Australian upload speeds when pairing with developers from all over the world. 

The good news, is that there are plenty of tools out there, but which one suits you? 


## [Screenhero](http://screenhero.com)

Screenhero is a great screen-sharing tool, and will soon come bundled with Slack to enable users to screenshare from their chat environment. 

Support for dual mouse cursors, means its easy to collaborate on the same bit of code and communicate where that missing `.` lies. The audio and screen visibility provided you have good upload and download speeds is pretty excellent. 

As this is a remote screensharing tool, it also enables you to pair on more visual aspects of your application.

Currently, this service is free, whilst it's being integrated with Slack, but new user registrations are closed, however if you can snag an invitation from an existing user, you can continue to use it free of charge.

## [Floobits](http://floobits.com)

I've only stumbled on floobits rather recently, but if you're looking for a tmux like experience for minimal latency and collaboration. 

It enables users to pair via workspaces, which will enable synching of files between the developers working on them.

Where floobits really shines, besides the low latency pairing functionality, is its support for multiple editors. This means you can each bring your own keybindings to the party, and continue to be productive. 

If you don't use an editor with a floobits extension, there is a web interface available, which is reasonably robust.

Unfortunately, it's monthly cost can be prohibitive, but if you're not a vim user and are working on open source projects, this is an exceptionally good tool.

## Tmux/[Tmate](http://tmate.io) + Vim

This is the ultimate low latency way to pair. Tmux is a fantastic tool in and of itself, but combined with Vim, makes it easy to remote pair. No workspaces means you're editing your pairs code, which removes the guesswork out of where stuff lies. 

Utilising tmate, a fork of tmux, it becomes incredibly simple to connect to a shared tmux session, whilst still being able to utilise your `tmux.conf` file. 

Unfortunately, not everyone is a Vim user, and when pairing you are ultimately bound to your pairs `.vimrc` and `tmux.conf` configuration settings. However, this can also be a particularly useful way of picking up new vim plugins or more comfortable key-bindings.

Personally as I'm becoming more of a fan of the Vim workflow, im leaning towards Tmux and Vim, but Floobits offers a great alternative.


