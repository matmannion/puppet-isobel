#!/usr/bin/env ruby
#^syntax detection

# Puppetfile: Puppet modules that can be installed
# by the `bundle exec r10k puppetfile install` command.
# Where a Forge module is fetched using Git, this is
# usually where we need an unreleased fix. When that
# fix is released to the forge we can change them to
# regular version numbers.
#
# R10K doesn't install transitive dependencies, so if
# module X requires another module Y, we have to
# explicitly add Y here. This is actually useful sometimes
# when Y is a bit broken and needs patching - we can
# require our fixed fork of Y instead.
#
# These modules don't get committed to the repository -
# it just gets Puppetfile, and the master
# pulls them all in when it detects changes.

# IMPORTANT: r10k doesn't keep a track of versions, so
# modules here must be specified as a specific version or ref
# to avoid the master pulling a different version to the one
# you tested with. This may be fixed by a future r10k, or
# by switching to using librarian-puppet. SYSAD-3069

forge "https://forgeapi.puppetlabs.com"

mod 'puppetlabs/stdlib', :latest
mod 'puppetlabs/apt', :latest
mod 'camptocamp/systemd', :latest
mod 'puppetlabs/mongodb', :latest
mod 'willdurand/nodejs', :latest
mod 'puppetlabs/vcsrepo', :latest
mod 'ploperations/bundler', :latest
