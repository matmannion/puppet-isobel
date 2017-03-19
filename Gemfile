# A sample Gemfile
source "https://rubygems.org"

# Note that these gems will only be used when running `bundle exec ...` commands
# in the project, not when the Puppet agent is running

gem 'rake'
# rspec-puppet goes weird in combination with rspec 3.0, so hold back the version for now.
gem 'rspec', '< 3.2.0'
gem 'rspec-puppet', :git => 'https://github.com/rodjek/rspec-puppet.git'
gem 'puppetlabs_spec_helper'
gem 'metadata-json-lint'
gem 'rspec-puppet-facts'
gem 'puppet-lint',
	:git => 'https://github.com/UniversityofWarwick/puppet-lint.git',
	:ref => 'fix/heredoc'
gem 'hiera-eyaml'
gem 'deep_merge'
gem 'rake-notes', 
     :git => 'https://github.com/UniversityofWarwick/rake-notes.git'
gem 'r10k'
gem 'puppet', ENV['PUPPET_VERSION'] || '~> 3.8.5'
gem 'puppet-profiler'
gem 'puppetdb-ruby'
gem 'puppetdb-terminus'

# For docs
gem 'yard'
gem 'redcarpet'
gem 'puppet-strings'
