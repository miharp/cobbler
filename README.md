[![Build Status](https://travis-ci.org/cobbler/cobbler.svg)](https://travis-ci.org/cobbler/cobbler)
[![Documentation Status](https://readthedocs.org/projects/cobbler/badge/?version=latest)](https://cobbler.readthedocs.io/en/latest/)
[![Gitter chat](https://badges.gitter.im/cobbler/gitter.png)](https://gitter.im/cobbler/community)

Cobbler
=======

Cobbler is a Linux installation server that allows for rapid setup of network installation environments. It glues
together and automates many associated Linux tasks so you do not have to hop between lots of various commands and
applications when rolling out new systems, and, in some cases, changing existing ones. It can help with installation,
DNS, DHCP, package updates, power management, configuration management orchestration, and much more.

Read more at [https://cobbler.github.io](https://cobbler.github.io)

To view the manpages, install the RPM and run `man cobbler` or run `perldoc cobbler.pod` from a source checkout.

To build the RPM, run `make rpms`. Developers, try `make webtest` to do a local `make install` that preserves your
configuration.

If you want to contribute you may find more information under [CONTRIBUTING.md](CONTRIBUTING.md).

The documentation can be found at [Readthedocs](https://cobbler.readthedocs.io)
