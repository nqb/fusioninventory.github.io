---
layout: page
title: Installation on Fedora
---

# Maintained Fedora version

*fusioninventory-agent* is part of the *official repository* for fedora >= 14

# EOL Fedora version

An old *fusioninventory-agent* package is available in the *remi* third party repository for for fedora >= 8

See [Remi repository configuration](http://blog.famillecollet.com/pages/Config-en) for details.

# Agent installation

Agent installation:

    $ sudo dnf install fusioninventory-agent

Only *fusioninventory-agent* is mandatory, other packages are additional tasks.

You can also install the *yum plugin* which will request a inventory after each yum operation

    $ sudo dnf install fusioninventory-agent-yum-plugin

If the latest release is not available in stable repositories, you may check on testing:

    $ sudo dnf --enablerepo=updates-testing install fusioninventory-agent
