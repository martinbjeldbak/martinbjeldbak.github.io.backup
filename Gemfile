source 'https://rubygems.org'
ruby RUBY_VERSION

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

# This is the default theme for new Jekyll sites.
gem 'minima', '~> 2.0'

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.6'
  gem 'github-pages', versions['github-pages']
end
