+++
author = "Kiba Fox"
date = "2016-08-15T20:53:59-04:00"
description = "description"
draft = true
keywords = ["key", "words"]
tags = ["one", "two"]
title = "How I install NixOS"
topics = ["topic 1"]
type = "post"

+++

I have been using NixOS as my primary Linux distribution for nearly a year now,
and I've installed it repeatedly on multiple machines and virtual machines.  One
of the advantages of using NixOS is that you can keep your NixOS configuration
in version control and bring up another machine to the same state using the same
configuration.  This is great when you have several computers and you want to
keep the work that you've done configuring one in sync with the others.
However, I've found that installing NixOS on a new machine can be time
consuming; even when you keep your configuration in version control there is
a good bit of bootstrapping to be done for each install.
