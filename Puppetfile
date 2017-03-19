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

mod 'puppetlabs/stdlib', '4.5.1'
mod 'puppetlabs/inifile', '1.2.0'
mod 'puppetlabs/concat', '2.1.0'
mod 'puppetlabs/apt', '1.7.0'
mod 'puppetlabs/ntp', '3.2.1'
mod 'richardc/datacat', '0.6.1'
mod 'puppetlabs/java_ks', '1.2.6'
mod 'sensu/sensu', '1.5.0'
mod 'maestrodev/wget', '1.5.7'
mod 'arnoudj/sudo', '1.3.0'
mod 'puppetlabs/xinetd', '1.5.0'
mod 'camptocamp/hiera_undef', '1.1.15'
mod 'camptocamp/systemd', '0.2.2'
mod 'puppetlabs/mongodb', '0.11.0'
mod 'willdurand/nodejs', '1.8.5'
mod 'puppetlabs/vcsrepo', '1.3.2'
mod 'ploperations/bundler', '1.0.1'
