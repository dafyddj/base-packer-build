# frozen_string_literal: true

# This is a placeholder version to remind us to update the Gemfile
# when a new stable Chef Workstation is released
# renovate: chef-workstation 25.13.7

source ENV.fetch('PROXY_RUBYGEMSORG', 'https://rubygems.org')

# Install the `inspec` gem using `git` because versions after `4.22.22`
# suppress diff output; this version fixes this for our uses.
# rubocop:disable Layout/LineLength
gem 'inspec', git: 'https://gitlab.com/saltstack-formulas/infrastructure/inspec', branch: 'ssf'
# rubocop:enable Layout/LineLength

gem 'kitchen-inspec', '3.1.0'
gem 'kitchen-salt', '0.7.2'
gem 'kitchen-vagrant', '2.2.1'

gem 'net-ssh', '7.3.0'

gem 'test-kitchen', '3.9.1'
