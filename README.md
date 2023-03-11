# Razor client
## FORK MAINTAINER NOTES
This is a fork of Puppet Labs' razor-server project. This fork adds the ability to create a fully bootstrapped version of Razor as a container. The motivation behind this repo and the container strategy is to avoid a situation where build artifacts and 3rd party libraries may become unavailable. This situation is already a reality due to what appears to be a lack of contributions to the upstream repo for over a year. To understand how to develop and deploy this tool within the context of SWCCDC see CCDC_README.md.

This code is still in development mode; that means that we might make
backwards incompatible changes, especially to the database schema which
would force you to rebuild all the machines that Razor is managing. Razor
will become stable RSN.

This is the command line client for the [Razor
server](https://github.com/puppetlabs/razor-server) Please have a look at
the Wiki over there for details, in particular, the [Getting
Started](https://github.com/puppetlabs/razor-server/wiki/Getting-started)
page contains instructions about installation and setup of the client.

## Getting in touch

* bug/issue tracker: [RAZOR project in JIRA](https://tickets.puppetlabs.com/browse/RAZOR)
* on IRC: `#puppet-razor` on [freenode](http://freenode.net/)
* mailing list: [puppet-razor@googlegroups.com](http://groups.google.com/group/puppet-razor)

## License

Razor is distributed under the Apache 2.0 license.
See [the LICENSE file](LICENSE) for full details.
